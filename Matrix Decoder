import numpy as np  
import colorama
from colorama import Fore
import time

colorama.init(autoreset=True)

special_chars = "!@#$%^&*()_+=-~'\\|?/>.<,|`"

def get_char(element):
    match element in special_chars, element.isalnum():
        case (True, _):   
            return ' '
        case (_, True):   
            return element
        case _:         
            return element  

# إدخال الأبعاد والمصفوفة
rows, col = map(int, input().split())
matrix = [list(input()[:col]) for _ in range(rows)]

char_matrix = np.array(matrix)

# استخراج الأحرف ومعالجتها
c = ''
for j in range(col):  
    for i in range(rows):
        c += get_char(matrix[i][j])

# طباعة الأحرف مع التأثير البطيء
for char in c:
    print(Fore.GREEN + char, end='', flush=True)
    time.sleep(0.1)
