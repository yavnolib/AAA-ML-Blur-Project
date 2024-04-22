# AAA ML Final Project

## Тема: 04. Background Blur / Crop / Face Blur / Замена Фона

### Направление проекта
Проект направлен на разработку инструментов для автоматической обработки фотографий в объявлениях. Основная задача — поиск и разметка (blur) лиц на фотографиях.

### Описание проекта
На платформе Авито каждое объявление сопровождается фотографией. Качество этих фотографий напрямую влияет на скорость и успешность продаж. Автоматическая обработка фотографий может значительно улучшить визуальное восприятие продукта, а также помочь скрыть нежелательную информацию, такую как лица людей или номера автомобилей.

- **Размытие лиц**: обеспечивает конфиденциальность, скрывая лица людей на фотографиях.

Целью проекта является разработка набора ML-модели и алгоритмов, которые будут автоматически применять обработки выше к пользовательским фотографиям, чтобы те соответствовали требованиям безопасности и конфиденциальности

### Название команды 
Фан-клуб Ольги Красовской

### Команда проекта 
- Донской Андрей
- Мельник Руслан 
- Николаев Ярослав

### Техническая информация 

**Системные требования:**

**OS `Linux`** (протестировано на `Ubuntu 22.04.3 LTS`).

<details>
  <summary>Структура проекта</summary>

```linux
.
├── blur             <--- Основной код
│   ├── backend      <--- Бекенд
│   └── frontend     <--- Фронтенд
├── data             <--- Используемые данные
├── docker           <--- Докер-файлы
├── docs             <--- Документация
├── notebooks        <--- Тестирование гипотез, ноутбуки
└── tests            <--- Тесты
```

</details>

<details>
  <summary>Основные команды (Makefile)</summary>
    
1. Сборка окружения
    ```bash
    make setup
    ```
2. Запуск тестирования
    ```bash
    make tests
    ```
3. Справочная информация по всем командам
    ```bash
    make help
    ```

</details>