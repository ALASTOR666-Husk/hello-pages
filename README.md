# 🚀 Индивидуальный проект: Статический сайт с CI/CD на GitHub Pages

Добро пожаловать в репозиторий моего индивидуального проекта! Цель данного проекта — продемонстрировать навыки создания статического сайта и настройки полностью автоматизированного пайплайна **CI/CD** с использованием **GitHub Actions** и **GitHub Pages**.

![Скриншот проекта](https://via.placeholder.com/800x400/7b1fa2/ffffff?text=CI/CD+GitHub+Pages+Project)

## 🛠 Технологии
- **HTML5** (Семантическая разметка, 5 страниц)
- **CSS3** (Градиентный сине-красно-фиолетовый дизайн, адаптивность)
- **JavaScript** (Анимация появления элементов при скролле через Intersection Observer)
- **GitHub Actions** (Автоматический билд и деплой)
- **Markdown & Mermaid** (Документация)

## 📂 Структура проекта
```mermaid
graph TD
    A[hello-pages] --> B[.github/workflows/deploy.yml]
    A --> C[index.html]
    A --> D[about.html]
    A --> E[services.html]
    A --> F[portfolio.html]
    A --> G[contact.html]
    A --> H[style.css]
    A --> I[script.js]
    A --> J[README.md]
    
    style A fill:#1565c0,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#7b1fa2,stroke:#fff,stroke-width:2px,color:#fff