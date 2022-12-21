# Инструкция по работе с Git

Начальная работа с системой контроля версий.

*git --version* - команда для проверки версии git

*git init* - инициализация пустого репозитория

*git status* - проверка текущего состояния файлов

*git add* - добавление версионности файлу

*git commit -m "Сообщение"* - команда для фиксации изменений файлов

*git log* - вывод истории комитов в хронологическом порядке

*git diff* - вывод изменений на текущий момент по отношению к последнему комиту

*git checkout master* или *git checkout хеш-номер_комита* - переход между изменениями либо возврат к текущему состоянию

### links

Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка"). Это — [без title]
(http://example.com/link).
А вот [пример][1] [нескольких][2] [ссылок][id]с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.
[1]: http://example.com/"Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links(Optional Title Here)
[короткая запись]: http://example.com/short
Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.

### sources

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
<ul>
<li class="tab-conversation active">
<a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
<span class="comment-count">0
комментариев</span>
<span class="comment-countplaceholder">Комментарии</span>
</a>
</li>
<li class="dropdown user-menu" data-role="logout">
<a href="#" class="dropdown-toggle" datatoggle="dropdown">
    <span class="dropdown-toggle-wrapper">
<span>
Войти
</span>
</span>
<span class="caret"></span>
</a>
</li>
</ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >`и амперсанд `&`на их html-сущности.

### tables

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is    | some wordy text |    **$1600** |
| col 2 is    | centered      |        $12  |
| zebra stripes | are neat      |      ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.

### inline code

<<<<<<< HEAD
abracadabra22
=======
Для вставки кода внутри предложений нужно заключать этот
код в апострофы (на букве Ё). Пример: `<html class="ie
no-js">`.
Если внутри кода есть апостроф, то код надо обрамить
двойными апострофами: ``There is a literal backtick (`)
here.``
>>>>>>> inline_code

### Горизонтальная черта

xnj ,s tot nfrjuj yfgbcfnm xnj,s ,skj f,hfrfl,hjq

### Картинки 
