---
layout: default
title: "Айсылу Россахацкая — Junior Data Analyst"
description: "SQL · Python · BI · A/B-тесты"
---

Запустила аналитику с нуля в туристическом бизнесе: БД → дашборды → автоматизация сбора данных. <br>
Ищу роль дата-аналитика (remote), открыта к офису: Сочи · Шерегеш · Алматы.

<a href="/portfolio/resume.pdf" target="_blank">Скачать резюме</a><br>

---

## Мои проекты
---

### BI-система для туристического клуба  

**Задача.** Собрать с нуля аналитику заявок, оплат и обратной связи, чтобы команда видела воронку и сезонность.<br>
**Подход.** Спроектировала реляционную БД (PostgreSQL) → построила дашборды в Yandex DataLens → разработала Telegram-бота (Python) для отзывов → данные сохраняются в CSV, грузятся в Yandex Object Storage и автоматически обновляются (APScheduler).<br>
**Результат.** Сократила ручную отчётность с 4 ч до 30 мин/неделю; увеличила долю обратной связи с 20% до 65%.<br>
**Стек.** PostgreSQL, DataLens, Python (pandas, aiogram, APScheduler), Yandex Object Storage, DBeaver.<br>
**Схема базы данных** (структура таблиц): <br> 
![Схема базы данных](https://raw.githubusercontent.com/rshtsk/portfolio/main/img/shema_baza.png)
**Пример дашборда (DataLens):**  <br>
![Дашборд](https://raw.githubusercontent.com/rshtsk/portfolio/main/img/datalens_dashboard.png)<br>
**Фрагмент взаимодействия с Telegram-ботом:**  <br>
![Telegram-бот](https://raw.githubusercontent.com/rshtsk/portfolio/main/img/telegram_bot.png)<br>

---

### A/B-тест: влияние UI на конверсию заказа (food delivery) 

**Задача.** Проверить, повышают ли новые варианты интерфейса (формат фото, кнопка «Заказать») CR до оплаты.<br>
**Подход.** Очистка и исследование данных → проверка рандомизации → нормальность/гомогенность дисперсий → t-test/ANOVA/ → визуализации и выводы.<br>
**Результат.** Дала продуктовую рекомендацию (катить/не катить), оценила ожидаемый uplift и доверительные интервалы.<br>
**Стек.** Python (pandas, numpy, scipy, matplotlib), статистика, Jupyter.<br>
[Посмотреть на GitHub →](https://github.com/rshtsk/ab_test_food_delivery)<br>
**Влияние формата фотографий блюд на число заказов**<br>
![Число покупок и формат фото](https://raw.githubusercontent.com/rshtsk/ab_test_food_delivery/main/img/photo_format_vs_orders.png)

---

### SQL-аналитика: экономика продукта и маркетинговые метрики

**Задача.** Рассчитать ключевые метрики: ARPU/ARPPU/AOV, валовую прибыль, retention (когорты), CAC/ROI; сравнить рекламные каналы.<br>
**Подход.** CTE + оконные функции, когортный анализ, витрины под дашборд; визуализация в Redash.<br>
**Результат.** 5+ инсайтов по выручке и удержанию, рекомендации по перераспределению маркет-бюджета.<br>
**Стек.** SQL (PostgreSQL), Redash.<br>
[Посмотреть на GitHub →](https://github.com/rshtsk/sql_product_analytics)<br>
**Визуализация**<br>
![Динамика выручки и маржинальности](https://raw.githubusercontent.com/rshtsk/sql_product_analytics/main/img/economika_task_7_viz_1.png)

---
## Обо мне

Дата-аналитик с опытом BI и дата аналитики. <br>
Собрала работающую аналитику в турбизнесе: БД, дашборды, автосбор данных через Python-бота. <br>
Умею считать продуктовые метрики (воронка, retention, LTV), строить SQL-запросы и визуализации. <br>
Хочу развиваться в дата аналитике, работать с большими данными и приносить измеримый эффект бизнесу.<br>

---
## Навыки

**SQL:** PostgreSQL, ClickHouse · оконные функции · CTE<br>
**Python:** pandas, numpy, matplotlib, seaborn<br>
**BI:** Yandex DataLens, Redash · построение дашбордов и метрик<br>
**Статистика:** A/B-тесты, t-test/ANOVA, бутстрап, доверительные интервалы<br>
**Инструменты:** Git/GitHub, DBeaver, Jupyter, Google Sheets/Excel, PyCharm, Redash<br>

---

## Опыт работы

**Аналитик данных — «Траектория» (11.2024 — наст.)** <br> 
- Спроектировала БД (PostgreSQL) и дашборды (DataLens): заявки, загрузка туров, retention. <br> 
- Автоматизировала сбор обратной связи (Telegram-бот → CSV → Object Storage → BI), расписание APScheduler.  <br>
- Построила воронку продаж по этапам и источникам привлечения (VK Ads, Яндекс.Директ, рекомендации).  <br>
**Результат:** отчётность **4 ч → 30 мин/нед**; доля отзывов **20% → 65%**.  <br>
**Стек:** Python (pandas, aiogram, APScheduler), PostgreSQL, DataLens, YOS.  <br>

---

**Бизнес-аналитик (ранее бизнес-менеджер) — «Траектория» (11.2021 — 11.2024)**  <br>
- Учёт спроса по сезонам и форматам, финмодели: доходы/расходы.  <br>
- Построила воронку: заявка → звонок → бронь → выезд, рассчитала конверсию по шагам и каналам.  <br>
**Результат:** оптимизация маркет-расходов **−15%** при сохранении выручки.  <br>

---

**Инженер ПТО — «Базовый элемент» (09.2018 — 05.2019)**  <br>
- Расчёты трудозатрат/смет, работа с нормативами и документацией для госконтрактов.  <br>

---

## Образование и Курсы<br>
- **ПНИПУ** — Бакалавр, ПГС (2018)  <br>
- **Яндекс Практикум** — Основы статистики и A/B-тестирования (2025)  <br>
- **It minimalist** — Базовый Python (2025)  <br>
- **Karpov.courses** — Симулятор SQL; Основы Python (2024)  <br>

---

## Контакты
Открыта к full-time (remote) и офису: Сочи · Шерегеш · Алматы<br>
- [Telegram @akataevva](https://t.me/akataevva)
- [LinkedIn](https://www.linkedin.com/in/a-rossakhatskaya)
- [Habr](https://career.habr.com/rossakhatskaya)
- +7(982)4840190
- a.akataeva@ya.ru
