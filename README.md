# RasPi4-UART-RS485
Raspberry Pi 4 のUART 5chをRS485に変換したコマンド式サーボモータを動かすための基板データ

Raspberry Pi OSの場合
/boot/config.txt

Ubuntuの場合
/boot/firmware/usercfg.txt

以下を追加
dtoverlay=pi3-miniuart-bt
dtoverlay=uart0
dtoverlay=uart2
dtoverlay=uart3
dtoverlay=uart4
dtoverlay=uart5
