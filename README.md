# Description
Скрипт позволяет собрать необходимую информацию об угрозах безопасности информации (УБИ) с [Банка данных УБИ ФСТЭК](https://bdu.fstec.ru), а именно:
* Номер УБИ
* Описание угрозы
* Источники угрозы
* Объект воздействия
* Последствия реализации угрозы

# Install
Для работы скрипта установить пакеты: `python-docx, beautifulsoup4, requests`, командой:
```bash
pip3 install -r requirements.txt
```

# Usage
```bash
python3 parse_bdu.py
```

# Examples
### Скрипт создает файл `Угрозы безопасности информации.docx` и выводит информацию в него в виде таблицы:
![image](https://user-images.githubusercontent.com/49790977/191255740-108d82b4-5b4c-43bb-8351-40eb8efba4a7.png)

### Также скрипт выводит информацию в консоль:
![image](https://user-images.githubusercontent.com/49790977/191255886-7cee8bb0-4b91-4660-8c02-008cb99d29c6.png)
