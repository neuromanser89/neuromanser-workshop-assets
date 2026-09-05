# neuromanser Workshop assets

Общие изображения для страниц модов neuromanser в Steam Workshop.

- `shared/branding/` — общие авторские хидеры и фирменные элементы.
- Изображения отдельных модов в будущем размещать в `mods/<slug>/`, языковые варианты — в `ru/` и `en/` внутри каталога мода.

Публиковать здесь только готовые материалы оформления. Новые версии сохранять под новым именем (`v2`, `v3`), чтобы существующие страницы не менялись неожиданно. Не удалять файлы, на которые ссылаются опубликованные описания.

## Общий хидер

Белая печать NM с шестью болтами, разделитель и округлая надпись neuromanser. Предназначен для тёмного фона. Один файл для RU и EN.

| Файл | Размер | Формат |
| --- | --- | --- |
| [Основной](shared/branding/neuromanser-header-white-v1.png) | 1181×402 | PNG RGBA |
| [Компактный](shared/branding/neuromanser-header-white-v1-640.png) | 640×218 | PNG RGBA |

Вне рисунка фон действительно прозрачен; чёрные детали внутри белой печати непрозрачны. Сохраняйте пропорции. Название мода размещайте отдельным блоком ниже.

Вставка компактного хидера в начало описания Steam Workshop:

```text
[img]https://raw.githubusercontent.com/neuromanser89/neuromanser-workshop-assets/main/shared/branding/neuromanser-header-white-v1-640.png[/img]
```

Основная версия:

```text
[img]https://raw.githubusercontent.com/neuromanser89/neuromanser-workshop-assets/main/shared/branding/neuromanser-header-white-v1.png[/img]
```

Используйте прямые ссылки `raw.githubusercontent.com`, а не ссылки на страницу файла GitHub. Изображение появится после сохранения описания. Проверяйте выбранный язык перед сохранением.

Графика создана для neuromanser с помощью imagegen; прозрачный хидер технически извлечён из согласованного оригинала скриптом. Исходник и скрипт подготовки хранятся в рабочем репозитории модов, `docs/branding/`.
