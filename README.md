import turtle

pen=turtle.turtle()

def curve():
    fort i in range(200):
          pen.right(1)
          pen.forward(1)

def heart():
    pen.fillcolor('red')
    pen.begin_fill()
    pen.left(140)
    pen.forward(113)
    curve()
    pen.left(120)
    curve()
    pen.forward(120)
    pen.end_fill()

    def text1():
    pen.up()
    pen.setpos(-68,95)
    pen.down()
    pen.color('yellow')
    pen.write("I love you")

 heart()
         text1()
         pen.ht()
