pipeline {
    agent any
    stages {
        stage('Paso 1: Saludo') {
            steps {
                echo 'Iniciando la prueba final de la automatización...'
            }
        }
        stage('Paso 2: Verificar Directorio') {
            steps {
                echo 'Contenido del directorio de trabajo:'
                sh 'ls -la'
            }
        }
        // --- NUEVA ETAPA PARA LA PRUEBA FINAL ---
        stage('Paso 3: Identificar Usuario') {
            steps {
                echo '============================================='
                echo 'Verificando el usuario que ejecuta el pipeline...'
                sh 'whoami' // Comando para mostrar el usuario actual
                echo '============================================='
            }
        }
        // ------------------------------------
        stage('Paso 4: Finalizado') {
            steps {
                echo '¡Conexión 100% confirmada! El webhook funcionó perfectamente. ✅'
            }
        }
    }
}