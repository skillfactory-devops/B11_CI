## Проектная работа 11. Continuous Integration

* Установил Jenkins на сервере №1, подргрузил плагины [Github](https://plugins.jenkins.io/github/) и [Telegram](https://plugins.jenkins.io/telegram-notifications),
* Настроил сервер №2 в качестве Jenkins Agent'а,
* В настройках этого репозитория создал веб-хук, отсылающий POST-запрос к Jenkins при каждом пуше коммита,
* Убедился в его работоспособности на стороне Jenkins,
* Дописал в pipeline создание на стороннем агенте веб-сервера, отдающего статический контент сайта (nginx в контейнере),
* Убедился в работоспособности.

История создания билдов доступна [здесь](https://jenkins-master.padme.keenetic.pro/job/Build%20site/).
Тестовый веб-сайт — [здесь](https://jenkins-runner.padme.keenetic.pro/).
