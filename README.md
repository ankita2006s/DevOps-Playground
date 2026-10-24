# 🚀 DevOps Playground — Learn Through Interactive Simulations

## 📌 Introduction

DevOps Playground is an interactive educational website designed to help students understand fundamental DevOps concepts through simple, interactive simulations.

The website includes learning modules for Git, CI/CD pipelines, Docker, and DevOps fundamentals. It also integrates Jenkins for automated validation of the project's source code.

## 🎯 Objectives

* To understand fundamental DevOps concepts.
* To learn Git and GitHub version control.
* To understand the stages of a CI/CD pipeline.
* To explore Docker and container operations.
* To test DevOps knowledge through interactive quizzes.
* To gain practical experience in website development.
* To understand Continuous Integration using Jenkins.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Git
* GitHub
* Jenkins
* Groovy (Jenkins Pipeline)

## ✨ Features

### 1. Home Page

Provides an introduction to DevOps Playground and navigation to the learning modules.

### 2. Git Simulator

Demonstrates basic Git operations through an interactive terminal-style simulation.

### 3. CI/CD Pipeline Simulator

Explains the main stages of a CI/CD pipeline, including Code, Build, Test, and Deploy.

### 4. Docker Simulator

Provides an educational simulation of basic Docker container operations.

### 5. DevOps Quiz

Allows users to test their understanding of DevOps concepts through an interactive quiz.

### 6. Jenkins Continuous Integration

Uses a Jenkins pipeline to retrieve the source code from GitHub and perform automated checks on required project files and basic HTML structure.

**Note:** The Git, CI/CD, and Docker learning modules are educational simulations. The Jenkins pipeline performs source-code validation; it does not deploy the website.

## 📸 Website Screenshots

### 1. Home Page

![Home Page](screenshots/index.png)

### 2. Home Page — Alternative View

![Home Page Alternative](screenshots/index1.png)

### 3. Git Simulator

![Git Simulator](screenshots/Git%20simulation.png)

### 4. CI/CD Pipeline Simulator

![CI/CD Pipeline Simulator](screenshots/CICD%20simulation.png)

### 5. CI/CD Pipeline — Alternative View

![CI/CD Pipeline Alternative](screenshots/CICD%20simulation1.png)

### 6. Docker Simulator

![Docker Simulator](screenshots/Docker%20simulation.png)

### 7. DevOps Quiz — Question View

![DevOps Quiz Question](screenshots/quiz1.png)

### 8. DevOps Quiz — Alternative View

![DevOps Quiz Alternative](screenshots/Quiz.png)

## ⚙️ How to Run the Project

1. Clone or download the GitHub repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser.

Alternatively, install the Live Server extension in Visual Studio Code, right-click `index.html`, and select **Open with Live Server**.

## 🔄 Git and GitHub Workflow

Git is used to track changes in the project, while GitHub hosts the repository and stores its commit history.

The following commands are used for version control:

```bash
git init
git add .
git commit -m "Describe your changes"
git push
```

The project is developed incrementally, with separate commits for meaningful changes.

### GitHub Repository

Repository: https://github.com/ankita2006s/DevOps-Playground

### GitHub Repository Screenshot

![GitHub Repository](screenshots/github-repository.png)

### GitHub Commit History

The commit history demonstrates the project's development and the use of Git for version control.

![GitHub Commit History](screenshots/github-commits.png)

## 📝 Project Changes and Commit History

The following table describes the main project changes. Verify the commit messages against the actual GitHub history before submission.

| No. | Commit Message                | Description                                                    |
| --- | ----------------------------- | -------------------------------------------------------------- |
| 1   | Add homepage and navigation   | Created the homepage and website navigation.                   |
| 2   | Add interactive Git simulator | Added the Git simulation page.                                 |
| 3   | Add CI CD pipeline simulator  | Added the CI/CD pipeline simulation.                           |
| 4   | Add Docker simulator          | Added the Docker simulation page.                              |
| 5   | Add DevOps quiz functionality | Added the DevOps quiz page.                                    |
| 6   | Add Jenkins CI pipeline       | Added Jenkins pipeline configuration for automated validation. |

**Note:** Include only commits that actually exist in your Git history. The Jenkins commit should be included after the `Jenkinsfile` has been committed and pushed.

## 🔧 Jenkins Continuous Integration (CI)

Jenkins is integrated with the DevOps Playground GitHub repository to automate checks on the project's source code.

The pipeline is defined in a file named `Jenkinsfile` in the root directory of the repository.

### Jenkins Pipeline Stages

**1. Checkout**

Retrieves the project's source code from the configured GitHub repository.

**2. Validate Website Files**

Checks whether the required HTML and CSS files exist in the project.

**3. Validate HTML Structure**

Performs basic checks to confirm that each required HTML page contains opening and closing HTML root tags.

**4. CI Result**

Reports whether the pipeline completed successfully or failed.

### Jenkins Configuration

* **Jenkins Job:** `DevOps-Playground-CI`
* **Pipeline Type:** Pipeline script from SCM
* **Source Control:** Git
* **Repository:** `https://github.com/ankita2006s/DevOps-Playground.git`
* **Branch:** `main`
* **Pipeline Script:** `Jenkinsfile`

### Jenkins Integration Screenshots

#### 1. Jenkins Dashboard

![Jenkins Dashboard](screenshots/jenkins-dashboard.png)

#### 2. Successful Jenkins Pipeline

![Jenkins CI Success](screenshots/jenkins-success.png)

#### 3. Jenkins Console Output

![Jenkins Console Output](screenshots/jenkins-console-output.png)

#### 4. Jenkinsfile on GitHub

![Jenkinsfile on GitHub](screenshots/jenkinsfile-github.png)

**Note:** The success screenshot should show a completed build with `Finished: SUCCESS`. If the console-output screenshot shows an earlier failed build, replace it with the output from the successful build before using it as proof of successful integration.

## 📚 Learning Outcomes

* Learned to develop a website using HTML, CSS, and JavaScript.
* Practiced version control using Git.
* Learned to manage a project repository using GitHub.
* Understood the fundamental stages of CI/CD.
* Explored Docker and container concepts through simulations.
* Learned how to configure a Jenkins pipeline.
* Gained practical experience with automated source-code validation.

## 🏁 Conclusion

DevOps Playground is an educational website that introduces fundamental DevOps concepts through interactive simulations.

The project combines front-end web development with Git, GitHub, and Jenkins to demonstrate version control and Continuous Integration. It provides practical learning experience and helps students understand how automated validation can be incorporated into a software development workflow.

## 🔗 GitHub Repository

**Project Repository:** https://github.com/ankita2006s/DevOps-Playground
