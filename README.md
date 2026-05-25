# exploding_Kittens_client
cliente para exploding_KIttens
PASO A PASO PARA EJECUTAR CLIENTE(LINUX):

1. Verificar Python (casi siempre ya viene instalado):
python3 --version

2. Instalar pip si no lo tiene:
sudo apt install python3-pip python3-venv -y

3. Extraer el zip:
unzip cliente_ek.zip -d cliente_ek
cd cliente_ek

4. Crear entorno virtual e instalar websockets:
python3 -m venv venv
venv/bin/pip install websockets

5. Correr el cliente:
venv/bin/python3 client_web.py 34.194.27.67 tu_nombre

6. Abrir la URL que aparece en el navegador, algo como:
http://localhost:8080/web/?name=tu_nombre
