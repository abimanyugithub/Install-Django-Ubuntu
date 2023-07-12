# INSTAL DJANGO DI UBUNTU
1. Instal pip python3 ```sudo apt install python3-pip```
2. Download https://www.djangoproject.com/download/ dan extract (ex.Django-4.2.2.tar.gz)
3. Instal Django ```sudo python3 setup.py install```

   Untuk cek versi Django, ketik ```python3``` masuk **Python console**, ketik ```import django``` tekan enter, ketik ```django.VERSION```

4. Memulai membuat folder program ```mkdir django-test```
5. Dalam folder tersebut, memulai membuat folder project ```django-admin startproject inventory .```
6. Jalankan server django ```python3 manage.py runserver``` atau dengan custom port ```python3 manage.py runserver 8081```
7. Ketik ```http://127.0.0.1:8000/``` atau dengan custom port ```http://127.0.0.1:8081/``` di browser

   <ins>Note:</ins>
- Untuk testing dan instal Django di Virtual Environment cek di https://github.com/abimanyugithub/Install-Django-With-Virtual-Environment
- Untuk koneksi Django dengan MySQL https://github.com/abimanyugithub/Connect-MySQL-To-Django
