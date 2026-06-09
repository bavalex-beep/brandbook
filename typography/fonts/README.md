# Шрифты — Roboto (self-host)

Фирменный шрифт — **Roboto**, лицензия Apache 2.0 (можно класть файлы сюда).

## Где взять

- Google Fonts: https://fonts.google.com/specimen/Roboto
- Исходники: https://github.com/googlefonts/roboto-3-classic

## Что положить сюда

Веб-форматы (woff2) нужных весов:

- `Roboto-Regular.woff2` (400)
- `Roboto-Medium.woff2` (500)
- `Roboto-SemiBold.woff2` (600)
- `Roboto-Bold.woff2` (700)

## Подключение (@font-face)

```css
@font-face{font-family:'Roboto';font-weight:400;font-display:swap;src:url('fonts/Roboto-Regular.woff2') format('woff2');}
@font-face{font-family:'Roboto';font-weight:500;font-display:swap;src:url('fonts/Roboto-Medium.woff2') format('woff2');}
@font-face{font-family:'Roboto';font-weight:600;font-display:swap;src:url('fonts/Roboto-SemiBold.woff2') format('woff2');}
@font-face{font-family:'Roboto';font-weight:700;font-display:swap;src:url('fonts/Roboto-Bold.woff2') format('woff2');}
```

> Если проще — используй Google Fonts через `../webfonts.css`, тогда файлы сюда класть не нужно.
