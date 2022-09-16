# Bouncing Balls

### <u>START</u>
### <u>INIT OBJECTS:</u>
> - **CREATE** Canvas
> - **CREATE** randomRgb
> - **CREATE** Ball


### <u>PROPERTIES OF OBJECTS:</u>
> - **Canvas**
>   - width is the width of screen
>   - Height is the height of screen

> - **RandomRgb**:
>   - min
>   - max

> - **Ball**:
>   - x
>   - y 
>   - velX
>   - velY
>   - color
>   - size

### <u>METHODS OF OBJECTS:</u>
> - **Canvas**
>   - Renders canvas on screen
>   - Gives balls an area to be drawn on



> - **RandomRgb**
>   - Returns a random integer between the min and the max paramters.
>   - Change colors of Balls random.

> - **Ball:**
>   - draw the ball on the canvas
>   - update the x and y values. 
>   - collision detect 
### <u>LOGIC:</u>
```
IF Ball x > width of screen
    Ball will bounce off the parimeter by inverting x

IF Ball y > hright of screen
    Ball will bounce off the parimeter by inverting y

IF distance between x&y balls distance == 0
    Change color
```

