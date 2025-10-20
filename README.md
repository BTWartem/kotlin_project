# Сапёр (Minesweeper)

![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-blue.svg)
![Java](https://img.shields.io/badge/Java-11%2B-orange.svg)
![JavaFX](https://img.shields.io/badge/JavaFX-17-purple.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Классическая игра "Сапёр", реализованная на Kotlin с использованием JavaFX для desktop-платформ.

![Главный экран игры](screenshots/game_screenshot.png)

## 🚀 Особенности

- **Три уровня сложности**:
  - 🟢 Новичок (8x8, 10 мин)
  - 🟡 Любитель (16x16, 40 мин) 
  - 🔴 Эксперт (16x30, 99 мин)

- **Интуитивный интерфейс**:
  - Визуальные смайлики для отображения состояния игры
  - Счетчик оставшихся мин
  - Простое управление мышью

- **Полная реализация геймплея**:
  - Открытие ячеек левой кнопкой мыши
  - Установка/снятие флажков правой кнопкой мыши
  - Автоматическое открытие пустых областей
  - Определение победы и поражения

## 🛠 Технологии

- **Язык**: Kotlin 1.9.0
- **Фреймворк UI**: JavaFX 17
- **Архитектура**: MVC (Model-View-Controller)
- **Система сборки**: Gradle
- **Целевая платформа**: Desktop (Windows, Linux, macOS)

## 📦 Установка и запуск

### Предварительные требования

- JDK 11 или выше
- Git

### Сборка и запуск

1. **Клонирование репозитория**:
   ```bash
   git clone https://github.com/BTWartem/kotlin_project.git
   cd kotlin_project
