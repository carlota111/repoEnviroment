  GNU nano 7.2                                                                              README.md *

# repoEnviroment

Este repositorio contiene un entorno configurado utilizando un archivo YAML, el cual puedes clonar y ejecutar fácilmente siguiendo las instrucciones a continuación.

## Requisitos

- [Conda](https://docs.conda.io/en/latest/miniconda.html) instalado en tu sistema.

## Instrucciones para clonar el repositorio

1. Clona el repositorio desde GitHub usando el siguiente comando:

    ```bash
    git clone git@github.com:carlota111/repoEnviroment.git
    ```

##Intrucciones para correr el código

1. Activar el enviroment:
```bash
conda activate envPrueba
```
```bash
python script_sample.py
```



## Crear un nuevo entorno con el archivo YAML

Para crear un entorno nuevo basado en el archivo `config.yml`, ejecuta el siguiente comando:

```bash
conda env create --file config.yml
```


