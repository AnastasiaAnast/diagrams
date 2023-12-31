# Основы диаграмм состояний

- Что такое состояние объекта, как с ним работать.
- Что такое диаграммы состояний.
- Как различные роли взаимодействуют с диаграммами состояний.
- Как можно представить полученную информацию визуально.

## Что такое состояние объекта, как с ним работать.

**Состояние** — текущее положение объекта/системы. Может относиться к физическому/логическому состоянию. Может быть описано с помощью св-в/параметров.

включен - открыт / выключен - закрыт

Один объект может находиться в большом кол-ве _состояний_. Каждое состояние важно в той парадигме, в которой разрабатывается система. Для описания этих состояний и используется диаграмма состояний. Инструмент для моделирования и анализа систем.

### Простейшая диаграмма состояний:

вход-состояние1-действие-состояние2-выход

Описание диаграмм состояния
**Состояния**
1-й эл-т - само состояние - указывается в прямоугольной рамке в которой есть описание фазы, конфигурации, в которой находится объект в момент времени. Это и есть название состояния.

**Переходы**
Механизм, позволяющий перейти из одного состояние в другое. Указывают действия, побуждающие изменения состояний. Представлены в виде стрелок.

**Вход**
Условие, вызывающее перход из одного состояния в другое. Точка входа в состояние. Событие, инициирующее действие в нашей системе.

**Выход**
Условие, вызывающее перход из одного состояния в другое. Завершающий этап всех состояний. Событие, завершающее действия в нашей системе.

### Жизненный цикл разработки, использование диаграммы состояния

**SDLS-модель - system development life sycle - жизненный цикл разработки ПО** - методология разработки инф. систем, описывающая шаги, необходимые для создания, поддержки, внедрения.

Состоит из этапов:
**Анализ требований** - изучение потребностей пользователей, анализ их возможных решений.

**Проектирование, реализация** - создаются спецификации, диаграммы, другие документы, описывающие архитектуру и дизайн системы; далее разработчики занимаются написанием кода для реализации дизайна и архитектуры системы.

**Тестирование** - проверяются, исправляются найденные ошибки.

**Развертывание, поддержка** - устанавливаем продукт у заказчика, занимаемся его поддержкой.

На каждом этапе свои роли отвечающие за стадию продукта (продакт-менеджер, проджект-менеджер, аналитик, разработчик, тестировщик).

### Продакт менеджеры, проджект менеджеры

ДС помогают охватывать различные состояния, которые может принимать продукт, действия, которые можно произвести в каждом состоянии.
Полезно, например, для описания поведения приложения/сайта, в котором пользователь может интерактивно перемещаться между различными экранами/состояниями+наглядно покажет, что является триггером для совершения пользователем действия.

### Аналитики (системные, бизнес)

Диаграммы помогают в анализе, понимании состояния, переходов в бизнес-процессах. Например, ДС могут использоваться для описания, анализа работы какого-либо бизнес-процесса.

### Разработчики

Разработчикам ДС помогают описывать, понимать состояния, переходы между состояниями системы/компонента. Полезно для разработки комплексных/изменяющихся систем, которые могут иметь мн-во различных состояний, переходов между ними.

### Тестировщики

С помощью ДС можно визуализировать возможные состояния, события, которые происходят в системе/приложении. Помогает лучше понимать:

- как работает система
- какие сценарии тестирования надо проверять.

## Инструменты сбора сведений/данных об объекте

1. Логика, открытые источники.
   Командой генерирует сн-во идей, как должна выглядеть система, что должна делать.

2. Интервью, общение со стейкхолдерами (всеми заинтересованными лицами в проекте).

3. Анализ бизнес-процессов.
   Анализируем регламенты/сложившиеся практики работы компании, учитываем эту инф. в разработке системы.

4. Составление mind map.
   Метод визуализации инф. Визуализируя проще найти недостающие звенья и дополнить их.

## Инструменты для построения диаграмм:

- draw.io (https://app.diagrams.net/)
- https://lucidchart.com/
- https://app.diagrams.net/
- https://whimsical.com/
- https://simplemind.eu/
- https://www.mindmeister.com/ru/
- https://www.wisemapping.com/
- https://www.mindomo.com/es/
- MS Visio
