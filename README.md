# docs-l10n
Translation of ION DV documentation into other languages (use https://weblate.iondv.com). Ready documentation on the site 

Below text in Russian.

Порядок действий:
На основе master ветки в docs-ru формируется русская версия документации iondv.reathedocs.io

Утилитой:
* Клонируется docs-l10n и переключаемся на ветку translations
* В ней клонируется docs-ru
* При наличии изменений в docs-ru, черех sphinx обновляется gettext и пушатся в ветку translations
* В веблейт получаем изменения вручную
* Переводим в веблейт изменения и пушим их в ветку tranlate
* Если все хорошо, мерджим вручную ветку translate в master
* iondv.reathedocs.io - собирает документацию, на основе ветки translate 

Подробнее в статье на Habr https://habr.com/ru/post/488956/
