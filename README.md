# NagiTech Web App 🚀

> Security-First React/Tailwind Full-Stack Project


## 🛡️ Security Features

| Feature | Tool | Stage |
|---------|------|-------|
| Static Code Analysis | GitLab SAST | `security` |
| Dependency Vulnerabilities | Dependency Scanning | `security` |
| Exposed Secrets Detection | Secret Detection | `security` |
| Code Quality | ESLint | `test` |
| Unit Tests + Coverage | React Testing Library | `test` |<img width="818" height="326" alt="NAGITECH1" src="https://github.com/user-attachments/assets/24ad80ee-0fb1-4e89-b9c8-b966c7e63d3a" />

## 🏗️ Tech Stack
- **Frontend:** React 18 + Tailwind CSS 3
- **Testing:** React Testing Library + Jest
- **Linting:** ESLint (with security rules)
- **CI/CD:** GitLab CI/CD
## 📁 Project Structure
```
nagitech-web-app/
├── .gitlab-ci.yml       # CI/CD Pipeline with security stages
├── .eslintrc.js         # ESLint config with security rules
├── .gitignore           # Security-focused ignore rules
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.js    # PostCSS configuration
├── package.json         # Dependencies and scripts
├── public/
│   └── index.html       # HTML with security meta tags
└── src/
    ├── index.js         # React entry point
    ├── index.css        # Tailwind imports
    ├── App.js           # Main component
    └── App.test.js      # Unit tests

Built  by Eng  Nagi Alshaikh· [NagiTech-group](https://gitlab.com/nagitech-group)
