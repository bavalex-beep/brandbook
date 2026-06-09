# DICOM TEAM — Brand Book

Единый источник правды по фирменному стилю DICOM TEAM: логотип, цвета, типографика, голос бренда, шаблоны.

Сайт: https://dicom.team · Живой стайлгайд: https://dicom.team/styleguide/

## Структура

| Раздел | Что внутри |
|---|---|
| [`logo/`](logo/) | Логотип во всех форматах (SVG/PNG), правила использования |
| [`mascot/`](mascot/) | Дикомыч — официальный маскот: [спецификация](mascot/dikomych.md) и ассеты |
| [`colors/`](colors/) | Палитра ([palette.md](colors/palette.md)), токены [CSS](colors/tokens.css) / [JSON](colors/tokens.json), swatches |
| [`tokens/`](tokens/) | Нецветовые токены: сетка, тени, радиусы, переход, шрифт ([system.css](tokens/system.css)) |
| [`directions/`](directions/) | 4 продуктовых направления и их цвета |
| [`typography/`](typography/) | Шрифт **Roboto**, веса, шкала, подключение |
| [`voice-tone/`](voice-tone/) | [Голос](voice-tone/voice.md), [тезисы](voice-tone/messaging.md), [boilerplate и цифры](voice-tone/boilerplate.md) |
| [`components/`](components/) | UI-паттерны, ссылка на стайлгайд |
| [`templates/`](templates/) | Презентации, документы, email-подпись, соцсети |
| [`imagery/`](imagery/) | Фотостиль, иконки, паттерны |
| [`examples/`](examples/) | Примеры применения, do / don't |

## Быстрый старт

- Нужен цвет в коде — бери токен из [`colors/tokens.css`](colors/tokens.css), не хардкодь hex.
- Пишешь текст от лица компании — сверься с [`voice-tone/`](voice-tone/).
- Делаешь макет под направление — см. [`directions/directions.md`](directions/directions.md).

## Версионирование

Изменения фиксируем в [`CHANGELOG.md`](CHANGELOG.md). Источник истины по цветам и компонентам — `dicom-design.css` сайта; этот репозиторий синхронизируем с ним.

## Использование бренда

Условия — см. [`LICENSE`](LICENSE). Логотип и фирменный стиль принадлежат DICOM TEAM.
