# UI-компоненты

Фирменные UI-паттерны DICOM TEAM живут в дизайн-системе сайта (шаблон `dicom_v2`).

## Стайлгайд

- **В брендбуке:** [`styleguide/index.html`](styleguide/index.html) — **полная** версия (31 раздел): цвета, направления `.dir-*`, типографика, бейджи, кнопки, шапки/фоны секций, карточки, media-row, hero/slider, stats, process, accordion, tabs, pricing, logo-cloud, галерея, calc-cta, формы, контакты и т.д. Подключает боевые CSS-модули с `dicom.team` по абсолютным ссылкам — рендерится один в один с сайтом (нужен интернет; Roboto и демо-картинки тоже внешние).
- **На сайте:** `https://dicom.team/styleguide/` — тот же файл (в репо сайта `patched/styleguide/`, деплоится через CI).

Компоненты: карточки, hero, формы, stats, process, tabs, accordion, pricing, бейджи и т.д.

## Базовые принципы

- Кнопка CTA `.btn--primary` — всегда синяя (`--c-cta-primary`).
- Секции: `section--light` (белая), `section--gray` (`#F6F7F9`), `section--dark` (`#0F1B33`).
- Цвет акцента внутри направления — через `var(--c-accent)`, см. [`../directions/`](../directions/).

> Не выдумывай новые классы — сначала проверь, нет ли готового в стайлгайде.
