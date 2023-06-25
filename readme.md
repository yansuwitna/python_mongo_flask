<h1>API Mongo Menggunakan Flask di Python</h1>

### Kebutuhan Aplikasi 
1. Python 
2. Mongo Server 
3. Flask 
4. Mongo Compas (Client Mongo Server)


### Instalasi Python
Link Download https://www.python.org/downloads/windows/

Instalasi di Linux : 
```
sudo apt-get install -y python3.8 
```

### Instalasi Mongo Server 
Link Download 

Instalasi Di Linux
```
sudo apt-get install gnupg
```

Download Key 
```
curl -fsSL https://pgp.mongodb.com/server-6.0.asc | \
   sudo gpg -o /usr/share/keyrings/mongodb-server-6.0.gpg \
   --dearmor
```

Update 
```
sudo apt-get update
```

Instalasi 
```
sudo apt-get install -y mongodb-org
```

Menjalankan 
```
sudo systemctl start mongod
```

Melihat Status Mongo DB
```
sudo systemctl status mongod
```

Menghentikan Mongo DB
```
sudo systemctl stop mongod
```

### Instalasi 
