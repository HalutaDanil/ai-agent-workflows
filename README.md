<div align="center">

# AI Agent Workflows

**[English](#english) | [Русский](#русский)**

</div>

---

<a name="english"></a>
## 🇬🇧 English

This project is about building autonomous AI agents using the **n8n** low-code platform. The goal was to move beyond simple LLM prompts and create proactive systems that can make decisions, use external tools, and maintain context across interactions.

### What was done

| Task | What & Why |
|------|-----------|
| Task 2 | Deployed n8n on a cloud server and connected it to the **GigaChat** LLM API. Learned how to bridge a visual workflow engine with a language model. |
| Task 3 | Built a **Telegram career consultant bot**. It asks structured questions about experience, skills, and goals, then recommends a specialization. Used system prompts to turn a passive LLM into a proactive agent with memory. |
| Task 4 | Created an **automated news digest**. The agent parses RSS feeds from Telegram channels, summarizes posts with GigaChat, and sends a daily digest to a private channel. |
| Task 5 | Built a **job market analyzer**. Parses vacancies from HeadHunter via API, extracts top-15 most frequent skills using an AI agent, and sends a weekly report. Learned to handle real-world data imperfections and token costs. |
| Task 6 | Developed a **personal learning mentor bot**. It builds a study plan based on user input, then sends daily educational posts on schedule using web search (Tavily) for content generation. |
| Bonus | Implemented a basic **RAG pipeline** in n8n: chunked PDF resumes and job descriptions, embedded them via Hugging Face, stored in a vector DB, and retrieved relevant context for LLM answers. |

### Key takeaways
- Learned the difference between an **AI assistant** (passive, command-driven) and an **AI agent** (autonomous, goal-driven).
- Gained hands-on experience with **prompt engineering**, **memory management**, **tool use** (RSS, APIs, search), and **RAG**.
- Understood production risks: LLM stochasticity, data privacy when using external APIs, and the danger of blind trust in AI-driven strategic decisions.

### Tech Stack

![n8n](https://img.shields.io/badge/n8n-FF6D5A?style=flat-square&logo=n8n&logoColor=white) ![GigaChat](https://img.shields.io/badge/GigaChat-412991?style=flat-square) ![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-00A4EF?style=flat-square)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:58a6ff,50:1f6feb,100:0969da&height=2&section=header&text=&fontSize=1"/>
</div>

<a name="русский"></a>
## 🇷🇺 Русский

Проект по созданию автономных ИИ-агентов на платформе **n8n**. Цель — выйти за рамки простых промптов к LLM и построить проактивные системы, способные принимать решения, использовать внешние инструменты и сохранять контекст между взаимодействиями.

### Что было сделано

| Задача | Что и зачем |
|--------|-------------|
| Задача 2 | Развёрнут n8n на облачном сервере и подключен API **GigaChat**. Изучено, как связать визуальный конструктор workflow с языковой моделью. |
| Задача 3 | Создан **Telegram-бот карьерный консультант**. Задаёт структурированные вопросы об опыте, навыках и целях, затем рекомендует специализацию. Через системный промпт пассивная LLM превращается в проактивного агента с памятью. |
| Задача 4 | Собран **автоматический дайджест новостей**. Агент парсит RSS из Telegram-каналов, суммаризирует посты через GigaChat и шлёт дайджест ежедневно в приватный канал. |
| Задача 5 | Построен **анализатор рынка вакансий**. Парсит вакансии с HeadHunter через API, выделяет топ-15 навыков с помощью ИИ-агента и отправляет еженедельный отчёт. Опыт работы с "грязными" данными и контролем расхода токенов. |
| Задача 6 | Разработан **бот-наставник для обучения**. Формирует план изучения темы на основе запроса пользователя, затем по расписанию шлёт образовательные посты, генерируя контент через веб-поиск (Tavily). |
| Бонус | Реализован базовый **RAG-конвейер** в n8n: PDF-резюме и описания вакансий разбиты на чанки, эмбеддинги через Hugging Face, векторное хранилище, ретривал релевантного контекста для ответов LLM. |

### Ключевые выводы
- Понял разницу между **ИИ-ассистентом** (пассивный, управляемый командами) и **ИИ-агентом** (автономный, целеустремлённый).
- Практика в **промпт-инжиниринге**, **управлении памятью**, **использовании инструментов** (RSS, API, поиск) и **RAG**.
- Осознание production-рисков: стохастичность LLM, приватность данных при использовании внешних API, опасность слепого доверия к стратегическим решениям ИИ.

### Стек технологий

![n8n](https://img.shields.io/badge/n8n-FF6D5A?style=flat-square&logo=n8n&logoColor=white) ![GigaChat](https://img.shields.io/badge/GigaChat-412991?style=flat-square) ![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-00A4EF?style=flat-square)

---

<div align="center">

*Project from portfolio | Проект из портфолио*

</div>
