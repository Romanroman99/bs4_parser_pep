[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/)
# Проект парсинга pep
## Описание
Парсер документации python
### Функционал
- latest_versions
Функция выводящая список версий и ссылки на документацию python
```
python main.py latest-versions [аргументы]
```
- whats-new   
Функция выводящий спсок изменений в python.
```
python main.py whats-new [аргументы]
```
- download   
Функция скачивающая zip архив с документацией python.
```
python main.py download [аргументы]
```
- pep
Функция выводящая список статусов документов pep
и количество документов в каждом статусе. 
```
python main.py pep [аргументы]
```
Получить список доступных аргуметов:
```
python main.py -h
```