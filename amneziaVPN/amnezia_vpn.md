Настройка AmneziaVPN для ПК и мобильного телефона.
Открывает доступ ко многим заблокированным ресурсам:

🔴 YouTube  
🔵 Discord  
🟣 Instagram  
🟠 и прочему.

1 Перейти в [консоль гугла по ссылке](https://shell.cloud.google.com/?pli=1&show=ide%2Cterminal) (через Google Chrome).

1.1 Скопировать и вставить команду в консоль: [Скрин 1](./steps/step1.jpg)
```bash
curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-generator/main/warp_generator.sh | bash
```
[описание оригинала](https://github.com/ImMALWARE/bash-warp-generator)  
1.2 Выполнить команду нажатием `Enter↵`  
1.3 Дождаться выполнения и скачать получившийся файлик `WARP.conf`. Этот файл больше не открывается в AmneziaWG [Скрин 2](./steps/step2.jpg)

2 Скачать и установить программу.
- на ПК (AmneziaVPN...windows_x64.exe (https://github.com/amnezia-vpn/amnezia-client/releases/download/4.8.9.2/AmneziaVPN_4.8.9.2_windows_x64.exe))
если ссылка выше не работает, качаем из общего репозитория (https://github.com/amnezia-vpn/amnezia-client/releases).
- для Android (Google (https://github.com/amnezia-vpn/amnezia-client/releases) | APK (https://github.com/amnezia-vpn/amnezia-client/releases/tag/4.8.9.2))
- IOS (App Store (https://apps.apple.com/us/app/amneziavpn/id1600529900))
2.1 Импортировать скачанный файл из пункта 1.3 в прогу. Имя файла должно быть без пробелов и скобок
2.2 нажимаем Подключиться

3 В AmneziaVPN можно сделать туннелирование приложений, чтобы игра работала в обход VPN

!Если вырубает ВЕСЬ интернет - конфиг сдох. Нужно от него отключиться.