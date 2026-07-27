# DAV.AUTOSHOP — превью сайта

Собранная витрина для показа. Исходный код лежит в приватном репозитории
`DevGreenBox/dav-autoshop` — здесь только результат сборки.

Обновляется командой из основного репозитория:

```bash
NEXT_STATIC_EXPORT=1 NEXT_BASE_PATH=/dav-autoshop-preview \
NEXT_PUBLIC_SITE_URL=https://devgreenbox.github.io/dav-autoshop-preview \
pnpm build
```

Сайт закрыт от индексации: `robots.txt` отдаёт `Disallow: /`. Это превью
с незаполненными данными, ему не место в поиске.
