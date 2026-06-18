pipeline {
    agent any

    stages {
        stage('Récupérer le code') {
            steps {
                echo 'Code récupéré depuis GitHub !'
            }
        }
        stage('Build') {
            steps {
                echo 'Build en cours...'
            }
        }
        stage('Test') {
            steps {
                echo 'Tests en cours...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement en cours...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline terminé avec succès !'
        }
        failure {
            echo 'Le pipeline a échoué !'
        }
    }
}
