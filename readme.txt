=== WP Typograph Full ===
Contributors: marapper
Donate link: http://iskariot.ru/wordpress/typo/
Tags: typograph, formatting, text, post, posts, page
Requires at least: 2.0.2
Tested up to: 2.7.1
Stable tag: 2.3.5

Russian typography for Wordpress. Full version with settings.

== Description ==

Плагин [WP Typograph Full](http://iskariot.ru/wordpress/typo/#typo-full) предназначен для автоматического форматирования текста в соответствии с правилами русской типографики. Обрабатывает все основные блоки - заголовки, тексты постов и страниц, комментарии. Форматирование происходит на лету - при отображении страницы, без изменения исходного текста постов.

Для большинства блогов рекомендуется использовать [облегченную версию плагина](http://wordpress.org/extend/plugins/wp-russian-typograph/).

__Основная функциональность__:

- Правильные кавычки («елочки и вложенные „лапки“»).
- Длинное тире между словами — не отрывая от предыдущего слова.
- — Тире, — в диалогах.
- Интервальные тире в датах и периодах (13 ноября—25 декабря).
- Минус между цифрами 0–9.
- Многоточие — тремя точками...
- Убирает точку в конце заголовка поста.
- В тегах &lt;code>, &lt;pre> и &lt;script> (и некоторых других) текст не изменяет.
- В теге &lt;code> автоматически заменяет &lt; на &amp;lt;, исправляет кавычки на машинописные для корректного копирования-вставки.
- Заменяет функцию фильтрации HTML (wpautop), исправляет ошибки визуального редактора со вставкой тегов.
- Делает ссылки в комментариях кликабельными (с http и www), автоматически сокращая якорь в длинных ссылках.

Остальные функции раздельно обрабатываются в __трех блоках__:

- Заголовки
- Основной текст
- Комментарии

Три основных __типа обработки__, раздельные для каждого типа блока:

- Спецсимволы (_по умолчанию — в тексте, комментариях_). ©, ®, ™, ½, ±, 10×10.
- Неразрывные конструкции (_по умолчанию — в заголовках, текстах_). Склеивает пробелы в названиях организаций, обращениях, в годах, в «до н.э.» («и т.д.»,«и т.п.»), мерах измерений, денежные суммы, инициалах, номере версии программы. Не разрывает со следующим (предыдущим словом) предлоги, союзы, короткие слова, частицы с дефисом и без. Также склеивает последнее слово в абзаце с предыдущим, чтобы предотвратить появление т.н. "вдов".
- Исправления (_по умолчанию — в тексте, комментариях_). Ошибочная пунктуация, повторяющиеся слова, и т.п.

_В целях снижения нагрузок на сервер желательно использовать с любым плагином кеширования._


== Installation ==

1. Скопируйте папку `wp-russian-typograph` в папку `/wp-content/plugins/` на вашем сайте.
2. Активируйте плагин в меню `Плагины` (`Plugins`) в админке Wordpress.
3. Измените настройки по умолчанию.