# Современный учебник Javascript

Всем привет!

Когда-то давно был только русский учебник https://learn.javascript.ru. Но несколько лет назад был полностью с нуля написан английский https://javascript.info. И с тех пор все существенные изменения вносились только в него.

Сейчас учебники уже довольно сильно разошлись. Между статьями есть общие фрагменты, но и много различий.

Самое лучшее, что можно сделать – это перевести русский с английского. Для этого создан этот репозиторий.

Пожалуйста, переводите статьи и делайте PR.

Если взяли статью на перевод - имеет смысл сделать issue этоб этом, чтобы другие люди не переводили ее же.

# Структура

<<<<<<< HEAD
Каждому разделу, статье или задаче соответствует директория.

Эта директория имеет вид `N-url`, где `N` - это номер для сортировки статей и разделов (они упорядочены), а `url` – URL-имя, по которому материал будет доступен.

В директории находится один из файлов:

  - `index.md` для раздела
  - `article.md` для статьи
  - `task.md` для условия задачи (+там же `solution.md` с решением)
=======
1. First, check if the translation has already started in the list above or in issues. If it exists, contact the original lead, ask him  to join efforts. If the translation is stalled, ask him to transfer the repo to you or just create a new one and continue from where they stopped.
2. If there's no such translation, create a new one. Clone the repository, change its name to `javascript-tutorial-<lang>` (by your language) and [create an issue](https://github.com/iliakan/javascript-tutorial-en/issues/new) for me to add you to the list.

**You can edit the text in any editor.** The tutorial uses enhanced "markdown" format, easy to grasp. And if you want to see how it looks on-site, there's a server to run the tutorial locally at <https://github.com/iliakan/javascript-tutorial-server>.  
>>>>>>> en/master

Каждый из этих файлов начинается с `# Заголовка материала`, и дальше текст в формате а-ля Markdown. Его довольно просто понять. Для редактирования достаточно простого текстового редактора.

Ресурсы и примеры, необходимые для статьи, раздела или задачи, находятся в её директории. На них можно ссылаться из материала.

# Запуск локально

Для удобства редактирования учебник можно запустить локально.

Сервер для этого находится здесь: <https://github.com/iliakan/javascript-tutorial-server>. 
