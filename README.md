# <img src="docs/logo.png" width="40"> Вяткино Агро Аналитик

**Платформа для анализа сельскохозяйственных данных с прогнозированием урожайности, контролем техники и финансовой аналитикой.**

[![Python 3.13](https://img.shields.io/badge/Python-3.13-%233776AB?logo=python)](https://www.python.org/)
[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL%203.0-green)](LICENSE)

---

## 🌟 Возможности
- **Анализ урожайности**  
  Прогнозирование урожая на основе данных почвы, метео и истории полей.
- **Контроль техники**  
  Мониторинг расхода топлива, пробега и простоя сельхозтехники.
- **Экономика хозяйства**  
  Расчет себестоимости культур, ROI удобрений, оптимизация расходов.
- **ГИС-картография**  
  Визуализация границ полей, зон болезней растений, карт продуктивности.
- **Мобильное приложение**  
  Офлайн-ввод данных скаутинга с фотофиксацией проблем.

---

## ⚙️ Технологический стек
| Компонент       | Технологии                          |
|-----------------|-------------------------------------|
| **Бэкенд**      | Python 3.13, FastAPI, PostGIS       |
| **Фронтенд**    | React, Leaflet, Chart.js            |
| **Мобильное**   | React Native (iOS/Android)          |
| **Базы данных** | PostgreSQL + TimescaleDB, Redis     |
| **Аналитика**   | Pandas, Scikit-learn, XGBoost      |
| **ГИС**         | GeoDjango, Rasterio, Satellite Imagery |
| **Инфраструктура** | Docker, GitHub Actions, AWS       |

---

## 🚀 Быстрый старт
### Установка
```bash
git clone https://github.com/your_username/viatkino_agro_analytics.git
cd viatkino_agro_analytics

# Создание виртуального окружения
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.\.venv\Scripts\activate   # Windows

# Установка зависимостей
pip install -r requirements.txt
