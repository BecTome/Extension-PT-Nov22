# Importaciones en python

## Configurar el PYTHONPATH
Si intentamos importar un módulo que no se encuentra en el directorio actual, Python lo buscará en los directorios que se encuentran en la variable de entorno PYTHONPATH.

```Powershell
$env:PYTHONPATH = "path\to\my\package"
```

## Añadir temporalmente con sys
Si queremos añadir un directorio temporalmente, podemos hacerlo con el módulo sys.

```Python
import sys
sys.path.append("path\to\my\package")
```