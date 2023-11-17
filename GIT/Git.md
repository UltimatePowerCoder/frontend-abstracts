# Основы Git и GitHub конспект.

---

## Описание:
В этом файле я собрал основные команды для работы с Git репозиториями.
По мере обучения, попался замечательный тренажер по основам Git: [Ссылка](https://learngitbranching.js.org/?locale=ru_RU).

---

## Имена для коммитов:
Важно выбирать "хорошие" и понятные имена для коммитов, что бы не страдать с структурой дерева проекта.
В сети есть [Соглашение о коммитах](https://www.conventionalcommits.org/ru/v1.0.0/), которое отлично помогает навести порядок в структуре и именах коммитов.

---

## Основные команды:

Команда: | Описание: | Примеры использования:
:-: | :-: | :-:
```git commit``` | Создание нового коммита.
```git branch``` | Создаёт новую ветку | ```git branch <имя ветки>```
```git checkout``` | Перемещает HEAD | ```git checkout main``` ```git checkout <коммит>```
```git cherry-pick``` | 
```git reset``` | 
```git revert``` | 
```git rebase``` | 
```git merge``` | 

---

```
mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```