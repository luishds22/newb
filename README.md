# newb

Trying to figure out why I can't run pygame... any guidance would be apreciated!

Here is my code:

import pygame
from pygame.locals import*

pygame.init()


screen_width = 1000
screen_height = 1000

screen = pygame.display.set_mode((screen_width, screen_height))
pygame.display.set_caption('Platformer')
pygame.display.flip()


And here is the error im getting in the terminal:

PS C:\Users\luish\projects>  & 'C:\Users\luish\AppData\Local\Programs\Python\Python39\python.exe' 'c:\Users\luish\.vscode\extensions\ms-python.python-2021.12.1559732655\pythonFiles\lib\python\debugpy\launcher' '63672' '--' 'c:\Users\luish\projects\import pygame.py'Traceback (most recent call last):  File "c:\Users\luish\projects\import pygame.py", line 1, in <module>
    import pygame
ModuleNotFoundError: No module named 'pygame'
    
PS C:\Users\luish\projects> pip install pygame
Requirement already satisfied: pygame in c:\users\luish\appdata\local\packages\pythonsoftwarefoundation.python.3.9_qbz5n2kfra8p0\localcache\local-packages\python39\site-packages (2.1.2)
PS C:\Users\luish\projects> 
