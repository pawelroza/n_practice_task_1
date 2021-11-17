# n_practice_task_1
Ansible practice task 1 for Nexign
Оценка  времени  выполнения: 45 мин
• Установите Ansible. Сгенерируйте на infra ssh ключи (playbooks)ssh-keygen). С 
помощью ansible скопируйте публичный ключ с infra (playbooks)id_rsa.pub) в файлы 
authorized_keys на хосты server1 и server2. С помощью команды ansible 
перезагрузите хосты server1 и server2 (playbooks)модуль Ansiblec);ommand, команда 
shutdown)
• Создайте inventory, включите хосты server1 и server2 в группу webservers. 
Настройте Ansible так, чтобы не нужно указывать имя inventory
• Создайте плейбук по установке, запуску и проверки работоспособности 
nginx. (playbooks)см. комментарии ниже)
• Создайте роль nginx и плейбук, использующий эту роль.
