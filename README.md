git-leaks-csv
=================

## Introducción
Instalar librerías de Python para el análisis de datos:
```
pip install -r requirements.txt
```
Se requieren los datos del repositorio [skale-manager](https://github.com/skalenetwork/skale-manager), los cuales ya se encuentran en la carpeta `skale` del repositorio.

## Ejecución
El archivo `leaks_to_csv.py` se encarga de generar un archivo CSV con los datos de los leaks encontrados en el repositorio. Consta de dos funciones:
- `extract()`: extrae los datos de los leaks encontrados en el repositorio a `commits.txt`.
- `get_leaks()`: Genera un archivo CSV con los datos de los `commits.txt` a `leaks.csv`.
