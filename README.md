# clock.py
# sandupama</>
<h2>from tkinter import *
from tkinter.ttk import *

from time import strftime

root =Tk()
root.title("Enter your title")

def time():
    string = strftime('%H:%M:%S %p')
    label.config(text=string)
    label.after(1000, time)

label = Label(root, font=("DS-DIGIB.TTF", 100), background = "black", foreground = "cyan")
label.pack(anchor='center')
time()

mainloop()<h2>


![clock](https://user-images.githubusercontent.com/88402272/136017166-fd76b4b8-087b-44b0-89b0-19c3a7511c82.png)

<h1>.py<h1>
