# Задание
Написать программу, в которой будет два потока: первый читает вводимую в консоль информацию и обрабатывает команды, второй поток ежесекундно читает файл и проверяет, есть ли для пользователя новые сообщения. Если есть — выводит их в консоль. В сообщении должно содержаться имя отправителя. 


**Команды:**
+ /reg USERNAME — регистрация (без этой команды остальной функционал недоступен)
+ /exit — выход из приложения
+ Просто текст — обычное сообщение
+ /pause и /resume [ОПЦИОНАЛЬНО] — приостановить и возобновить чтение файла


**Требования:**
+ maven/gradle

**Пример работы:**
```
» /reg Alex
Привет, Alex! 
» Джава — круто
[Alex]: Джава — круто
[Bob]: Я пишу из файла!
» /exit
Пока, Alex. Приходи еще 
``Process finished with exit code 0``
```

Полезные материалы: [ссылка](MATERIALS.md)
