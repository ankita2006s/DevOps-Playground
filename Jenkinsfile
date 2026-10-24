pipeline {
agent any

```
options {
    timestamps()
}

stages {
    stage('Checkout') {
        steps {
            echo 'Checking out DevOps Playground source code'
            checkout scm
        }
    }

    stage('Validate Website Files') {
        steps {
            script {
                def requiredFiles = [
                    'index.html',
                    'git.html',
                    'pipeline.html',
                    'docker.html',
                    'quiz.html',
                    'style.css'
                ]

                def missingFiles = requiredFiles.findAll {
                    !fileExists(it)
                }

                if (missingFiles) {
                    error "Missing required files: ${missingFiles.join(', ')}"
                }

                echo 'All required website files exist.'
            }
        }
    }

    stage('Validate HTML Structure') {
        steps {
            script {
                def htmlFiles = [
                    'index.html',
                    'git.html',
                    'pipeline.html',
                    'docker.html',
                    'quiz.html'
                ]

                htmlFiles.each { file ->
                    def content = readFile(file)

                    if (!content.toLowerCase().contains('<html')) {
                        error "${file} does not contain an HTML root element."
                    }

                    if (!content.toLowerCase().contains('</html>')) {
                        error "${file} is missing the closing HTML tag."
                    }

                    echo "Basic HTML structure check passed: ${file}"
                }
            }
        }
    }

    stage('CI Result') {
        steps {
            echo 'SUCCESS: DevOps Playground validation completed.'
        }
    }
}

post {
    success {
        echo 'Jenkins CI pipeline completed successfully.'
    }
    failure {
        echo 'Jenkins CI pipeline failed. Check the stage logs.'
    }
}
```

}
