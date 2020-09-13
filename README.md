# Curso03TrabajoSemana03
Proyecto de la tercer semana del curso "Desarrollo de aplicaciones con android". Capturas de la aplicación en la carpeta "Capturas".

Para el proyecto se crearon cinco actividades; la primera ("Mascota.java") incluye un constructor de mascotas, permite ingresar la imagen de las mascota, la imagen del botón para dar like, el nombre de la mascota y el rating inicial de la mascota; también incluye un constructor de mascotas gustadas, es similar al primer constructor, pero pide el rating inicial.
Las segunda ("MainActivity.java") y la tercera (MascotaAdaptador.java) actividad se encargan de mostrar en la primera pantalla de la aplicación, los datos ingresados al constructor en forma de CardViews dentro de un RecyclerView, estos datos son varias mascotas para rankear; además en la segunda actividad se vinculan un menu (menus.xml) y un ToolBar (action_bar.xml) a la primer pantalla de la aplicación.
Las cuarta ("MascotasGustadas.java") y la quinta (MascotasGustadasAdaptador.java) actividad se encargan de mostrar en la segunda pantalla de la aplicación, los datos ingresados al constructor en forma de CardViews dentro de un RecyclerView, estos datos son cinco mascotas de las disponibles para rankear (en un futuro las cinco mascotas con mas likes); además en la cuarta actividad se vinculan un menu (menu_secundario.xml) y un ToolBar (action_bar_back.xml) a la segunda pantalla de la aplicación.

Se hace un vinculo de padre-hijo entre "MainActivity" y "MascotasGustadas" para garantizar el flujo entre actividades de manera solicitada.

En la primer pantalla de la aplicacion se puede dar like a la mascota al tocar el corazon con una huella (blanco y negro), los likes se ven reflejados en el número al lado del corazon con una huella (rojo); también se puede ir a una segunda pantalla que muestra cinco de las mascotas disponibles para rankear, esto al tocar la estrella roja con un cinco que se encuentra en la ToolBar
En la segunda pantalla se observan cinco mascotas, y es posible volver a nuestra actividad padre ("MainActivity.java") al tocar el botón de atras que se encuentra en la Toolbar.
