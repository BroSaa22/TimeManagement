# ⏱️ Time Management Tracker

> Веб-приложение для отслеживания времени, анализа продуктивности
> и формирования привычек эффективного тайм-менеджмента.

![Status](https://img.shields.io/badge/status-MVP-success)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📋 О проекте

**Time Management Tracker** — веб-сайт, который помогает фиксировать,
сколько времени уходит на задачи, визуализировать статистику и находить
«пожирателей времени». Запускайте таймер, добавляйте записи вручную,
ставьте цели и смотрите аналитику по дням, неделям и месяцам.

Работает прямо в браузере — без установки и регистрации сложных настроек.

---

## ✨ Возможности

- ⏱️ **Таймер задач** — старт / пауза / стоп
- 📝 **Ручной ввод** — добавление записей задним числом
- 🏷️ **Категории и теги** — работа, учёба, спорт, отдых
- 📊 **Дашборд аналитики** — графики по дням, неделям, месяцам
- 🎯 **Цели и лимиты** — дневные и недельные нормы
- 📤 **Экспорт** — CSV, JSON, PDF-отчёты
- 🌙 **Тёмная тема** и адаптивная вёрстка

---

## 🛠️ Стек

| Слой | Технологии |
|------|-----------|
| Frontend | React + Vite + TypeScript + TailwindCSS |
| Backend | Node.js + Express + Prisma |
| БД | PostgreSQL (prod), SQLite (dev) |
| Графики | Recharts |
| Auth | JWT + bcrypt |
| Деплой | Docker + Nginx |

---

## 🚀 Быстрый старт

```bash
git clone https://github.com/username/time-management-tracker.git
cd time-management-tracker

npm install
cp .env.example .env
npm run migrate
npm run dev
