# Overlord

## Installation (**Visual Studio Code**)
1) Open [pyproject.toml](./pyproject.toml) and click on **Create Environment...**
![Create Environment...](./images/create_environment.png?raw=true "Create Virtual Environment")

2) Select **Venv**
![Select Venv](./images/venv.png?raw=true "Create .venv virtual environment")

3) Select desired python intepreter for virtual environment
![Select Python Interpreter](./images/py_version.png?raw=true "Select Python Interpreter")

4) Select **dev** and **doc** to install dependencies used for development and writing documentation 
![Select Optional Dependencies](./images/optional_dependencies.png?raw=true "Additional Dependencies are used for Development")

5) VS Code will create virtual environment and install dependencies
![VS Code Log](./images/vs_code_log.png?raw=true "Logs will show additional information")

**NOTE:** Overlord package is now installed as editable package. Any local changes will be immediately available when virtual environment is activated.