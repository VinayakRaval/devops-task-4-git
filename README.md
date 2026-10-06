# DevOps Internship - Task 4
## Build a Version-Controlled DevOps Project with Git

![Git](https://img.shields.io/badge/Git-Version%20Control-orange)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

This project was created as part of the DevOps Internship Task 4.

The objective of this task is to manage a DevOps project using Git and GitHub best practices.

The project demonstrates:

- Git repository initialization
- GitHub repository creation
- Branching
- Feature development
- Pull Requests
- Git commits
- `.gitignore`
- Git tags
- Markdown documentation

---

## 🎯 Objective

The main objective of this task is to understand and implement a basic Git workflow for a DevOps project.

The workflow used in this project is:

```text
                  ┌─────────────┐
                  │    main     │
                  │ Production  │
                  └──────▲──────┘
                         │
                    Pull Request
                         │
                  ┌──────┴──────┐
                  │     dev     │
                  │ Development │
                  └──────▲──────┘
                         │
                    Pull Request
                         │
                  ┌──────┴──────┐
                  │   feature   │
                  │ New Feature │
                  └─────────────┘