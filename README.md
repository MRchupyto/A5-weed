LA CARPETA LLAMADA "IMAG" UNA VEZ DESCARGADA , RENOMBRALA CON EL NOMBRE "img" , AL SUBIRLA NO ME DEJABA PONER IMG , DA ERR
TODAS LAS RUTAS SERAN REFERIDAS A LA CARPETA IMG NO A IMAG 
LA CARPETA IMAG DEBERA SER NOMBRADA IMG

[REVISA QUE LOS ENLACES A FOTOGRAFIAS DENTRO DE EL "INDEX HTMLw] ESTEN REFERIDOS A IMG

CUALQUIER DUDA YA SABES QUE ESTOY A TU LADO , NO ME SEAS CAPULLO "GRACIAS"
..................................................................................................................................

- Primeros Pasos -

1. Crea la hoja de estilos y importa esta fuente : (https://fonts.googleapis.com/css2?family=Rubik:wght@300&display=swap)
2. Crea un id en la hoja estilos "body" con un margen de (0) y pon al uso esta fuente :
```
{font-family: 'Quicksand', sans-serif;}
```
4. Crea la regla "#header" con una altura de 100vh y pon la imagen {wp2559457.jpg} de fondo
5. Añade en el id #header : la posicion de la imagen en el centro y que cubra la hoja .
6. Crea una regla llamada "header h1" y añade los siguientes atributos : 

    - letra blanca
    - margen 0
    - un padding de 0 y 20
    - el tamaño de la fuente a 50
    - y un degradado linear de verdes a tu gusto 

6. Debajo de "header h1" pega esta linea : {@media only screen and (max-width: 600px}
7. Dentro e este añade un padding de 0 y 1% tambien cambia el tamaño de la letra a 40px
8. Añade una clase llamada "#main" y dentro añade un padding derecho y izquierdo de 1%
9. Añade una clase llamada "#main p" y dentro modifica el tamaño de la letra a 35px
10. Añade una clase llamada "#main h1" modifica la letra a 35px
11. Añade un slelector de  "h2" y dentro de este pon la letra a 25 px
12. Pega este ultimo trozo de mediaqueries debajo :
```css
........................................................................
@media only screen and (max-width: 600px) {                            |
    #main {                                                            |
        padding: 0 1%;                                                 |
        font-size: 40px;                                               |
    }                                                                  |
    #main p {                                                          |
    font-size: 15px;                                                   |
    }                                                                  |
                                                                       | 
    #main h1 {                                                         | 
    font-size: 35px;                                                   | 
    }                                                                  | 
}                                                                      | 
iframe{                                                                | 
    width: 100%;                                                       | 
    height: 500%;                                                      | 
}                                                                      | 
                                                                       |  
.font2 {                                                               | 
    font-family: 'BhuTuka Expanded One', cursive;                      | 
}                                                                      | 
                                                                       | 
.imagenes {                                                            |
    width: 100%;                                                       |
}                                                                      |
........................................................................
```
13. crea una regla llamada "#fother" y añade lo siguiente  : 
   
    - alineea el texto en el frente
    - agrega un color blanquecino a tu gusto
    - establece un fondo negro
    - pon un padding "top" de 15px
    - pon un padding "bottom" de 15px

14. crea un id llamado "flex" que contenga :

-  display: flex;
-  align-items: center;
-  justify-content: center;

15. REVISA QUE LA HOJA DE ESTILOS ESTE CORRECTAMENTE ENLAZADA CON LA HOJA "INDEX.HTML"

                                                                        


                                                                        
