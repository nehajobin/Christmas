# Christmas
Wishing you christmas 
from turtle import *
import time
speed(6)
#circle
penup()
goto(0,-300)
pendown()
color("skyblue")
begin_fill()
circle(300)
end_fill()
#trunk
penup()
goto(-15,-50)
pendown()
color("brown")
begin_fill()
for i in range(2):
    forward(30)
    right(90)
    forward(30)
    right(90)
end_fill()
y=-50
width=240
height=25
#tree
while width>20:
    width=width-30
    x=0-width/2
    color("green")
    penup()
    goto(x,y)
    pendown()
    begin_fill()
    for i in range(2):
        forward(width)
        left(90)
        forward(height)
        left(90)
    end_fill()
    y=y+height
#star
goto(-15,150)
pendown()
color("red")
begin_fill()
for i in range(5):
    forward(30)
    right(144)
end_fill()
hideturtle()

#wish greeting message
import turtle
import time

letter_writer = turtle.Turtle()
letter_writer.speed(1)
letter_writer.hideturtle()

def write_letter(letter, x, y):
    letter_writer.color("white")
    letter_writer.penup()
    letter_writer.goto(x, y)
    letter_writer.pendown()
    letter_writer.write(letter, font=("Arial", 24, "bold"))

def write_merry_christmas():
    write_letter("M", -180, -150)
    time.sleep(0.5)
    write_letter("E", -150, -150)
    time.sleep(0.5)
    write_letter("R", -120,-150)
    time.sleep(0.5)
    write_letter("R", -90, -150)
    time.sleep(0.5)
    write_letter("Y", -60, -150)
    time.sleep(0.5)
    write_letter("C", 0, -150)
    time.sleep(0.5)
    write_letter("H", 30, -150)
    time.sleep(0.5)
    write_letter("R", 60, -150)
    time.sleep(0.5)
    write_letter("I", 90, -150)
    time.sleep(0.5)
    write_letter("S", 100, -150)
    time.sleep(0.5)
    write_letter("T", 120, -150)
    time.sleep(0.5)
    write_letter("M", 150, -150)
    time.sleep(0.5)
    write_letter("A", 180, -150)
    time.sleep(0.5)
    write_letter("S", 210, -150)

write_merry_christmas()

turtle.done()

hideturtle()
