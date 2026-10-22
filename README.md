# Контрольная работа №2: Учебный каталог на Bootstrap 5

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание проекта

Многостраничный сайт учебного интернет-магазина (каталога товаров), разработанный с использованием CSS-фреймворка **Bootstrap 5**. 

Проект является отдельной реализацией предметной области. Он выполнен в новом репозитории и не является прямым продолжением кода Контрольной работы №1 (HTML/CSS).

## Используемый фреймворк и способ подключения

- **Фреймворк:** Bootstrap v5.3.8.
- **Способ подключения:** Локальный (файлы находятся в папке `vendor/bootstrap/`). 
- **CDN не используется.** Это обеспечивает работу сайта без подключения к интернету (выполнено дополнительное задание из методических указаний).

## Структура проекта

```text
kr2-bootstrap-shop/
├── css/
│   └── custom.css          — кастомные стили поверх Bootstrap
├── vendor/
│   └── bootstrap/
│       ├── css/
│       │   └── bootstrap.min.css
│       └── js/
│           └── bootstrap.bundle.min.js
├── index.html              — Главная страница
├── catalog.html            — Каталог товаров
├── product.html            — Страница товара
├── order.html              — Форма заявки
├── contacts.html           — Контакты
└── README.md               — Описание проекта

```

## Реализованные страницы

1. **Главная (`index.html`)** — навигация, hero-блок, карточки популярных товаров, модальное окно.
2. **Каталог (`catalog.html`)** — сетка карточек с бейджами, боковой блок фильтров (статический), хлебные крошки, модальное окно заявки.
3. **Товар (`product.html`)** — блок с описанием товара, заглушка изображения, таблица характеристик (`table-responsive`), хлебные крошки.
4. **Заявка (`order.html`)** — форма с различными элементами ввода, карточка с заголовком.
5. **Контакты (`contacts.html`)** — контактная информация и заглушка карты.

## Использованные компоненты Bootstrap

В проекте задействованы следующие компоненты и классы фреймворка:

- **Навигация (Navbar):** `navbar`, `navbar-expand-md`, `navbar-dark`, `bg-dark`, `collapse`, `navbar-toggler`.
- **Сетка (Grid):** `container`, `row`, `col-12`, `col-md-6`, `col-lg-4`, `col-xl-3`, `g-4` (обеспечивает полную адаптивность).
- **Карточки (Card):** `card`, `card-body`, `card-title`, `card-text`, `h-100`.
- **Кнопки (Buttons):** `btn`, `btn-primary`, `btn-outline-primary`, `btn-outline-secondary`, `btn-sm`, `btn-lg`, `disabled`.
- **Значки (Badges):** `badge`, `text-bg-success`, `text-bg-warning`, `text-bg-danger`.
- **Сообщения (Alerts):** `alert`, `alert-info`, `alert-warning`, `role="alert"`.
- **Модальное окно (Modal):** `modal`, `modal-dialog`, `modal-content`, `modal-header`, `modal-footer`, атрибуты `data-bs-toggle`, `data-bs-target`, `data-bs-dismiss`.
- **Формы (Forms):** `form-control`, `form-select`, `form-check`, `form-check-input`, `input-group`, `input-group-text`.
- **Таблицы (Table):** `table`, `table-striped`, `table-hover`, `table-responsive`.
- **Навигационная цепочка (Breadcrumb):** `breadcrumb`, `breadcrumb-item`.
- **Utility-классы:** `d-flex`, `justify-content-between`, `align-items-center`, `gap-*`, `mb-*`, `mt-*`, `py-*`, `text-muted`, `shadow-sm`, `border-0`.
- **Аккордеон (Accordion):** `accordion`, `accordion-item`, `accordion-button`, `accordion-collapse`, `accordion-body`.

## Самостоятельные доработки (для повышенного балла)

1. **Локальное подключение Bootstrap:** Фреймворк размещён в папке `vendor/`, что демонстрирует умение работать с зависимостями без CDN.
2. **Собственный файл `css/custom.css`:** 
   - Добавлены плавные анимации при наведении на карточки (`transform: translateY`, `box-shadow`).
   - Реализовано прижатие подвала к низу страницы с помощью `flex-direction: column` и `min-height: 100vh`.
   - Добавлены стили для заглушек изображений (`placeholder-image`).
3. **Расширение структуры:** Проект включает 5 полноценных страниц (вместо базовой одной), объединённых единой навигацией.
4. **Компонентная насыщенность:** Помимо обязательных `navbar`, `card`, `modal` и `alert`, добавлены `breadcrumb`, `input-group`, `table-responsive`, `form-check`.

## Как запустить проект

1. Откройте файл `index.html` в любом современном браузере.
2. Интернет не требуется, так как все стили и скрипты Bootstrap подключены локально из папки `vendor/`.
3. Для проверки адаптивности откройте DevTools (F12) и включите режим эмуляции мобильных устройств (ширины 375px, 768px, 1024px).
4. Опубликованная версия доступна по ссылке: **https://kukoru.github.io/kr2-bootstrap-shop/**

## Автор

- **ФИО:** Кутлунин Константин Русланович
- **Группа:** ЭФБО-15-25
- **Дисциплина:** Фронтенд и бэкенд разработка
- **Семестр:** 3
```