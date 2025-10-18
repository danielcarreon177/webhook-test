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
                // Este comando funciona en la terminal de Windows
                bat 'dir'
            }
        }
        stage('Paso 3: Finalizado') {
            steps {
                echo 'Pipeline completado con éxito. ¡Felicidades! 🎉'
            }
        }
    }
}