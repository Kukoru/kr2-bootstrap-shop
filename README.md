# Учебный каталог на Bootstrap 5

Этот одностраничный пример продолжает предыдущий учебный проект HTML/CSS: сохранены «Учебный каталог», hero «Компоненты для рабочего пространства», три товара, состояния кнопок, сравнительная таблица и форма заявки. Те же блоки реализованы Bootstrap Grid и готовыми компонентами Bootstrap 5.

Проект демонстрирует:

- Bootstrap Navbar с мобильным toggler;
- mobile-first сетку `container → row → col-*` как основу layout;
- компоненты Card, Buttons, Badge, Alert, Table, Form и Modal;
- интерактивное поведение через `data-bs-*` и Bootstrap JS Bundle;
- адаптивное перестроение карточек: одна колонка на mobile, две на tablet, три на desktop.

Utilities используются только минимально для gutters, интервалов и штатной формы; они не заменяют Grid или структуру компонентов. Собственного CSS и custom JavaScript нет. Проект не является готовой контрольной работой или законченным интернет-магазином.

## Запуск

Откройте `index.html` в современном браузере. Интернет не требуется: Bootstrap CSS и JS Bundle находятся в `vendor/bootstrap/`.

Для проверки изменяйте ширину окна, открывайте mobile navbar и modal «Оставить заявку».

## Структура

```text
index.html
vendor/bootstrap/css/bootstrap.min.css
vendor/bootstrap/js/bootstrap.bundle.min.js
```

## Bootstrap

- Version: `5.3.8`.
- Official source: `https://getbootstrap.com/docs/5.3/getting-started/download/`.
- Official compiled distribution: `https://github.com/twbs/bootstrap/releases/download/v5.3.8/bootstrap-5.3.8-dist.zip`.
- Retrieved: `2026-10-12`.
- Runtime: local/offline; CDN и jQuery не используются.
- `bootstrap.min.css` SHA-256: `d85327d99c7a3ee1f9b5d0500d1370acea3ad2db39c163c2f51f232baedbdede`.
- `bootstrap.bundle.min.js` SHA-256: `e4fd49181388c48ec5040bd3fe66f57c29c8e67fcd8502b3354b96ec7ab47cc7`.
