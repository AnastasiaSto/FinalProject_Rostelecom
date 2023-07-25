Итоговый тестовый проект "Ростелеком ID"_QAP-114

Автоматизированное тестирование интерфейса авторизации в личном кабинете (Заказчик: Ростелеком Информационные Технологии (https://b2c.passport.rt.ru/)
____

+ Тест-кейсы доступны по ссылке: https://docs.google.com/spreadsheets/d/1n23QmCIKy4pvF2UlO3oGzENhg-CsyFs0/edit?usp=sharing&ouid=104766159124306016011&rtpof=true&sd=true

+ Баг-репорт доступен по ссылке: https://docs.google.com/spreadsheets/d/1LA5V29MjZW232O25zwHRchtqF3JHFLET/edit?usp=sharing&ouid=104766159124306016011&rtpof=true&sd=true


1. В папке pages в файле base_page.py находится конструктор webdriver и общие для всех тестируемых страниц методы.

2. В папке pages в файлах auth_page.py, change_pass_page.py, reg_page.py описаны методы проверок: 
- файл auth_page.py содержит методы проверок формы авторизации; 
- файл change_pass_page.py содержит методы проверок формы восстановления пароля; 
- файл reg_page.py содержит методы проверок формы регистрации.

3. В папке tests в файлах test_auth_page.py, test_change_pass_page.py, test_reg_page.py находятся тесты. Все тесты помечены номером, совпадающим с номером тест-кейса в файле: https://docs.google.com/spreadsheets/d/1n23QmCIKy4pvF2UlO3oGzENhg-CsyFs0/edit?usp=sharing&ouid=104766159124306016011&rtpof=true&sd=true

4. В папке pages в файле "locators.py находятся все локаторы.

5. В проекте в файле conftest.py написана фикстура с функцией открытия и закрытия браузера. 

6. В проекте в файле settings.py указаны методы и переменные для параметризации тестов.

7. В проекте в файле pytest.ini зарегистрированы метки маркировок тестов.

8. В проекте в файле requirements.py описаны используемые библиотеки.
