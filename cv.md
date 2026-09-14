# АБДИГАФУРОВ ХУСАНЖОН

**Fullstack-разработчик · React / Node.js / TypeScript**

---

## Контактная информация

📧 **Email:** [abdigafurovhusan@gmail.com](mailto:abdigafurovhusan@gmail.com)  
🇺🇿 **Локация:** Ташкент, Узбекистан  
🔗 **LinkedIn:** [LinkedIn профиль](https://www.linkedin.com/in/husan-abdigafurov-a45389220/)  
💻 **GitHub:** [github.com/abdigafurov](https://github.com/husanGuru)  
💬 **Telegram:** [@husanGuru](https://t.me/husan_devs)

---

## О СЕБЕ

Fullstack-разработчик с многолетним опытом в продуктовых компаниях и агентствах. Занимаюсь полным циклом разработки — от архитектуры до деплоя и поддержки, работал как в команде, так и руководя ей. Реализовывал проекты разного масштаба: от коммерческих сайтов до продуктов с большой пользовательской аудиторией, в том числе с внедрением AI-функций в production.

Мои сильные стороны:

- 🚀 Полный цикл разработки: от архитектуры до деплоя
- 🤖 Опыт интеграции AI-функций в production (OpenAI, LangChain)
- 👥 Опыт руководства и масштабирования команды
- 🏗️ TypeScript по всему стеку: React/Next.js, NestJS/Express, MySQL/PostgreSQL, Redis
- 🔄 Реализовал 20+ коммерческих проектов разного масштаба

---

## НАВЫКИ

| Категория          | Технологии                                                                                          |
| ------------------ | --------------------------------------------------------------------------------------------------- |
| **Frontend**       | React, Next.js, TypeScript, Tailwind CSS, Material UI, Redux, Zustand, Vite                         |
| **Backend**        | Node.js, NestJS, Express, MySQL, PostgreSQL, MongoDB, Redis, ClickHouse, Prisma, TypeORM, Sequelize |
| **Тестирование**   | Jest, React Testing Library, Playwright, Vitest                                                     |
| **AI**             | OpenAI API, LangChain, Claude Code, Cursor, GitHub Copilot                                          |
| **DevOps & Tools** | Docker, Git, CI/CD, REST API, GraphQL, Figma, Strapi, Linux                                         |

---

## ПРИМЕРЫ КОДА

### Решение с Codewars: Grid Partition

Задача: проверить, можно ли разделить сетку на две части с равной суммой элементов

```typescript
function canPartitionGrid(grid: number[][]): boolean {
  const n = grid.length;

  // Вычисляем общую сумму
  const total = grid.reduce(
    (acc, row) => row.reduce((sum, val) => sum + val, 0) + acc,
    0,
  );

  // Проверяем горизонтальные разделения
  let tempSum = 0;
  for (let i = 0; i < n - 1; i++) {
    tempSum += grid[i].reduce((sum, val) => sum + val);
    if (tempSum === total - tempSum) {
      return true;
    }
  }

  // Проверяем вертикальные разделения
  tempSum = 0;
  const m = grid[0].length;
  for (let i = 1; i <= m - 1; i++) {
    tempSum += grid
      .map((row) => row.slice(i - 1, i))
      .reduce((acc, col) => col.reduce((sum, val) => sum + val, 0) + acc, 0);
    if (tempSum === total - tempSum) {
      return true;
    }
  }

  return false;
}
```

**Ключевые навыки:** TypeScript, алгоритмы, оптимизация

---

## ОПЫТ РАБОТЫ

### 🏢 Twistly.ai — Fullstack-разработчик

**Сентябрь 2023 – Июнь 2024**

- Разрабатывал надстройки Microsoft Office (React, TypeScript) для 3+ млн пользователей
- PowerPoint-надстройка с AI-генерацией презентаций заняла **№1 место** на Microsoft Marketplace (⭐ 4.7, 440+ отзывов)
- Внедрял AI-функции используя OpenAI API и LangChain
- Разрабатывал backend-сервисы на **NestJS, MySQL, Redis, ClickHouse**
- Проектировал UI на **React, Material UI, Zustand** с покрытием тестами (Jest, Playwright)
- Участвовал в архитектурных решениях и technical planning

**Технологический стек:** React, TypeScript, NestJS, MySQL, Redis, ClickHouse, OpenAI, LangChain

---

### 🏢 amoCRM / Kommo — Frontend-разработчик

**Апрель 2023 – Август 2023**

- Модернизировал legacy-фронтенд CRM: миграция с Backbone.js/jQuery на React + TypeScript
- Повысил производительность и улучшил поддерживаемость кода
- Мигрировал часть кодовой базы с JavaScript на TypeScript
- Разрабатывал интерфейсы для ключевых бизнес-процессов с интеграцией backend API

**Технологический стек:** React, TypeScript, Redux, REST API

---

### 🚀 Фриланс — Fullstack-разработчик

**Август 2022 – Апрель 2023**

- Реализовал под ключ business и e-commerce сайты для локальных клиентов
- Вёл полный цикл: требования → архитектура → разработка → деплой → поддержка
- Работал с **Next.js, Material UI, Express/Strapi, MySQL**

**Примеры проектов:**

- E-commerce платформа на Next.js + Express (MySQL, Stripe интеграция)
- Corporate website на Next.js с CMS функциональностью

---

### 🏢 The Agency (маркетинговое агентство) — Fullstack-разработчик → Тимлид

**Декабрь 2020 – Август 2022**

**Достижения:**

- Пришёл первым разработчиком и вырастил команду с **1 до 6 инженеров**
- Внедрил код-ревью, CI/CD и единые стандарты разработки
- Реализовал **20+ коммерческих проектов:**
  - интернет-магазины и e-commerce решения
  - корпоративные сайты
  - Telegram-боты (Telegraf.js)
  - интеграции со сторонними сервисами
  - **Примеры:** [parfumgallery.uz](https://parfumgallery.uz), [yapondokon.uz](https://yapondokon.uz), [iqwatt.uz](https://iqwatt.uz)

- Отвечал за оценку трудозатрат и приоритизацию задач
- Управлял пайплайнами деплоя и серверной инфраструктурой
- Обеспечивал качество релизов и поддержку production

**Технологический стек:** React, Next.js, Node.js, Express, NestJS, MySQL, PostgreSQL, Docker, CI/CD

---

## ОБРАЗОВАНИЕ

### 📚 Ташкентский университет информационных технологий (TUIT)

**2019 – 2023**

**Бакалавр** — Программная инженерия

---

### 🎓 RS School

**2025**

- **[REACT 2025 Q3](https://app.rs.school/certificate/njph6vik)** — Advanced React patterns, hooks, performance optimization
- **[NODEJS 2025 Q2](https://app.rs.school/certificate/riu0l7ga)** — Backend development, REST APIs, database design

---

## АНГЛИЙСКИЙ ЯЗЫК

🌐 **Уровень:** C1 (Advanced)  
📜 **Сертификат:** IELTS 7.5 (2018)
