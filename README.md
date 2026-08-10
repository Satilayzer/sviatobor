# Sviatobor

Статичний сайт (HTML) — готовий до деплою на Vercel.

## Структура

| Файл | Сторінка |
| --- | --- |
| `index.html` | Головна |
| `properties.html` | Проєкти (перелік) |
| `properties/family-townhouse.html` | Сімейний 180 |
| `properties/luxury-condo.html` | Комфорт 150 |
| `properties/spacious-family-home.html` | Сімейний 180 з гаражем |
| `404.html` | Сторінка помилки |

## Деплой

`vercel.json` вмикає `cleanUrls`, вимикає `trailingSlash` і кешує статичні
ресурси (зображення, шрифти, медіа) з `max-age=31536000, immutable`.

Локальний перегляд:

```bash
npx serve .
```
