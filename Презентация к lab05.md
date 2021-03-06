# Отчет о выполнеии лабораторной работы №5
# Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки

----

## Российский Университет Дружбы Народов

### Факульткт Физико-Математических и Естественных Наук

*Дисциплина: Операционные системы*

Студент: Алших маслем Ахмад

Группа: НФИБД-02-20

Москва, 2021г.

----

### Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

----

### Ход работы:

1. Определил полное имя моего домашнего каталога.
   
2. Перешел в каталог /tmp и вывел содежимое с помощью команды ls с разными опциями.

![12a6b826016aa9cbb.png](https://ic.wampi.ru/2021/05/13/12a6b826016aa9cbb.png)

![29e45f2f3be2277d4.png](https://ic.wampi.ru/2021/05/13/29e45f2f3be2277d4.png)

Определил, есть ли в каталоге /var/spool подкаталог с именем cron.

![3d924854692fff5ec.png](https://ic.wampi.ru/2021/05/13/3d924854692fff5ec.png)

Отобразил содержимое домашнего каталога и его владельцев (владелец всех файлов - я)

![429ddf8cba98f4903.png](https://ic.wampi.ru/2021/05/13/429ddf8cba98f4903.png)

3.	Выполните следующие действия: В домашнем каталоге создал новый каталог с именем newdir. А в каталоге ~/newdir создал новый каталог с именем morefun. В домашнем каталоге создал одной командой три новых каталога с именами letters, memos, misk. Затем удалил их. Попробовал удалить ранее созданный каталог ~/newdir командой rm. Произошла ошибка, так как данный каталог не был пустым.

Удалил каталог ~/newdir/morefun из домашнего каталога. Проверил.

![58bc9bd8861bab46b.png](https://ic.wampi.ru/2021/05/14/58bc9bd8861bab46b.png)

4.	С помощью команды man определил, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов, входящих в него.
 
![61c2b745d9e816e90.png](https://ic.wampi.ru/2021/05/14/61c2b745d9e816e90.png)

5.	С помощью команды man определил набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым
 
![777937f617c71291d.png](https://ic.wampi.ru/2021/05/14/777937f617c71291d.png)

6.	Использовал команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm. Пояснил основные опции этих команд.
 
 Основные опции cd - переходить по ссылкам и выдавать ошибку если директория не найдена.
 
![8fd37dda67f25e67b.png](https://ic.wampi.ru/2021/05/14/8fd37dda67f25e67b.png)

Основные опции pwd - отбрасывать все символические ссылки и отображать справку об утилите и ее версию.

![9730e8cc56f0b9eac.png](https://ic.wampi.ru/2021/05/14/9730e8cc56f0b9eac.png)
 
Основные опции mkdir - назначать режим доступа и выводить сообщение о каждом новом каталоге.

![10.png](https://ic.wampi.ru/2021/05/14/10.png)
 
Основные опции rmdir - удалять все дочерние каталоги.

![11.png](https://ic.wampi.ru/2021/05/14/11.png)

Основные опции rm - рекурсивное удаление, выводить запрос на подтверждение, выводить информацию о удаляемых файлах, игнорировать несуществующие файлы.

![12.png](https://ic.wampi.ru/2021/05/14/12.png)

7.	Используя информацию, полученную при помощи команды history, выполнил модификацию и исполнение команды из буфера команд.

![Ekran-Resmi-2021-05-14-02.23.55.png](https://ic.wampi.ru/2021/05/14/Ekran-Resmi-2021-05-14-02.23.55.png)

----

## Контрольные вопросы

1.	Командная строка является программной оболочкой позволяющей в текстовом виде вводить компьютеру различные команды.


2.	Aбсолютный путь к текущему каталогу можно определить с помощью команды pwd.

![130e5bf21fde81b2a5.png](https://ic.wampi.ru/2021/05/14/130e5bf21fde81b2a5.png)
3.	При помощи команды ls и опции -F можно определить только тип файлов и их имена в текущем каталоге.

![14.png](https://ic.wampi.ru/2021/05/14/14.png)
4.	Некоторые файлы в операционной системе скрыты от просмотра и обычно используются для настройки рабочей среды. Имена таких файлов начинаются с точки. Для того, чтобы отобразить имена скрытых файлов, необходимо использовать команду ls с опцией -a.

![15.png](https://ic.wampi.ru/2021/05/14/15.png)

5.	Команда rm используется для удаления файлов и/или каталогов.

![16.png](https://ic.wampi.ru/2021/05/14/16.png)

6.	Команда history выводит список ранее выполненных команд.

7.	Можно модифицировать команду из выведенного на экран списка при помощи следующей конструкции: !<номер_команды>:s/<что_меняем>/<на_что_меняем> 

![171586fe379a37cbc0.png](https://ic.wampi.ru/2021/05/14/171586fe379a37cbc0.png)

8.	«;». Если требуется выполнить последовательно несколько команд, записанный в одной строке, то для этого используется символ точка с запятой.

![Ekran-Resmi-2021-05-14-02.54.28.png](https://ic.wampi.ru/2021/05/14/Ekran-Resmi-2021-05-14-02.54.28.png)
9.	Экранирование символов — замена в тексте управляющих символов на соответствующие текстовые подстановки. Если встречаются специальные символы (типа «.», «/», «*» и т.д.), надо перед ними поставить символ экранирования \ (обратный слэш).

10.	Чтобы вывести на экран подробную информацию о файлах и каталогах, необ- ходимо использовать опцию l. При этом о каждом файле и каталоге будет выведена следующая информация: – тип файла, – право доступа, – число ссылок, – владелец, – размер, – дата последней ревизии, – имя файла или каталога.

11.	Относительный путь представляет собой путь по отношению к текущему рабочему каталогу пользователя или активных приложений. Используется в команде cd.

12.	Команда man используется для просмотра (оперативная помощь) в диалоговом режиме руководства (manual) по основным командам операционной системы типа Linux.

13.	TAb служит для автоматического дополнения вводимых команд.

----

### Вывод
Приобрел практические навыки взаимодействия пользователя с системой посредством командной строки. Изучил опции различных команд и понял как и где их преминять.

----
