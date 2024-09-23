# Fill me in! 
"idea"
"project of simple calculator"
#use this simple calculator as usual by pressing 
# the key you have  given.
app.background="cornflowerBlue"
# label the condition words
Label("calculate by pressing as usual and you get the ansuer",200,10,size=15,fill="White")
# calculator
Rect(90,30,220,330,fill="snow",border="gray",borderWidth=1)
Line(96,31,308,31,fill=rgb(90,100,100))
Line(96,31,91,34,fill=rgb(90,100,100),lineWidth=4)
Line(307,31,308,34,fill=rgb(90,100,100),lineWidth=4)
Line(94,358,306,358,opacity=30,lineWidth=3)
Rect(92,32,216,326,fill="gainsboro",border="gray",borderWidth=1)
Rect(95,36,210,320,fill="silver",border="gray",borderWidth=1)
Rect(96,36,210,320,fill="lavender",border="gray",borderWidth=1)
Rect(96,46,210,40,fill=rgb(120,130,130))
Line(96,86,306,86,fill="lavender")
Rect(96,87,210,90,fill=rgb(120,130,130))

# draw +solar cell
Rect(106,49,190,30,fill="thistle")
Line(106,64,296,64,lineWidth=30,fill="white",dashes=(2,50))
Rect(106,49,190,30,fill=None,border=rgb(90,100,100),borderWidth=4)
Line(108,51,294,51,lineWidth=4)

# draw screen
Rect(110,91,180,60,fill=rgb(170,180,180))
Line(110,94,110,148,opacity=50)
Line(110,94,112,91,opacity=50)
Line(110,148,112,151,opacity=50)
Line(112,91,288,91,opacity=50)
Rect(110,91,180,60,fill=None,border="black",opacity=20,borderWidth=4)
Line(288,91,290,93,opacity=40)
Rect(123,96,155,48,fill=rgb(220,230,230),border="gray")
Line(99,188,303,188,lineWidth=5,fill=rgb(170,180,180))
Line(100,188,98,186,lineWidth=5,fill=rgb(170,180,180))
Line(303,188,305,186,lineWidth=5,fill=rgb(170,180,180))

