# 2048
created for final project

import tkinter as tk

Class my2048Game:

    def __init__(self):
        self.rootWin = tk.Tk()
        
        homePageSign = tk.Label(self.rootWin, text = "2048", font = "Arial 18 bold", relief = tk.RAISED)
        homePageSign.grid(row = ?, column = ?)
        
        startButton = tk.Button(self.rootWin)
        startButton["text"] = "Start"
        startButton["font"] = "Arial 12"
        testButton.grid(row = ?, column = ?)


testButton.grid(row = 1, column = 0)


    def run(self):
            self.rootWin.mainloop()
        


my2048 = BasicGui()
my2048.run()

class my2048Gamequit()

    def __init__(self):
        self.rootWin = tk.Tk()

        quitButton = tk.Button(self.rootWin, text="Quit", command=self.doQuit)
        quitButton.grid(row=25, column=25, padx=10, pady=10)
    def doQuit(self):
      self.rootWin.destroy()
    def run(self):
        self.rootWin.mainloop()
