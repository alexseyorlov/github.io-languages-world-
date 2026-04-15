# 🌍 Топ-15 языков мира | Vibe Coding Training

> Интерактивный веб-проект для визуализации данных о распределении говорящих на топ-15 языках мира по континентам. **Это учебный проект для тренировки Vibe Coding.**

![Languages](https://img.shields.io/badge/HTML5-CSS3-JavaScript-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Status](https://img.shields.io/badge/Status-Training%20Project-orange)

---

## 📋 Описание проекта

Интерактивный дашборд с визуализацией данных о распределении 3.68 млрд говорящих на 15 самых распространённых языках мира по континентам.

### Основные возможности:
- 📊 **Два интерактивных графика** (Chart.js)
  - График распределения по континентам
  - График по числу говорящих
  
- 📑 **Переключаемые вкладки** (JavaScript)
  - Динамическое переключение между графиками
  - Плавные переходы (CSS animations)

- 📋 **Интерактивная таблица** с сортировкой
  - Сортировка по названию языка (A-Z)
  - Сортировка по числу говорящих (возрастание/убывание)
  - Сортировка по процентам от населения
  - Номер позиции остаётся без изменений

- 🎨 **Современный дизайн**
  - Glassmorphism эффект (полупрозрачные элементы + blur)
  - Градиентные фоны и тексты
  - Адаптивный дизайн (работает на мобильных)
  - Цветное распределение по континентам

- 🌐 **Полная адаптивность**
  - Desktop (1600px+)
  - Tablet (900px-1200px)
  - Mobile (< 900px)

---

## 🎓 ЭТО УЧЕБНЫЙ ПРОЕКТ!

### Навыки, которые я отрабатывал:

#### **Frontend:**
- ✅ **HTML5** — семантическая разметка
- ✅ **CSS3** — 
  - Flexbox & Grid layouts
  - CSS variables & gradients
  - Backdrop filters (стекловидный эффект)
  - Media queries (адаптивный дизайн)
  - CSS animations & transitions
  
- ✅ **JavaScript (Vanilla)**
  - DOM манипуляция
  - Event listeners
  - Функции сортировки (локальная сортировка таблиц)
  - Динамическое переключение элементов
  - Методы работы с массивами (sort, filter, map)

#### **Библиотеки:**
- ✅ **Chart.js** — создание интерактивных графиков
- ✅ **Google Fonts** (Sora, Playfair Display) — типографика

#### **Дизайн:**
- ✅ **Color theory** — гармоничная палитра (#22c55e, #3b82f6, #06b6d4, #f59e0b)
- ✅ **UI/UX принципы** — информативность, читаемость, интерактивность
- ✅ **Современный web дизайн** — тренды 2025 года

---

## 📁 Структура проекта

```
languages-world/
├── README.md                      # Этот файл
├── index.html                     # Главный файл проекта
├── SOURCES.md                     # Источники данных
├── docs/
│   ├── ZEROBLOCK_SETUP_GUIDE.md   # Интеграция в Tilda via ZeroBlock
│   ├── TILDA_FREE_COMPATIBILITY.md # Совместимость с бесплатным Tilda
│   └── FREE_HOSTING_GUIDE.md      # Гайд по бесплатному хостингу
└── assets/
    └── (все ресурсы загружаются с CDN)
```

---

## 🚀 Быстрый старт

### Локально:
```bash
# 1. Клонируйте репозиторий
git clone https://github.com/YOUR_USERNAME/languages-world.git
cd languages-world

# 2. Откройте файл в браузере
open index.html
# или через Live Server в VS Code
```

### Online:
1. Откройте: `https://YOUR_USERNAME.github.io/languages-world/`
2. Наслаждайтесь интерактивным дашбордом!

---

## 📊 Данные в проекте

### Топ-15 языков мира (по числу родных говорящих):

| # | Язык | Говорящих | % мира | Континенты |
|---|------|----------|--------|-----------|
| 1 | Мандаринский китайский | 929 млн | 11.47% | 🌏 Азия |
| 2 | Испанский | 474.7 млн | 5.86% | 🌎 Америка, 🌍 Европа, 🌍 Африка |
| 3 | Английский | 372.9 млн | 4.60% | 🌍 Европа, 🌎 Америка, 🌏 Азия |
| 4 | Хинди | 343.9 млн | 4.25% | 🌏 Юж. Азия |
| 5 | Арабский | 274 млн | 3.38% | 🌍 Африка, 🌏 Западн. Азия |
| 6 | Бенгальский | 228 млн | 2.81% | 🌏 Юж. Азия |
| 7 | Португальский | 220 млн | 2.72% | 🌎 Америка, 🌍 Африка |
| 8 | Русский | 150 млн | 1.85% | 🌍 Европа |
| 9 | Японский | 125.4 млн | 1.55% | 🌏 Восточн. Азия |
| 10 | Панджаби | 125 млн | 1.54% | 🌏 Юж. Азия |
| ... | ... | ... | ... | ... |

**Итого:** 3.68 млрд говорящих = **45.4% мирового населения**

### Источники данных:
- 🔗 [Ethnologue 2025](https://www.ethnologue.com)
- 🔗 [United Nations UNPD](https://www.un.org/development/desa/pd/)
- 🔗 [Organization Internationale de la Francophonie](https://www.francophonie.org)

---

## 🎨 Технологический стек

### Frontend:
- **HTML5** — семантическая разметка
- **CSS3** — современные фишки (Grid, Flexbox, Gradients, Filters)
- **JavaScript ES6+** — чистый код без фреймворков

### Библиотеки:
- **Chart.js 3.9.1** — графики (через CDN)
- **Google Fonts** — типографика (Sora, Playfair Display)

### Инструменты разработки:
- VS Code
- Git & GitHub
- Chrome DevTools

### Хостинг:
- GitHub Pages (бесплатный, надёжный)

---

## 💻 Примеры кода

### Функция сортировки таблицы:
```javascript
function sortTable(headerCell, dataType) {
    const table = headerCell.closest('table');
    const tbody = table.querySelector('tbody');
    const rows = Array.from(tbody.querySelectorAll('tr'));
    const columnIndex = Array.from(headerCell.parentNode.children)
        .indexOf(headerCell);
    
    // Удалить классы сортировки у других заголовков
    table.querySelectorAll('th.sortable').forEach(th => {
        th.classList.remove('sort-asc', 'sort-desc');
    });
    
    const isAscending = !headerCell.classList.contains('sort-asc');
    
    // Сортировка в зависимости от типа данных
    rows.sort((a, b) => {
        const aValue = a.children[columnIndex].textContent.trim();
        const bValue = b.children[columnIndex].textContent.trim();
        
        if (dataType === 'number') {
            return isAscending ? 
                parseFloat(aValue) - parseFloat(bValue) :
                parseFloat(bValue) - parseFloat(aValue);
        }
        
        return isAscending ? 
            aValue.localeCompare(bValue, 'ru') :
            bValue.localeCompare(aValue, 'ru');
    });
    
    // Добавить обратно отсортированные строки
    rows.forEach(row => tbody.appendChild(row));
    
    // Обновить класс сортировки
    headerCell.classList.add(isAscending ? 'sort-asc' : 'sort-desc');
}
```

### CSS Glassmorphism эффект:
```css
.stat-box {
    background: linear-gradient(
        135deg, 
        rgba(255, 255, 255, 0.07) 0%, 
        rgba(255, 255, 255, 0.02) 100%
    );
    border: 1px solid rgba(255, 255, 255, 0.12);
    backdrop-filter: blur(15px);
    border-radius: 20px;
    transition: all 0.3s ease;
}

.stat-box:hover {
    background: linear-gradient(
        135deg, 
        rgba(255, 255, 255, 0.11) 0%, 
        rgba(255, 255, 255, 0.05) 100%
    );
    transform: translateY(-4px);
}
```

### Инициализация Chart.js:
```javascript
const ctxDist = document.getElementById('distributionChart')
    .getContext('2d');
    
window.distributionChart = new Chart(ctxDist, {
    type: 'bar',
    data: {
        labels: ['Мандарин', 'Испанский', ...],
        datasets: [
            {
                label: 'Азия',
                data: [929, 0, 70, ...],
                backgroundColor: '#22c55e'
            },
            // ... остальные континенты
        ]
    },
    options: { /* конфигурация */ }
});
```

---

## 📱 Адаптивность

### Desktop (1600px+)
- Два столбца: график + статистика
- Полный размер всех элементов
- Оптимально для мониторов

### Tablet (900px - 1200px)
- Один столбец (график над статистикой)
- Масштабирование элементов
- Удобно на планшетах

### Mobile (< 900px)
- Один столбец
- Уменьшенные шрифты
- Таблица прокручивается горизонтально
- Оптимизирована для пальца

---

## 🔐 Безопасность & Производительность

✅ **Безопасность:**
- Нет внешних скриптов (только Chart.js и Google Fonts с CDN)
- Нет отслеживания (no tracking, no cookies)
- Нет форм (нечего взламывать)

✅ **Производительность:**
- Размер HTML: ~250 KB
- Оптимизированный CSS (в одном файле)
- JavaScript без фреймворков (быстрый)
- CDN для внешних ресурсов (быстрая загрузка)

---

## 📚 Что я изучил через этот проект

### 1. **Web Design Trends 2025**
   - Glassmorphism
   - Gradient text
   - Dark theme с акцентными цветами
   - Backdrop filters

### 2. **Интерактивность**
   - Tab switching
   - Table sorting
   - Chart animations
   - Hover effects

### 3. **Data Visualization**
   - Chart.js library
   - Stacked bar charts
   - Doughnut charts
   - Custom colors & legends

### 4. **Responsive Design**
   - Mobile-first approach
   - CSS Grid & Flexbox
   - Media queries
   - Touch-friendly UI

### 5. **Чистый код**
   - Семантический HTML
   - Организованный CSS (с префиксами классов)
   - Читаемый JavaScript
   - Комментарии к сложным функциям

---

## 🚦 Статус проекта

| Функция | Статус |
|---------|--------|
| HTML структура | ✅ Завершено |
| CSS стили | ✅ Завершено |
| JavaScript функции | ✅ Завершено |
| Графики Chart.js | ✅ Завершено |
| Сортировка таблиц | ✅ Завершено |
| Переключение вкладок | ✅ Завершено |
| Адаптивный дизайн | ✅ Завершено |
| Данные & источники | ✅ Завершено |
| Документация | ✅ Завершено |

---

## 📖 Документация

- 📄 **README.md** — этот файл (обзор проекта)
- 📄 **SOURCES.md** — источники данных
- 📄 **docs/ZEROBLOCK_SETUP_GUIDE.md** — интеграция в Tilda
- 📄 **docs/TILDA_FREE_COMPATIBILITY.md** — совместимость
- 📄 **docs/FREE_HOSTING_GUIDE.md** — гайд по хостингу

---

## 🔗 Полезные ссылки

### Использованные ресурсы:
- [Chart.js документация](https://www.chartjs.org/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [GitHub Pages Guide](https://pages.github.com/)

### Данные:
- [Ethnologue: Languages of the World](https://www.ethnologue.com)
- [UN Population Division](https://www.un.org/development/desa/pd/)

---

## 💡 Что можно улучшить (для будущего)

- [ ] Добавить фильтр по континентам
- [ ] Экспорт данных в CSV
- [ ] Темный/светлый режим переключатель
- [ ] Поиск по названию языка
- [ ] Информацию о каждом языке при клике
- [ ] Анимация при загрузке страницы
- [ ] PWA версия (работает offline)

---

## 👨‍💻 Автор

**Тренировка веб-кодинга**

Этот проект создан как учебный материал для практики:
- HTML5, CSS3, JavaScript
- Работа с данными
- Создание интерактивных UI
- Адаптивный дизайн
- Деплой на GitHub Pages

---

## 📄 Лицензия

MIT License - используйте как хотите!

---

## 🙏 Благодарности

- Chart.js команде за потрясающую библиотеку
- Google Fonts за красивые шрифты
- Всем источникам данных о языках

---

## 📞 Обратная связь

Если нашли баги или есть идеи улучшения:
1. Откройте Issue на GitHub
2. Создайте Pull Request с улучшениями
3. Напишите в discussions

---

## 🎯 Заключение

Этот проект демонстрирует:
- ✅ Чистый, организованный код
- ✅ Современный веб-дизайн
- ✅ Интерактивность без фреймворков
- ✅ Адаптивность на всех устройствах
- ✅ Работа с данными и визуализацией

**Это отличный пример для портфолио веб-разработчика!** 🚀

---

**Создано:** 2025  
**Последнее обновление:** Февраль 2026  
**Статус:** Тренеровочный проект
