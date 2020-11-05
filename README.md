# Тестовое задание

[Задание](https://www.dropbox.com/s/vfy31y44k41mnc4/%D0%94%D0%BE%D0%BC%D0%B0%D1%88%D0%BD%D0%B5%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%28%D0%91%D0%98%D0%9A%29.docx?dl=0)

Так как не было найдено ни одного случая, чтобы ОКПО не был пустым, было принято решение исключить его из требований к заполнению для демонстрации работоспособности.

## Структура

1. BICExtractor - директория основного проекта
2. TestSeq - директория тестового проекта

## Входные данные

- .zip архив, загружаеммый с https://www.cbr.ru/

## Выходные данные

- Таблица ОтчетПроверки_БИК_[текущая_дата(ДД_ММ_ГГГГ)].xlsx

## Особенности

- Основной проект выполнен на основе REF
- Обработаны исключения
- Конфигурируется при помощи файла BICExtractor/Data/Config.xlsx
- После окончания работы удаляются неиспользуемые файлы (архив, распакованный .xml файл)
- При возникновении системных исключений, администратор информируется по e-mail
- Каждый этап работы робота логгируется
