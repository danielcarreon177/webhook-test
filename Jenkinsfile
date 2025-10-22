pipeline {
    agent any
    stages {
        stage('Paso 1: Iniciar Prueba') {
            steps {
                echo 'Iniciando una nueva prueba con pwd y hostname...'
            }
        }
        // --- NUEVA ETAPA DE PRUEBA ---
        stage('Paso 2: Mostrar Información del Sistema') {
            steps {
                echo '============================================='
                echo '1. Directorio de trabajo actual (pwd):'
                sh 'pwd'
                echo ' '
                echo '2. Nombre del host (hostname):'
                sh 'hostname'
                echo '============================================='
            }
        }
        // -----------------------------
        stage('Paso 3: Finalizado') {
            steps {
                echo 'Prueba de automatización completada. ✅'
            }
        }
    }
}