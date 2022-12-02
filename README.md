git-leaks-csv
=================

## Introducción
Instalar librerías de Python para el análisis de datos:
```
pip install -r requirements.txt
```
Se requieren los datos del repositorio [skale-manager](https://github.com/skalenetwork/skale-manager). La carpeta `skale` contiene el skale-manager.zip, el cual se debe descomprimir dentro de la carpeta antes de ejecutar el script.

## Ejecución
El archivo `leaks_to_csv.py` se encarga de generar un archivo CSV con los datos de los leaks encontrados en el repositorio. Consta de dos funciones:
- `extract()`: extrae los datos de los leaks encontrados en el repositorio a `commits.txt`.
- `git_leaks()`: Genera un archivo CSV con los datos de los `commits.txt` a `leaks.csv`.
