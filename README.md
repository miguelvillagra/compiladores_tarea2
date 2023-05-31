# compiladores_tarea2
Repositorio para tarea2 de la materia compiladores.
Integrante: Miguel Villagra.
contacto: miguel.villagra@fpuna.edu.py

Version de python: Python 3.10.11

Se requiere de la libreria ply, instalarlo con el siguiente comando.
```
pip install ply
```

Este script implementa un analizador sintáctico descendente recursivo utilizando la biblioteca ply. 
Define las reglas de la gramática JSON simplificada y utiliza la estrategia de manejo de errores Panic Mode 
para sincronizar y continuar el análisis en caso de encontrar errores.

El JSON a probar se encuenta en el archivo: 'ejemplo.json'

Luego de instalar las librerias necesarias, ejecutar el programa con el siguiente comando:
```
python main.py
```
Se adjuntan la gramatica correjida eliminado la recursión por izquierda y factoreo.

![1](https://github.com/miguelvillagra/compiladores_tarea2/assets/88117555/d2982a8c-0dd7-4ca9-aeed-3365f2097435)
![2](https://github.com/miguelvillagra/compiladores_tarea2/assets/88117555/6603185a-6785-4e37-afbb-fbce14ff6819)
