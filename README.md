# 🎨 "С чистого листа" — Адаптивный лендинг

**Верстка по макету Figma с использованием семантической разметки и Flexbox**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/ru/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/ru/docs/Web/CSS)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://figma.com)

---

## 📖 О проекте

Этот проект — лендинг "С чистого листа", созданный для преодоления страха перед первыми проектами. Я разработала его полностью самостоятельно, следуя макету в Figma и рекомендациям по семантической верстке.

**Основная цель:** Освоить на практике современные подходы к верстке, включая семантическую разметку, Flexbox и организацию CSS-кода.

### 🎯 Ключевые особенности

- **Семантическая верстка:** Использование тегов `<header>`, `<main>`, `<section>`, `<footer>`, `<article>`, `<time>`
- **Адаптивный дизайн:** Полная адаптация под мобильные устройства
- **Модульная структура:** Применение методологии БЭМ для именования классов
- **Типографика:** Работа с кастомными шрифтами (EB Garamond, Inter)
- **Flexbox layout:** Использование flex-контейнеров для выравнивания элементов

### 🛠 Технологический стек

**Frontend:**
- HTML5 (семантическая разметка)
- CSS3 (Flexbox, кастомные свойства)
- Шрифты: EB Garamond (400, 500), Inter (400, 700)

**Инструменты:**
- Figma (работа с макетом)
- Git (контроль версий)
- GitHub Pages (деплой)

---

## 🚀 Быстрый старт

### Посмотреть онлайн

🌐 **[Живая демо-версия](https://cutevil-magal.github.io/first-project/)**

### Запуск локально

1. **Клонирование репозитория**
   ```bash
   git clone https://github.com/cutevil-magal/first-project.git
   cd first-project
   ```

2. **Запуск проекта**
   - Откройте файл `index.html` в браузере
   - Или используйте Live Server в VS Code

### Системные требования
- Любой современный браузер (Chrome, Firefox, Safari, Edge)
- Доступ к интернету для загрузки шрифтов

---

## 📁 Структура проекта

```
first-project/
├── index.html          # Главная страница
├── styles/
│   ├── style.css       # Основные стили
│   └── fonts.css       # Подключение шрифтов
├── fonts/              # Локальные шрифты
├── images/             # Изображения проекта
└── README.md           # Документация
```

---

## 🎨 Особенности реализации

### Семантическая разметка
```html
<header class="header">
  <main class="main">
    <section class="content-section content-section_theme_dark">
    <article class="card card_theme_bright">
```

### Flexbox для компоновки
```css
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

### Работа с типографикой
```css
@font-face {
  font-family: 'Inter';
  src: url('../fonts/inter-regular.woff2') format('woff2');
  font-weight: 400;
}
```

### Модификаторы по БЭМ
```css
.content-section_theme_dark {
  background-color: #1e1e1e;
  color: #f5f5f5;
}

.content-section_theme_bright {
  background-color: #fee42a;
  color: #131313;
}
```

---

## 📊 Чек-лист реализации

- [x] Семантическая HTML-разметка
- [x] Адаптивная верстка (360px)
- [x] Flexbox для компоновки
- [x] Кастомные шрифты
- [x] БЭМ-именование классов
- [x] Сброс браузерных стилей
- [x] Оптимизация изображений
- [x] Валидный HTML/CSS код
- [x] Деплой на GitHub Pages

---

## 🎯 Результаты и выводы

**Достигнутые результаты:**
- ✅ Полностью реализован макет из Figma
- ✅ Освоена семантическая верстка
- ✅ Применена методология БЭМ на практике
- ✅ Наработан опыт работы с Flexbox
- ✅ Проект успешно размещен на GitHub Pages

**Приобретенные компетенции:**
- Глубокое понимание семантической HTML-разметки
- Практический опыт работы с макетами в Figma
- Навыки организации CSS-кода по БЭМ
- Умение работать с кастомными шрифтами
- Опыт деплоя статических сайтов на GitHub Pages

---

## 🔮 Планы по развитию

- [ ] Добавить desktop-версию (адаптивность до 1440px)
- [ ] Реализовать dark/light theme switcher
- [ ] Добавить микроанимации и переходы
- [ ] Оптимизировать загрузку шрифтов
- [ ] Написать тесты на доступность (a11y)

---

## 👩‍💻 Разработчик

**Анна Хвостикова** - Frontend Developer

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cutevil-magal)
[![Email](https://img.shields.io/badge/Email-ana.magal@yandex.by-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ana.magal@yandex.by)

---

## 📄 Лицензия

Проект создан на основе дизайн-макета из Figma. Исходный код доступен для ознакомления и обучения.

**Макет в Figma:** [Ссылка на макет](https://www.figma.com/design/TfBMZ0tWEUuOZP7rGmxkrz/%231-%D0%A1-%D1%87%D0%B8%D1%81%D1%82%D0%BE%D0%B3%D0%BE-%D0%BB%D0%B8%D1%81%D1%82%D0%B0-(Copy)?node-id=0-1&node-type=canvas&t=Q3iCQGIDyDbbliYb-0)

---
