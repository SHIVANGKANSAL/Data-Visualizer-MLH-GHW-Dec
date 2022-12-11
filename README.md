# Data-Visualizer-MLH-GHW-Dec
Global Hack Week December Day 7: Build 2022 Day 7 Task: Build a Data Visualization

## Task Statement
Data science is one of the fastest growing fields in tech. There are so many different ways to visualize data. It can be as simple as a graph or as complex as a piece of art. Show off your visualization on the Day 7 Devpost when you’re finished.

## An Introduction
What's the connection between a dripping faucets, the Mandelbrot set, a population of rabbits, thermal convection in a fluid, and the firing of neurons in your brain?
It's this one simple equation -
![Logistic Map Equation](https://mathworld.wolfram.com/images/equations/LogisticMap/NumberedEquation2.gif)

(known as the discrete logistic equation or logistic map).

The logistic map is a one dimensional map that, for certain parameter values, can give rise to chaos; this lets us generate pseudo-random numbers from a deterministic process.

This equation defines the rules, or dynamics, of our deterministic system: x represents the population at any given time t, and r represents the growth rate. In other words, the population level at any given time is a function of the growth rate parameter and the previous time step’s population level. If the growth rate is set too low, the population will die out and go extinct. Higher growth rates might settle toward a stable value or fluctuate across a series of population booms and busts.
![](https://i2.wp.com/geoffboeing.com/wp-content/uploads/2015/03/logistic-model-line.png?resize=624%2C359&ssl=1)

As simple as this equation is, it produces chaos at certain growth rate parameters.

When we adjust the growth rate parameter beyond 3.5, we see the onset of chaos. A chaotic system has a strange attractor, around which the system oscillates forever, never repeating itself or settling into a steady state of behavior. It never hits the same point twice and its structure has a fractal form, meaning the same patterns exist at every scale no matter how much you zoom into it.

![](https://i2.wp.com/geoffboeing.com/wp-content/uploads/2015/03/logistic-bifurcation-full1.png?w=613&ssl=1)

Beyond a growth rate of 3.6, however, the bifurcations ramp up until the system is capable of eventually landing on any population value. This is known as the period-doubling path to chaos. As you adjust the growth rate parameter upwards,  the logistic map will oscillate between two then four then eight then 16 then 32 (and on and on) population values. These are periods, just like the period of a pendulum.

By the time we reach growth rate 3.9, it has bifurcated so many times that the system now jumps, seemingly randomly, between all population values. I only say seemingly randomly because it is definitely not random. Rather, this model follows very simple deterministic rules yet produces apparent randomness. This is chaos: deterministic and aperiodic.

![](https://i1.wp.com/geoffboeing.com/wp-content/uploads/2015/03/logistic-bifurcation-narrow1.png?w=616&ssl=1)

### Made By : Shivang Kansal
