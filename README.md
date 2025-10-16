# 🎭 Hizirwright

A modern **Playwright + TypeScript** automation framework built and maintained.
This repository serves as a professional and extendable base for end-to-end web automation projects — designed with scalability, clarity, and best practices in mind.

---

## 🧱 Purpose

The goal of **Hizirwright** is to create a robust, maintainable, and cross-platform UI test automation framework using [Playwright](https://playwright.dev/) with **TypeScript**.  
It’s an evolving project to explore advanced automation techniques such as:
- Parallel test execution  
- Cross-browser and cross-platform testing  
- Custom reporting and configuration  
- CI/CD integration (GitHub Actions, Jenkins, etc.)  

---

## 🧩 Tech Stack
| Tool | Purpose |
|------|----------|
| **Playwright** | Web automation framework |
| **TypeScript** | Strongly-typed scripting language |
| **Node.js / npm** | Package management & runtime |
| **Allure / HTML Reporter** | (To be added) Test result visualization |
| **ESLint / Prettier** | (To be added) Code style and linting |

---

## ⚙️ Project Setup

### 🪜 1. Clone the repository
```bash
git clone https://github.com/hzrylmz/Hizirwright.git
cd Hizirwright

npm install

npx playwright test

npx playwright show-report


.
├── tests/                     # Test files
│   └── example.spec.ts        # Sample test
├── playwright.config.ts       # Main Playwright configuration
├── package.json               # Dependencies and npm scripts
├── .gitignore
└── README.md

