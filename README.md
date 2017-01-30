Скрипт выбирает случайные 20 онлайн-курсов с сайта https://www.coursera.org/, и собирает информацию о них. Собранная информация состоит из следующих пунктов: Название курса; языки, на которых этот курс преподается; дата начала регистрации на курс; длительность курса в неделях и средний рейтинг(если он определен).
Собранная информация выгружается в xlsx-файл, который генерируется автоматически в той же папке, что и этот скрипт.

<hr>

# ЗАПУСК.

Запуск из командной строки:<br>
`python3.5 coursera.py`

<hr>

# ТРЕБОВАНИЯ

Python3.5
Requests (<a href=http://docs.python-requests.org/en/master/>документация</a>)<br>
BeautifulSoup (<a href=https://pypi.python.org/pypi/beautifulsoup4>документация</a>)<br>
OpenPyXL (<a href=https://openpyxl.readthedocs.io/en/default/>документация</a>)<br>
lxml (<a href=http://lxml.de/>документация</a>)
