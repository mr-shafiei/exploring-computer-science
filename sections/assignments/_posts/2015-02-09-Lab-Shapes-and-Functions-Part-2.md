---
title:  Lab - Shapes and Functions (Part 2)
subtitle: 
due-date: 2015-02-12
type:  Lab
submission:  Dropbox
---

# Goals

- Practice developing an abstraction for drawing shapes
- Build a custom block (function) that takes input (arguments)
- Use the custom block as part of a larger program:


## Example (Draw Square):

<pre class="blocks">

    define Draw Square with sides (length) long
        Pen Down
        repeat (4)
            move (length) steps
            turn right (90) degrees
        end
        Pen Up
    

    When flag clicked
    point in direction (90 v)
    go to x:(0) y:(0)
    hide
    Repeat (36)
        Draw Square with sides (50) long
        Move (10) Steps
        Turn Right (10) degrees
    End

</pre>


### Output:

![drawsqaureprogram]({{ site.baseurl }}/media-library/2015/02/draw-sqaure-program.png)


[View In Scratch](http://scratch.mit.edu/projects/47362756/#editor)

---

# Instructions:

1. Replicate the program above
2. Build additional custom blocks that create:
    - Triangle
    - Hexagon
    - Circle (challenge!)
3. Try different combinations to create interesting and complex designs!


# Guiding Questions:

Are you stuck trying to create the triangle or hexagon?

Think about the following:

1. The <code class="blocks">Draw Square :: custom</code> function contained a move/turn sequence that repeated 4 times, once for each of the 4 sides of the square.
2. How many times would move/turn need to be repeated for a triangle?  How about a hexagon?
3. In <code class="blocks">Draw Square :: custom</code>, the turn command was set to 90 degrees <code class="blocks">turn right (90) degrees</code>.  For an equilateral triangle, what would the angle need to be?  What about for a hexagon?








