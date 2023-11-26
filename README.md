# JSlinuxHW4
 1 уровень сложности: Выполняйте в песочнице:
1 Создайте файл file.txt при помощи vi в папке /tmp
2 Добавьте в него 3 первые строчки из вывода команды df -h
3 Дайте права для группы пользователей на запись
4 Уберите права на чтение для хозяина файла.
5 Дайте права на исполнение файла для всех остальных.

0 df -h
   1 vi /tmp/file.txt
   2 chmod g+w /tmp/file.txt
   3 chmod u-r /tmp/file.txt
   4 chmod o+x /tmp/file.txt
   5 cat/tmp/file.txt
   6 df -h
   7 vi /tmp/file.txt
   8 df -h | head -n 3 >> /tmp/file.txt
   9 chmod g+w /tmp/file.txt
  10 chmod u-r /tmp/file.txt
  11 chmod o+x /tmp.file.txt
  12 chmod o+x /tmp/file.txt
  13 cat /tmp/file.txt
  14 ls -l /tmp/file.txt
  15 history > history_25.txt
