# Taller Practico de Analisis de Datos con Pandas

Proyecto de analisis de ventas de una libreria cultural usando Python, Pandas, NumPy, Matplotlib y Seaborn.

## Crear el entorno en Windows

Abre PowerShell en la carpeta del proyecto y ejecuta:

```powershell
py -m venv datos
.\datos\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requierements.txt
pip install jupyter ipykernel
python -m ipykernel install --user --name taller-pandas --display-name "Python (Taller Pandas)"
```

Si PowerShell bloquea la activacion, ejecuta una vez:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Luego vuelve a ejecutar:

```powershell
.\datos\Scripts\Activate.ps1
```

## Abrir y ejecutar el notebook

1. Abre `AnalisisDatos.ipynb` en VS Code.
2. Selecciona el kernel `Python (Taller Pandas)`.
3. Ejecuta las celdas del notebook en orden.

Tambien puedes iniciar Jupyter desde PowerShell:

```powershell
jupyter notebook
```

## Desactivar el entorno

Cuando termines, ejecuta:

```powershell
deactivate
```

La carpeta `datos/` es un entorno local y esta excluida mediante `.gitignore`; no debe subirse al repositorio.