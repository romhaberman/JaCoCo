# Домашнее задание к занятию «Выстраивание процесса непрерывной интеграции»

## Цель задания

1. Научиться настраивать CI на основе GitHub Actions.

------

## Инструкция к заданию

1. Скачайте и установите профессиональный редактор кода [Intellij Idea Community Version](https://www.jetbrains.com/idea/download/).
1. Откройте IDEA и [создайте и настройте новый Maven-проект](QA_Maven_Idea_Create.md). Под каждую задачу следует создавать отдельный проект, если обратное не сказано в условии.
2. Создайте пустой репозиторий на GitHub и свяжите его с папкой вашего проекта, а не с какой-либо другой.
3. Правильно настройте репозиторий в плане `.gitignore`. Проигнорируйте папки `.idea` и `target` (раньше была `out`) и `.iml`-файл — их в репозитории быть не должно.
4. :new: Закоммитьте и запушьте созданный проект на ГитХаб, [настройте GitHub Actions](QA_CI.md), сделайте `git pull`.
4. Выполните в IDEA требуемую задачу согласно условию.
5. Проверьте соблюдение [правил форматирования кода](QA_Java_Idea_Format.md).
6. :new: Убедитесь что при запуске `mvn clean verify` (раньше было `mvn clean test`) все тесты запускаются, проходят, а сборка завершается успешно
7. Закоммитьте и отправьте в репозиторий содержимое папки проекта.
8. :new: Убедитесь, что CI запустился на последнем коммите и завершился успешно — появилась зелёная галочка.

------
