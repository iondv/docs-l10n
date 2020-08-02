# docs-l10n
Translation of ION DV documentation into other languages (use https://weblate.iondv.com). Ready documentation on the site https://iondv.readthedocs.io/en/latest/ 

Below text in Russian.

Порядок действий:
На основе master ветки в docs-ru формируется русская версия документации iondv.reathedocs.io

Утилитой:
* Клонируется iondv/docs-l10n и переключаемся на ветку translations
* В папке репозитория клонируется iondv/docs-ru
* При наличии изменений в iondv/docs-ru, черех sphinx в ветку translate репозитория iondv/docs-l10n обновляется папка gettext и пушатся изменения 
* В веблейт втягиваем изменения вручную
* Переводим в веблейт изменения и пушим их в ветку translate. iondv.reathedocs.io - собирает документацию по этой ветке https://iondv.readthedocs.io/en/translation/ для проверки
* Если все хорошо, мерджим вручную ветку translate в master
* iondv.reathedocs.io - на основе изменений ветки master собирает дефолтную версию документации https://iondv.readthedocs.io/en/latest/ 

Подробнее в статье на Habr https://habr.com/ru/post/488956/
