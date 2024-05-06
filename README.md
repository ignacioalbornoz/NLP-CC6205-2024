# nlp_t1

### Creación del Entorno Conda

Para crear el entorno Conda desde 0 con python 3.10.12, ejecuta:

```bash
conda create -n nombre_del_entorno python=3.10.12
```

Para crear el entorno Conda a partir de un environment.yml, ejecuta:

```bash
conda env create -f environment.yml
```

Esta instrucción creará un entorno Conda basado en la configuración especificada en `environment.yml`.

### Actualización del Entorno Conda

Si necesitas actualizar las dependencias y guardar los cambios en `environment.yml`, ejecuta:

```bash
conda env export > environment.yml
```

### Activación del Entorno

Una vez creado el entorno, actívalo con:

```bash
conda activate nlp_t1
```


