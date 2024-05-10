Django AI
Wymagania:

python 3.10 (python --version)
Django==4.0
Pillow
numpy
pandas
tensorflow==2.8.0
tensorflow-hub
protobuf==3.20
Ustawienie środowiska
python -m venv .venv
Aktywacja zmiennej środowiskowej (Windows)
Założenie - pracuje na CMDER
.venv/Scripts/activate
Założenie - pracuje na gitbash
source .venv\Scripts\activate
lub
source .venv/Scripts/activate
Aktywacja zmiennej środowiskowej (Mac/Unix)
Założenie - pracuje na gitbash
source .venv/bin/activate
Jak jest aktywna wirtualna zmienna środowiskowa to przechodzimy do instalacji (czyli w terminalu koło kursora jest w nawiasie .venv)

Instalacja
pip install -r requirements.txt
Uruchomienie
python manage.py runserver
