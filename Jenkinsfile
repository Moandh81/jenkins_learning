pipeline {
    agent any  // Exécute sur n'importe quel agent disponible

    stages {
        stage('Build') {
            steps {
                echo 'Clonage du repository...'

                echo 'Installation des dépendances...'

                echo 'Compilation du projet...'
            }
        }

        stage('Test') {
            steps {
                echo 'Exécution des tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Déploiement en production...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline terminé avec succès ✅'
        }
        failure {
            echo 'Échec du pipeline ❌'
        }
    }
}
