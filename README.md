Проект подготовлен в среде разработки IntelliJ IDEA.
В архиве FirstProject содержатся UI-тесты из второго задания, все 3 кейса реализованы в одном проекте.
СУТЬ ЗАДАЧИ:
Задача состоит в написании автотестов которые покрывают следующие 3 кейса:
Кейс 1 Разница двух целых чисел
Открыть сайт https://testsheepnz.github.io/BasicCalculator.html 
Проскроллить вниз до конца
Выбрать сборку (Build) «Prototype»
Ввести в поле First number значение «2»
Ввести в поле Second number значение «3»
Выбрать операцию (Operation) «Subtract»
Нажать на кнопку «Calculate»
Проверить, что в поле ответа (Answer) значение равно «-1»

Кейс 2 Конкатенация двух строк.
Открыть сайт https://testsheepnz.github.io/BasicCalculator.html 
Проскроллить вниз до конца
Выбрать сборку (Build) «Prototype»
Ввести в поле First number значение «gs»
Ввести в поле Second number значение «bu»
Выбрать операцию (Operation) «Concatenate»
Нажать на кнопку «Calculate»
Проверить, что в поле ответа (Answer) значение равно «gsbu»

Кейс 3 Появление сообщения при вводе строки в поле
Открыть сайт https://testsheepnz.github.io/random-number.html 
Проскроллить вниз до конца
Выбрать сборку (Select Build) «Demo»
Нажать на кнопку «Roll the dice»
Ввести в поле значение «string»
Нажать на кнопку «Submit»
Проверить, что появилось сообщение «string: Not a number!»

КАК ОТКРЫТЬ ТЕСТЫ:
1. Распаковываем архив FirstProject.zip в удобное для нас место.
2. Открываем папку и находим элемент FirstProject.iml
3. Открываем данный элемент при помощи IntelliJ IDEA
4. После того как среда открылась, вверху на панели инструментов нажимаем на кнопку "Run" и в выпадающем списке нажимаем кнопку "Run" и выбираем Run FirstTest
5. После того как все тесты выполнятся, в терминале для каждого теста мы можем увидеть конечные значения которые мы получили при Выполнении кейсов. Таким образом реализована проверка.
Так же если необходимо просто посмотреть код без запуска добавил html-файл с кодом.
