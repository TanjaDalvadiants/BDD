# BDD
[![Build status](https://ci.appveyor.com/api/projects/status/uufd8w9h0rh2bkba?svg=true)](https://ci.appveyor.com/project/TanjaDalvadiants/bdd)

##  Page Object's
#### Вам необходимо добить тестирование функции перевода с карты на карту. Разработчики пока реализовали возможность перевода только между своими картами, но уже хотят, чтобы вы всё протестировали.

* Для этого они не поленились и захардкодили вам целого одного пользователя:

* login: 'vasya'
* password: 'qwerty123'
* verification code (hardcoded): '12345'
* cards:
    * first:
        * number: '5559 0000 0000 0001'
        * balance: 10 000 RUB
    * second:
        * number: '5559 0000 0000 0002'
        * balance: 10 000 RUB
 После логина, который уже мы сделали на лекции, вы получите список карт:

![cards](https://github.com/TanjaDalvadiants/BDD/assets/121951420/049b4d68-8a4e-4e4b-a67c-e5f00b2ff1ce)
Нажав на кнопку «Пополнить», вы перейдёте на страницу перевода средств

##### При успешном переводе вы вернётесь назад на страницу со списком карт.

* Это ключевой кейс, который нужно протестировать.

###### Нужно, чтобы вы через Page Object's добавили доменные методы:

* перевода с определённой карты на другую карту энной суммы,
* проверки баланса по карте со страницы списка карт.


