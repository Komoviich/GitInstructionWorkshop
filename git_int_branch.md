# Инструкция по работе с ветками в Git

Работа с ветками в Git позволяет изолировать изменения, тестировать новые функции и удобно управлять развитием проекта.

## Основные команды для работы с ветками
## 1. Создание новой ветки

Создайте новую ветку:

```bash
git branch <имя_ветки>
```

## 2. Переключение между ветками

Переключится на другую ветку:

```bash
git checkout <имя_ветки>
```

Создать и переключится на новую ветку одновременно:

```bash
git checkout -b <имя_ветки>
```

## 3. Просмотр списка веток

Просмотреть все локальные ветки:

```bash
git branch
```

## 4. Удаление ветки

Удаление локальной ветки:

```bash
git branch -d <имя_ветки>
```

Принудительное удаление локальной ветки (если она не была слита):

```bash
git branch -D <имя_ветки>
```

## 5. Слияние веток

Для начала перейдите на основную ветку(например, main):

```bash
git checkout main
```

Потом выполните слияние ветки:

```bash
git merge <имя_ветки>
```