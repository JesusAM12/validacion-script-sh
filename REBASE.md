# Documentación del Rebase Interactivo

## Paso 1: Crear commits con mensajes poco claros

Inicialmente, se creo varios commits con mensajes poco claros. Los mensajes fueron:

1. **"Arreglos"**
2. **"Cambios"**
3. **"Actualización de cosas"**

Estos mensajes no eran claros ni descriptivos, por lo que decidimos realizar un rebase interactivo para mejorar el historial.

---

## Paso 2: Iniciar el rebase interactivo

Ejecutamos el comando git rebase -i HEAD~3 para iniciar el rebase interactivo, una vez ejecutado tuvimos
que cambiar la palabra pick por reword de las tres lineas de mensajes, una vez guardado una a una cambiamos los mensajes 
por otros mejores. Por ultimo, volvimos a usar el comando de rebase para fusionar el segundo y tercer commit en el primero.
Al ejecutarlo, se cambio la palabra pick por squash de la segunda y tercera linea que son las que queriamos fusionar. Una vez
guardado tendriamos que borrar todas las lineas y escribir solo una con los cambios que queremos, para finalizar, lo guardamos
y lo actualizamos para el repositorio de github.
