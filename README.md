# GitHub Deployment Workflow

This project demonstrates **Continuous Integration and Continuous Deployment (CI/CD)** using GitHub Actions to automatically deploy a static website to GitHub Pages.

## 🎯 Project Overview

This repository contains a simple static website that automatically deploys to GitHub Pages whenever changes are made to the `index.html` file. This showcases the power of automation in modern software development workflows.

## 🚀 Features

- **Automated Deployment**: Any push to the `main` branch that modifies `index.html` triggers automatic deployment
- **GitHub Actions Workflow**: Custom workflow configuration for efficient CI/CD
- **GitHub Pages Hosting**: Free, reliable hosting for the static website

## 📋 How It Works

1. Developer makes changes to `index.html` and pushes to the `main` branch
2. GitHub Actions detects the push and checks if `index.html` was modified
3. If modified, the workflow automatically deploys the updated content to GitHub Pages
4. The website is accessible at: `https://<username>.github.io/gh-deployment-workflow/`

## 🛠️ Technologies Used

- **GitHub Actions**: For workflow automation
- **GitHub Pages**: For hosting the static website
- **HTML/CSS**: For the website content

## 📁 Project Structure

```
gh-deployment-workflow/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions workflow configuration
├── index.html                   # Main website file
├── README.md                    # Project documentation
└── PROJECT.MD                   # Project requirements
```

## 🔧 Setup Instructions

1. **Fork or Clone** this repository
2. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Set source to "GitHub Actions"
3. **Make changes** to `index.html`
4. **Push to main branch**
5. **Watch the workflow** run in the Actions tab
6. **Visit your site** at `https://<username>.github.io/gh-deployment-workflow/`

## 📚 Learning Outcomes

By completing this project, you'll understand:

- ✅ How to write GitHub Actions workflows
- ✅ Continuous Integration and Continuous Deployment concepts
- ✅ Path-based workflow triggers
- ✅ Deploying to GitHub Pages programmatically
- ✅ Automation in software development

## 🎓 Next Steps

Consider extending this project by:

- Using a static site generator (Hugo, Jekyll, Astro)
- Building a personal portfolio website
- Adding automated testing before deployment
- Implementing staging environments

## 📄 License

This is a learning project and is free to use.
