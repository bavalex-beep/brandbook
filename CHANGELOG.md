# Changelog

Все значимые изменения фирменного стиля DICOM TEAM.

## [Unreleased]

### Added
- Первичная структура brand book: logo, colors, directions, typography, voice-tone, components, templates, imagery, examples.
- Цветовые токены (CSS + JSON) из `dicom-design.css`.
- Канонические цифры и boilerplate (синхронизировано с `/about/manifest/` от 01.06.2026).
- `imagery/visual-language.md` — правила для изображений (hero: квадрат/центр; обложки: свободная левая зона, блюр слева; инженерный стиль, без перегруженности).
- `mascot/dikomych.md` — спецификация маскота Дикомыч (v2.0): характер, визуальный образ, цвета, эмоции, жесты, масштабирование, правила использования.
- `mascot/assets/dikomych-character-sheet.png` — финальный лист персонажа (v2.0).
- `mascot/visual-spec.md` — техническая визуальная спека персонажа (raw-ссылка на эталон, цвета, пропорции, prompt для генерации).
- `mascot/assets/parts/` — детальные рендеры конструкции (head, arm, torso, leg) в нескольких ракурсах.
- `mascot/assets/dikomych-parts-reference.png` — сводный collage-референс (все части + палитра) для прикрепления в чат с ИИ.
- `logo/svg/logo.svg` — логотип DICOM TEAM.

### Changed
- Уточнена цветовая схема корпуса Дикомыча: **бело-синий** (белый `#F5F7FA` + синие акценты `#0D75B2`), а не сплошь синий — по детальным рендерам.

### Аудит против канона сайта (dicom-design.css)
- Типографика: зафиксирован фирменный шрифт **Roboto** (`--f-body`), веса 400/500/600/700, лицензия Apache 2.0; `typography.md`, `webfonts.css`, `fonts/README.md`.
- Цветовые токены дополнены до полного канона: триады `-d`/`-soft`/`-rgb` всех направлений, `--c-cta-primary-d`, `--c-number-light/-dark`, `--c-accent-shadow`, `--c-accent-rgb`.
- Добавлены нецветовые токены дизайн-системы: `tokens/system.css` (сетка, тени, радиусы, переход).
- Сцены Дикомыча переименованы в ASCII и убраны в `mascot/assets/scenes/`.

### TODO
- Положить файлы логотипа (SVG/PNG) в `logo/`.
- Подтвердить гарнитуру и лицензию шрифтов, заполнить `typography/`.
- Добавить шаблоны: pptx, docx-шапки, email-подпись, обложки соцсетей.
- Наполнить `imagery/` и `examples/`.
