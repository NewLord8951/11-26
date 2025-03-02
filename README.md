# 11-26
1. **Логическая разметка** — это разметка, которая описывает содержимое с точки зрения его семантики (например, заголовки, параграфы, списки), тогда как **физическая разметка** определяет, как визуально отображать это содержимое (например, жирный шрифт, курсив). Логическая разметка помогает поисковым системам и assistive technologies понять структуру и содержание документа.

2. Вынесение оформления веб-страниц в отдельный файл считается более грамотным потому, что это позволяет улучшить структурирование кода, минимизировать дублирование кода, сделать изменения более простыми и быстрыми, а также улучшить производительность за счет кэширования CSS-файлов.

3. Тэги логической разметки: `<h1>`, `<p>`, `<strong>`, `<em>`, `<ul>`, `<ol>`, `<li>`. Тэги физической разметки: `<b>`, `<i>`, `<u>`, `<font>`, `<center>`. Рекомендуется использовать логическую разметку, так как она лучше передает смысл контента и соответствует стандартам доступности.

4. Тэг `<strong>` обозначает важность текста и придаёт ему семантический вес, а `<b>` просто делает текст жирным, не придавая ему особого значения. `<strong>` рекомендуется использовать для обозначения важного контента, тогда как `<b>` — для визуального оформления без смысловой нагрузки.

5. Для оформления текстов программ используется тэг `<code>`.

6. CSS (Cascading Style Sheets) — это таблицы стилей, предназначенные для описания внешнего вида и форматирования документа, написанного на HTML или XML.

7. Обычно стилевые файлы имеют расширение `.css`. Их можно редактировать в любом текстовом редакторе, например, Notepad++, Visual Studio Code, Sublime Text и т.д.

8. Чтобы подключить стилевой файл к веб-странице, необходимо добавить в `<head>` вашего HTML-документа следующий код: `<link rel="stylesheet" type="text/css" href="style.css">`.

9. Чтобы изменить оформление стандартных тэгов, например `<h1>`, можно использовать CSS, например: `h1 { font-size: 24px; color: blue; }`.

10. Цвет элемента на веб-странице можно определить, используя CSS-свойство `color` для текста, или `background-color` для фона.

11. Классы используются для группировки элементов, к которым можно применить одинаковые стили. Это позволяет более гибко управлять стилями и переиспользовать их.

12. Класс — это способ обозначить группы элементов с одинаковыми стилями, а псевдокласс — это состояние элемента (например, `:hover`, `:focus`). Примеры псевдоклассов: `:hover`, `:active`, `:focus`, `:first-child`.

13. a) `p.qq { color: white; }` — этот селектор применяет стиль к элементу `<p>` с классом `qq`. 
    b) `.qq { color: white; }` — этот селектор применяет стиль ко всем элементам с классом `qq`. 

14. Тэг `<span>` используется для выделения небольших фрагментов текста или контента внутри других элементов, без создания новых блоков.

15. Наследование свойств в CSS означает, что некоторые стили (например, цвет текста и шрифт) могут передаваться от родительских элементов их потомкам. Это полезно для упрощения стилизации и поддержания согласованности.

16. Таблицы стилей называют каскадными, потому что стили применяются в порядке их определения и могут перекрываться. Это позволяет последним определениям иметь приоритет.

17. 
a) `p span { font-style: italic; }` — курсивный стиль применяется к элементам `<span>`, находящимся внутри `<p>`.
b) `p.qq span { font-style: italic; }` — курсивный стиль применяется к элементам `<span>`, находящимся внутри `<p>` с классом `qq`.
c) `p span.qq { font-style: italic; }` — курсивный стиль применяется к элементам `<span>` с классом `qq`, находящимся внутри `<p>`.
d) `p span.zz { font-style: italic; }` — курсивный стиль применяется к элементам `<span>` с классом `zz`, находящимся внутри `<p>`.
e) `p span { color: green; }` — зеленый цвет применяется к элементам `<span>`, находящимся внутри `<p>`.
