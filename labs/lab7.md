### Тема
Калькулятор, библиотеки классов

### Время на выполнение
10 дней

### Задание
1. Перейти в локальный репозиторий и создать ветку от main с наименованием по шаблону <наименование_работы>_<номер_студенческого_билета> (например, lab7_325689).
2. Перейти в каталог студента создать новое пустое решение (solution) с именем BUKEP.Student.
3. Добавить в решение ранее созданные проекты BUKEP.Student.ConsoleCalculator и BUKEP.Student.WindowsCalculator.
4. Удалить решения BUKEP.Student.ConsoleCalculator и BUKEP.Student.WindowsCalculator. В результате должно остаться одно решение BUKEP.Student. Удалить из каталога студента каталог BUKEP.Student.SharpInstructions.
5. Создать в решении новый проект типа Class Library с наименованием BUKEP.Student.Calculator.
6. Подключить проект BUKEP.Student.Calculator к проектам BUKEP.Student.ConsoleCalculator и BUKEP.Student.WindowsCalculator как зависимость.
7. Провести рефакторинг проектов BUKEP.Student.ConsoleCalculator и BUKEP.Student.WindowsCalculator, вынести класс калькулятора в проект BUKEP.Student.Calculator класс не должен быть зависимым от типа приложения, в классе должна быть реализована только логика вычисления.
8. Выполнить синхронизацию изменений локального репозитория в удаленный.
9. Создать pull request в ветку main. Создание pull request выполняется из интерфейса вашей системы контроля версий кода (например, GitHub, GitLab).
10. По завершению предоставить ссылку на pull request.
11. Пройти code review со стороны вашего куратора стажировки и исправить все замечания к коду программы.
12. После получения согласования вашего pull request, выполнить его сливание в ветку main c использованием параметра squash (для исключения промежуточных commits). Сливание pull request выполняется из интерфейса вашей системы контроля версий кода (например, GitHub, GitLab).
13. По завершению предоставить ссылку на репозиторий.

### Критерии приема работы
Пройти по предоставленной ссылке и провести code review. Проверить работоспособность приложения на нескольких контрольных примерах. Проверить поведение приложения при некорректном вводе выражений/операций.

### Ссылки для самостоятельного изучения:
1. https://metanit.com/sharp/tutorial/3.46.php
2. https://learn.microsoft.com/ru-ru/dotnet/core/tutorials/library-with-visual-studio?pivots=dotnet-7-0
3. https://web-creator.ru/articles/refactoring