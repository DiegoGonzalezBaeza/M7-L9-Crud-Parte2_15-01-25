# M7-L9-Crud-Parte2_15-01-25
Proyecto educativo


```bash
pip install django djangorestframework drf-spectacular psycopg2

pip freeze > requirements.txt
```

PROBLEMAS CON serialazer.py 

```txt
Import "rest_framework" could not be resolvedPylancereportMissingImports
```

```py
from rest_framework import serializers
```

1- Control+ shift + p.
2-type 'Python: Select Interpreter' and select the same.
3-choose your virtual env from the list if it is not listed please choose Enter Interpreter path'
4-path of your virtual env python.exe file.

para saber el path de python:

```bash
where python
```
respuesta:
```bash
(venv) C:\Users\diego\OneDrive\Documents\FullStack Python\Modulo 7\Sesion 9.1\M7-L9-Crud-Parte2_15-01-25>where python
C:\Users\diego\OneDrive\Documents\FullStack Python\Modulo 7\Sesion 9.1\M7-L9-Crud-Parte2_15-01-25\venv\Scripts\python.exe
```

De esta manera se obliga que el interprete sea con el entorno virtual.

se arregla el problema.