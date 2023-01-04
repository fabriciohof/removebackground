Como remover o fundo de uma foto no Python


pip install rembg

pip install Pillow


from rembg import remove

from PIL import Image

foto=Image.open("C:\imagens\eu.jpg") # o caminho onde está sua foto

saida=remove(foto).save("eusemfundo.png") # a saída da foto sem fundo


![i](https://user-images.githubusercontent.com/91196904/210466384-79cc12a4-1e33-4e3c-b223-6bdab73975ff.png)
![i am](https://user-images.githubusercontent.com/91196904/210466487-ee59f68a-fbb8-4ff3-bbf4-f8c1d6579e03.png)

