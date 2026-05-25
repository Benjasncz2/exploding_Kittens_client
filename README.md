# exploding_kittens_client
Cliente para Exploding Kittens

## Paso a paso para ejecutar (Linux)

### 1. Verificar Python
```bash
python3 --version
```

### 2. Instalar pip si no lo tienes
```bash
sudo apt install python3-pip python3-venv -y
```

### 3. Extraer el zip
```bash
unzip cliente__ek.zip -d cliente_ek
cd cliente_ek
```

### 4. Crear entorno virtual e instalar websockets
```bash
python3 -m venv venv
venv/bin/pip install websockets
```

### 5. Correr el cliente
```bash
venv/bin/python3 client_web.py 34.194.27.67 tu_nombre
```

### 6. Abrir en el navegador
La URL que aparece en la terminal, algo como:
```
http://localhost:8080/web/?name=tu_nombre
```
