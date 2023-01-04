 removebackground

Como remover o fundo de uma foto no Python


pip install rembg
pip install Pillow


from rembg import remove
from PIL import Image

foto=Image.open("C:\imagens\eu.jpg") # o caminho onde está sua foto
saida=remove(foto).save("eusemfundo.png") # a saída da foto sem fundo
