# discordfix
1. Для тех кто пользуется goodbyedpi от величайшего ValdikSS для обхода блокировки YouTube всё просто:
  Заходим в папку с программой и открываем файл russia-blacklist.txt ![image](https://github.com/user-attachments/assets/06411f42-9e40-44a9-a3b5-e11ce2486e73)
  Добавляем в файл домены дискорда:
    ```
    discord-attachments-uploads-prd.storage.googleapis.com 
    dis.gd 
    discord.co 
    discord.com 
    discord.design 
    discord.dev 
    discord.gg 
    discord.gift 
    discord.gifts 
    discord.media 
    discord.new 
    discord.store 
    discord.tools 
    discordapp.com 
    discordapp.net 
    discordmerch.com 
    discordpartygames.com 
    discord-activities.com 
    discordactivities.com 
    discordsays.com
    ```
   Заходим по ссылке https://www.browserling.com/tools/random-hex , генерируем хекс по этим параметрам![image](https://github.com/user-attachments/assets/794ad2e5-e795-477e-a60f-ccc65dd426a4). После чего нажимаем Generate и копируем его.
   Заходим в файл service_install_russia_blacklist.cmd нажимаем "изменить" ![image](https://github.com/user-attachments/assets/e3615d1c-d4d8-4a0c-9fb4-238aee466123). Вместо "-9" вставляем "-9 -e1 -q --fake-gen 29 --fake-from-hex ВАШ HEX". Выглядить должно следующим образом: ![image](https://github.com/user-attachments/assets/c109d3c2-bd30-44aa-b32b-9bbfcdff9035). То же самое проделываем с 1_russia_blacklist.cmd . Вставляем туда всё тоже самое вместо "-9"

   Запускаем service_install_russia_blacklist.cmd и перезапускаем пк. Если вы сделали всё правильно, дискорд должен заработать. Но, к сожалению это не фиксит голосовые каналы, только текстовые чаты.

3. Для тех кто в душе не ебет что такое goodbyedpi: заходим по ссылке ( https://github.com/ValdikSS/GoodbyeDPI/releases/tag/0.2.3rc3 ) и скачиваем ласт версию программы. Распаковываем в удобное для нас место и делаем все, что указано в первом способе. ![image](https://github.com/user-attachments/assets/895d968f-03ad-4228-9510-a46de087ae3e)

ВАЖНО!!!!!
ЕСЛИ У ВАС НАБЛЮДАЮТСЯ ПРОБЛЕМЫ С ЗАПУСКОМ ПРИЛОЖЕНИЙ, ИГР ИЛИ ЛЮБЫХ ДРУГИХ ПРОГРАММ ЗАПУСТИТЕ ФАЙЛ service_remove.cmd И ПЕРЕЗАПУСТИТЕ ПК. В ТАКОМ СЛУЧАЕ ЗАПУСКАЙТЕ ФАЙЛ 1_russia_blacklist.cmd , И НЕ ЗАКРЫВАЙТЕ ЕГО ПОКА ВЫ ПОЛЬЗУЕТЕСЬ ДИСКОРДОМ ИЛИ ЮТУБОМ

  
