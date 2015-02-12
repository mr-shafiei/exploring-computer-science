---
title: Abstraction
---

# Abstraction

Abstraction is arguably the central idea of all of computer science. Computer programming is easy, as long as the programs are small. What’s hard isn’t the programming, but the keeping track of details in a huge program.

The solution is chunking, or layering – two metaphors for abstraction.

In other words, a complicated computer program can be divided into smaller parts that perform specific functions.



# Practical Abstraction Example

A classic example of abstraction is the car. Cars are made of nuts, bolts, metal rods, big metal blocks, rubber or paper gaskets, plastic containers for fluids, rivets, wires, and so on.

But if you’re trying to repair a car, you don’t think in those terms; if you did, you’d never find where the problem is. Instead you think about the bigger picture:  The engine, the alternator, the fuel injectors, the brakes, the transmission, and so on.

That’s abstraction.


# Abstraction and Technological Progress

The march of technological progress is, at least in part, a march toward greater and greater abstraction. Each step reduces the extent to which people have to think about details.

Sticking with cars as the example, in the early days, every driver had to be at least something of a mechanic, knowing how to deal with the rather frequent failures of the machinery. Before automatic transmissions, only people with some understanding of gear ratios could drive.

The automatic transmission made possible an enormous abstraction. All the complexity of the machinery that makes a car work was hidden under the surface of a very simple model: You push the pedal on the right and the car speeds up; you push the pedal on the left and it slows down. Suddenly just about anyone could drive a car.


# Interfaces

Those two pedals – the gas pedal and the brake – are an interface, also known as an abstraction barrier. On the driver’s side of the abstraction, what matters is the behavior provided by this interface. Push this one to speed up, that one to slow down.

Once that interface became standardized, further technical development has dramatically changed what happens up in the engine compartment. Originally, the gas pedal mechanically pushed a lever controlling a valve that determined the rate at which gasoline could flow into the engine. More gasoline, bigger explosions inside the engine, more power, so more speed.

Today, the gas pedal doesn’t really do anything mechanically, except provide an input to a computer inside the car, whose job is to control the fuel injection system. Your input is combined with other information about the car’s environment to operate smaller valves, one per cylinder, that control the gas/air mixture more precisely.

The brake pedal has had a similar history. Originally, your foot directly provided the power to push the brake pads against the wheels. Then a new mechanism was developed, preserving the interface – push here to slow down – but now using the pressure from your foot to operate a hydraulic system that does the hard work of pressing the pads against the wheels. But there was one important difference.

The first “power brakes,” like the modern gas pedal, completely eliminated the mechanical linkage between the pedal and the actual brakes. But after a few accidents in which people couldn’t stop their cars because the engine died, this design was modified. Today you have “power assisted brakes,” which means that your foot both operates a hydraulic cylinder and also directly puts pressure on the brakes. If the engine fails, you have to push a lot harder to stop the car, but at least it’s possible.

The latest development, anti-lock brakes, actually lets a computer in the car override your pressure on the brake pedal if you are in danger of putting the car into a skid by trying to stop too abruptly.

The point is that drivers who aren’t particularly interested in cars don’t have to know any of this. All they have to know is that you push the pedal on the right to speed up, and the one on the left to slow down! This interface has survived through several generations of underlying technology, because it’s a good interface – simple but expressive. Car engineers could have made each generation of new technology more visible to drivers, with lots of knobs and switches and readouts, but they wisely refrained, and stayed with the abstraction – the interface – developed a century ago.


# Abstraction in Computer Programming

How does abstraction work in computer programming? We’ll be revisiting this question all semester. But, for a starting point, think about the blocks in the Scratch menu.

Each block names a simple intention ("move 10 steps," for instance), comparable to “speed up” or “slow down” in a car. But the mechanisms that make those blocks do their job are actually doing very complicated detail work. 

For example, “move 10 steps” just tells the sprite to move over a little.  Simple and quick to use!

But there is a lot going on behind the scenes.

The picture you see on the screen is really a collection of tiny dots of light (called pixels).

“Move 10 steps” really means, "erase each of those pixels, then redraw them all in a different position."


But if the abstraction is working well, you’re not thinking about tiny dots of light at all while working in Scratch; you’re moving a cat!




_Adapted from material by Dr. Brian Harvey, UC Berkeley_