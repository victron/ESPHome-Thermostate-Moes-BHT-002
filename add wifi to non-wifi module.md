## Інфа про додавання ESP-12 на плату
[інформація про chip термостата](http://www.cachip.com.cn/Products_details/7362824.html)
фото з tuya:
[польський форум](https://www.elektroda.com/rtvforum/topic4003974.html)  
[github](https://github.com/Koenkk/zigbee2mqtt/issues/4185#issuecomment-1401897521)
[dismount](https://smarthomescene.com/reviews/moes-zigbee-smart-thermostat-bht-002/)
https://github.com/bikemike/MikesThermostat
https://github.com/UlrichMai/MaiThermostat
https://github.com/maccoylton/esp-homekit-wired-thermostat/tree/master

## Схема
потрібно замінити asm1117 на dc-dc convertor (12v to 3.3) - так як з esp12 дуже гріється
наприклад на такий [6pcs Mini MP1584EN DC-DC Buck Converter 3A Power Adjustable Power Supply Module 24V to 12V 9V 5V 3V Step-Down Power Module - AliExpress 502](https://www.aliexpress.com/item/1005006365918330.html?spm=a2g0o.order_list.order_list_main.29.35341802X4NNUn)
потрібно буде в корпусі зробити місце для дроселя.
![thermostat2](https://github.com/victron/ESPHome-Thermostate-Moes-BHT-002/assets/8330202/231b7dcd-7f18-438f-86cc-125c29d0c10c)
![thermostat](https://github.com/victron/ESPHome-Thermostate-Moes-BHT-002/assets/8330202/48f9b75e-ff58-4eb4-a8fd-e0bea83312a2)


TODO:
- sleep mode - можливо

