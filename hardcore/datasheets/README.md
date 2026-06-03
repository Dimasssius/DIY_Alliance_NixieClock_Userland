# Datasheets

Даташиты компонентов для плат Hardcore Edition.

Файлы собраны по BOM `Bill Of Materials - Excell.xlsx`. Обычные резисторы и конденсаторы не обрабатывались.

## Скачанные даташиты

| Компонент | Файл | Примечание |
| --- | --- | --- |
| AN2051-245 | `AN2051-245.pdf` | Чип-антенна 2.4 GHz |
| CR1025 | `CR1025.pdf` | Литиевая батарейка CR1025 |
| US1M | `US1M.pdf` | Ultrafast rectifier |
| TL1838 | `TL1838.pdf` | IR receiver module |
| TLP291 | `TLP291.pdf` | Оптопара |
| 74HC595D | `74HC595D.pdf` | Сдвиговый регистр |
| W25Q64JVSSIQ | `W25Q64JVSSIQ.pdf` | SPI Flash W25Q64JV family |
| ESP8266EX | `ESP8266EX.pdf` | Wi-Fi SoC |
| MAX668 | `MAX668.pdf` | Step-up controller |
| ATMEGA328P-AU | `ATMEGA328P-AU.pdf` | AVR microcontroller |
| AMS1117-3.3 | `AMS1117-3.3.pdf` | LDO-регулятор 3.3 V |
| RV-3028-C7 | `RV-3028-C7.pdf` | RTC module |
| K155ID1 | `K155ID1.pdf` | Дешифратор для индикации |
| LQG15HS2N2B02D | `LQG15HS2N2B02D.pdf` | RF-индуктивность |
| MMBTA42 | `MMBTA42.pdf` | Высоковольтный NPN-транзистор |
| AON7264E | `AON7264E.pdf` | N-channel MOSFET |
| BME280 | `BME280.pdf` | Датчик температуры, влажности и давления |
| CH340C | `CH340C.pdf` | USB-UART CH340 family |
| SS12 | `SS12.pdf` | Schottky diode |
| FUET-4020 | `FUET-4020.pdf` | SMD buzzer |
| TSA016A2518C | `TSA016A2518C.pdf` | Tactile switch |
| TS-1009B | `TS-1009B.pdf` | Tactile switch |
| TS-1187A-B-A-B | `TS-1187A-B-A-B.pdf` | Tactile switch |
| XTM20026000FT00351005 | `XTM20026000FT00351005.pdf` | Кварц 26 MHz |
| Female Header 2.54mm | `Female Header 2.54mm.pdf` | Разъем 2.54 mm |
| TYPE-C 16PIN 2MD(073) | `TYPE-C 16PIN 2MD(073).pdf` | USB Type-C connector |

## Не скачано автоматически

| Компонент | Причина |
| --- | --- |
| LED0402, LED0603 | В BOM указаны как обобщенные LED без точного MPN/производителя |
| EE0504S | Не найден надежный публичный даташит по указанному названию |

## Рекомендация

Для позиций без точного MPN лучше уточнить производителя и полный part number в BOM. После этого даташиты можно будет добрать точнее и без риска положить в репозиторий документ от похожего, но не того компонента.
