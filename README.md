# Ilya Skvortsov

AI / Software Engineer. Создаю прикладные AI-продукты целиком: от постановки
задачи, данных и evals до API, desktop/web-интерфейса, контейнера и CI.

Основной фокус — воспроизводимый ML, computer vision, local-first системы и
инструменты, которые автоматизируют реальную операционную работу.

## Selected work

| Проект | Задача и результат | Инженерный контур |
|---|---|---|
| [Local Document Generator](https://github.com/ilyascw/local-document-generator) | Desktop-приложение для пакетной генерации юридических DOCX-документов | Rust, Tauri, React, TypeScript, SQLite |
| [UnitKeeperBot](https://github.com/ilyascw/UnitKeeperBot) | Telegram Mini App для регулярных задач, peer approval и планирования спринтов | FastAPI, React, PostgreSQL, SQLAlchemy, Docker |
| [Local Meal Planner](https://github.com/ilyascw/local-meal-planner) | Недельное меню с ограничениями поставщика, сроками хранения, бюджетом и пищевыми нормами | Python, SQLite, Vanilla JS, Docker |
| [Chest CT Classification](https://github.com/ilyascw/chest-ct-classification) | Research pipeline для скрининга патологий на КТ грудной клетки | CT-CLIP, PyTorch, CatBoost, FastAPI |
| [Car Color Detector](https://github.com/ilyascw/CarColorDetector) | Детекция автомобиля, сегментация кузова и оценка доминирующего цвета | YOLOv8, SAM, FastAPI, Gradio |
| [Demand Forecasting](https://github.com/ilyascw/demand_forecasting) | Прогноз спроса в ритейле с корректной временной валидацией | CatBoost, Ridge, SARIMA, time-series evals |

## More projects

- [Early Retirement Risk Model](https://github.com/ilyascw/early-retirement-risk-model) — privacy-safe risk ranking, calibration и fairness audit.
- [Road Safety Video Analyzer](https://github.com/ilyascw/traffic_violation_checker) — desktop/CLI CV-pipeline для приоритизации эпизодов с видеорегистраторов.
- [Travel Dashboard](https://github.com/ilyascw/travel-dashboard) — аналитика маршрута, бюджета и расходов на воспроизводимых demo-данных.

## Engineering approach

- Сначала фиксирую бизнес-инварианты и критерии качества, затем выбираю модель.
- Для ML использую holdout/temporal validation, imbalance-aware метрики,
  calibration и воспроизводимые benchmarks.
- Пользовательские данные отделяю от demo-данных; предпочитаю local-first там,
  где облачная инфраструктура не создаёт продуктовой ценности.
- Поставляю проекты с типизацией, тестами, документацией, Docker и GitHub
  Actions — когда это соответствует масштабу задачи.

`Python` · `FastAPI` · `PyTorch` · `scikit-learn` · `OpenCV` · `React` ·
`TypeScript` · `Rust` · `Tauri` · `PostgreSQL` · `SQLite` · `Docker`
