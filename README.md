# Телеграм бот для интернет магазина

## Установка

### Windows
    git clone https://github.com/AndreyZarn/final_work.git
    pip install -r requirements.txt
### Linux/Mac
    git clone https://github.com/AndreyZarn/final_work.git
    pip3 install -r requirements.txt

##### Настройка в файле configure.py
 
    'name': 'название бота',
    'token': 'токен телеграм бота',
    'tokenqiwi': 'QIWI токен',
    'phoneqiwi': 'номер телефона QIWI',
    'telegramid': ваш телеграм ID,

##### QIWI токен получать по ссылке 
    qiwi.com/api

## Запуск
### Windows
    cd final_work/
    python bot.py

### Linux/Mac
    cd final_work/
    python3 bot.py
