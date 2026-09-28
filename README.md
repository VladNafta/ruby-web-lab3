# Лабораторна робота №3. HTML, CSS. Використання таблиць та стилів. Бібліотеки та фреймворки

Сторінка власного резюме у двох варіантах верстки. В обох варіантах усе оформлення —
лише у зовнішніх файлах CSS (тегу `<style>` і атрибутів `style` немає).

## Структура

```
part1_table/                 — завдання 1: таблична верстка
  index.html                 — резюме таблицею з двох стовпчиків
  css/style.css              — зовнішня таблиця стилів
part2_bootstrap/             — завдання 2: блочна верстка (div) + Bootstrap 5 + Sass
  index.html                 — те саме резюме на сітці Bootstrap (без table)
  scss/style.scss            — власні стилі на SCSS (змінні, мапа, mixin, @each, вкладеність)
  css/style.css              — скомпільований CSS (генерується, руками не редагувати)
  css/bootstrap.min.css      — CSS-фреймворк Bootstrap 5.3.8 (з npm-пакета bootstrap)
  package.json               — залежності (sass, bootstrap) і скрипти компіляції
```

## Запуск

Частина 1 — відкрити `part1_table/index.html` у браузері, сервер не потрібен.

Частина 2:

```
cd part2_bootstrap
npm install        # sass і bootstrap
npm run build      # scss/style.scss -> css/style.css
```

Потім відкрити `part2_bootstrap/index.html` у браузері.

## Кольори і запозичене

Кольори — з палітри Material Design, контраст перевірено сервісом WebAIM Contrast Checker
(https://webaim.org/resources/contrastchecker/): усі пари проходять рівень WCAG AA (≥ 4.5:1).
`css/bootstrap.min.css` — файл фреймворку Bootstrap (MIT License, https://getbootstrap.com).
