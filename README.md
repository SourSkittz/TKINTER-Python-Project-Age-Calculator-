From tkinter import 
from datetime import date\n",

def agecalcalcuator():
global result\n",
result = str(entry.get())
today = date.today()
data = result.split(\"/\")
date1 = int(age_data[0])
month = int(age_data[1])
year = int(age_data[2])
age = data(year.month,date1)
numberdays = (today - data).days
age = numberdays // 365
label=Label(root, text= \"You are\" +str(age))
label.pack()
 
  root = Tk()
  root.geometry(\"250x500\")
  entry = Entry(root)
  entry.pack()
  
  button = Button(root, text=\"age\", command=agecalculator)
  button.pack()
  root.mainloop
