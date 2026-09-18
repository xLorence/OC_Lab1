1. Ввёл команду `uname -a`

Получил от терминала вывод:

<img width="915" height="24" alt="изображение" src="https://github.com/user-attachments/assets/59965600-8d2f-4d7c-aaa3-46d3d4222ee3" />

Эта команда показывает основную информацию о ядре ОС. В выводе можно увидеть название системы, имя компьютера, версию ядра и архитектуру процессора.

2. Ввёл команду `cat etc/os-release`

Получил от терминала вывод:

<img width="406" height="185" alt="изображение" src="https://github.com/user-attachments/assets/6862fb17-b56c-4ef8-b132-e66b7bbf58f9" />

Эта команда уже показывает БОЛЬШУЮ часть информации именно о дистрибутиве.

3. Ввёл команду `uptime`

Получил от терминала вывод:

<img width="572" height="22" alt="изображение" src="https://github.com/user-attachments/assets/aa9f9a7c-eb83-48e6-a23d-c135e2799670" />

Показывает, сколько времени компьютер работает с момента включения.

4. Ввёл команду `whoami`

Получил от терминала вывод:

<img width="84" height="22" alt="изображение" src="https://github.com/user-attachments/assets/02d0a7aa-dd75-4f81-9463-3a82d01e475c" />

Показывает имя пользователя, под которым я сейчас работаю.

5. Ввёл команду `id`

Получил от терминала вывод:

<img width="1266" height="48" alt="изображение" src="https://github.com/user-attachments/assets/786a6bf6-a318-49f1-a369-d0a095979734" />

Эта команда показывает информацию о текушем пользователе: Его UID, GID и группы, в которые он входит.

6. Ввёл команду `lsblk`

Получил от терминала вывод:

<img width="454" height="106" alt="изображение" src="https://github.com/user-attachments/assets/1b5bd3ce-a08d-4341-9396-96e030649666" />

Данная команда показывает блочные устройства, то есть диски и разделы

7. Ввёл команду `df -h`

Получил от терминала вывод:

<img width="478" height="154" alt="изображение" src="https://github.com/user-attachments/assets/520ef971-e013-4048-a7dc-cb1e1f57f01b" />

Показывает, сколько места занято и сколько свободно на файловых системах.

8. Ввёл команду `free -h`

Получил от терминала вывод:

<img width="742" height="65" alt="изображение" src="https://github.com/user-attachments/assets/9e6435bf-eaea-4f09-a0fa-ee10e3537154" />

Показывает состояние оперативной памяти и состояние раздела подкачки (swap)

9. Ввёл команду `lscpu | head -20`

Получил от терминала вывод:

<img width="1700" height="687" alt="изображение" src="https://github.com/user-attachments/assets/cbcd41fa-f9bc-4179-8fc0-a18f16dadf22" />

lscpu показывает характеристики процессора, а head -20 ограничивает вывод первыми двадцатью, чтобы он занимал меньше места.

10. Ввёл команду `ps aux | head -15`

Получил от терминала вывод:

<img width="1652" height="628" alt="изображение" src="https://github.com/user-attachments/assets/2be15867-18c2-4c04-9b0f-6aeb4093ecd6" />

ps aux показывает процессы, которые сейчас запущены в системе, а head -15 используется,чтобы только вывести первые строки списка.

11. Ввёл команду `syetemctl list-units --type=service --state=running`

Получил от терминала вывод:

<img width="1799" height="1269" alt="изображение" src="https://github.com/user-attachments/assets/71e60c23-9619-42ae-a546-4723366309c4" />

Эта команда показывает службы, которые в данный момент запущены в Linux`e














