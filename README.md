# 🚀 DevOps Playground — Learn Through Interactive Simulations

## 📌 Introduction

DevOps Playground is an interactive educational website designed to help students understand basic DevOps concepts through simple simulations.

The website provides interactive pages for learning Git commands, CI/CD pipelines, Docker concepts, and DevOps fundamentals through quizzes.

## 🎯 Objectives

- To understand basic DevOps concepts.
- To learn Git and GitHub version control.
- To understand the stages of a CI/CD pipeline.
- To explore Docker container operations.
- To test DevOps knowledge through interactive quizzes.
- To gain practical experience in website development and GitHub.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- GitHub Actions (for DevOps tool integration)

## ✨ Features

### 1. Home Page
Provides an introduction to the DevOps Playground and navigation to the learning modules.

### 2. Git Simulator
Demonstrates basic Git operations through an interactive terminal-style simulation.

### 3. CI/CD Pipeline Simulator
Demonstrates the main stages of a CI/CD pipeline, including Code, Build, Test, and Deploy.

### 4. Docker Simulator
Provides a simulation to understand basic container operations.

### 5. DevOps Quiz
Allows users to test their knowledge of DevOps concepts through an interactive quiz.

## 📸 Website Screenshots

### 1. Home Page

The home page introduces the DevOps Playground and its learning modules.

![Home Page](screenshots/index.png)

### 2. Home Page — Alternative View

![Home Page Alternative](screenshots/index1.png)

### 3. Git Simulator

This page demonstrates Git commands through an interactive simulation.

![Git Simulator](screenshots/Git%20simulation.png)

### 4. CI/CD Pipeline Simulator

This page demonstrates the stages of a CI/CD pipeline.

![CI/CD Pipeline](screenshots/CICD%20simulation.png)

### 5. CI/CD Pipeline — Alternative View

![CI/CD Pipeline Alternative](screenshots/CICD%20simulation1.png)

### 6. Docker Simulator

This page demonstrates Docker container operations through a simulation.

![Docker Simulator](screenshots/Docker%20simulation.png)

### 7. DevOps Quiz — Question View

![DevOps Quiz Question](screenshots/quiz1.png)

### 8. DevOps Quiz — Alternative View

![DevOps Quiz](screenshots/Quiz.png)

## 💻 How to Run the Project

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser.

Alternatively, install the Live Server extension in VS Code, right-click `index.html`, and select **Open with Live Server**.

## 🔄 Git and GitHub Workflow

Git is used to track project changes, while GitHub stores the repository and its commit history.

The following commands are used to manage the project:

```bash
git init
git add .
git commit -m "Describe your changes"
git push
```

The project is maintained in a GitHub repository with separate commits for meaningful changes.

## 📝 Project Changes and Commit History

The project was developed incrementally using Git.

| No. | Commit Message | Description |
|---|---|---|
| 1 | Add homepage and navigation | Created the homepage and website layout. |
| 2 | Add interactive Git simulator | Added the Git simulation page. |
| 3 | Add CI CD pipeline simulator | Added the CI/CD pipeline simulation. |
| 4 | Add Docker simulator | Added the Docker simulation page. |
| 5 | Add DevOps quiz functionality | Added the DevOps quiz page. |

*Note: The table above describes the planned changes. Verify that each commit exists in the GitHub repository before submission.*

## ⚙️ DevOps Tool Integration

GitHub Actions is used to automate checks on the project when changes are pushed to GitHub.

The workflow can verify that required website files exist in the repository.

### Integration Steps

1. Create a workflow file at `.github/workflows/validate.yml`.
2. Configure the workflow to run when code is pushed to the `main` branch.
3. Add steps to check the required project files.
4. Commit and push the workflow file to GitHub.
5. Open the **Actions** tab in the GitHub repository.
6. Check the workflow execution result.

### DevOps Integration Evidence

Add a screenshot of the successful GitHub Actions workflow below after the integration has been configured and tested.

![GitHub Actions Workflow](screenshots/devops-integration.png)

## 📚 Learning Outcomes

- Learned how to structure a website using HTML and CSS.
- Practiced version control using Git.
- Learned how to maintain a repository on GitHub.
- Understood the basic stages of a CI/CD pipeline.
- Explored Docker concepts through simulation.
- Learned the basics of automating repository checks with GitHub Actions.

## 🏁 Conclusion

DevOps Playground is an educational website that introduces fundamental DevOps concepts through interactive simulations. It combines website development with Git, GitHub, and DevOps tool integration to provide practical learning experience.

## 🔗 GitHub Repository

Repository: https://github.com/ankita2006s/DevOps-Playground