# neuromanser Workshop assets

Общие изображения для страниц модов neuromanser в Steam Workshop.

- [shared/translation-badge/](shared/translation-badge/README.md) — единая отметка перевода: флаг России с печатью NM поверх.
- `shared/branding/` — общие авторские хидеры и фирменные элементы.
- [shared/footer/](shared/footer/README.md) — универсальное завершение страницы RU/EN.
- [shared/sections/](shared/sections/README.md) — согласованные плашки разделов RU/EN и готовый BBCode.
- [mods/](mods/README.md) — отдельный каталог для изображений каждого мода: `mods/<slug>/ru/`, `en/` и при необходимости `common/`.

Публиковать здесь только готовые материалы оформления. Новые версии сохранять под новым именем (`v2`, `v3`), чтобы существующие страницы не менялись неожиданно. Не удалять файлы, на которые ссылаются опубликованные описания.

## Общий хидер

Текущая компактная по высоте версия — **v2, 1181×196**: печать уменьшена, размер ника сохранён. PNG RGBA.

```text
[img]https://raw.githubusercontent.com/neuromanser89/neuromanser-workshop-assets/main/shared/branding/neuromanser-header-white-v2.png[/img]
```

Версии v1 ниже сохранены для существующих ссылок; для новых страниц использовать v2.

Белая печать NM с шестью болтами, разделитель и округлая надпись neuromanser. Предназначен для тёмного фона. Один файл для RU и EN.

| Файл | Размер | Формат |
| --- | --- | --- |
| [Основной](shared/branding/neuromanser-header-white-v1.png) | 1181×402 | PNG RGBA |
| [Компактный](shared/branding/neuromanser-header-white-v1-640.png) | 640×218 | PNG RGBA |

Вне рисунка фон действительно прозрачен; чёрные детали внутри белой печати непрозрачны. Сохраняйте пропорции. Название мода размещайте отдельным блоком ниже.

Дополнительная компактная версия (для страниц Steam предпочитать полноразмерную ниже):

```text
[img]https://raw.githubusercontent.com/neuromanser89/neuromanser-workshop-assets/main/shared/branding/neuromanser-header-white-v1-640.png[/img]
```

Основная версия для Steam: по пользовательскому тесту на странице выглядит чётче компактной:

```text
[img]https://raw.githubusercontent.com/neuromanser89/neuromanser-workshop-assets/main/shared/branding/neuromanser-header-white-v1.png[/img]
```

Используйте прямые ссылки `raw.githubusercontent.com`, а не ссылки на страницу файла GitHub. Изображение появится после сохранения описания. Проверяйте выбранный язык перед сохранением.

Графика создана для neuromanser с помощью imagegen; прозрачный хидер технически извлечён из согласованного оригинала скриптом. Исходник и скрипт подготовки хранятся в рабочем репозитории модов, `docs/branding/`.
