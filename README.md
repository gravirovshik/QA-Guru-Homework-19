### Запуск тестов

<br>

> [!IMPORTANT]
> **Локальный запуск** (параметр `-Denv=local` является `не обязательным`)
> ```
> ./gradlew clean test -Denv=local
> ```

<br>

> [!IMPORTANT]
> **Удаленный запуск на Selenoid** (параметр `-Denv=remote` является `обязательным`)
> ```
> ./gradlew clean test -Denv=remote
> ```

<br>

> [!IMPORTANT]
> **Удаленный запуск на Selenoid** (параметр `-Denv=prod` является `обязательным`)
> ```
> ./gradlew clean test -Denv=prod
> ```
Сделать пример конфигурации для WEB тестов:

1. Имя браузера

2. Версия браузера

3. Локальный или удаленный (RemoteWebDriver)

Сделать два вида конфигурационных файлов:

1. Для локального запуска на chrome

2. Для удаленного запуска на selenoid

Сделать возможность с помощью одной системной переменной переключать запуск с локального на удаленный.
