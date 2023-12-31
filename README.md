# Курсовая работа «Защищённая сеть» по курсу «Сети передачи данных и безопасность»

### Цель проекта

Построить защищённую сеть небольшой компании. 

Вам предстоит:

- собрать схему сети небольшой компании;
- настроить сетевые интерфейсы серверов, рабочих станций, роутеров;
- настроить шлюзы по умолчанию (gateway) для рабочих станций;
- разграничить доступ к серверам компании, используя статические маршруты роутеров (так делают небольшие компании, которые не могут себе позволить приобрести межсетевых экранов).

-----

### Чеклист готовности к курсовой работе

- установлен Cisco Packet Tracer;
- изучены материалы занятий по работе в Cisco Packet Tracer.


------

### Инструменты и дополнительные материалы, которые пригодятся для выполнения задания

1. [Инструкция по установке Cisco Packet Tracer](https://github.com/netology-code/ibnet-homeworks/tree/v2/01_intro).
2. [Шпаргалка по настройке статических маршрутов](https://artemsannikov.ru/cisco/packet-tracer/ip-route-cpt/).

-----

### Инструкция к выполнению курсовой работы

1. Соберите схему по рисунку, приведенному ниже.
<img width="1233" alt="Схема" src="https://github.com/netology-code/ibnetk-diplom/assets/96241243/ff7af947-a54e-4d0d-8b9c-352e6a497fd2">

2. Настройте сетевые интерфейсы серверов, как указано на рисунке.
Примечание: формат 10.10.10.10/24 означает, что ip-адрес - 10.10.10.10, маска подсети - 255.255.255.0. А 10.10.10.100/8 означает, что ip-адрес - 10.10.10.100, маска подсети - 255.0.0.0.
5. Настройте сетевые интерфесы рабочих станций и роутеров в соответствии с заданными подсетями на рисунке.
6. Настройте шлюз по умолчанию (gateway) для рабочих станций. Шлюз будет являться сетевым интерфейсом роутера, к которому подключены рабочие санции через коммутатор.
7. Для Router0 и Router3 настройте по одному статическому маршруту, для Router1 - два статических маршрута. Настройте таким образом, чтобы рабочии станции бухгалтерии пинговали только Сервер бухгалтерии и Файлообменник, а рабочие станции отдела кадров - Сервер отдела кадров и Файлообменник.

-----

### Критерии оценки

Для зачёта работа должна соответствовать критериям:

1. Схема собрана согласно представленному рисунку.
2. Сетевые интерфейсы серверов, рабочих станций и роутеров настроены согласно рисунку.
3. Рабочие станции бухгалтерии пингуют только Сервер бухгалтерии и Файлообменник.
4. Рабочие станции отдела кадров пингуют только Сервер отдела кадров и Файлообменник.

Работа направляется на доработку, если есть несоответствия одному или нескольким критериям.
