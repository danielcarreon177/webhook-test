pipeline {
    agent any
    stages {
        stage('Paso 1: Iniciar Prueba') {
            steps {
                echo 'Probando la nueva configuración de "Poll SCM" (sondeo SCM)...'
            }
        }
        // --- NUEVA ETAPA DE PRUEBA ---
        stage('Paso 2: Mostrar Hora del Servidor') {
            steps {
                echo '============================================='
                echo 'Verificando la hora actual del servidor de Jenkins...'
                sh 'date' // Muestra la fecha y hora del servidor
                echo '============================================='
            }
        }
        // -----------------------------
        stage('Paso 3: Finalizado') {
            steps {
                echo '¡Prueba de "Poll SCM" completada! ✅'
            }
        }
    }
}