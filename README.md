# Mi-clasificador-de-generos-de-videojuegos."
Si lo que quieres es hacer un bot de Discord que detecte géneros de videojuegos y te diga su probabilidad de reconocimiento haz esto.

Habre Google Teachable machine, haz 5es clases de géneros de videojuegos, a cada clase dale 6 imágenes que no sean ni ".web" ni ".avif",
aprieta en Train Model y luego exporta el modelo en la sección de python con Tensor Flow y en archivos te aparecerá una carpeta llamada converted_keras.zip

Si te fijas hay 2 códigos, un archivo ".ipynb" y otro archivo ".py", cada archivo tiene una funcionalidad diferente.
El archivo ".ipynb" es un cuaderno de Google Colab, lo que tienes que hacer es, crear un cuadernillo de Google Colab, pegar cada código 
en su celda correspondiente y ponerlos a correr(lo único que debes hacer es poner el token de tu propio bot de DISCORD y tu propio 
converted_keras.zip).

Mientras tanto el archivo ".py" es un código de Python que unifica todos los códigos del archivo ".ipynb". Hace lo mismo solo que en una 
sola celda, tienes que hacer lo mismo, pero con un solo código con sus correspondientes pasos, es preferible que uses el otro tipo de 
archivo.

Por último, tienes que probar todo en tu propio servidor de bots de Discord usando el comando $checky subiendo la imagen de el género de 
videojuegos que vos quieras.
Te tiene que aparecer esto:
<img width="820" height="445" alt="image" src="https://github.com/user-attachments/assets/ba886ec1-ce2b-4e88-8708-6012d8ad1caf" />

