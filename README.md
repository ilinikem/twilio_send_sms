# twilio_send_sms

## Скрипт для отправки смс на коменр телефона
- python 3.9
- Для доступа к переменным установите через pip библиотеку dotenv: pip install python-dotenv
- Затем импортируйте и выполните функцию load_dotenv :
		import os
		from dotenv import load_dotenv 
		load_dotenv()
		
		token = os.getenv('Token')
- TWILIO_ACCOUNT_SID - sid аккаунта
- TWILIO_AUTH_TOKEN -токен
- phone_to - телефон на который посылаете сообщение
- phone_from - телефон с которго приходит сообщение
- Зарегистрироваться в сервисе https://twilio.com

