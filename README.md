# Rush Detailing Test Hero

Тестовый статический блок (header + hero + credit) для отправки заказчику.

## Структура

- `index.html`
- `assets/css/style.css`
- `assets/images/logo-rush.png`
- `assets/images/hero-bg.jpg`
- `assets/images/telegram-icon.svg`

## Что нужно добавить

1. Замените `assets/images/logo-rush.png` на ваш логотип.
2. Замените `assets/images/hero-bg.jpg` на фоновое фото hero.

## Локальный просмотр

Откройте `index.html` в браузере
или поднимите простой сервер из папки `test works`:

```powershell
python -m http.server 5500
```

После этого откройте `http://localhost:5500`.

## Настройка ссылок

В `index.html` внизу есть объект `LINKS`:

- `ctaHero` — кнопка "Записаться на детейлинг"
- `headerTelegram` — круглая кнопка Telegram в хедере
- `credit` — ссылка `made by bakeev_ai`

## GitHub Pages (отдельный репозиторий)

1. Создайте новый репозиторий на GitHub, например `rush-test-hero`.
2. Загрузите содержимое папки `test works` в корень репозитория.
3. В GitHub: `Settings -> Pages`.
4. Source: `Deploy from a branch`.
5. Branch: `main`, folder: `/ (root)`.
6. Сохраните и дождитесь публикации.
7. Проверьте ссылку в режиме инкогнито.
