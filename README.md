# Zilliqa_switcher_hiveos
[English version](https://github.com/mitagmio/Zilliqa_switcher_hiveos/blob/master/READMEENG.md)
# *Версия только при покупке пулом.*

Скрипт использует две утилиты для своей работы cURL и JQ\
<https://stedolan.github.io/jq/download/>\
<https://curl.haxx.se/windows/>

# Краткое описание работы скрипта:
1) на 99 блоке будет останавливаться основной майнинг и запускаться майнер зилики (номер блока выбран с запасом можно изменить настройки под себя)\
2) по окончанию майнинга на 01 блоке майнер зилики закрывается (номер блока выбран с запасом можно будет изменить настройки под себя)\
3) открывается основной майнер\
4) скрипт продолжает работать в фоне обращаясь к API zilliqa проводя проверку номера блока каждые 20 секунд (20 секунд только потому что новый TX блок не ровно каждую минуту появляется)

# Описание параметров:
StartBlock=98 # Блок с которого включается майнинг Zilliqa\
EndBlock=01 # Блок с которого выключается майнинг Zilliqa

# В планах:
1) Есть возможность Zilliqa switcher расширить программным WatchDog для отслеживания загруженности карт и проверкой доступности интернет.\
(Есть наработки как по красным так и по зеленым под win 7\10)\
и еще много интересных идей может возникнуть у вас.

Обсуждение: <https://mininghub.cc/resources/32/>

--------------------------------------------------------------\
Заинтересовашихся прошу обращаться в телеграмм [@mitagmio](https://mininghub.cc/members/1889/)
# Донат:
BTC: 12yDg5uYrcHqN2HoeVp1tR1eanXAJxHsDb\
LTC: LhAxQLTHacm8WoWQ9mHSZmfbqFGCphHqgg\
ETH: 0xb48f60b5e69bcbd95b00b5bd2dd76d8eec524894\
ETC: 0xb48f60b5e69bcbd95b00b5bd2dd76d8eec524894\
CALLISTO: 0x66aefd45d0d7da104dd140f0bd7917967a122a3b

QIWI: 79155009589\
Сбербанк: 79155009589
