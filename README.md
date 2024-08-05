Proyecto [Django]
Instrucciones para configurar el entorno de desarrollo
1. Clonar el repositorio
Primero, clona el repositorio en tu máquina local:

bash

git clone https://github.com/stivenga/proyecto_Django.git
2. Abrir el proyecto en Visual Studio Code
Abre la carpeta del proyecto en Visual Studio Code.

3. Configurar el entorno virtual
Abre una terminal PowerShell en Visual Studio Code y ejecuta el siguiente comando para crear un entorno virtual:

powershell
Copiar código
py -m venv venv
4. Activar el entorno virtual
Activa el entorno virtual con el siguiente comando:

powershell

.\venv\Scripts\activate.ps1
5. Instalar Django
Con el entorno virtual activado, instala Django con el siguiente comando:

powershell

pip install django
Nota: En algunos casos, puede que necesites actualizar pip. Si ves un mensaje sugiriendo usar el siguiente comando, es recomendable ejecutarlo:

powershell

python.exe -m pip install --upgrade pip
6. Ejecutar el servidor de desarrollo
Para ejecutar el servidor de desarrollo de Django, usa el siguiente comando:

powershell

py manage.py runserver
Esto iniciará el servidor y podrás acceder a la aplicación web en http://127.0.0.1:8000/.

