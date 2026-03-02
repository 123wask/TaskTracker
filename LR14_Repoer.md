# Отчёт ЛР14 — Юнит-тесты

**Автор:** Чинчикеев А.Б 
**Группа:**  25ИС11=Д-Д

## Что сделано
- Создан проект TaskTracker.Tests (MSTest)  
- Добавлены тесты TaskValidator:
  - Пустой Title ? ошибка  
  - Слишком длинный Title ? ошибка  
  - Слишком длинное Description ? ошибка  
  - Валидная задача ? ok  
- Добавлены тесты TaskService:
  - Add валидной задачи  
  - Add пустого Title ? исключение  
  - Delete существующей задачи  
  - Update меняет Title и Description  

## Как запускать тесты
Visual Studio ? Test ? Test Explorer ? Run All  

## Результат
Все тесты анализируються 
