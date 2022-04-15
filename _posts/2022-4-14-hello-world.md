---
title:  "Hello world"
toc: true
toc_label: "Table of Contents"
toc_sticky: true
---
Hello :3 
# Tui là ai :> ?
Nothing here
# Đây là đâu =))) ?
??????????????
### Hm :))) ?

`testing`

```cpp
int main() {
    std::cout << "Hello world";
    //testingggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggg
}
```

```python
import turtle
import winsound
import time

window = turtle.Screen()
window.title("Pong")
window.bgcolor("black")
window.setup(width=600, height=400)
window.tracer(0, 0)

# Score
lose = 0

# Paddle AI
paddle_AI = turtle.Turtle()
paddle_AI.speed(0)
paddle_AI.shape("square")
paddle_AI.color("white")
# paddle_AI.shapesize(stretch_wid=5,stretch_len=1)
paddle_AI.penup()
paddle_AI.goto(-250, 0)

# Paddle Player
paddle_player = turtle.Turtle()
paddle_player.speed(0)
paddle_player.shape("square")
paddle_player.color("white")
paddle_player.shapesize(stretch_wid=5,stretch_len=1)
paddle_player.penup()
paddle_player.goto(250, 0)

# Ball
ball = turtle.Turtle()
ball.speed(0)
ball.shape("square")
ball.color("white")
ball.penup()
ball.goto(0, 0)
ball.dx = 2
ball.dy = 2

# Pen
pen = turtle.Turtle()
pen.speed(0)
pen.shape("square")
pen.color("white")
pen.penup()
pen.hideturtle()
pen.goto(0, 160)
pen.write("You lose : {}".format(lose), align="center", font=("Calibri", 24, "normal"))

# Functions
def paddle_AI_up():
    y = paddle_AI.ycor()
    y += 5
    paddle_AI.sety(y)

def paddle_AI_down():
    y = paddle_AI.ycor()
    y -= 5
    paddle_AI.sety(y)

def paddle_player_up():
    if paddle_player.ycor() < 150:
        y = paddle_player.ycor()
        y += 5
        paddle_player.sety(y)

def paddle_player_down():
    if paddle_player.ycor() > -140:
        y = paddle_player.ycor()
        y -= 5
        paddle_player.sety(y)
```

> Mình viết lại những gì tuổi trẻ mình đi, mình học, mình trải nghiệm để sau này khi lớn lên mình có thể nhìn lại được một chặng đường thật dài mình đã đi qua.