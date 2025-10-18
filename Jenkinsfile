pipeline {
    agent any
    stages {
        stage('Paso 1: Saludo') {
            steps {
                echo '¡Hola! El pipeline se ha iniciado correctamente.'
            }
        }
        stage('Paso 2: Verificar Directorio') {
            steps {
                echo 'Estoy revisando los archivos en el espacio de trabajo...'
                // 'sh' es para sistemas Linux/Unix. 'ls -la' lista los archivos.
                sh 'ls -la'
            }
        }
        // --- NUEVA ETAPA AÑADIDA AQUÍ ---
        stage('Paso Extra: Demostración') {
            steps {
                echo '*****************************************************'
                echo '*** ¡LA AUTOMATIZACIÓN ESTÁ FUNCIONANDO! ***'
                echo '*****************************************************'
            }
        }
        // ------------------------------------
        stage('Paso 3: Finalizado') {
            steps {
                echo 'Pipeline completado con éxito. ¡Felicidades! 🎉'
            }
        }
    }
}