pipeline {
    agent any
    stages {
        stage('Paso 1: Saludo') {
            steps {
                echo 'Iniciando una nueva prueba de automatización...'
            }
        }
        stage('Paso 2: Verificar Directorio') {
            steps {
                echo 'Contenido del directorio de trabajo:'
                sh 'ls -la'
            }
        }
        // --- ETAPA MODIFICADA ---
        stage('Paso Extra: Verificar Versión de Java') {
            steps {
                echo '============================================='
                echo 'Revisando la versión de Java del sistema...'
                sh 'java --version'
                echo '============================================='
            }
        }
        // ------------------------
        stage('Paso 4: Finalizado') {
            steps {
                echo 'Pipeline de prueba completado exitosamente. ✅'
            }
        }
    }
}