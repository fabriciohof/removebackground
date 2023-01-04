![i](https://user-images.githubusercontent.com/91196904/210466384-79cc12a4-1e33-4e3c-b223-6bdab73975ff.png)
![eu](https://user-images.githubusercontent.com/91196904/210466388-d307c85b-ff4c-445b-8c31-a008f07286fd.png)
 removebackground

Como remover o fundo de uma foto no Python


pip install rembg
pip install Pillow


from rembg import remove
from PIL import Image

foto=Image.open("C:\imagens\eu.jpg") # o caminho onde está sua foto
saida=remove(foto).save("eusemfundo.png") # a saída da foto sem fundo
