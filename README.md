# Lab-5_202001013

**Introduction:**
The python tool used for this lab is Mypy.
It has been selected because of the following reasons: 
A strong and user-friendly type system is available in Mypy, supporting features like type inference, generics, etc. It will be simpler to comprehend, troubleshoot, and maintain the programme if mypy is used.

**Repository 1: Bank Management System**
Link: https://github.com/jaigora24/BankManagementSystem/blob/master/SourceCode.py

<img src="https://user-images.githubusercontent.com/99882265/225285392-7d9f105d-b968-4668-8b54-7328c214b8b1.png">

This code has no errors thus it returned “Success”. This can be confirmed as this was a simple code and it did not require anything to be installed.

**Repository 2: Tetris Game**
Link: https://github.com/randaller/llama-chat/blob/main/merge-weights.py

<img src="https://user-images.githubusercontent.com/99882265/225286123-fb660baa-43e4-4e2c-946d-00076436e802.png">

Error 1: Import
```
import pygame #Error 1
import random


pygame.init()
```

Import error: Typically, this error happens if:
The imported class was either not made or is not available.
The module's imported class is not where it should be.
There is no equivalent of the imported class in the Python library.


Error 2: Miscellaneous Errors
```
                if event.key == pygame.K_SPACE:
                    tetris.go_space()


            if event.key == pygame.K_r:
                tetris.__init__(ROWS, COLS) #Error 2


            if event.key == pygame.K_p:
                can_move = not can_move
```

**Repository 3: Pong game**
Link: https://github.com/pyGuru123/Python-Games/blob/master/Pong/game.py

<img src="https://user-images.githubusercontent.com/99882265/225286986-fc789a9c-6261-430a-85cc-c79e98324886.png">

Error 1 & 2: Attribute errors
```
# Ball
ball = turtle.Turtle()
ball.speed(0)
ball.shape('circle')
ball.color('white')
ball.penup()
ball.goto(0,0)


ball.dx = 1.0 #Error 1
ball.dy = 1.0 #Error 2




# Pen
pen = turtle.Turtle()
pen.speed(0)
pen.color('white')
pen.penup()
pen.hideturtle()
pen.goto(0,250)
```
All the errors in this code are Attribute errors.
When an attribute reference or assignment fails, AttributeError is raised as an error. For example, if we take the variable x and we are given the number 45. Let's say we wish to add a new value to that variable during this operation. It isn't feasible. The variable does not allow the append method because it is an integer type. This type of issue results in a "AttributeError" error.  Suppose if the variable is list type then it supports the append method.
We can conclude that the 

**Repository 4: Music Player**
Link: https://github.com/ndleah/python-mini-project/blob/main/Music-Player/music_player.py

<img src="https://user-images.githubusercontent.com/99882265/225287723-d2bf8662-8251-4980-9e26-83bcafea73f0.png">

Error 1: Import error
```
import glob
import tkinter as tk
from tkinter import *
import vlc #Error 1
```

Import error occurs because of the libraries that were not installed and we can confirm this error as I had not installed the library and it gave the error. Thus it is a true positive.

Error 2: NameError
```
forward = tk.Button(window, image=forward_image, command=next_music)
backward = tk.Button(window, image=backward_image, command=previous_music)
stop = tk.Button(window, image=stop_image, command=lambda: sys.exit()) 
#The line above has an error#


play.place(x=130, y=50)
pause.place(x=10, y=50)
```
In Python, the NameError occurs when you try to use a variable, function, or module that doesn't exist or wasn't used in a valid way.
