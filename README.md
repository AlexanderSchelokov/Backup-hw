Задание 1
Составьте команду rsync, которая позволяет создавать зеркальную копию домашней директории пользователя в директорию /tmp/backup
Необходимо исключить из синхронизации все директории, начинающиеся с точки (скрытые)
Необходимо сделать так, чтобы rsync подсчитывал хэш-суммы для всех файлов, даже если их время модификации и размер идентичны в источнике и приемнике.
На проверку направить скриншот с командой и результатом ее выполнения

Ответ 1
![image](https://github.com/AlexanderSchelokov/Backup-hw/assets/121572590/bb1645b7-df6e-4458-8e2c-6ce5587d50ee)

Задание 2
Написать скрипт и настроить задачу на регулярное резервное копирование домашней директории пользователя с помощью rsync и cron.
Резервная копия должна быть полностью зеркальной
Резервная копия должна создаваться раз в день, в системном логе должна появляться запись об успешном или неуспешном выполнении операции
Резервная копия размещается локально, в директории /tmp/backup
На проверку направить файл crontab и скриншот с результатом работы утилиты.

Ответ 2

![image](https://github.com/AlexanderSchelokov/Backup-hw/assets/121572590/bb89b0f5-07ad-4090-98eb-f9448e985860)
![image](https://github.com/AlexanderSchelokov/Backup-hw/assets/121572590/a092933b-d469-4b4b-93c7-f49fd11acb85)
![image](https://github.com/AlexanderSchelokov/Backup-hw/assets/121572590/fd654c2f-f951-4d26-97ea-30bfc89374d0)

