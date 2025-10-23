pipeline {
    agent any
    stages {
        stage('Paso 1: Iniciar Prueba de Variables') {
            steps {
                echo 'Vamos a ver todas las variables de entorno que Jenkins nos da...'
            }
        }
        // --- NUEVA ETAPA DE PRUEBA ---
        stage('Paso 2: Mostrar Variables de Entorno') {
            steps {
                echo '============================================='
                echo '1. Esta es la lista completa de variables (printenv):'
                sh 'printenv' // Muestra TODAS las variables
                echo ' '
                echo '2. Aquí está el número de build específico:'
                // Jenkins inyecta $BUILD_NUMBER automáticamente
                sh 'echo "Este build es el número: $BUILD_NUMBER"'
                echo '============================================='
            }
        }
        // -----------------------------
        stage('Paso 3: Finalizado') {
            steps {
                echo 'Prueba de variables de entorno completada. ✅'
            }
        }
    }
}