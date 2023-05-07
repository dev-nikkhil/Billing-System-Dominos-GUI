#********DOMINOS BILLING SYSTEM***********
from tkinter import *



root=Tk()
root.geometry('1000x500')
root.title('Dominos Bill Management')
root.resizable(FALSE,False)


def Reset():
    entry_Pizza.delete(0,END)
    entry_Burger.delete(0,END)
    entry_Pasta.delete(0,END)
    entry_Parcel.delete(0,END)
    entry_Drinks.delete(0,END)
    entry_Tea.delete(0,END)
    entry_coffee.delete(0,END)

def Total():
    try:a1=int(Pizza.get())
    except:a1=0

    try:a2=int(Burger.get())
    except:a2=0

    try:a3=int(Pasta.get())
    except:a3=0

    try:a4=int(Parcel.get())
    except:a4=0

    try:a5=int(Drinks.get())
    except:a5=0

    try:a6=int(Tea.get())
    except:a6=0

    try:a7=int(Coffee.get())
    except:a7=0

    #price define
    b1=a1*150
    b2=a2*100
    b3=a3*75
    b4=a4*30
    b5=a5*40
    b6=a6*40
    b7=a7*100
    
    lbl_total=Label(f2,font=("arial",30,"bold"),text="Total",width=16,bg="white",fg="black")
    lbl_total.place(x=0,y=50)

    entry_total=Entry(f2,font=("aria",20,'bold'),textvariable=Total_bill,bd=6,width=15,bg='lightgreen')
    entry_total.place(x=20,y=100)

    total_cost=b1+b2+b3+b4+b5+b6+b7
    bill="Rs",str('%.2f'%total_cost)
    Total_bill.set(bill)
Label(text="Dominos Bill Management",bg='DodgerBlue3',fg="white",font=("Futura",33),width="300",height="2").pack()


#menu card

f=Frame(root,bg="DeepSkyBlue4",highlightbackground="Gray",highlightthickness=1,width=300,height=370)
f.place(x=10,y=120)

Label(f,text="Menu",font=("Gabriola",40,"bold"),fg="white",bg="DeepSkyBlue4").place(x=80,y=0)

Label(f,font=("Lucida calligraphy",15,"bold"),text="Pizza--------------->Rs.150",fg="white",bg="DeepSkyBlue4").place(x=10,y=80)
Label(f,font=("Lucida calligraphy",15,"bold"),text="Burger------------>Rs.100",fg="white",bg="DeepSkyBlue4").place(x=10,y=110)
Label(f,font=("Lucida calligraphy",15,"bold"),text="Pasta--------------->Rs.75",fg="white",bg="DeepSkyBlue4").place(x=10,y=140)
Label(f,font=("Lucida calligraphy",15,"bold"),text="Parcel-------------->Rs.30",fg="white",bg="DeepSkyBlue4").place(x=10,y=170)
Label(f,font=("Lucida calligraphy",15,"bold"),text="Drinks-------------->Rs.40",fg="white",bg="DeepSkyBlue4").place(x=10,y=200)
Label(f,font=("Lucida calligraphy",15,"bold"),text="Tea------------------>Rs.40",fg="white",bg="DeepSkyBlue4").place(x=10,y=230)
Label(f,font=("Lucida calligraphy",15,"bold"),text="Coffee------------>Rs.100",fg="white",bg="DeepSkyBlue4").place(x=10,y=260)

#bill
f2=Frame(root,bg="red2",highlightbackground="Gray",highlightthickness=1,width=300,height=370)
f2.place(x=690,y=118)
bill=Label(f2,text="Bill",font=("Gabriola",20,"bold"),fg="white",bg="red2")
bill.place(x=120,y=10)

#entry work
f1=Frame(root,bg="Royalblue2",bd=5,height=350,width=280,relief=RAISED)
f1.pack()

Pizza=StringVar()
Burger=StringVar()
Pasta=StringVar()
Parcel=StringVar()
Drinks=StringVar()
Tea=StringVar()
Coffee=StringVar()
Total_bill=StringVar()

#label
lbl_Pizza=Label(f1,font=("aria",20,"bold"),text="Pizza",width=12,fg="DeepSkyBlue3")
lbl_Burger=Label(f1,font=("aria",20,"bold"),text="Burger",width=12,fg="DeepSkyBlue3")
lbl_Pasta=Label(f1,font=("aria",20,"bold"),text="Pasta",width=12,fg="DeepSkyBlue3")
lbl_Parcel=Label(f1,font=("aria",20,"bold"),text="Parcel",width=12,fg="DeepSkyBlue3")
lbl_Drinks=Label(f1,font=("aria",20,"bold"),text="Drinks",width=12,fg="DeepSkyBlue3")
lbl_Tea=Label(f1,font=("aria",20,"bold"),text="Tea",width=12,fg="DeepSkyBlue3")
lbl_coffee=Label(f1,font=("aria",20,"bold"),text="Coffee",width=12,fg="DeepSkyBlue3")
lbl_Pizza.grid(row=1,column=0)
lbl_Burger.grid(row=2,column=0)
lbl_Pasta.grid(row=3,column=0)
lbl_Parcel.grid(row=4,column=0)
lbl_Drinks.grid(row=5,column=0)
lbl_Tea.grid(row=6,column=0)
lbl_coffee.grid(row=7,column=0)



#entry
entry_Pizza=Entry(f1,font=("aria",20,"bold"),textvariable=Pizza,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_Burger=Entry(f1,font=("aria",20,"bold"),textvariable=Burger,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_Pasta=Entry(f1,font=("aria",20,"bold"),textvariable=Pasta,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_Parcel=Entry(f1,font=("aria",20,"bold"),textvariable=Parcel,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_Drinks=Entry(f1,font=("aria",20,"bold"),textvariable=Drinks,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_Tea=Entry(f1,font=("aria",20,"bold"),textvariable=Tea,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_coffee=Entry(f1,font=("aria",20,"bold"),textvariable=Coffee,bd=6,width=8,bg="SteelBlue1",fg="white")
entry_Pizza.grid(row=1,column=1)
entry_Burger.grid(row=2,column=1)
entry_Pasta.grid(row=3,column=1)
entry_Parcel.grid(row=4,column=1)
entry_Drinks.grid(row=5,column=1)
entry_Tea.grid(row=6,column=1)
entry_coffee.grid(row=7,column=1)

#buttons
btn_reset=Button(f1,bd=5,fg="white",bg="cyan3",font=('ariel',16,'bold'),width=9,text="Reset",command=Reset)
btn_reset.grid(row=8,column=0)

btn_total=Button(f1,bd=5,fg='white',bg='cyan3',font=('ariel',16,'bold'),width=9,text='Total',command=Total)
btn_total.grid(row=8,column=1)


root.mainloop()
