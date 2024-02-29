# smsParser
Класс для парсинга команд рукописного вода (например, команд в СМС сообщениях).
За командой может следовать определенное количество блоков данных, разделителем является пробел или несколько пробелов.

Структура команды: [command_name][spases...][data1][spases...][data2]... 

Пример команды: "Min2 10.5".
Результат парсинга не зависит от количества пробелов после команды и пробелов между блоками данных.
