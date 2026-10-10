<div align="center">

# DIY_Alliance · Nixie Clock

**База знаний для сборки и использования часов на газоразрядных индикаторах**

[Начать сборку](START_HERE.md) · [Управление часами](common/manuals/USER_GUIDE.md) · [Решение проблем](common/troubleshooting/README.md)

</div>

Здесь собраны материалы для владельцев плат и наборов DIY_Alliance: инструкции, схемы, списки компонентов, настройки прошивки и 3D-модели.

## Что вы хотите сделать?

| Задача | Куда перейти |
| --- | --- |
| Получил плату и собираю впервые | [Пошаговый маршрут сборки](START_HERE.md) |
| Нужны BOM, схема или сборочный чертёж | Выберите свою плату в таблице ниже |
| Нужно настроить и загрузить прошивку | [Прошивка и совместимость](common/firmware/README.md) |
| Хочу настроить время, подсветку или будильник | [Руководство пользователя](common/manuals/USER_GUIDE.md) |
| Часы не запускаются или показывают неверные цифры | [Диагностика по симптомам](common/troubleshooting/README.md) |
| Подбираю газоразрядные индикаторы | [Поддерживаемые индикаторы и сокеты](common/indicators/README.md) |

## Выберите свою плату

**Standard** — базовая линейка. **Hardcore** — расширенная линейка с комплектациями Minimal, Base и Maximal. Выбирайте раздел по своей плате и количеству индикаторов.

| Standard Edition | Hardcore Edition |
| --- | --- |
| **[Standard · 4 индикатора](standard/assembly/standard-boards-x4-tubes/README.md)**<br><a href="standard/assembly/standard-boards-x4-tubes/README.md"><img src="standard/assembly/standard-boards-x4-tubes/pcb-3d-print/Верхний%20слой%20%28Печатная%20плата%29.png" alt="Верхняя сторона платы Standard на 4 индикатора" width="280"></a> | **[Hardcore · 4 индикатора](hardcore/assembly/hardcore-boards-x4-tubes/README.md)**<br><a href="hardcore/assembly/hardcore-boards-x4-tubes/README.md"><img src="hardcore/assembly/hardcore-boards-x4-tubes/base-configuration/pcb-3d-print/Top%20Layer%20%28Black%2C%20PCB%29.png" alt="Верхняя сторона платы Hardcore на 4 индикатора, базовая комплектация" width="280"></a> |
| **[Standard · 6 индикаторов](standard/assembly/standard-boards-x6-tubes/README.md)**<br><a href="standard/assembly/standard-boards-x6-tubes/README.md"><img src="standard/assembly/standard-boards-x6-tubes/pcb-3d-print/Верхний%20слой%20%28Печатная%20плата%29.png" alt="Верхняя сторона платы Standard на 6 индикаторов" width="280"></a> | **[Hardcore · 6 индикаторов](hardcore/assembly/hardcore-boards-x6-tubes/README.md)**<br><a href="hardcore/assembly/hardcore-boards-x6-tubes/README.md"><img src="hardcore/assembly/hardcore-boards-x6-tubes/base-configuration/pcb-3d-print/Top%20Layer%20%28Black%2C%20PCB%29.png" alt="Верхняя сторона платы Hardcore на 6 индикаторов, базовая комплектация" width="280"></a> |

Изображения помогают ориентироваться в линейках. Ревизию и комплектацию уточняйте по маркировке платы и документам к набору.

## Какие материалы уже доступны?

| Материалы | Статус |
| --- | --- |
| BOM, электрические схемы, сборочные чертежи и рендеры | Есть для Standard x4/x6 и трёх комплектаций Hardcore x4/x6 |
| Пошаговые PDF-инструкции по сборке | Есть для [Standard x4/x6](standard/manuals/README.md); отдельная инструкция [Hardcore](hardcore/manuals/README.md) пока не опубликована |
| Общая подготовка к сборке и управление часами | [Подготовка](common/manuals/ASSEMBLY_GUIDE.md) · [Управление](common/manuals/USER_GUIDE.md) |
| Прошивка | Есть [заметки по настройке внешней прошивки](common/firmware/README.md); готовых сборок для скачивания в этой Wiki пока нет |

> [!CAUTION]
> В часах используется высокое напряжение. Перед сборкой и первым запуском прочитайте [общие рекомендации](common/manuals/ASSEMBLY_GUIDE.md) и инструкцию своей платы.

## Справка и новости

[Частые вопросы](FAQ.md) · [Общие материалы](common/README.md) · [Инструменты](common/tools/README.md) · [Новости проекта](announcements/README.md) · [История изменений](CHANGELOG.md)

По вопросам платы и набора обращайтесь к автору проекта: **DIY_Alliance / @Dimasssius**. При обращении укажите линейку, число индикаторов, ревизию, комплектацию и описание проблемы.

<details>
<summary>О репозитории и использовании материалов</summary>

Репозиторий предназначен для владельцев готовых плат и наборов. Исходники печатных плат, Gerber-файлы и производственные проекты PCB здесь не публикуются.

Код и прошивки распространяются по MIT, документация, BOM, схемы, изображения и 3D-модели — по CC BY 4.0 с указанием автора и первоисточника. Даташиты принадлежат производителям. Полные условия: [LICENSE](LICENSE).

Для сопровождающих Wiki: [аудит и дальнейшие улучшения](WIKI_REVIEW.md).

</details>
