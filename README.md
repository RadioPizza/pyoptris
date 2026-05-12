# pyoptris

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PyPI version](https://badge.fury.io/py/pyoptris.svg)](https://badge.fury.io/py/pyoptris)
![Status](https://img.shields.io/badge/Status-Active%20development-orange)
![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
[![GitHub stars](https://img.shields.io/github/stars/RadioPizza/pyoptris)](https://github.com/RadioPizza/pyoptris/stargazers)

> 🚧 **Project Status: Early Development**  
> This repository is being actively developed. No stable release yet. Code will appear soon.
> 
> Сейчас репозиторий — это «скелет». Первый рабочий код появится в ближайшее время. Следите за обновлениями или подключайтесь к разработке! 🚀

## 🎯 Goal

`pyoptris` — это обёртка на Python для работы с тепловизорами **Optris** (серии PI и Xi) через официальный SDK `libirimager`.

**Зачем это нужно:**
- Писать код для тепловизоров на чистом Python, без C++ и компиляции
- Быстро прототипировать приложения для термографии
- Упростить интеграцию Optris в проекты на Python, например на фрейсворке PySide 6
- Дать студентам и коллегам понятный, документированный интерфейс к камере

## ✨ Планируемые возможности

| Фича | Статус |
|------|--------|
| 🔌 Инициализация камеры по USB | ⚪ В планах |
| 📸 Захват RGB-палитры и сырых температурных данных | ⚪ В планах |
| 🌡️ Конвертация значений в °C | ⚪ В планах |
| 🎨 Управление палитрами (Iron, Rainbow, Medical...) | ⚪ В планах |
| ️✨ Ручная и авто-калибровка затвора (flag) | ⚪ В планах |
| 🔒 Потокобезопасный захват кадров | ⚪ В планах |
| 🪟 Поддержка Windows 10/11 (AMD64) | ⚪ В планах |
| 🐧 Поддержка Linux (AMD64) | ⚪ В планах |
| 🐧 Поддержка Linux (ARM64) | ⚪ В планах |
