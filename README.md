# Caso ARMUR

## Configurar entorno de desarrollo

1. Crear y activar *virtual environment*
   
  **Windows:**

  ```{bash}
  python -m venv venv
  venv\Scripts\activate.ps1
  ```

  **OS X:**

  ```{bash}
  python3 -m venv venv
  source venv/bin/activate
  ```

2. Instalar requerimientos

  **Windows:**

  ```{bash}
  python -m pip install -r environment/requirements.txt
  ```

  **OS X:**

  ```{bash}
  pip install -r environment/requirements.txt
  ```
