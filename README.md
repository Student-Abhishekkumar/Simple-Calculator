# Simple-Calculator

#Clear Button
'''python
Button1=Button(win,text="Clear",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_clear())
'''

#Just Numbers
Button_1=Button(win,text="1",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(1))
Button_2=Button(win,text="2",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(2))
Button_3=Button(win,text="3",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(3))
Button_4=Button(win,text="4",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(4))
Button_5=Button(win,text="5",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(5))
Button_6=Button(win,text="6",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(6))
Button_7=Button(win,text="7",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(7))
Button_8=Button(win,text="8",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(8))
Button_9=Button(win,text="9",width=10,borderwidth=3,height=3,background="white",relief=SUNKEN,command=lambda: button_actions(9))
Button_10=Button(win,text="0",width=10,borderwidth=3,background="white",height=3,relief=SUNKEN,command=lambda: button_actions(0))

#Action Buttons
Button_11=Button(win,text="=",width=10,borderwidth=3,height=3,bg="purple",fg="white",relief=SUNKEN,command=lambda: button_equal())
Button_12=Button(win,text="+",width=10,borderwidth=3,background="grey",fg="white",height=3,relief=SUNKEN,command=lambda: button_add())
Button_13=Button(win,text="-",width=10,borderwidth=3,background="grey",fg="white",height=3,relief=SUNKEN,command=lambda: button_sub())
Button_14=Button(win,text="*",width=10,borderwidth=3,background="grey",fg="white",height=3,relief=SUNKEN,command=lambda: button_multiply())
Button_15=Button(win,text="/",width=10,borderwidth=3,background="grey",fg="white",height=3,relief=SUNKEN,command=lambda: button_division())

#Positioning The Buttons
Button1.grid(row=0,column=3)
Button_1.grid(row=1,column=0)
Button_2.grid(row=1,column=1)
Button_3.grid(row=1,column=2)

Button_4.grid(row=2,column=0)
Button_5.grid(row=2,column=1)
Button_6.grid(row=2,column=2)

Button_7.grid(row=3,column=0)
Button_8.grid(row=3,column=1)
Button_9.grid(row=3,column=2)

Button_10.grid(row=4,column=0)
Button_11.grid(row=4,column=1)
Button1.grid(row=4,column=2)

Button_13.grid(row=5,column=0)
Button_14.grid(row=5,column=1)
Button_15.grid(row=5,column=2)
