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
