from tkinter import *

class HalderApp:
    def __init__(self):
        self.root = Tk()
        self.root.title('HalderApp')
        self.root.iconbitmap('favicono/favicon.ico')
        self.root.geometry('350x600')
        self.root.configure(bg = "red")
        self.login_gui()
        self.root.mainloop()


    def login_gui(self):
        self.clear()
        Heading = Label(self.root,text = "HalderApp",bg="red",fg="white")
        Heading.pack(pady=(30,30))
        Heading.configure(font=("Arial",24,"bold"))
        Label1 = Label(self.root, text="Enter Email")
        Label1.pack(pady=(10,10))
        self.email_input = Entry(self.root,width=40)
        self.email_input.pack(pady=(5,10),ipady=4)

        Label2 = Label(self.root, text="Password")
        Label2.pack(pady=(10, 10))
        self.Password_input = Entry(self.root, width=40, show = "*")
        self.Password_input.pack(pady=(5, 10), ipady=4)

        login_btn = Button(self.root,text="Login",width=30,height=2)
        login_btn.pack(pady=(10,10))

        Label3 = Label(self.root, text="Not a Member")
        Label3.pack(pady=(10, 10))

        redirect_btn = Button(self.root, text="Register Now", command=self.register_gui)
        redirect_btn.pack(pady=(10, 10))

    def register_gui(self):
       self.clear()

       Heading = Label(self.root, text="HalderApp", bg="red", fg="white")
       Heading.pack(pady=(30, 30))
       Heading.configure(font=("Arial", 24, "bold"))

       Label0 = Label(self.root, text="Enter Name")
       Label0.pack(pady=(10, 10))
       self.name_input = Entry(self.root, width=40)
       self.name_input.pack(pady=(5, 10), ipady=4)

       Label1 = Label(self.root, text="Enter Email")
       Label1.pack(pady=(10, 10))
       self.email_input = Entry(self.root, width=40)
       self.email_input.pack(pady=(5, 10), ipady=4)

       Label2 = Label(self.root, text="Password")
       Label2.pack(pady=(10, 10))
       self.Password_input = Entry(self.root, width=40, show="*")
       self.Password_input.pack(pady=(5, 10), ipady=4)

       register_btn = Button(self.root, text="Register", width=30, height=2)
       register_btn.pack(pady=(10, 10))

       Label3 = Label(self.root, text="Already a Member")
       Label3.pack(pady=(10, 10))

       redirect_btn = Button(self.root, text="Login Now", command=self.login_gui)
       redirect_btn.pack(pady=(10, 10))

    def clear(self):
        for i in self.root.pack_slaves():
            i.destroy()

p = HalderApp()