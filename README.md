# 🧠 Coding Quiz App with CI/CD

This is a full-stack coding quiz application built with TypeScript, Node.js, Express, MongoDB, and React. The project also includes a continuous integration and continuous deployment (CI/CD) pipeline configured using GitHub Actions and Render.

---
## Table of Contents
- [Description](#description)
- [Features](#Features)
- [Tech Stack](#TechStack)
- [Installation](#installation)
 
---

## 🚀 Features

- Take a timed quiz with coding questions
- Score tracking and feedback
- Component testing using Cypress
- CI setup to run tests on Pull Requests to `develop` branch
- CD setup to deploy the app automatically to Render when merging to `main` branch

## 📁 Tech Stack

- **Frontend:** React + TypeScript + Vite
- **Backend:** Node.js + Express + TypeScript
- **Database:** MongoDB Atlas
- **Testing:** Cypress (Component tests)
- **CI/CD:** GitHub Actions + Render

---

## ⚙️ Installation

```bash
git clone https://github.com/<gabipayan>/coding-quiz.git
cd coding-quiz
npm run install     # Installs client + server dependencies
