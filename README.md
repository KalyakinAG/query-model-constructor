# Двунаправленный конструктор модели запроса

![Версия](https://img.shields.io/badge/Версия_1С-8.3.25-yellow)

Конструктор позволяет интерактивно создать модель запроса на основе текста запроса. Также по созданной модели можно получить исходный текст запроса.

## Состав и установка

Объединить с файлом конфигурации из Демо-базы к статье [Модель запроса](https://infostart.ru/1c/articles/1390402/) или с конфигурацией **KASL.cf** из релиза [сборного проекта KASL](https://github.com/KalyakinAG/kasl):
- Установить режим объединения с приоритетом в файле
- Отметить по подсистемам файла:
	- KASL->[ОбщегоНазначения](https://github.com/KalyakinAG/common)
	- KASL->[АТДМассив](https://github.com/KalyakinAG/adt-array)
	- KASL->Модели->[МодельЗапроса](https://github.com/KalyakinAG/query-model)


## Зависимости

- KASL->[ОбщегоНазначения](https://github.com/KalyakinAG/common)
- KASL->[АТДМассив](https://github.com/KalyakinAG/adt-array)
- KASL->Модели->[МодельЗапроса](https://github.com/KalyakinAG/query-model)
- KASL->Модели->МодельТекста
