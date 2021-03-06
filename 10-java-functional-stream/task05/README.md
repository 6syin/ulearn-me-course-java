# Задание 05 MailService

В этой задаче вам предстоит самостоятельно написать набор классов таким образом, 
чтобы данный код успешно компилировался и выполнялся. 

Вам предстоит использовать новые знания про generics, коллекции и Stream API.

В приведенном коде используется оператор assert. Этот оператор используется для того, 
чтобы проверять определенные инварианты в коде. С помощью него 
возможно писать небольшие тесты и следить за корректностью своей программы 
(в обычной ситуации предпочтительно для этих целей использовать библиотеки 
для модульного тестирования, которые выходят за рамки базового курса).

Оператор выглядит следующим образом: 
```
assert предикат: сообщение;
```
Предикат – выражение с типом boolean. Если выражение является ложным, 
то в программе возникает исключение AssertionError с соответствующим сообщением.

По-умолчанию данная функциональность отключена. Чтобы ее включить, 
необходимо передать специальный ключ -ea в параметры виртуальной машины. 
Сделать это можно прямо при запуске в консоли с помощью программы java, 
либо указав этот ключ в настройках запуска программы в вашей IDE. 
В случае IntellijIDEA, например, эта опция указывается в поле 
Run -> Edit Configurations... -> конфигурация запуска вашей программы -> VM Options.

Код, который необходимо заставить успешно работать находится в классе Task05Main.

В конечном итоге, вам нужно реализовать классы MailService, MailMessage и Salary 
(и, вероятно, вспомогательные классы и интерфейсы).

В идеологически правильном решении не должно фигурировать ни одного оператора instanceof.

