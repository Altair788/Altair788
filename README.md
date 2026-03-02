# 👋 Eduard Slobodyanik — Python Backend Developer

> 📌 **Python-разработчик с фокусом на REST API, микросервисы, ML-интеграции и AI-агенты. Создаю масштабируемые решения на FastAPI/Django/DRF и проектирую AI-системы с RAG, LLM и автоматизацией.
Автор open source-пакета для автоматизации тестирования DRF API.**

>  Повышаю экспертность в School21 (направление — backend, языки C, Golang (на 2026 год)).  
> 🥉 **4 место из 22 команд в Хакатоне Glowbyte AUTUMN 2025.**

> 🎓 Имею диплом государственного образца по специальности Python-разработчик, прошел ряд курсов и посетил несколько конференций (Positive hack days, IT-Пикник, AIJ и др.).  
> 💡 Ориентируюсь на результат, поддерживаю инженерную культуру, автоматизирую процессы разработки и code-review.
> 
> 🎯 Интересуюсь развитием в области высоконагруженных систем и AI-агентов (LangChain/LangGraph).


---

## 🚀 Коммерческие проекты (более 17 реализованных решений)

### 1. 🟢 SINGLE — Сервис электронных пропусков с интеграцией IoT-шлагбаумов  
*(Python 3.12, FastAPI, Celery, Redis, Docker)*  
- Автоматизация выдачи временных пропусков, интеграция с IoT-оборудованием.  
- Обработано свыше **50 000 заявок** с момента запуска.  
- **Сокращение времени ожидания на въезде на 90%**, снижение затрат на охрану до **20–30%**.  
- Кастомизация под клиента — разработано **более 5 дополнительных решений**.  
🔗 [Статья на VC.ru](https://vc.ru/dev/1832401-kak-my-avtomatizirovali-proezd-v-parking-v-klastere-lomonosov-i-izbavili-gostei-ot-ocheredei)

---

### 2. 🔵 COMMAND — Интеграция с Контур.Реестро API (AI due diligence)  
*(FastAPI, PostgreSQL, Nginx, Celery)*  
- Backend для получения сведений об объектах, истории владения, банкротстве.  
- Покрытие тестами, настройка Nginx как реверс-прокси, документация API.  
- Подготовлено и сгенерировано свыше **1000 отчетов** с момента запуска.  

---

### 3. 🔵 COMMAND — Парсер курсов валют и агрегация данных  
*(FastAPI, aiohttp, Playwright, Docker, PostgreSQL)*  
- Сервис для получения актуальных курсов валют с высокой точностью за счёт прямого парсинга с веб-сайтов (Playwright).  
- Обеспечивает актуальность данных на **10–15 секунд быстрее**, чем через API — критично при высокой волатильности.  

---

### 4. 🟢 SINGLE — Система оценки качества услуг с QR-кодами  
*(Python 3.12, PostgreSQL, SQLAlchemy ORM, Docker)*  
- Сервис для сбора обратной связи от пользователей через генерируемые QR-коды.  
- Оптимизированы SQL-запросы → **снижение времени отклика на 30–40%**.  
- Интегрирован с внутренней инфраструктурой клиента (государственная структура).  
- Получено более **500 отзывов**, рост удовлетворённости клиентов на **20%**.  
- Проект масштабирован и используется в ежедневной операционной деятельности.  

---

### 5. 🟢 SINGLE — Система визуализации логистических данных
*(JavaScript ES6, Google Apps Script, Leaflet.js, Nominatim API, OpenStreetMap)*
- Разработал full-stack решение для автоматического геокодинга и визуализации адресов из Google Sheets
- Заменил платные Google Geocoding/Maps API ($5-7/1000 запросов) на бесплатные Nominatim + Leaflet.js → экономия ~$200/мес при масштабировании
- Реализовал кэширование, rate-limiting и обработку ошибок (429/403) для соблюдения лимитов бесплатного тарифа
- Обеспечил точность геокодинга >95%, автообновление данных каждые 5 минут
- Добавил экспорт в KML, управление видимостью слоёв, логирование ошибок в отдельный лист

**Результаты:**
- Экономия ~$200/мес при масштабировании (10 пользователей × 50 адресов)
- Точность геокодинга: >95% для адресов СПб и МО (47/49 адресов)
- Время обновления: с ручного (15-30 мин) до автоматического (1-5 мин)

🔗 [Демо](https://script.google.com/...) | 🔗 [Код](https://github.com/Altair788/delivery-map-sync)

---

### 6. 🟢 SINGLE — Платформа объявлений adHub  
*(Django, DRF, PostgreSQL, Docker)*  
- MVP за 3 дня, оптимизированный для быстрого вывода продукта.  
- Безопасность: JWT, UID вместо ID, антиспам.  
- Кеширование → **−30% времени обработки запросов**.  
- Ролевая модель (user/admin).  
- Docker-развертывание с PostgreSQL и Gunicorn.  
- Покрытие тестами **97%** (pytest, coverage).  
🔗 [GitHub](https://github.com/Altair788/AdHub.git  )  
🔗 [Swagger API](http://178.208.85.7:8082/swagger/)  
🔗 [Админ-панель](http://178.208.85.7:8082/admin/login/?next=/admin/)  
*(login: demo_admin@mail.ru, pass: UZw5qXBVIsdrt7shgGrdc)*

---

## 🏆 Open Source & Хакатоны

### 🔹 DRF Universal API Test Mixins
[![PyPI](https://img.shields.io/pypi/v/drf-universal-api-test-mixins.svg  )](https://pypi.org/project/drf-universal-api-test-mixins/  )
[![GitHub](https://img.shields.io/github/repo-size/Altair788/drf-universal-api-test-mixins  )](https://github.com/Altair788/drf-universal-api-test-mixins  )
> Инструмент для автоматизации тестирования DRF API — сокращает время написания тестов на 70%. Используется в реальных проектах.

---

### 🔹 Coal Fire Alert Service (Хакатон)
[![GitHub](https://img.shields.io/github/repo-size/Altair788/coal-fire-alert-service  )](https://github.com/Altair788/coal-fire-alert-service.git  )
> Асинхронный FastAPI-сервис + YOLOv11 + Telegram-бот. Обнаруживает огонь/дым на складах угля → мгновенные оповещения.

---

### 🔹 Coal Fire Predictor (GlowByte Hack 2025)
[![GitHub](https://img.shields.io/github/repo-size/Altair788/coal-fire-predictor  )](https://github.com/Altair788/coal-fire-predictor  )
> Прогноз риска самовозгорания угля на 3 дня через ML (joblib). Clean Architecture, FastAPI, PostgreSQL, Docker.

---

## 🛠️ Образовательные проекты

- Разработал персонализированного ИИ-агента на базе GigaChat и n8n для анализа рынка труда, рекомендации специализаций и автоматической генерации учебных планов. Система ежедневно анализирует Telegram-каналы и вакансии (HH.ru), формируя дайджесты с актуальными навыками и трендами.
- Реализовал RAG-систему для подбора релевантных вакансий на основе анализа резюме и личностных данных, используя Hugging Face эмбеддинги, векторное хранилище и GigaChat.
- Автоматизировал сбор, суммаризацию и доставку контента через Telegram-бота с контекстным запоминанием (SimpleMemory) и интеграцией внешних API (Tavily Search).

---

## 💼 Технологический стек

| Категория | Технологии |
|-----------|-----------|
| **Языки** | Python 3.12+, C, JavaScript (ES6), SQL, Bash |
| **Backend** | DDD, FastAPI, Django/DRF, asyncio/aiohttp, Celery, Redis, PostgreSQL, SQLAlchemy, Pydantic |
| **Infra/DevOps** | Docker, Kubernetes, Nginx, GitHub Actions, Linux, Git, Flower, Google Apps Script |
| **Data/Analytics** | ClickHouse, Apache Kafka, Pandas, NumPy, Playwright |
| **AI/ML** | GigaChat API, RAG, LangChain, llama.cpp, Hugging Face, Nominatim API |
| **Testing** | pytest, coverage, TDD, DRF Universal API Test Mixins (own package) |
| **Frontend** | Leaflet.js, OpenStreetMap, HTML/CSS |

---

## 📫 Контакты

- 📬 Email: slobodyanik.ed@gmail.com  
- 📱 Telegram: [@eslobodyanik](http://t.me/eslobodyanik)  
- 💻 GitHub: [Altair788](https://github.com/Altair788  )  
- 🌐 LinkedIn: *(по запросу)*

---

> *Готов подтвердить свои навыки тестовым заданием или интервью. Детали всех проектов — в репозиториях.*
