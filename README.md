# Геосфера — география для гимназии

Статическая учебная платформа (без сборки) по программе географии гимназии Tallinna Linnamäe Vene Lütseum: 3 курса, 51 урок, 390 вопросов, 439 карточек, карта мира с 66 объектами, 9 тренажёров, требования программы с образцами ответов.

## Публикация на Vercel
1. Создайте репозиторий `geosfera-gymnaasium` на GitHub и загрузите в корень все файлы из этой папки.
2. vercel.com → Add New → Project → Import этого репозитория. Framework Preset: **Other**, Build Command — пусто, Output Directory — `./`.
3. Имя проекта: `geosfera-gymnaasium` → адрес `https://geosfera-gymnaasium.vercel.app/`.

**Важно для превью в соцсетях:** og:image и og:url в `index.html` указывают на `https://geosfera-gymnaasium.vercel.app/`. Если Vercel выдал другой адрес или вы подключили свой домен — замените этот адрес в `index.html` (поиск и замена, 8 мест) и в `config.js` (`baseUrl`), затем сбросьте кэш превью: Telegram — @WebpageBot, Facebook — Sharing Debugger.

## Альтернатива — GitHub Pages
Settings → Pages → Deploy from a branch → `main` / root. Тогда адрес будет `https://ВАШ_ЛОГИН.github.io/geosfera-gymnaasium/` — замените его в `index.html` и `config.js` так же, как выше.

## Обновление контента
Уроки — `c1.js`, `c2.js`, `c3.js`; словарь, тренажёры, карта — `extra.js`; требования программы — `tests.js`. Не меняйте `id` уроков после запуска — на них держится прогресс учеников.
