# VK-Cup-2022
Задание отборочного раунда для VK Cup 2022

## Описание

В данном этапе необходимо доработать клиентский сервис почты и реализовать следующие фичи:

- Интернационализация проекта
- Темизацию проекта
- Фильтры писем (непрочитанные, с флагом, с вложениями, новые, старые)

**В приоритете были следующие критерия:**

- Размер приложения
- Скорость работы приложения
- Внимание к деталям
- Доступность на 2 языках:
  - русский
  - английский

**Требования:**

- Запрещены серверные библиотеки, например: express, fast, server-static…, кроме стандартных для Node.js версии 18.12.1 (LTS)
- Сервер должен прослушивать порт 3000
- Вся статика должна раздаваться сервером
- Все урлы должны быть относительными

Для соответствия требованиям решено было пределать архитектуру приложения c использованием Pre-Rendering.
Это позволило значительно сократить время загрузки приложения и снизить временные метрики.