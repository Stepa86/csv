# csv
Чтение csv в оскрипте

Чтение csv из файла или строки с учетом кавычек и произвольного разделителя.

## Пример использования

```bsl
#Использовать csv

ИсходнаяСтрока = "1,2,3,4";
разделитель = ",";

результат = ЧтениеCSV.ИзСтроки(ИсходнаяСтрока, разделитель);

кодировкаФайла = КодировкаТекста.UTF8;

ЧтениеТекста = Новый ЧтениеТекста(ПутьКФайлу, кодировкаФайла);

данныеФайла = ЧтениеCSV.ИзЧтенияТекста(ЧтениеТекста, разделительВФайле);

ЧтениеТекста.Закрыть();

перваяСтрока = данныеФайла[0];

```

Использован шаблон: https://github.com/silverbulleters/oscript-actions-template