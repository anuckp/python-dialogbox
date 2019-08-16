# python-dialogbox
python dialogbox
from tkinter import *
from tkinter import filedialog
root= Tk()
root.fileName= filedialog.askopenfilename(filetypes = ( ("howcode files","*.hc"),("only excel files","*.*") ) )
destination=(root.fileName)
