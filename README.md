Пакет Python3 для сохранения/извлечения данных по ключу.

### Как это работает

Данные в неизменном виде записываются в текстовый файл общим потоком. Ключи, идентифицирующие эти данные, в виде хешей сохраняются в бинарном файле. Причем при добавлении каждого нового хеша производится сортировка файла, чтобы в дальнейшем можно было использовать бинарный поиск. Для каждого типа хранимых данных в папке скрипта создается своя директория.

### Примеры использования

**from jbird.Jbird import ***



