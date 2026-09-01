<style>
.markdown-body {
  max-width: 860px !important;
  margin: 0 auto !important;
  padding: 36px 28px 88px !important;
  color: #20242a !important;
  font-size: 17px !important;
  line-height: 1.72 !important;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3 {
  border-bottom: 0 !important;
  padding-bottom: 0 !important;
  letter-spacing: -0.025em !important;
}

.markdown-body h1 {
  margin: 0 0 20px !important;
  font-size: 38px !important;
  line-height: 1.16 !important;
  font-weight: 760 !important;
}

.markdown-body h2 {
  margin: 52px 0 18px !important;
  font-size: 27px !important;
  line-height: 1.25 !important;
  font-weight: 720 !important;
}

.markdown-body h3 {
  margin: 30px 0 10px !important;
  font-size: 20px !important;
  line-height: 1.35 !important;
  font-weight: 680 !important;
}

.markdown-body p {
  margin: 0 0 17px !important;
}

.markdown-body ul,
.markdown-body ol {
  margin: 14px 0 24px !important;
  padding-left: 28px !important;
}

.markdown-body ul {
  list-style: disc !important;
}

.markdown-body ol {
  list-style: decimal !important;
}

.markdown-body li {
  display: list-item !important;
  margin: 7px 0 !important;
  padding-left: 3px !important;
}

.markdown-body li::marker {
  color: #7b8490 !important;
}

.markdown-body blockquote {
  margin: 24px 0 !important;
  padding: 16px 20px !important;
  color: #353b44 !important;
  background: #f6f7f9 !important;
  border-left: 4px solid #8b96a5 !important;
  border-radius: 0 10px 10px 0 !important;
}

.markdown-body blockquote > :last-child {
  margin-bottom: 0 !important;
}

.markdown-body hr {
  height: 1px !important;
  margin: 44px 0 !important;
  border: 0 !important;
  background: #e8eaed !important;
}

.markdown-body code:not(pre code) {
  padding: 0.16em 0.42em !important;
  border-radius: 6px !important;
  background: #f1f3f5 !important;
  font-size: 0.9em !important;
}

.markdown-body pre {
  margin: 22px 0 !important;
  padding: 18px 20px !important;
  border-radius: 12px !important;
  overflow-x: auto !important;
}

.markdown-body img {
  display: block !important;
  max-width: 100% !important;
  height: auto !important;
  margin: 28px auto !important;
  border: 1px solid #e7e9ec !important;
  border-radius: 12px !important;
}

.markdown-body a {
  text-decoration-thickness: 1px !important;
  text-underline-offset: 3px !important;
}

@media (max-width: 720px) {
  .markdown-body {
    padding: 24px 18px 64px !important;
    font-size: 16px !important;
  }

  .markdown-body h1 {
    font-size: 32px !important;
  }

  .markdown-body h2 {
    margin-top: 42px !important;
    font-size: 24px !important;
  }
}
</style>

# Добро пожаловать в Axottle 👋

Добро пожаловать в **Axottle Academy**.

В этом курсе мы не будем заставлять вас сначала изучать десятки страниц документации и запоминать назначение каждой кнопки. Вместо этого сразу начнём с практики.

Шаг за шагом вы установите Axottle, подключите существующую инфраструктуру и соберёте свою первую рабочую конфигурацию.

> **Цель курса**  
> Пройти путь от чистой установки Axottle до первой применённой Connection Unit.

## Что мы построим

К концу курса у вас будет понятна базовая цепочка работы:

> **Remnawave → Axottle → Gateway → Entry Node → Internet**

Пока достаточно понимать четыре вещи:

- **Remnawave** хранит пользователей и связанные с ними данные;
- **Axottle** помогает управлять инфраструктурой;
- **Node** — сервер, участвующий в вашей инфраструктуре;
- **Connection Unit** описывает путь подключения и движения трафика.

Не переживайте, если некоторые термины пока незнакомы. Мы разберём их тогда, когда они понадобятся на практике.

## Что вы сделаете в этом курсе

За время прохождения курса вы:

- установите Axottle;
- выполните первоначальную настройку панели;
- активируете лицензию;
- подключите Remnawave;
- выполните первую синхронизацию;
- добавите первый сервер в Axottle;
- установите Axottle Agent;
- убедитесь, что Node находится в состоянии **Online**;
- создадите первую Connection Unit;
- проверите конфигурацию;
- примените её.

После этого у вас будет базовое понимание того, как устроена работа с Axottle и как связаны основные компоненты платформы.

## Как устроено обучение

Мы придерживаемся простого принципа:

> **Сначала результат — потом детали.**

Каждое практическое занятие строится примерно одинаково.

### 1. Объясняем задачу

Сначала коротко разбираем, **что нужно сделать и зачем это нужно**. Без длинной теории перед первым действием.

### 2. Показываем интерфейс

В уроках используются реальные скриншоты Axottle. На них будут выделены только те кнопки, поля и разделы, которые нужны на текущем этапе.

### 3. Вы повторяете действие у себя

После объяснения выполняете тот же шаг в собственной установке Axottle.

> **Практика**  
> Если в уроке есть такой блок, пора переключиться в свою панель и выполнить указанное действие.

### 4. Проверяем результат

После важных этапов будет указано состояние, которое вы должны увидеть.

> **Ожидаемый результат**  
> Например, после добавления сервера Node должна отображаться со статусом **Online**.

Если результат отличается, разберём наиболее распространённые причины и точки проверки.

## Не пытайтесь изучить всё сразу

В Axottle значительно больше возможностей, чем понадобится в первом курсе:

- мониторинг и Health;
- сложная маршрутизация;
- Transit Nodes;
- WARP;
- CDN;
- резервное копирование;
- диагностика;
- безопасность;
- Axosun;
- автоматизация.

Мы специально не будем подробно разбирать их сейчас.

Первый курс посвящён только основному маршруту:

> **Установка → Remnawave → Node → Connection Unit → Apply**

Когда этот процесс станет понятен, переходить к более сложным возможностям Axottle будет намного проще.

## Что понадобится

Для практической части курса желательно подготовить:

- действующую лицензию Axottle;
- сервер для установки Axottle;
- root- или sudo-доступ к серверу;
- домен для панели, если вы планируете использовать HTTPS;
- работающую установку Remnawave;
- сервер, который можно будет добавить в качестве первой Node.

Если чего-то из этого пока нет — ничего страшного. В следующих занятиях мы отдельно разберём требования и подготовим всё необходимое.

## Ваш прогресс

На протяжении курса мы постепенно соберём четыре основных элемента.

### Axottle Lab

- ⬜ Axottle Panel
- ⬜ Remnawave
- ⬜ Первая Node
- ⬜ Первая Connection Unit

В конце курса список должен выглядеть так:

- ✅ Axottle Panel
- ✅ Remnawave
- ✅ Первая Node
- ✅ Первая Connection Unit

## Academy и документация

Axottle Academy не заменяет официальную документацию. У них разные задачи.

**Academy** отвечает на вопрос:

> Как мне сделать это в первый раз?

**Документация** отвечает на вопрос:

> Как именно работает эта функция и какие параметры у неё есть?

Поэтому в уроках будут появляться ссылки на документацию для тех, кто хочет разобраться глубже. Для прохождения базового курса читать документацию целиком не требуется.

## Перед следующим занятием

Убедитесь, что основная идея понятна:

- мы собираем первую рабочую инфраструктуру Axottle шаг за шагом;
- знать все возможности платформы заранее не требуется;
- документация остаётся справочником, а Academy ведёт вас по практическому сценарию.

> **Следующее занятие:** Как устроен Axottle
