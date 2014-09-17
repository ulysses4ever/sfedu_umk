sfedu_umk
=========

Латех-шаблон для УМК/РПД в Южном федеральном университете. Вас должна интересовать ветка `master`.

Файлы, предназначенные для редактирования преподавателем:

* `general_info.tex` — общая информация о курсе и составителе УМК,
* `umk.tex` — пока тут только РПД,
* `ukd_body.tex` — УКД,
* `my_units.tex` — информация о модулях дисциплины.

В некоторых местах этих файлов явно указано, что в *некоторых* случаях придётся внести некоторые изменения в другие файлы с указанием этих файлов.

Файлы, которые нужно компилировать (pdf)LaTeX:

* `umk.tex` для получения УМК/РПД,
* `ukd.tex` для получения standalone УКД.

Для компиляции любого из этих файлов необходимо заполнить информацию в файлах `general_info.tex` и `my_units.tex`.

[Пример рыбы для УМК/РПД в PDF можно посмотреть здесь](https://www.sharelatex.com/github/repos/ulysses4ever/sfedu_umk/builds/latest/output.pdf).
