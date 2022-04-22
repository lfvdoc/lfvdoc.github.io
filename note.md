## Ruta absoluta
Tuvimos problemas con la ruta abusoluta y eso rompia la pagina sin mostrar las paginas, estilos, imagenes y problemas para poder
ingresar a las rutas, eso lo solucionamos con en _config.yml cambiando la base URL que no coincidia con el de github pages.
(no modifiquemos URL: porque tmbn nos generó problemas de ruptura de enlaces) 
pueda que dejar la base url en "" (sin ruta) nos ayude con un dominio propio, pero con el subdominio de ghp se rompe.

#baseurl: '/vardoc'

baseurl: '/vardoc'

-----

eso ayudó a solucionar el problema.

-----

## Imagen Rota en develop
Otro problemita que teniamos era que teniamos la segunda **imagen** despues de **latest** rota, por lo que decidimos modficiar un codigo en:
la linea 57 de index.html

## Deploy en forestry
1 Subimos nuestro proyecto a github y gh pages (generamos el link y la rama master)
2 lo vinculamos con forestry desde el dashboard donde dice **Add Site**
3 Se apertura el **setup process** 1, 2 y 3 le damos a **mark as done**, es probable que nos vaya a dar problemas el 4to paso con esta plantilla pero tmbn lo omitiremos.
4 Cuando intentemos crear un nuevo **post** nos pedira crear una plantilla > le damos a crear nuevo a partir de > elegimos algun post anterior.  
5 listo con esto solo nos queda revisar si funciona correctamente. 

