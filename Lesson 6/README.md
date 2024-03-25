## Урок 6. Основы компьютерных сетей. Транспортный уровень. UDP и TCP.

### Запустите несколько клиентов.

<image src="img/диалог с serverom.png" alt="consol">

<image src="img/Диалог клиента с serverom.png" alt="consol">

### Cокеты с помощью команды netstat.

<image src="img/port 55555.png" alt="consol">


<image src="img/Активные подключения.png" alt="consol">

### Перехват трафик своего чата в Wireshark +  сессия

<image src="img/фильтр по адресу.png" alt="vrshark">

<image src="img/фильтр по адресу 2.png" alt="vrshark">

<image src="img/сессия.png" alt="vrshark">

### Общение клиента с сервером.

- Server - Client.pdf

#### Как можно изменить программу server-1.py

1. Логирование: Вместо простого вывода сообщений в консоль, можно использовать модуль logging для более гибкого управления логами.
 
2. Кодирование сообщений: Вместо 'ascii' можно определить переменную для кодировки, изменяя её в одном месте.
. 
3. Опечатка: В последней строке кода написано "Server if listening...", наверно лучше "Server is listening...".(исправлено)



