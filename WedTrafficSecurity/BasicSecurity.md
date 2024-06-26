## Базовый уровень защиты

Базовый уровень безопасности и анонимности, выглядит так:
клиент → VPN/TOR/SSH-тунель → цель.

Схема базового уровня - это лишь продвинутая альтернатива прокси, позволяющая просто подменить IP. Один шаг, один клик и о анонимности тут говорить не придется. Уже не придется. Одна неверная или дефолтная настройка пресловутого WebRTC и ваш реальный IP уже известен. Данный тип защиты уязвим и перед компрометацией узла, и перед fingerprints и перед простым анализом логов у провайдера и в дата центре

Часто на просторах Телеграмм встречаются статьи, воспевающие частный VPN, представляя его лучше чем публичный, т.к. человек уверен в своей настройке системы. Давайте на секунду представим, кому-то известен твой внешний IP, соответственно известен и дата центр, соответственно дата центру известно, какому серверу этот IP принадлежит. Сложно ли на месте, установить с какого реального IP к этому серверу подключались? Если ты там один клиент? Ответ очевиден. Когда клиентов, например 100, 1000 - тут уже все намного сложнее

Это даже не касаясь аспектов, что редкий человек, заморочится на шифрованные диски и защиту от выемки, врятли бы даже заметил, если его сервер перезагрузят с init level 1 и включат логи на VPN, описав это как «небольшие технические проблемы в дата центре». Да и разве это вообще нужно, если известны все входящие адреса на сервер и исходящие с него же

Что же касается Tor, во-первых, его использование напрямую может вызывать подозрение, а во-вторых, выходные ноды, которых около 1000 штук известны и многие из них забанены, для многих сайтов это как красная тряпка. Например в Cloudflare есть возможность в Firewall'e разрешать или принимать подключения из сети Tor. В качестве страны следует использовать T1. Кроме того, использование Tor намного медленнее VPN (Скорость в сети Тор на данный момент не превышает 10 мбит, а часто находится на уровне 1-3 мбит)

Итог: Если вам нужно просто не носить по миру свой открытый паспорт и обходить простейшие запреты на сайты, иметь хорошую скорость соединения и возможность полностью пускать весь трафик через другой узел, то следует выбрать VPN. И на эту роль лучше подходит платный сервис, за те же деньги, что вы отдали бы за свой VPS, в 1-й стране, который еще нужно настроить и как-никак поддерживать, вы получите десятки стран и сотни или даже тысячи выходных IP

В этом случае нет смысла использовать Tor, но в каких-то случаях и Tor является хорошим решением, особенно, если существует еще дополнительный слой безопасности, такой как VPN или SSH-туннель. Но об этом дальше


## Средний уровень защиты
Средний уровень безопасности и анонимности, выглядит так:
Клиент → VPN → Тор → цель

Это оптимальный и рабочий инструмент, для любого, не безразличного к подмене IPадреса человека, это именно тот случай, когда сочетание технологий усилило каждую из них. Но не стоит питать иллюзий, да, узнать твой реальный адрес, будет затруднительно, но ты по-прежнему подвержен всем тем же атакам, что и выше. Твое слабое место — это твое физическое место работы, твой компьютер.

## Высокий уровень защиты

Высокий уровень безопасности и анонимности, выглядит так:
Клиент → VPN → Удаленное рабочее место (через RDP/VNC) → VPN → цель

Рабочий компьютер должен быть не твой, а удаленный, например, на Windows 8, с Firefox, парой плагинов вроде Flash, парой кодеков, [ВНИМАНИЕ] никаких уникальных шрифтов и прочих плагинов. Скучный и неотличимый от миллионов других в сети. И даже в случае какой-либо утечки или компрометации твоей системы, ты все равно остаешься прикрыт еще одним VPN'о

Раньше считалось, что высокий уровень анонимности достигался путем использования Tor/VPN/SSH/Socks, но не сегодня. Поэтому обязательно добавляем еще и использование удаленного рабочего места в эту схему

## Максимальный уровень

Клиент → Double VPN (в разных дата центрах, но рядом друг с другом) → Удаленное рабочее место + Виртуальная машина