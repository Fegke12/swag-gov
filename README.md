<div align="center">

# 🏛 Правительство штата SWAG

**Официальный сайт органов власти RP-штата SWAG** — Правительство, Прокуратура и Судейская коллегия в одном месте: законы, структура, новости, вакансии и приём обращений.

[![Открыть сайт](https://img.shields.io/badge/▶_Открыть_сайт-0d1a30?style=for-the-badge)](https://fegke12.github.io/swag-gov/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/хостинг-GitHub_Pages-222?logo=github)

<br>

<img src="docs/screenshots/home.jpg" alt="Главная страница сайта Правительства штата SWAG" width="100%">

</div>

---

## О проекте

Сайт для государственной фракции RP-сервера **Arizona RP — SWAG** (GTA San Andreas). Игроки находят здесь всё, что касается власти штата: действующие законы, кто занимает руководящие должности, открытые вакансии и форму обращения. Стилистика — официальный портал госучреждения: тёмно-синий, золото, герб штата.

## Возможности

- 📜 **Нормативные документы.** Конституция, Уголовный, Дорожный и процессуальные кодексы, федеральные законы — с поиском по названию и фильтрами по типу. Тексты хранятся отдельными файлами в `data/`, поэтому их легко обновлять.
- 🏛 **Структура власти.** Три ветви — Правительство, Прокуратура, Судейская коллегия — с руководством и гербами ведомств.
- 📰 **Новости и указы** на главной.
- 💼 **Вакансии.** Открытые и закрытые должности со ссылками на заявления на форуме сервера — берутся из `data/vacancies.json`.
- ✉️ **Обращения граждан.** Форма отправляется через прокси на **Cloudflare Workers**: токены и адреса назначения не лежат в коде страницы.
- 🌗 **Светлая и тёмная тема**, адаптивная вёрстка под телефон.

## Скриншоты

<table>
  <tr>
    <td><img src="docs/screenshots/documents.jpg" alt="Нормативные документы"></td>
    <td><img src="docs/screenshots/structure.jpg" alt="Структура власти"></td>
  </tr>
  <tr>
    <td align="center"><sub>Документы с поиском и фильтрами</sub></td>
    <td align="center"><sub>Структура и состав руководства</sub></td>
  </tr>
  <tr>
    <td><img src="docs/screenshots/vacancies.jpg" alt="Вакансии"></td>
    <td align="center"><img src="docs/screenshots/mobile.jpg" alt="Мобильная версия" width="260"></td>
  </tr>
  <tr>
    <td align="center"><sub>Вакансии со ссылками на форум</sub></td>
    <td align="center"><sub>Мобильная версия</sub></td>
  </tr>
</table>

## Как обновлять контент

| Что | Где |
|---|---|
| Тексты законов и кодексов | `data/*.txt` — один файл на документ |
| Вакансии | `data/vacancies.json` — ветвь, должность, статус `open`/`closed`, ссылка |
| Всё остальное | `index.html` |

После пуша в `main` GitHub Pages обновляет сайт автоматически.

## Связанные проекты

- [**swag-vote**](https://github.com/Fegke12/swag-vote) — электронная система голосования Генеральной Ассамблеи и Конгресса этого же штата.

---

<div align="center"><sub>Сделано <a href="https://github.com/Fegke12">@Fegke12</a> · проект для RP-сервера, не связан с реальными органами власти</sub></div>
