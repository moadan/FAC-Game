# FAC-Game
Pong game task 2/2


# Game

This document will explain the code and provide some insight into my learning during the game development. 

- HTML: The (canvas) element is a container which allows for the drawing of graphics and animations, using JavaScript.
(h1) for title.

- CSS: (canvas id="board") background-color, & border-top, bottom, styles. 


# Project, my understanding of the code.
Image-1: show's the dimentions of canvas starting at (0.0) point or X, Y. width & height of 500px. Also the positioning of the player paddle, which is boarderheight/2, size of the paddle is stored in a variable (playerHeight = 100;)

<img src="/img's%20readme/1.png" alt="" width="850" height="350">

Image-2: Ball starting point center, when ever the ball touches the boardHeight it revers.    

// if ball touches top or bottom of canvas<br>
    if (ball.y <= 0 || (ball.y + ball.height >= boardHeight)) {<br>
        ball.velocityY *= -1; //reverse direction<br> 
    }

<img src="/img's%20readme/2.png" alt="" width="850" height="350">


<img src="/img's%20readme/3.png" alt="" width="850" height="350">

# Project Inspiration



# Project in hindsight

