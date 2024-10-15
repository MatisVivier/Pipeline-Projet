pipeline {
    agent any

    stages {
        stage('Clone repository') {
            steps {
                // Cloner le repository depuis GitHub
                git 'https://github.com/MatisVivier/Pipeline-Projet.git'
            }
        }
        stage('Build') {
            steps {
                // Construire le projet
                echo 'Building...'
                // Ajouter des commandes de build ici (e.g. mvn, npm, etc.)
            }
        }
        stage('Test') {
            steps {
                // Lancer les tests
                echo 'Running tests...'
                // Ajouter des commandes de test ici
            }
        }
        stage('Deploy') {
            steps {
                // Déployer l'application
                echo 'Deploying...'
                // Ajouter des commandes de déploiement ici
            }
        }
    }
}
