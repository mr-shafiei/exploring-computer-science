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


## Example:

<pre class="blocks">

    define Draw Square with sides (length) long
        repeat (4)
            move (length) steps
            turn right (90) degrees
        end
    

    When flag clicked
    Repeat (36)
        Draw Square with sides (50) long
        Move (10) Steps
        Turn Right (10) degrees
    End

</pre>

# Instructions

Build custom blocks (functions) to draw different shapes of different sizes:

- Square (Tutorial Below)
- Triangle (Figure it out!)
- Hexagon (Figure it out!)
- Circle (Challenge!)


Then, use those functions as a part of a bigger program.


---
<pre class="blocks">
    define Draw Square

</pre>


# Tutorial

## Step 1:  Create a new