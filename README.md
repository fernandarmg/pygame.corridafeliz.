# pygame.corridafeliz.

import pygame
from pygame.locals import *
import random

pygame.init()

# Criar a janela
largura = 500
altura = 500
tamanho_tela = (largura, altura)
tela = pygame.display.set_mode(tamanho_tela)
pygame.display.set_caption('Corrida Feliz')
