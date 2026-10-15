
# Привет, я Артём 👋

Студент 2-го курса МАИ, направление «Прикладная математика и информатика».

Занимаюсь **Data Science и ML Engineering**. Разрабатываю ML-проекты на Python: от анализа данных, feature engineering и обучения моделей до REST API и контейнеризации.

## Основные проекты:

### 1. [Прогноз температуры по городам России](https://github.com/spTrent/Time_Series_Weather_Forecasting)

ML-сервис прогнозирования температуры для 6 городов России на горизонтах 1–7 дней.

**Результаты:**
- XGBoost: MAE **2.07 °C** на 1 день и **3.30 °C** на 7 дней.
- Снижение MAE относительно наивного бейзлайна на 11% и 21% соответственно.

**Что реализовано:**
- Direct-стратегия прогнозирования и временная валидация.
- Feature engineering: лаги, скользящие статистики, циклические признаки.
- ETL-пайплайн с Open-Meteo API и PostgreSQL.
- REST API на FastAPI, веб-интерфейс и Docker Compose.

Стек: `Python` `XGBoost` `Optuna` `FastAPI` `PostgreSQL` `Docker`

### 2. [Детекция ботов-парсеров](https://github.com/spTrent/bot_detection)

Классификация пользователей сайта объявлений по поведению в течение суток.

**Результаты:**
- CatBoost: **Precision 0.737 при Recall ≥ 0.7**.
- Логистическая регрессия: 0.471; rule-based бейзлайн: 0.227.

**Что реализовано:**
- EDA и разработка 58 поведенческих признаков.
- Обнаружение и устранение утечки таргета.
- Отложенный test по времени, GroupKFold и Optuna.
- Модульный ML-пайплайн, CLI для инференса и тесты.

Стек: `Python` `pandas` `CatBoost` `scikit-learn` `Optuna` `pytest`

## Опыт:
**Т1 Иннотех - стажёр-системный аналитик**  
Апрель - июнь 2026

В команде из 8 стажёров МАИ работал над реальным продуктом для Т1 в закрытом контуре.

- Взаимодействовал с заказчиками, анализировал требования.
- Проектировал архитектуру, схему БД и API-контракты.
- Разрабатывал ИИ-агента на Python.
- Команда победила в кейсе «Агрегатор мессенджеров».

## 🛠 Технологии

**Языки:** Python, SQL, C++

**Machine Learning:** scikit-learn, CatBoost, XGBoost, Optuna

**Data:** pandas, NumPy, PostgreSQL, Matplotlib

**Backend / DevOps:** FastAPI, Docker, Git

**Инструменты:** pytest, uv, ruff, mypy, pre-commit

## 📫 Контакты

- **Telegram:** [@amrazumov](https://t.me/amrazumov)
- **Email:** [artemrazumovvv@gmail.com](mailto:artemrazumovvv@gmail.com)
