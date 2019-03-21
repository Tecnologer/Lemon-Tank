# Lemon-Tank

Juego de tanques 

# Depencias

- Python 2.x
- [`pip`][1] para instalar pygame: `pip install pygame`

# Debug
- Usando Visual Studio Code
  
  Requiere usarse Python 2.x, en caso de tener instalado ambas versiones, en vscode se puede especificar con que version de python se desea hacer debug.

  Solo basta con agregar `pythonPath` al archivo `launch.json` en la configuracion que se este usando.

  Ejemplo:
  ```json
    {
        "name": "Python: Current File (Integrated Terminal)",
        "type": "python",
        "request": "launch",
        "program": "${file}",
        "console": "integratedTerminal",
        "pythonPath": "/usr/bin/python"
    }
    ```

# Como iniciar
- Instala [Python 2][2]
- Instala [pip][1]
- Instala [pygame][3]
  
  `pip install pygame`

- Clona el repositorio
  
  `git clone git@github.com:hug58/Lemon-Tank.git`
- Abre la carpeta del codigo

  `cd Lemon-Tank`
- Ejecuta el script
 
  `python main.py`

[1]: https://tecnonucleous.com/2018/01/28/como-instalar-pip-para-python-en-windows-mac-y-linux/
[2]: https://www.python.org/download/releases/2.7/
[3]: https://www.pygame.org/