---
title: Bash cd
localeTitle: Bash cd
---
## Comando Bash: cd

**Cambie Directorio** a la ruta especificada, por ejemplo, `cd projects` .

Hay algunos argumentos realmente útiles para ayudar a esto:

*   `.` se refiere al directorio actual, como `./projects`
*   `..` se puede usar para subir una carpeta, usar `cd ..` , y se puede combinar para subir múltiples niveles `../../my_folder`
*   `/` es la raíz de su sistema para llegar a las carpetas principales, como el `system` , los `users` , etc.
*   `~` es el directorio de inicio, generalmente la ruta `/users/username` . Vuelva a las carpetas a las que se hace referencia en relación con esta ruta incluyéndola al comienzo de su ruta, por ejemplo `~/projects`.
*   `-` puede ser usado para desplazarse al directorio previo. Por ejemplo, si se encuentra en `/A`, y posteriormente realiza `cd` a `/B`, empleando `cd -` volverá de nuevo a `/A`.
* `~[number]` se realizará un cd a esa entrada desde la salida de `dirs` los directorios pueden ser enviados a la pila 'dirs' empleando `pushd` y `popd` respectivamante.
* Escribiendo únicamente `cd` le desplazará al directorio home, por lo tanto funciona exactamente igual que `cd ~`

### Más información:

*   [Wikipedia](https://en.wikipedia.org/wiki/Cd_(command))
