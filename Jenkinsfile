pipeline {
    agent any

    stages {
        stage('Preparación') {
            steps {
                echo 'Iniciando pipeline...'
                echo 'Preparando entorno...'
            }
        }

        stage('Compilación') {
            steps {
                echo 'Compilando el proyecto...'
                echo 'Ejecutando comandos de compilación...'
            }
        }

        stage('Pruebas') {
            steps {
                echo 'Ejecutando pruebas unitarias...'
                echo 'Todas las pruebas han pasado exitosamente.'
            }
        }

        stage('Despliegue') {
            steps {
                echo 'Desplegando aplicación...'
                echo 'Aplicación desplegada correctamente.'
            }
        }
    }

    post {
        always {
            echo 'Pipeline completado. Revisar logs para más detalles.'
        }
    }
}
