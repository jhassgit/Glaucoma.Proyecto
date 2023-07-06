# Glaucoma.Proyecto
## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update entity
5. Update configuration manager in src config
6. Update components
7. Update pipeline 
8. Update main.py
9. Update dvc.yaml



### PASOS:

Clonar repositorio git

```bash
https://github.com/jhassgit/Glaucoma.Proyecto.git
```
### PASO 1- CREAR EL ENTORNO

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### PASO 2- INSTALAR REQUERIMIENTOS
```bash
pip install -r requirements.txt
```


```bash

python app.py
```

Now,
```bash
open up you local host and port
```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag



