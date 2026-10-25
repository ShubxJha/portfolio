# Shubham Jha | Portfolio

A responsive portfolio website featuring my projects, skills, and background.

**Live portfolio:** [shubxjha.github.io/portfolio](https://shubxjha.github.io/portfolio/)

## Featured projects

- **Student Management API** — Student record management with Node.js, Express, and MySQL. [Source code](https://github.com/ShubxJha/student-management-api)
- **Online Course Enrollment API** — Course registration with seat tracking and duplicate enrollment protection. [Source code](https://github.com/ShubxJha/online-course-enroll-api)
- **Personal Portfolio** — This responsive portfolio built with HTML, CSS, and JavaScript. [Live site](https://shubxjha.github.io/portfolio/) · [Source code](https://github.com/ShubxJha/portfolio)
- **Dockerized Student Task Manager** — Task management app with persistent storage and a REST API. [Live app](https://taskmanager-s9ei.onrender.com) · [Source code](https://github.com/ShubxJha/student-task-manager)

Browse [all my GitHub repositories](https://github.com/ShubxJha?tab=repositories).

## Built with

HTML5, CSS3, and vanilla JavaScript. The layout adapts to mobile screens, includes a mobile navigation menu, and supports reduced-motion preferences.

## Run locally

Open `index.html` in a browser, or serve the folder locally:

```powershell
py -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy

The GitHub Actions workflow in `.github/workflows/deploy.yml` publishes the static site from the repository root whenever `main` is updated. To enable deployment, set the repository's **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. The workflow can also be started manually from the Actions tab.

## Git workflow

The portfolio was developed on a feature branch and merged into `main`. Review the history with:

```bash
git log --oneline --graph --all
```