#  drow space of numbers
a1=Rect(108,178,26,16,fill="indianRed",border=rgb(80,90,90))
n=Rect(158,320,30,30,fill="indianRed",border=rgb(80,90,90))
a=Rect(108,195,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
b=Rect(158,195,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
c=Rect(208,195,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
d=Rect(258,195,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
e=Rect(108,236,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
f=Rect(158,236,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
g=Rect(208,236,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
h=Rect(258,236,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
i=Rect(108,279,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
j=Rect(158,279,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
k=Rect(208,279,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
z=Rect(258,279,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
m=Rect(108,320,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
o=Rect(208,320,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))
p=Rect(258,320,30,30,fill=rgb(120,130,130),border=rgb(80,90,90))

# draw numbers or value
u1=Label(7,123,210,size=20,fill="White")
u2=Label(8,173,210,size=20,fill="White")
u3=Label(9,223,210,size=20,fill="White")
u4=Label(4,123,251,size=20,fill="White")
u5=Label(5,173,251,size=20,fill="White")
u6=Label(6,223,251,size=20,fill="White")
u7=Label(1,123,294,size=20,fill="White")
u8=Label(2,173,294,size=20,fill="White")
u9=Label(3,223,294,size=20,fill="White")
u10=Label(0,123,335,size=20,fill="White")
ab=Label("on",119,186,size=13,fill="yellow")
ac=Label("OFF",173,335,size=12,fill="yellow")
# value to be used in calculating 
l=Label(0,260,127,size=30)
l1=Label(0,260,105,size=0)
l2=Label("",260,105,size=0)
l3=Label(0,245,105,size=0)
l4=Label("",260,105,size=0)
# draw the operators
Label("/",273,210,size=20,fill="White")
Label("*",273,255,size=20,fill="White")
Label("-",273,294,size=20,fill="White")
Label("+",273,335,size=20,fill="White")
Label("=",223,335,size=20,fill="White")
# draw the function that covers if you get solution which will go beyond 
# the calculator
# function used to start when you press key on
def start(mouseX,mouseY):
    if(a1.contains(mouseX,mouseY)==True):
            l.visible=True
            l.value=0
            l.size=30
            l.centerX=260
            l1.value=l2.value
            l1.size=l2.size
            l3.value=l2.value
            l3.size=l2.size
# funtion for cllosing off the calculator
def off(mouseX,mouseY):
    if(n.contains(mouseX,mouseY)==True):
            l.visible=False
            l1.value=l2.value
            l1.size=l2.size
            l3.value=l2.value
            l3.size=l2.size
# funtion for when you press any sign except equal
def sign():
    # if(l1.value==0):
    # l1.value=l.value
    l1.size=12
    l1.right=270
    l.value=0
    l.centerX=260
    l.size=30
# function for when you press equal sign 
def equal():
    l3.value=l.value
    l3.size=12
    l3.centerX=l1.centerX
    l3.right=270
# funtion for when you press the key which are
# the numbers
def numbers():
    l.size=20
    l.centerX-=5
    l.right=270

def onMousePress(mouseX,mouseY):
    # make an if condition for entering numbers for when the number
    # greater or equals to 220 it means also calculator will take only
    # 9 numbers and call function numbers
    if(l.centerX>=230):
        if(a.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u1.value
            numbers()
        elif(b.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u2.value
            numbers()
        elif(c.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u3.value
            numbers()
        elif(e.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u4.value
            numbers()
        elif(f.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u5.value
            numbers()
        elif(g.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u6.value
            numbers()
        elif(i.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u7.value
            numbers()
        elif(j.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u8.value
            numbers()
        elif(k.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u9.value
            numbers()
        elif(m.contains(mouseX,mouseY)==True):
            l.value=l.value*10+u10.value
            numbers()

          
            # condition of when you press division sign
    if(d.contains(mouseX,mouseY)==True):
        l4.value="/"
        if(l1.value!=0):
            l1.value=l1.value/l.value
        elif(l1.value==0):
            l1.value=l.value
        # call fucntion sign
        sign()
        # if condition for when you press equal after you enter
        # other numbers
    if(l4.value=="/"):
        if(o.contains(mouseX,mouseY)==True):
            if(l.value!=0):
                # call function equal
                equal()
                
                l.value=l1.value/l.value
                l1.value=l2.value
                l1.size=l2.size
                l.centerX=210
                # if condition for position of any ansuer
                if(l.right<=260):
                    l.right=260
                    # else for when you divided bigger numbers 
                else:
                    l.size=12
                    l.left=140
                    
                
            else:
                l.value="math error"
                l.size=15
                l.centerX=240
                l1.value=l2.value
                l1.size=l2.size
            
    # condition of when you press multiplication  sign
    elif(h.contains(mouseX,mouseY)==True):
        l4.value="*"
        if(l1.value!=0):
            l1.value=l1.value*l.value
        elif(l1.value==0):
            l1.value=l.value
        # call fucntion sign
        sign()
    # if condition for when you press equal after you enter
    # other numbers
    if(l4.value=="*"):
        if(o.contains(mouseX,mouseY)==True):
            # call function equal
            equal()
    
            l.value=l1.value*l.value
            l.centerX=210
            l1.value=l2.value
            l1.size=l2.size
            # if condition for position of any ansuer
            if(l.right<=260):
                l.right=260
                # else for when you multiplied many numbers 
            else:
                l.size=12
                l.left=150
              
        # condition of when you press substraction sign
    elif(z.contains(mouseX,mouseY)==True):
        l4.value="-"
        if(l1.value!=0):
            l1.value=l1.value-l.value
        elif(l1.value==0):
            l1.value=l.value
        # call fucntion sign
        sign()
        
    # if condition for when you press equal after you enter
    # other numbers
    if(l4.value=="-"):
        if(o.contains(mouseX,mouseY)==True):
            # call function equal
            equal()
            
            l.value=int(l1.value-l.value)
            l1.value=l2.value
            l1.size=l2.size
            l.centerX=210
            # if condition for position of any ansuer
            if(l.right<=260):
                l.right=260
            
        # condition of when you press addition sign
    elif(p.contains(mouseX,mouseY)==True):
        l4.value="+"
        if(l1.value!=0):
            l1.value=l1.value+l.value
        elif(l1.value==0):
            l1.value=l.value
        # call fucntion sign
        sign()
    # if condition for when you press equal after you enter
    # other numbers
    if(l4.value=="+"):
        if(o.contains(mouseX,mouseY)==True):
             # call function equal
            equal()
            l.value=l1.value+l.value
            l.centerX=210
            l1.value=l2.value
            l1.size=l2.size
            # if condition for position of any ansuer
            if(l.right<=260):
                l.right=260
                
    # call the fucntion start 
    start(mouseX,mouseY)
    # call of funtion to close
    off(mouseX,mouseY)
