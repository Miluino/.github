---
custom-width: 85
---
# Участие в проектах Miluino

Этот документ — краткая точка входа для работы с репозиториями организации.

## Перед началом работы

1. Прочитайте [стиль кода](https://github.com/Miluino/dev-guidelines/blob/main/code-style.md).
2. Ознакомьтесь с [Git workflow](https://github.com/Miluino/dev-guidelines/blob/main/git-workflow.md).
3. Для нетривиальной задачи создайте или выберите GitHub Issue.
4. Проверьте критерии готовности задачи и назначьте исполнителя.

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

Убедитесь, что выполнены критерии готовности, разрешены комментарии ревью и
изменения не смешивают независимые задачи. Подробные правила описаны в
[Git workflow](https://github.com/Miluino/dev-guidelines/blob/main/git-workflow.md).

## Планирование

Порядок оформления и движения задач описан в документе
[Работа с GitHub Issues и GitHub Projects](https://github.com/Miluino/dev-guidelines/blob/main/github-issues-projects.md).
