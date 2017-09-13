# computationalphysics_N2015301510089
## first_work_print_my_name
import turtle
wn=turtle.Screen()
wn.bgcolor("lightgreen")
pan=turtle.Turtle()
pan.color("red")
pan.shape("turtle")
pan.penup()
def heng():
    for each in range(5,20,2):
        pan.stamp()
        pan.forward(each)

def shu():
    pan.right(90)
    for each in range(5,20,2):
        pan.stamp()
        pan.forward(each)
    pan.left(90)
    
def pie():
    pan.right(145)
    for each in range(5,20,2):
        pan.stamp()
        pan.forward(each)
    pan.left(145)
    
def na():
    pan.right(45)
    for each in range(5,20,2):
        pan.stamp()
        pan.forward(each)
    pan.left(45)
        
      
    

pan.goto(-200,200)
na()
pan.goto(-200,160)
na()
pan.goto(-130,80)
pie()
pan.goto(-110,200)
heng()
pan.goto(-70,200)
shu()
pan.goto(-70,200)
pie()
pan.goto(-70,200)
na()
pan.goto(-110,140)
heng()
pan.goto(-70,140)
na()
pan.goto(-70,140)
pie()
pan.goto(-110,100)
shu()
pan.goto(-110,100)
heng()
pan.goto(-110,60)
heng()
pan.goto(-70,100)
shu()
pan.goto(-30,100)
shu()
pan.goto(-110,20)
heng()
pan.goto(0,0)
shu()
pan.goto(0,-80)
shu()
pan.goto(0,0)
heng()
pan.goto(80,0)
shu()
pan.goto(80,-80)
shu()
pan.goto(0,-40)
heng()
pan.goto(0,-80)
heng()
