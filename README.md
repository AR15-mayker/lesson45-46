# lesson45-46

### параграф 45

1. Что такое топология сети?  

Топология сети – это схема, описывающая физическое или логическое распределение узлов в сети и способы их подключения друг к другу. Топология определяет, как устройства взаимодействуют, какие используют протоколы связи и как осуществляется передача данных.

2. Описание структур, достоинства и недостатки:

Тип сети "Общая шина":  
- Структура: Все узлы подключены к единой шине (кабелю), по которой передаются данные.  
- Достоинства:  
  - Простота установки и дешевизна.  
  - Легкость в добавлении новых узлов.  
- Недостатки:  
  - Ограниченная длина кабеля.  
  - Проблемы с производительностью при увеличении количества узлов.  
  - Появление единой точки отказа – выход из строя шины приводит к сбою всей сети.

Тип сети "Звезда":  
- Структура: Все узлы подключены к центральному устройству (например, свичу или концентратору).  
- Достоинства:  
  - Высокая устойчивость – выход из строя одного устройства не влияет на остальные.  
  - Простота в управлении и диагностике сети.  
- Недостатки:  
  - Необходимость в центральном устройстве – его сбой может привести к отключению всей сети.  
  - Более высокие затраты на кабели.

Тип сети "Кольцо":  
- Структура: Узлы соединены в замкнутый контур. Данные передаются по кругу от одного устройства к другому.  
- Достоинства:  
  - Стабильная производительность при относительно небольшом количестве узлов.  
  - Простота передачи данных между узлами.  
- Недостатки:  
  - Если одно устройство выходит из строя, вся сеть может быть нарушена.  
  - Сложности в добавлении новых узлов.

3. Предлагаемая структура для школьной сети:  
В зависимости от ситуации можно рассмотреть разные структуры:

- Для небольших кабинетов или классов:  
  Рекомендуется использовать топологию звезда, так как она обеспечивает устойчивую работу сети и упрощает подключение новых устройств.

- Для большого количества компьютеров вкорпусах или лабораториях:  
  Может быть целесообразным использовать топологию смешанная (вариант звезды и шины). Это позволяет уменьшить нагрузку на кабельные линии и обеспечить хорошую производительность.

- Для мобильных лабораторий или выездных классов:  
  Попробуйте беспроводную сеть (Wi-Fi), чтобы позволить ученикам подключаться к сети без проводов, обеспечивая гибкость и удобство.

### паранраф 46

1. Что такое локальная сеть?

Локальная сеть (LAN) – это сеть, ограниченная небольшой географической площадью, такой как дом, офис или учебное заведение. Она позволяет устройствам обмениваться данными и ресурсами, такими как принтеры и файлы.

3. В каких случаях лучше использовать сеть с выделенными серверами?

Сеть с выделенными серверами рекомендуется использовать в случаях, когда необходимо:  
- Обеспечить централизованное управление данными и ресурсами.  
- Обработать большие объемы данных и обеспечить высокую производительность.  
- Гарантировать надежность и доступность сервисов (например, для бизнеса или организаций).  
- Обеспечить безопасность, используя серверное программное обеспечение для защиты данных.

3. Какие задачи решают компьютеры-серверы?

Компьютеры-серверы решают ряд задач, включая:  
- Хранение и управление данными.  
- Обслуживание запросов от клиентов (например, веб-серверы обслуживают веб-страницы).  
- Обеспечение доступности ресурсов (например, принтеров или файлов).  
- Обработка запросов в режиме реального времени (например, для баз данных и приложений).

4. Чем отличаются серверные ОС от клиентских?

Серверные операционные системы отличаются от клиентских:  
- Оптимизированы для управления большими объемами запросов от клиентов.  
- Поддерживают многопользовательский доступ и работу с сетью.  
- Обычно имеют больше возможностей для администрирования и управления ресурсами.  
- Обеспечивают повышенную безопасность и защиту данных.

5. Какими возможностями должны обладать сетевые операционные системы?

Сетевые операционные системы должны обладать следующими возможностями:  
- Поддержка многопользовательского доступа.  
- Управление сетевыми ресурсами (например, файловыми и печатающими).  
- Обеспечение сетевой безопасности (аутентификация, авторизация).  
- Мониторинг и учет сетевого трафика.  
- Инструменты для администрирования и диагностики сети.

6. Что такое терминальный доступ?

Терминальный доступ – это возможность входа в систему с удаленного устройства через терминал или программу удаленного доступа. Это позволяет пользователю взаимодействовать с сервером или компьютером и выполнять команды без физического присутствия у устройства.

8. Что такое точка доступа? Что такое зона доступа Wi-Fi?
  
- Точка доступа (Access Point) – это устройство, позволяющее разблокировать беспроводное подключение к сети, обеспечивая взаимодействие между проводной сетью и беспроводными устройствами.  
- Зона доступа Wi-Fi – это область, в которой устройства могут подключаться к беспроводной сети через точку доступа. Размер зоны доступа зависит от мощности передатчика, препятствий и других факторов.

8. В каких случаях применяются стандарты беспроводных сетей Bluetooth и Wi-Fi?

- Bluetooth используется для связи на коротких расстояниях (например, для подключения гарнитур, клавиатур, мышей).  
- Wi-Fi применяется для создания более широких беспроводных сетей, позволяя устройствам подключаться к интернету и обмениваться данными на разных расстояниях.

9. Как обеспечивается защита данных в беспроводных сетях?
   
Защита данных в беспроводных сетях обеспечивается с помощью:  
- Шифрования данных (например, WPA2 или WPA3).  
- Аутентификации пользователей и устройств.  
- Файрволов и систем обнаружения вторжений.  
- Регулярного обновления программного обеспечения и прошивок.

10. Какие оборудование необходимо для создания беспроводной сети? Назовите преимущества и недостатки беспроводных сетей.  
Необходимое оборудование:
  
- Точка доступа (Access Point).  
- Роутер.  
- Беспроводные адаптеры для устройств.  

Преимущества:  
- Гибкость подключения.  
- Удобство для мобильных устройств.  
- Быстрое развертывание.

Недостатки:  
- Подверженность внешним помехам и уязвимостям.  
- Ограниченная зона действия.  
- Менее высокая скорость по сравнению с проводными сетями.

11. Какое сетевое оборудование необходимо для кабельных сетей?  

Для создания кабельных сетей нужно:
- Коммутаторы (Switches).  
- Маршрутизаторы (Routers).  
- Кабели (например, витая пара, оптоволокно).  
- Сетевые карты для устройств.

12. Что такое коммутатор?

Коммутатор (Switch) – это устройство, которое соединяет несколько устройств в локальной сети, позволяя им обмениваться данными. Он передает данные только нужному адресу, что повышает эффективность и безопасность сети.

14. Что такое патч-корд?

Патч-корд – это короткий кабель, используемый для подключения сетевых устройств к сетевой инфраструктуре (например, для подключения компьютера к коммутатору). Обычно имеет стандартные коннекторы RJ45 на обоих концах.

16. Что такое маршрутизатор? Какую роль он выполняет в локальной сети?  
Маршрутизатор (Router) – это устройство, которое соединяет разные сети и направляет данные между ними. В локальной сети он выполняет следующие роли:  
- Обеспечивает доступ к Интернету для всех устройств в сети.  
- Управляет маршрутизацией данных внутри сети.  
- Предоставляет функции безопасности (например, NAT, брандмауэры).
