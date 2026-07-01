<div align="center">

# Базаров Михаил

### Fullstack AI Engineer · Data Scientist

<p align="center">  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+Engineer;Data+Scientist;Building+real+projects+step+by+step" alt="Typing SVG" /></p>


[![Telegram](https://img.shields.io/badge/Telegram-@DSt06-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/DSt06)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michailbazarov-835bb23b8)
[![Email](https://img.shields.io/badge/Email-mixailbaz%40yandex.ru-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mixailbaz@yandex.ru)

</div>

---

## About

Собираю AI-продукты от гипотезы до прода, в связке с AI-агентами: чат-боты, RAG-пайплайны, агентские системы, интеграции с внешними сервисами. Параллельно занимаюсь Data Science — EDA, статистические гипотезы, ML-модели, A/B-тесты с полным циклом (power analysis, статзначимость, деплой дашбордов).

Fullstack-бэкграунд позволяет доводить фичу от идеи до результата самостоятельно: от архитектуры и данных до интерфейса.

Учусь на 2 курсе ГУАП (Программная инженерия). Открыт к задачам в AI Engineering, Data Science и продуктовой аналитике.

---

## Experience

**Fullstack AI Engineer · ZOLT Agency** — май 2026 – наст. время
Веду AI-продукты агентства целиком: чат-боты и LLM-ассистенты, RAG-пайплайны и базы знаний, агентские системы с инструментами и памятью, интеграции с мессенджерами/CRM/API, мониторинг после релиза.

**Fullstack AI Engineer · AgentAPI** — ноя 2025 – наст. время
Платформа-агрегатор AI-моделей (единый API к OpenAI, Anthropic, Gemini). Дашборды продуктовой аналитики, оптимизация SQL на PostgreSQL, фичи end-to-end на NestJS/TypeORM/React.

---

## Tech Stack

| Область | Инструменты |
|---|---|
| **AI / LLM** | LLM API (OpenAI, Anthropic) · RAG · AI-агенты · чат-боты |
| **AI-кодинг** | Cursor · Claude Code |
| **Data Science** | pandas · numpy · scikit-learn · SciPy · SHAP · Optuna |
| **Backend** | Node.js · NestJS · PostgreSQL · REST API |
| **Frontend** | React · TypeScript |
| **Languages** | Python · TypeScript · SQL |
| **Tools** | Git · GitHub · Jupyter |

---

## Featured Projects

### A/B-тест алгоритма рекомендаций
`Python` `SQL` `PostgreSQL` `SciPy` `Plotly Dash` `Docker` · сен – окт 2025

Полный цикл эксперимента: power analysis (22 848 пользователей на группу, 14 дней), SRM- и A/A-тест перед запуском, калибровка false positive rate на 1000 пересплитах.

- delta method (cluster-robust variance) для корректности при рандомизации на уровне пользователя
- прирост конверсии **+10.1%** (p=2.5e-18) и среднего чека **+5.5%** (p=0.0001) с поправкой Бенджамини-Хохберга
- дашборд на Plotly Dash, задеплоенный в Docker

### Avito Demand Prediction — EDA & ML
`pandas` `scikit-learn` `SciPy` `SHAP` `Optuna` · июн – авг 2025

Статистический анализ рынка на 1.5 млн объявлений и двухэтапная ML-модель (классификация + регрессия) для прогноза сделок.

- Kruskal-Wallis и попарный Mann-Whitney с поправкой Бенджамини-Хохберга: эффект категории (ε²=0.55) оказался в 32 раза сильнее регионального (ε²=0.017)
- leakage-safe target encoding, TF-IDF+SVD; RMSE снижен на 13% (0.226 против 0.260), ROC-AUC 0.815
- доведено до production: модульный пакет, 17 pytest-тестов, CI на GitHub Actions, SHAP-интерпретация

---

<div align="center">
<sub>Санкт-Петербург · Open to AI Engineering / Data Science</sub>
</div>
