# vkcoin_miner

https://www.charlesproxy.com/ 

Тебе надо скачать это приложение на компьютер и включить его, 
открыть коммандную строку и ввести `ipconfig` 
И найти IPv4 Address, он будет чтото типа `192.168.1.18` 
потом в телефоне открыть настройки wifi и сделать HTTP Proxy 
туда ввести в адрес (host) этот айпи, а в порт ввести 8888 
после этого запросы будут транслироваться на компьютер с телефона 

на телефоне открой приложениие VK и зайди в VK Coin и потыкай на синюю кнопку пару раз 

потом в Charles найти `wss://coin-without-bugs.vkforms.ru` 
и там найди полный запрос в General, длинный и скопировать его в config 
Будет типа того `"wss://coin-without-bugs.vkforms.ru/channel/20/?vk_access_token_settings=friends&vk_app_id=6915965&vk_are_notifications_enabled=0&vk_is_app_user=1&vk_language=en&vk_platform=mobile_iphone&vk_user_id=123456&sign=asdfasdfasdfasdfasdfasdfasdfasdf&ver=1&pass=123456"`
