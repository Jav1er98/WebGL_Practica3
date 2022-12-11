## Third activity WebGL.
## Objective: After going through the tutorial on lighting and flat shadows, try to show a suitable color for the shadow by using a second special fragment shader for the shadows. To do this, compile a second shader program and render the flat shadow with this second program.

First of all, to carry out the following activity, we must define the variables that we need, which in this case assign names with the prefix "shadow" to distinguish them from our activity and we will create the new fragment shader.

![gif ejercicio 1](/images/Captura1.png)

![gif ejercicio 1](/images/Captura2.png)

We'll build the new program into the function named "Gameloop" using the new fragment shader, and then specify the locations in "Task  getAttributeLocations" and to finish with the rendering of the shadows, we use the uniforms and the attributes of the locators inside the "Task Draw".

![gif ejercicio 1](/images/Captura3.png)

![gif ejercicio 1](/images/Captura4.png)

The result is:

![gif ejercicio 1](/images/gif.gif)
