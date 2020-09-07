# Лабораторная работа на тему "Безопасность в сети Интернет. Фишинг."

Для запуска лабораторной работы необходимо склонировать этот репозиторий на свой компьютер.<br>Убедитесь, что у Вас установлен python v3.6 и выше:
* Для Linux
```
python3 --version
```
Далее перейти в папку склонированной лабораторной работы, создать и запустить в ней venv (виртуальное окружение python):
* Для Linux
```
sudo python3 -m venv myenv
source myenv/bin/activate
```
После устанавливаем все необходимые для python пакеты:
```
pip install -r requirements.txt
```
Запускаем сервер Django:
```
python manage.py runserver
```
Сервер Django по стандарту запускается по адресу http://127.0.0.1:8000/.
