---
custom-width: 85
---
# Участие в проектах Miluino

Этот документ — краткая точка входа для работы с репозиториями организации.

## Перед началом работы

1. Прочитайте [стиль кода](https://github.com/Miluino/dev-guidelines/blob/master/code-style.md).
2. Ознакомьтесь с [Git workflow](https://github.com/Miluino/dev-guidelines/blob/master/git-workflow.md).
3. Создайте Issue для своей задачи и назначьте себя исполнителем, если Issue ещё не создан тимлидом.

## Изменения в репозиториях

Работа выполняется в отдельной ветке от актуального `master`:

```text
feature/<номер-задачи>
bugfix/<номер-задачи>
task/<номер-задачи>
```

Одна ветка и один Pull Request соответствуют одной логической задаче.
Перед открытием Pull Request синхронизируйте ветку с `master`.

## Pull Request

В описании Pull Request укажите связанный Issue:

```text
Closes #<номер-задачи>
```

Убедитесь, что выполнены критерии готовности и учтены комментарии ревью. Подробные правила описаны в [Git workflow](https://github.com/Miluino/dev-guidelines/blob/master/git-workflow.md).

## Планирование

Порядок оформления и движения задач описан в документе [Работа с GitHub Issues и GitHub Projects](https://github.com/Miluino/dev-guidelines/blob/master/github-issues-projects.md).
