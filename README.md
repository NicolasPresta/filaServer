# concepto

Para pruebas de concepto varias... 


### Instalación

```
npm install
npm install -g grunt-cli
```

### Ejecutar

```
1° - Cambiar la URL donde corre el servidor en el método: getServerURL, de Angular.
2° - npm start
3° - Abrir CAJAS: desde el explorador http://192.168.0.102:3001/#/caja
4° - Abrir CLIENTES: desde el explorador http://192.168.0.102:3001/#/cliente
```

### Levantar cliente con grunt

```
1° - asegurarse de tener npm install -g grunt-cli
2° - npm run client: esto inicia un servidor Grunt sirviendo los archivos de /Cliente
3° - desde el entorno local se pueden abrir clientes y cajas, desde el explorador:  http://localhost:9000
```


### Ejecutar en otro puerto *(Ej: 3001)*

```
npm run dist
node dist/src 3001
```


### Conectar clientes:

```
Abrir la página web Cliente/cliente.html

abrir varias paginas para obtener varios clientes
pueden ser cajas o clientes.

```


