# -DEMIT_FinalProject
import turtle

def draw_lamput():
    screen = turtle.Screen()
    screen.bgcolor("white")

    lamput = turtle.Turtle()
    lamput.speed(3)

    # Draw Lamput's body
    lamput.color("orange")
    lamput.penup()
    lamput.goto(0, -50)
    lamput.pendown()
    lamput.begin_fill()
    lamput.circle(50)
    lamput.end_fill()

    # Draw Lamput's eyes
    lamput.color("white")
    lamput.penup()
    lamput.goto(-20, 20)
    lamput.pendown()
    lamput.begin_fill()
    lamput.circle(10)
    lamput.end_fill()

    lamput.penup()
    lamput.goto(20, 20)
    lamput.pendown()
    lamput.begin_fill()
    lamput.circle(10)
    lamput.end_fill()

    # Draw Lamput's pupils
    lamput.color("black")
    lamput.penup()
    lamput.goto(-20, 20)
    lamput.pendown()
    lamput.begin_fill()
    lamput.circle(5)
    lamput.end_fill()

    lamput.penup()
    lamput.goto(20, 20)
    lamput.pendown()
    lamput.begin_fill()
    lamput.circle(5)
    lamput.end_fill()
    
    # Draw Lamput's smile
    lamput.penup()
    lamput.goto(-20, -10)
    lamput.pendown()
    lamput.setheading(-60) 
    lamput.circle(20, 120) 

    # Hide the turtle
    lamput.hideturtle()

    screen.mainloop()

# Run the function to draw Lamput
draw_lamput()
