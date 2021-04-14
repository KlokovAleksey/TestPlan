# TestPlan

## Тестирование возможности записи на обучение профессии "Тестировщик ПО"

### 1. Перечень автоматизируемых сценариев
* #### Переход с главной страницы на страницу профессии через меню "Каталог курсов" -> Программирование -> Профессия Тестировщик
* #### Переход с главной страницы на страницу профессии через меню "Каталог курсов" -> Полный каталог -> Тестировщик ПО
* #### Переход с главной страницы на страницу профессии через каталог курсов "Нео для начинающих" -> Тестировщик ПО
* #### Переход с главной страницы на страницу профессии через контент "Изучайте актуальные темы" -> Программирование -> Тестировщик ПО
* #### Переход с главной страницы на страницу профессии через контент "Раскройте свои сильные стороны" -> Выбрать курс -> Тестировщик ПО
* #### Переход к форме регистрации через кнопку "Записаться"
* #### Запись на обучение через форму регистрации (позитивное/негативное)

### 2. Перечень используемых инструментов
* Java - универсальный объектно-ориентированный язык программирования общего назначения.
* Intellij IDEA - интегрированная среда разработки.
* GIT,GitHub - cистема управления проектами и версиями кода.
* Gradle - система автоматической сборки.
* JUnit5 - многофункциональный фреймворк.
* Selenide - для написания UI тестов.
* Faker - для генерации пользователей.
* Lombok - уменьшает количество строк кода, генерация кода на этапе компиляции.
* Allure - визуализация прохождения тестов.

### 3. Перечень необходимых разрешений/данных/доступов
* Разрешение на тестирование и автоматизацию.
* Тестовый аккаунт.

### 4. Перечень и описание возможных рисков при автоматизации
* Изменение дизайна сайта.
* Если использовать сгенерированных пользователей и заглушки сервисов, возможность выпустить баг в продакшине.

### 5. Перечень необходимых специалистов для автоматизации
* Один специалист по автоматизированному тестированию имеющий компетентность с инструментами в п.2.

### 6. Интервальная оценка с учётом рисков (в часах):
* Сбор сведений, уточнение требований, подготовка тестового окружения - 2 часа.
* Написание и прохождение тестов 8 часов.
* Составление отчёта - 4 часа.
* Резерв (рефакторинг кода, баг репорты, непредвиденные обстоятельства) - 8 часов.
