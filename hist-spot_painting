#### The following lines are used to print color_list

#import colorgram

#rgb_colors=[]
#colors=colorgram.extract('pic-2.jpeg',30)
#r=colors.rgb.r
#g=colors.rgb.g
#b=colors.rgb.b
#new_color=(r,g,b)
#rgb_colors.append(new_color)
#print(rgb_colors)
#import colorgram

import turtle as t
import random
tim=t.Turtle()
tim.penup()
tim.hideturtle()
tim.speed('fastest')
t.colormode(255)
color_list = [(202, 164, 109), (238, 240, 245), (150, 75, 49), (223, 201, 135), (52, 93, 124), (172, 154, 40), (140, 30, 19), (133, 163, 185), (198, 91, 71), (46, 122, 86), (72, 43, 35), (145, 178, 148), (13, 99, 71), (233, 175, 164), (161, 142, 158), (105, 74, 77), (55, 46, 50), (183, 205, 171), (36, 60, 74), (18, 86, 90), (81, 148, 129), (148, 17, 20), (14, 70, 64), (30, 68, 100), (107, 127, 153), (174, 94, 97), (176, 192, 209)]

#to set the turtle position in the correct place
tim.setheading(225)
tim.forward(300)
tim.setheading(0)
total_dots=100

for i in range(1,total_dots+1):
  tim.dot(20,random.choice(color_list))
  tim.forward(50)

  if i%10==0:
    tim.setheading(90)
    tim.forward(50)
    tim.setheading(180)
    tim.forward(500)
    tim.setheading(0)
  



  
screen =t.Screen()
screen.exitonclick()
