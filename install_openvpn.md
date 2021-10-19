Установим и настроим OpenVPN
Для установки и последующей настройки пакетов, требуемых при запуске OpenVPN, будет использован соответствующий скрипт. Вам следует предоставить ему корректный IP-адрес сервера.
Загрузим данный скрипт:

wget https://raw.githubusercontent.com/angristan/openvpn-install/master/openvpn-install.sh

Далее необходимо сделать его исполняемым:

chmod +x openvpn-install.sh

А затем запустить:

./openvpn-install.sh
