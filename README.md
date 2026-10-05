# apuntes-p1-moya
Apuntes del Parcial 1 de Big Data Moya

# ENTORNO VIRTUAL EN PYTHON
En python un enotnro virtual es aislamiento del intérprete y de las dependencias de un proyecto.
Se aisla la versión de Pip, librerias instaladas y scripts de consola asociadas al entorno.

**Crear:**
`python -m venv .venv`
donde `.venv` es el nombre de la carpeta y el punto es para ocultarlo.

**Activar el entorno:** 
`.venv/Scripts/Activate.ps1`

**Instalar paquetes:**
`pip install flask numpy pandas`

**ver paquetes:**
`pip list`

**Desactivar:**
`deactivate`

# Reproducibilidad: Requirements.txt
Para generarlo:
`pip freeze > requirements.txt`

**instalar desde archivo:**
`pip install -r requirements.txt`

---

# Repositorios de GitHub:
**Clonar Repositorio:**
`git clone URL_DE_REPOSITORIO`

**Entrar:**
`cd nombre-del-repositorio`

Y crear VENV.

**Inicializar Git:**
`git init`

# Uso de Git
Para realizar commits:
`git add.`
`git commit -m "Mensaje de los cambios que se han realizado"`

Para aplicar cambios a github:
`git push`

**Conectar repositorio con proyecto local:**
```
git remote add origin URL_DE_TU_REPOSITORIO
git branch -M main
git push -u origin main
```

# Datos del GitIgnore Minimos:
```
.venv/
__pycache__/
.ipynb_checkpoints/
.DS_Store
```
