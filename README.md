# ModernDarkTime 🌓⏲️

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/equvale/ModernDarkTime/blob/main/LICENSE)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Современные цифровые часы с динамической анимацией и локализацией на русском языке. Идеальный компонент для персонального сайта или демонстрации возможностей веб-технологий.

![Скриншот интерфейса](https://raw.githubusercontent.com/equvale/ModernDarkTime/main/screenshot.png)

## 🌟 Особенности

- **Адаптивный дизайн** - идеальное отображение на любых экранах
- **Живые анимации**  
  - Мерцающие разделители времени
  - Эффект нажатия контейнера
- **Локализация**  
  - Дата на русском языке
  - Автоматическое обновление
- **Минималистичный стиль**  
  - Тёмная тема с оранжевым акцентом
  - Текстовые тени для эффекта свечения

## 🛠️ Технологии

| Категория       | Реализация                          |
|-----------------|-------------------------------------|
| **Вёрстка**     | HTML5 + CSS Grid/Flex               |
| **Стилизация**  | CSS-анимации, переходы              |
| **Логика**      | Нативный JavaScript (ES6)           |
| **Оптимизация** | Резиновая типографика, Debounce     |

## 🚀 Быстрый старт

1. Клонируйте репозиторий:
```bash
git clone https://github.com/equvale/ModernDarkTime.git

2. Откройте в браузере:

bash
Copy
xdg-open index.html  # Для Linux
open index.html      # Для macOS
start index.html     # Для Windows

## 🧩 Структура кода
Файловая структура:
bash 
Copy
index.html          # Основной файл
LICENSE            # Лицензия MIT
README.md          # Документация
screenshot.png     # Скриншот интерфейса
##  🔄 Логика работы

Инициализация:

javascript
Copy
new DigitalClock(); // Автозапуск при загрузке страницы
2. Обновление данных:

Каждую секунду через setInterval

Форматирование времени с дополнением нулей

 ##  🎨 Кастомизация
Измените в CSS:

css
Copy
:root {
  --accent-color: #ff9500; /* Основной акцентный цвет */
  --text-glow: 0 0 10px rgba(255,255,255,0.1); /* Эффект свечения */
}
 ## 🤝 Развитие проекта
Рекомендуемые улучшения:

Добавление переключателя тем

Интеграция с TimeZone API

Анимация перелистывания цифр
 ## 📄 Лицензия
MIT License © 2025 Equvale
Полный текст лицензии: LICENSE
