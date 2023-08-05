# Graphics-using-Turtlegraphics

<p>In this project, we would like to introduce you to the basics of python graphics and things you could do even before starting your
specialisation in graphics design. We would give you more exposure to pythonturtles and how to utilise colors in its domain</p>

<h3> Technology Used </h3>

<img  align = "center"  src="https://www.python.org/static/img/python-logo@2x.png" 
  width="300" 
  height="60" />
  
<i>Download latest version of python IDLE 3.11.4.Below chick--></i>

  <i>WINDOWS, MAX, LINUX USERS</i>

      https://www.python.org/downloads

CONTENT REQUIRED TO SOLVE THE PROJECT

| Method | Parameters| Description|
--- | --- | --- |
Turtle() | None |Creates and returns a newturtle object | 
forward() | amount |Moves the turtle forwardby the specified amount| 
backward() | amount |Moves the turtle backward by the specified amount | 
right() | angle | Turns the turtle clockwise
penup() | None | Picks up the turtle’s Pen
pendown()| None | Puts down the turtle’s Pen
up()| None |Picks up the turtle’s Pen
down()| None | Puts down the turtle’s Pen
color()| Color|  name Changes the color ofthe turtle’s pen.
fillcolor() |Color name| Changes the color of the turtle will use to fill a polygon
heading() | None |Returns the current heading
position()| None | Returns the current position
goto()| x, y| Move the turtle to position x,y
begin_fill()| None |Remember the starting point for a filled polygon
end_fill()| None | Close the polygon and fill with the current fill color
dot() | None |Leave the dot at the current position
tamp()| None| Leaves an impression of a turtle shape at the current location
shape()| shapename | Should be ‘arrow’, ‘classic’,‘turtle’ or ‘circle

<h43>Referral code</h3>

    ## turtle Graphics using python
     from turtle import *
     from random import randint 
     speed(0)
     bgcolor('black')

     x = 1
   
    while x < 400:
        r = randint(0,255) 
        g = randint(0,255) 
        b = randint(0,255) 
                   
        colormode(255)
        pencolor(r,g,b) 
        fd(50 + x)
        rt(90.911)
        x = x+1 
        exitonclick() 

Output

<img  align = center  src="https://lh6.googleusercontent.com/deHwZhiHjR1eghl6mQ1z_XK8IL36Huv62rvnKleFTWARqycfV-i3rDOQmzpT8t5uml3zgRHWodMOPRy-W0kfU0flrJxare2MdLWaIwcBG_s176zHVk5n9zNB8kdDStRkPLEItVba" 
  width="450" 
  height="300" />
