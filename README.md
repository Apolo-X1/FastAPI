# FastAPI-Python

1. Crea un entorno virtual:
   - Abre el símbolo del sistema (CMD) en Windows.
   - Navega hasta la carpeta del proyecto.
   - Crea el entorno virtual:
   ```
   python -m venv test-env
   ```
   - Activa el entorno virtual:
   ```
   test-env\\Scripts\\activate.bat
   ```

2. Instala las bibliotecas necesarias:
     ```
     pip install fastapi
     ```
     ```
     pip install uvicorn
     ```


## Iniciar el servidor

- Navega hasta la carpeta del proyecto utilizando el símbolo del sistema.
- Ejecuta el siguiente comando:
```
uvicorn main:app --reload
```


Al seguir estos pasos, configurarás un entorno virtual, instalarás las bibliotecas necesarias (FastAPI y uvicorn) y comenzarás el servidor utilizando uvicorn.
