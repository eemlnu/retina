# Retina

## Antes de ejecutar el codigo:

Es necesario contar con credenciales y luego reemplazar en vez de las Xs
En el siguiente link indica el procedimiento:
https://github.com/Kaggle/kaggle-api#api-credentials


### Importar el dataset a la notebook

import os

os.environ['KAGGLE_USERNAME'] = "XXXX"
os.environ['KAGGLE_KEY'] = "XXXXXXXXX"

!kaggle datasets download -d andrewmvd/ocular-disease-recognition-odir5k

### Finalmente, descomprimir el zip

!unzip ocular-disease-recognition-odir5k.zip
