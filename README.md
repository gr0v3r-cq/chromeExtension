# chromeExtension

* Google ofrece un conjunto de información para quienes deseen desarrollar extensiones para su navegador. Esta información se puede encontrar [aquí](https://developer.chrome.com/extensions/devguide)

* Como se indica, el archivo manifest.json tiene la información sobre la extensión, como por ejemplo el nombre de la extensión, la versión, los archivos que se van a cargar, etc.

```
* name: Nombre de la extensión
* version: Versión de la extensión
* description: Pequeña descripción de la extensión
* browser_action: carga el icono de la extensión a través de parámetros default_icon y también la ventana emergente que se crea en el archivo popup.html
* permissions: Hasta este punto hemos creado los permisos para activeTab – se puede ver [aquí] (https://developer.chrome.com/extensions/declare_permissions) otros permisos
```

#How to load the extension in Chrome

Después de preparar el código anterior, en el archivo popup.html y manifest.json, junte también, en una sola carpeta el icono icon.png.

Entonces deben ir a escribir barra de direcciones y escribir chrome://extensions/ y activar el modo de desarrollador como se muestra en la figura

![chrome://extensions/](https://adictec.com/wp-content/uploads/2018/01/modo-de-desarrollador-Chrome.png)

Luego seleccionar “Cargar extensión descomprimida…” e indicar el directorio que contiene su extensión.
![](https://adictec.com/wp-content/uploads/2018/01/Cargar-extensi%C3%B3n-descomprimida-Chrome.png)

Si todo está bien, la extensión se debe cargar como se muestra en la imagen:

![](https://adictec.com/wp-content/uploads/2018/01/Extensi%C3%B3n-para-Chrome-Hola-Adictec.png)

Junto a las otras extensiones deberá ser presentada la extensión que hemos creado. Intente pulsar el botón para ver si el texto que definimos aparece.

![](https://adictec.com/wp-content/uploads/2018/01/Extensi%C3%B3n-creada-para-Chrome.png)

informacion obtenoda de [ADICTEC -> Aprende cómo crear una extensión para Chrome](https://adictec.com/como-crear-extension-para-chrome/?fbclid=IwAR2ZuNTOPXuOdPiA0ABvHPlLZFOa2dWsE1ToQd4K_zWNgSKFje_pF7nXLVE)

