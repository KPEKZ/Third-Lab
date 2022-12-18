## ✅Лабораторная работа №3
### Тема: "Разработка проекта компьютерной сети c реализацией VLAN в Cisco Packet Tracer"
#### Задание: Компания арендовала 3 помещения в бизнес-центре. В этих помещениях есть только голые стены и розетки, необходимо разработать схему сети.

<hr>

<h4 align="center">Добавление оборудования</h4>

<hr>

Открываем Packet Tracer и создаем на рабочем поле:
- a. 16 компьютеров
- b. Сервер
- c. 3 коммутатора Cisco 2960
- d. Маршрутизатор Cisco 1941
- e. Роутер Cisco WRT300N 

<p align="center">
  <img src="https://user-images.githubusercontent.com/31378456/208290823-d1a4d3d9-f47e-4fe5-b01c-6cf623433082.png">
</p>

Рис. 1. Базовый набор устройств для построения сети

<hr>

<h4 align="center">Установка Wi-Fi модуля в ПК</h4>

<hr>

У четырёх компьютеров в третьем отделе заменяем LAN разъём на Wi-Fi антенну

![image](https://user-images.githubusercontent.com/31378456/208290932-61e4d45c-6386-45c2-9ba7-c849aee66df2.png)

Рис. 2. Физическая модель устройства (ПК-12)

![image](https://user-images.githubusercontent.com/31378456/208290941-431dd3f7-9cf5-4bea-9fe0-0d3c442d4ba3.png)

Рис. 3. Физическая модель устройства (ПК-13) 

![image](https://user-images.githubusercontent.com/31378456/208290945-995a2c55-757f-4937-a56a-99969023ccb2.png)

Рис. 4. Физическая модель устройства (ПК-14) 

![image](https://user-images.githubusercontent.com/31378456/208290950-51a74140-b996-4dc6-96b5-d7c7af4dc0ba.png)

Рис. 5. Физическая модель устройства (ПК-15)

![image](https://user-images.githubusercontent.com/31378456/208290953-553ee454-f8c4-4029-82f9-a793f7c390e1.png)

Рис. 6. Активные беспроводные подключения

<hr>

<h4 align="center">Настройка ПК первого и второго отдела</h4>

<hr>


Каждому компьютеру в первом и втором отделе, а также серверу присвоим значения по формуле: N0.0.0.n, где N – номер отдела, а n – номер устройства (например, 10.0.0.2 – второй компьютер на первом этаже). Сервер, так как он третье устройство на втором этаже будет иметь адрес 20.0.0.3. 
Маску подсети выставим на 255.255.255.0. 
Default Gateway выставим N0.0.0.254. 
DNS Server выставляем на 20.0.0.3.


![image](https://user-images.githubusercontent.com/31378456/208290971-bd45cf47-2625-4ca4-b1b2-a204d1511b2a.png)

Рис. 7. Настройка ПК в первом (левом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208290983-6f07a5b2-c636-489a-84e2-21f5a771809c.png)

Рис. 8. Настройка ПК в первом (левом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208290994-e61f1ca5-d27a-49bb-9eae-f22183df9e5f.png)

Рис. 9. Настройка ПК в первом (левом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291001-66461ec3-5ad4-4773-b105-a4fc093299f9.png)

Рис. 10. Настройка ПК в первом (левом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291007-5958a16e-4003-44ed-80f3-f9314a972460.png)

Рис. 11. Настройка ПК во втором (среднем) отделе

![image](https://user-images.githubusercontent.com/31378456/208291012-923a98cb-b2ef-456f-b69a-de7cab06f963.png)

Рис. 12. Настройка ПК во втором (среднем) отделе

![image](https://user-images.githubusercontent.com/31378456/208291015-97d27cfc-18d1-4d55-9967-7825f531dcdd.png)

Рис. 13. Настройка сервера во втором (среднем) отделе

<hr>

<h4 align="center">Настройка третьего отдела</h4>

<hr>

![image](https://user-images.githubusercontent.com/31378456/208291028-ed18bbda-9478-4ac6-ae8b-15bf1b785d1c.png)

Рис. 14. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291032-4f13a5fd-9614-431d-892e-6f58b430813c.png)

Рис. 15. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291036-a320ac64-154f-418d-8738-82f7e0e6f356.png)

Рис. 16. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291042-052d3f96-9578-4886-9b5c-bad29e624860.png)

Рис. 17. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291054-3b451bb4-4dad-4689-8734-b7cc477f8576.png)

Рис. 18. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291058-6583c356-48e8-48d8-a1fd-0853df74d554.png)

Рис. 19. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291066-9b28cc56-02fd-4813-8999-7c201bebf917.png)

Рис.20. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291073-8c3a0dc9-aa67-4902-b002-f94b103efe6e.png)

Рис.21. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291078-5d3cc31b-dc08-4516-bec1-8a45594f4285.png)

Рис.22. Настройка ПК в третьем (правом по схеме) отделе

![image](https://user-images.githubusercontent.com/31378456/208291086-5007d88f-8174-4923-a68f-b49850eae1d0.png)

Рис. 23. Настройка ПК в третьем (правом по схеме) отделе

<hr>

<h4 align="center">Настройка беспроводного роутера</h4>

<hr>

![image](https://user-images.githubusercontent.com/31378456/208291098-6b550182-4419-46fb-9ea2-f7b29caa6c90.png)

Рис. 24. Основные настройки беспроводного роутера

![image](https://user-images.githubusercontent.com/31378456/208291103-1cd93bc2-2f21-42e4-898b-78e6e162c4b7.png)

Рис. 25. Настройки беспроводного подключения

![image](https://user-images.githubusercontent.com/31378456/208291108-672ecc28-ada1-414d-9f90-f416739cf0e1.png)

Рис. 26. Настройки безопасности подключения

<hr>

<h4 align="center">Настройка беспроводных ПК</h4>

<hr>

Задаём имя сети Cisco2107 и WPA2-Personal пароль – junior17

![image](https://user-images.githubusercontent.com/31378456/208291121-787499e0-62e6-45db-ae74-55e5464e88f8.png)

Рис. 27. Настройки беспроводной связи ПК

![image](https://user-images.githubusercontent.com/31378456/208291127-3340b36f-178c-4cb1-ad57-f067b450b5ae.png)

Рис. 28. Настройки беспроводной связи ПК

![image](https://user-images.githubusercontent.com/31378456/208291132-c55fa4a7-10d7-438e-9130-9f0d1c7bdf56.png)

Рис. 29. Настройки беспроводной связи ПК

![image](https://user-images.githubusercontent.com/31378456/208291142-f167d0d0-0f6e-4628-855a-45a28e193c6d.png)

Рис.30. Настройки беспроводной связи ПК

<hr>

<h4 align="center">Подключаем кабели и соединяем отделы</h4>

<hr>

Соединяем ПК, коммутаторы и роутеры кабелями.


![image](https://user-images.githubusercontent.com/31378456/208291154-c377c8e2-29ee-4932-9407-0d32c9ed631b.png)

Рис.31. Схема сети со всеми подключениями

Настраиваем VLAN на всех коммутаторах.

![image](https://user-images.githubusercontent.com/31378456/208291163-d3e09393-883b-4cbb-8120-df98ef4ff009.png)

Рис.32.Настройка VLAN на порт коммутатора 1 отдела

![image](https://user-images.githubusercontent.com/31378456/208291168-e0010ce7-63b9-4967-a9fc-d7e38bfdb5d1.png)

Рис.33.Настройка VLAN на порт коммутатора 2 отдела

![image](https://user-images.githubusercontent.com/31378456/208291175-1d3b713c-cffe-4fd1-87ad-3cf07c5d48c0.png)

Рис.34.Настройка VLAN на порт коммутатора 3 отдела

![image](https://user-images.githubusercontent.com/31378456/208291179-4a75a213-96a1-4bb6-8f94-f6ae887bd67b.png)

Рис.35.Установка VLAN на порт коммутатора 1 отдела

![image](https://user-images.githubusercontent.com/31378456/208291186-9d44abfb-f2f2-402b-99b0-d8087753d786.png)

Рис.36.Установка VLAN на порт коммутатора 2 отдела

![image](https://user-images.githubusercontent.com/31378456/208291193-a91b8cc4-f8e8-4e02-b8da-c253e83b228f.png)

Рис.37.Установка порта в режим Trunk

![image](https://user-images.githubusercontent.com/31378456/208291203-a96700f1-c7c7-4521-afe2-6d67118db9a6.png)

Рис.38.Установка VLAN на порт коммутатора 3 отдела

<hr>

<h4 align="center">Производим настройку маршрутизатора для работы с VLAN</h4>

<hr>


![image](https://user-images.githubusercontent.com/31378456/208291221-a1ea640e-45f6-4dd8-bd90-cb6200705b56.png)
Рис.39.Настройка роутера

<hr>

<h4 align="center">Протестируем сеть командой ping</h4>

<hr>


Пример (пинг из первого отдела во второй)

![image](https://user-images.githubusercontent.com/31378456/208291237-ff20d61a-f6fe-478f-83f0-95e04375ffd6.png)

Рис.40. Пинг машины из другого отдела

<hr>

<h4 align="center">Настройка сервера</h4>

<hr>


Включаем DNS (вкладка Services -> DNS).
Name — www.cisco.com
Address – 20.0.0.3

![image](https://user-images.githubusercontent.com/31378456/208291247-a4f8ba44-25f2-4b0a-b18d-c905680d3cf9.png)

Рис.41. Параметры DNS сервера

![image](https://user-images.githubusercontent.com/31378456/208291250-3a2d3cb6-1094-4c5a-ac64-cd2ccffdc4a5.png)

Рис.42. Проверка DNS

<hr>

<h4 align="center">Настройка SSH</h4>

<hr>

![image](https://user-images.githubusercontent.com/31378456/208291266-f5ca79ff-de7f-457a-900f-3312fe058fbd.png)

Рис.43. Настройка SSH

![image](https://user-images.githubusercontent.com/31378456/208291273-d8263959-0bf9-42b6-b341-5b8c28d5d9fd.png)

Рис.44. Подключение по SSH

![image](https://user-images.githubusercontent.com/31378456/208291279-ead949bc-74f7-4e0c-b8d2-3a8669315efc.png)

Рис.45. Проверка работы соединения

<hr>

<h4 align="center">Вывод</h4>

<hr>

В ходе лабораторной работы разработали схему сети из 22 устройств c реализацией VLAN и безопасного доступа SSH в Cisco Packet Tracer.





















