# Keepsake — landing page

Навчальний проєкт для лабораторної роботи №9. Сайт збирається за допомогою Pug, SCSS, Vite та Vituum.

**Джерело основи:** [UdalovIvanw/landing-keepsake-vite](https://github.com/UdalovIvanw/landing-keepsake-vite). Цей репозиторій є адаптованою навчальною копією, а не повністю незалежною реалізацією. Деталі — у [SOURCE-CREDITS.md](./SOURCE-CREDITS.md).

## Запуск

Потрібні Node.js 20+ і npm 10+.

```bash
npm ci
npm run dev
```

## Перевірка та production-збірка

```bash
npm run format
npm run lint
npm run build
npm run preview
```

Для оптимізації зображень:

```bash
npm run images
```

## Технології

- Pug — шаблонізація, наслідування макетів, компоненти та міксини.
- SCSS — модульна структура стилів, змінні, функції та міксини.
- Vite + Vituum — локальна розробка й production-збірка.
- PostCSS, Autoprefixer, Browserslist — обробка CSS.
- Sharp — генерація оптимізованих зображень.
- Prettier, Stylelint, Husky, lint-staged — контроль якості коду.

GitHub Actions налаштований для збірки та розгортання GitHub Pages після push у гілку `main`.
