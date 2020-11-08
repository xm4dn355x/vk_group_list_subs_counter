# sn_subs_and_views_counter
Парсер вконтакте по списку групп со сбором количества подписчиков.

## Подготовка данных к обработке
1. Проверьте данные в таблице "Информационная карта интернета ЯНАО" в airtable
1. Экспортируйте таблицу в CSV
1. Перенесите данный csv-файл в папку **/data/** и назовите его **information_map_*текущая дата*.csv**
1. В скрипте **main.py** измените имя глобальной переменной **CSV_PATH** на новый путь к CSV файлу
1. Эксортируйте из Google Docs документ **Telegram дайджест** в xlsx и перенесите его в папку **/data/**
1. Переименуйте его в **tg_digest_*текущая_дата*.xlsx**
1. Уберите лишние строки в таблице, чтоб остались голые данные без заголовков и разделителей
1. В скрипте **main.py** измените имя глобальной переменной **XLSX_PATH** на новый путь к xlsx файлу
1. В скрипте **main.py** измените имя глобальной переменной **XLSX_ROWS_COUNT** на количество строк в новой таблице xlsx
1. Запустите скрипт **main.py**. Вы получите в результате файл **"Информационная карта интернета ЯНАО.xls"**
1. ?????
1. PROFIT!!!
