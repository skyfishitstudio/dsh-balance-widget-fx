# Происхождение кода

Этот пакет — производная от `dsh-balance-widget` версии 0.6.4.

- Оригинал: https://github.com/LL-cmyk-so/dsh-balance-widget
- Автор оригинала: LL-cmyk-so
- Лицензия оригинала: MIT
- Пакет в npm: https://www.npmjs.com/package/dsh-balance-widget
- SHA-256 tarball'а апстрима 0.6.4: `d508d0ffec8a48b861bf04fb377f36872166e760` (shasum)

Файлы `lib/client.js` и `lib/index.js` взяты из 0.6.4 и изменены. Перечень
изменений — в `CHANGELOG.md` и в шапке README. Внутренние идентификаторы
(`dsh-balance-widget` в клиентском бандле, `balance-widget` в `cordis.patch.yml`,
пространство локализации `balance-widget`) намеренно оставлены как в оригинале,
чтобы продолжали работать сторонние словари локализации, включая
`dsh-balance-widget-ru`.

Побочное следствие: оригинал и этот форк нельзя держать в профиле одновременно —
оба регистрируют одну и ту же карточку в `sidebar.footer.action`.
