# Aprendiendo Git & github

## Configurar git

1. Ingresar tu nombre
```
$ git config --global user.name "John Doe"
```
2. Configurar tu email 
```
$ git config --global user.email johndoe@example.com
```

## Como puedo verificar la configuracion de mis credenciales?

Usa este comando
```
git config --list
```

### Muchas letras en la consola? Quieres limpiar la consola de los comandos anteriores?

```
clear
```

### Como puedo empezar?

1. Crea tu repositorio con el comando 
```
git init // Este comando crea un repositorio Git vacío.
```

2. Luego verifica los cambios realizados en tu repo con el comando.

```
git status
```
3. Luego debes llevar esos cambios a la zona *staging*, con el comando :
```
git add . // si colocas el punto despues de la palabra add "." le estas confirmando a git que deseas consolidar/guardar/confirmar todos los cambios, que de antemano visualizaste en el 
        // comando git status

git add ./ruta/del/archivo.js // Tambien puedes indicarle a git especificamente que archivo (en donde hay cambios) quieres confirmar.
```

# Que es el staging?
El Staging es el lugar de preparación en la RAM antes de enviar los cambios de nuestro archivo en repositorio. El repositorio es el lugar donde se almacenan los cambios de nuestro archivo.

### Que es una rama?
