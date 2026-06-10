# Changelog

Все значимые изменения фирменного стиля DICOM TEAM.

## [Unreleased]

### Added
- Первичная структура brand book: logo, colors, directions, typography, voice-tone, components, templates, imagery, examples, mascot.
- Цветовые токены (CSS + JSON) из `dicom-design.css`.
- Канонические цифры и boilerplate (синхронизировано с `/about/manifest/` от 01.06.2026).
- `imagery/visual-language.md` — правила для изображений (hero: квадрат/центр; обложки: свободная левая зона, блюр слева; инженерный стиль, без перегруженности).
- `logo/svg/logo.svg` — логотип DICOM TEAM.

### Маскоты
- **Дикомыч** (v2.0) — основной маскот, инженер, бело-синий: `mascot/dikomych.md` + `mascot/visual-spec.md` + ассеты (лист персонажа, parts, scenes, collage-референс). Цвета `#0D75B2` / `#3CB8FF` / `#10182F` / `#F5F7FA`, токены `--c-mascot-*`.
- **Дизайныч** (v1.0) — маскот направления «Дизайн», бургунди: `mascot/dizainych/dizainych.md` + assets. Цвета `#BE185D` / `#FF4D90` / `#10182F` / `#F5F7FA`, токены `--c-mascot-dz-*`.
- Совместная сцена пары — `mascot/assets/scenes/dikomych-and-dizainych.png`. Все файлы — ASCII-имена.

### Аудит против канона сайта (dicom-design.css)
- Типографика: зафиксирован фирменный шрифт **Roboto** (`--f-body`), веса 400/500/600/700, лицензия Apache 2.0; `typography.md`, `webfonts.css`, `fonts/README.md`.
- Цветовые токены дополнены до полного канона: триады `-d`/`-soft`/`-rgb` всех направлений, `--c-cta-primary-d`, `--c-number-light/-dark`, `--c-accent-shadow`, `--c-accent-rgb`.
- Добавлены нецветовые токены дизайн-системы: `tokens/system.css` (сетка, тени, радиусы, переход).

### Styleguide
- `components/styleguide/index.html` — полный стайлгайд сайта (31 раздел), подключает боевые CSS-модули `dicom_v2` с dicom.team.
- Битые ссылки на мёртвый `/styleguide/` поправлены по всему брендбуку.

### Из скилла dicom-kp (КП)
- Зафиксирован фирменный **тэглайн** «DIgitise your COMpany» (DI/COM — акцентом): `messaging.md`, `logo/README.md`, `boilerplate.md`.
- Добавлен логотип PNG `logo/png/logo.png` (720×156, чёрный знак на прозрачном).
- Шрифт документов — **Arial** (веб — Roboto): `typography.md`.
- Публичные контакты (сайт/email/телефон/Telegram/адрес): `boilerplate.md`.
- Стиль фирменных документов (КП): `templates/documents/README.md` — шапка с логотипом+тэглайном, заголовки с акцентной линией, таблицы на акценте, process-таймлайн, тёмный подвал. Генерация — скилл dicom-kp.

### TODO
- Логотип: добавить монохром/инверсию (белый) и favicon (есть SVG + чёрный PNG).
- Подтвердить шрифты в `typography/fonts/` (или оставить Google Fonts).
- Шаблоны: pptx, docx-шапки, email-подпись, обложки соцсетей.
- Swatches `.ase/.gpl` для Figma/Illustrator.
- Дозаполнить `imagery/` и `examples/`.
