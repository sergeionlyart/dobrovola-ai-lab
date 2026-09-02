# AI-native Web Product 01

[Русский](#русский) · [English](#english)

## Русский

### Цель модуля

За девять часов участник проходит полный цикл создания первого веб-продукта вместе с AI-агентами:

- 3 онлайн-занятия по 60 минут;
- 2 часа самостоятельной лаборатории после каждого занятия;
- итоговая сдача работающего продукта и проектных артефактов.

Курс не обещает сделать участника профессиональным веб-разработчиком за три встречи. Он даёт воспроизводимый процесс: сформулировать идею, подготовить blueprint, передать milestone руководителю, организовать автономную работу исполнителя, проверить доказательства и выпустить первую версию.

### Основной паттерн

```text
Пользователь → milestone руководителю
Руководитель → крупные рабочие пакеты исполнителям
Исполнитель → автономная реализация и отчёт
Руководитель → проверка, интеграция и финальная приёмка
```

Роль назначается простой командой в чате:

- `Ты руководитель` — агент читает [`starter/roles/leader.md`](starter/roles/leader.md);
- `Ты исполнитель` — агент читает [`starter/roles/executor.md`](starter/roles/executor.md).

Маршрутизация и обязательные правила прописаны в [`starter/AGENTS.md`](starter/AGENTS.md).

### Итоговый продукт

Одностраничный сайт компании, услуги, проекта или курса с одним полным пользовательским сценарием:

```text
Ценность → призыв к действию → форма заявки
→ проверка данных → подтверждение → запись на встречу
```

### Контрольные точки

1. `READY` — рабочая среда подготовлена.
2. `SCOPE APPROVED` — blueprint и границы проекта приняты.
3. `VERTICAL WORKS` — основной сценарий работает локально.
4. `RELEASED` — продукт проверен, опубликован и изменён студентом самостоятельно.

### Начало работы

1. Прочитайте [START_HERE.md](START_HERE.md).
2. Изучите [программу](SYLLABUS.md).
3. Используйте [пакет промптов](PROMPTS.md).
4. Заполняйте документы из каталога [`templates/`](templates/).
5. Установите настройки из каталога [`starter/`](starter/).

### Границы первой версии

В обязательную программу не входят полноценная Figma-практика, собственная облачная инфраструктура, авторизация, платежи, сложная CRM, production-grade security и индивидуальная юридическая экспертиза. Эти темы относятся к следующим модулям.

> Статус: методический draft для первого пилота. Технологический профиль приложения должен быть зафиксирован преподавателем до начала потока.

---

## English

### Module goal

In nine hours, the participant completes the full cycle of building a first web product with AI agents:

- three 60-minute online sessions;
- two hours of independent lab work after each session;
- a final submission with a working product and verifiable project artifacts.

The module does not promise professional web-development mastery in three meetings. It teaches a repeatable process: define the product, create a blueprint, assign an entire milestone to the leader, delegate substantial work packages to executors, verify evidence, and release a first version.

### Core operating pattern

```text
User → milestone to the leader
Leader → substantial work packages to executors
Executor → autonomous delivery and evidence report
Leader → verification, integration, and final acceptance
```

Role routing is defined in [`starter/AGENTS.md`](starter/AGENTS.md), with canonical role instructions in [`starter/roles/leader.md`](starter/roles/leader.md) and [`starter/roles/executor.md`](starter/roles/executor.md). The working instructions themselves are written in Russian for the initial Russian-speaking audience.

### Final product

A one-page website for a company, service, project, or course with one complete user flow:

```text
Value proposition → call to action → lead form
→ validation → confirmation → meeting booking
```

### Gates

1. `READY` — the environment is prepared.
2. `SCOPE APPROVED` — the blueprint and scope are accepted.
3. `VERTICAL WORKS` — the core flow works locally.
4. `RELEASED` — the product is reviewed, published, and independently changed by the student.

### Start here

Open [START_HERE.md](START_HERE.md), then follow the [syllabus](SYLLABUS.md), [prompt pack](PROMPTS.md), [`templates/`](templates/), and [`starter/`](starter/).

> Status: methodology draft for the first pilot. The application technology profile must be frozen by the instructor before the cohort begins.
