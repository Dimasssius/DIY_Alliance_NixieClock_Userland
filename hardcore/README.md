# Hardcore Edition

Материалы для плат DIY_Alliance Nixie Clock Hardcore Edition.

Этот раздел предназначен для расширенной версии платы: прошивки, инструкции, даташиты, ответы на частые вопросы и материалы сборки по версиям плат.

## Версии плат и комплектации

Hardcore Edition делится на две версии по количеству индикаторов:

| Вид платы | Версия платы | Назначение |
| --- | --- | --- |
| <img src="assembly/hardcore-boards-x4-tubes/base-configuration/pcb-3d-print/Top%20Layer%20(Black,%20PCB).png" alt="Hardcore Boards x4 Tubes PCB" width="220"> | [Hardcore Boards x4 Tubes](assembly/hardcore-boards-x4-tubes/) | Версия Hardcore для 4 индикаторов |
| <img src="assembly/hardcore-boards-x6-tubes/base-configuration/pcb-3d-print/Top%20Layer%20(Black,%20PCB).png" alt="Hardcore Boards x6 Tubes PCB" width="220"> | [Hardcore Boards x6 Tubes](assembly/hardcore-boards-x6-tubes/) | Версия Hardcore для 6 индикаторов |

Внутри каждой версии платы есть три комплектации:

| Комплектация | Назначение |
| --- | --- |
| Minimal Configuration | Минимальная комплектация компонентов, необходимая для запуска часов |
| Base Configuration | Стандартная комплектация с реализацией всех основных функций часов |
| Maximal Configuration | Максимальная комплектация с дополнительными датчиками и модулями: температура, IR-приемник и другие опции |

Все материалы по сборке лежат в папке [assembly](assembly/).

Внутри каждой комплектации используются одинаковые разделы с файлами для сборки и проверки:

- `pdf3d/` - 3D PDF и похожие интерактивные материалы;
- `schematic-print/` - печатные версии схем;
- `pcb-3d-print/` - 3D-представления печатной платы;
- `pcb-print/` - печатные изображения платы;
- `bom/` - список компонентов;
- `report-board-stack/` - отчеты по стеку платы;
- `pick-place/` - pick and place файлы, если они разрешены к публикации.

## Общие разделы Hardcore

- [assembly](assembly/) - материалы сборки по версиям Hardcore Boards x4/x6 Tubes и комплектациям;
- [datasheets](datasheets/) - даташиты компонентов;
- [firmware](firmware/) - прошивки и инструкции по обновлению;
- [manuals](manuals/) - инструкции по сборке, запуску и эксплуатации;
- [faq](faq/) - частые вопросы по Hardcore Edition.
