# Tutorial

Haremos una APP que desee un Feliz Cumpleaños paso por paso, partiendo del codigo base aportado por Android Studio , 
haciendo los pertinentes cambios y añadiendo lo que sea necesario.

Este sería el codigo base aportado por Android Studio

![img.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg.png)

Para Empezar cambiaremos el nombre de fun GreetingPreview por una más acorde a nuestro proyecto en este caso por BirthdayCardPreview

pasara a :

![img_3.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_3.png)

Continuamos en incidir el apartado Greeting para así cambiar el nombre Android por el de el usuario, en mi caso Jorge.

![img_5.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_5.png)

Para Saber si los cambios se han realizado dirijase a la esquina superior derecha de su programa y clickee en el apartado Design
para ver de forma grafica los cambios.

![img_1.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_1.png)



![img_4.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_4.png)

# Añadir Elementos

Como primer paso eliminariamos el siguiente codigo

![img_6.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_6.png)

Tambien los Greeting ya que nos dan error 

![img_7.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_7.png)
![img_8.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_8.png)

Y nos quedaría así el codigo depurado 

![img_11.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_11.png)


Ahora añadimos la funcion GreetingText que nos muestra texto en la IU, *no nos olvidemos del @composable*

![img_9.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_9.png)

Y la llamamos en la funcion JetpackCompose_RecTheme {

![img_12.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_12.png)

para ver el resultado final iriamos de nuevo a Design

![img_1.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_1.png)

![img_10.png](src%2Fmain%2Fjava%2Fcom%2Fexample%2Fjetpackcompose_rec%2Fui%2Ftheme%2FImagenes%2Fimg_10.png)