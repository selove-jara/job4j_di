## Job4j Внедрение зависимостей (DI)
Добро пожаловать в репозиторий Job4j DI! Здесь представлены примеры и упражнения, связанные с внедрением зависимостей (Dependency Injection) в Java с использованием фреймворка Spring.

## Оглавление
1. Перехват управления (Inversion of Control)
Spring реализует принцип IoC, перехватывая управление созданием объектов. Это позволяет фреймворку контролировать жизненный цикл и зависимости объектов, а не вручную управлять этим в коде.

2. Внедрение зависимостей (Dependency Injection)
Spring использует DI для передачи зависимостей между объектами. Зависимости могут быть внедрены через:

- Конструктор
- Сеттеры
- Аннотации
3.  Жизненный цикл Spring Bean

Spring Beans — это объекты, которые управляются контейнером Spring. Жизненный цикл бина включает:

- Инициализацию
- Конфигурацию зависимостей
- Завершение работы

3. Определение Bean (Bean Definitions)

Bean определяется в конфигурационных файлах или с помощью аннотаций. Это позволяет Spring создавать и управлять объектами на основе описанных зависимостей.

## Примеры:
- Конфигурация через XML
- Использование аннотаций @Autowired и @Component
- Конфигурирование бинов с Java-based конфигурацией


## Требования
- JDK 11+
- Spring Framework