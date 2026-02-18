<head>
<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    displayMath: [['$$', '$$'], ['\\[', '\\]']]
  }
};
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>

# Heat Engines
Reading:
* Textbook sections 

Materials:
* Stirling engine, Heating pot, Warm cup
* Steam engine
* Bouncy ball
* Balance scale, objects to represent energy (1-g blocks, coins, etc.)

A __heat engine__ is a machine that utilizes the flow of heat to do work
* There needs to be a difference in temperatures for heat to flow
    * Hot Reservoir – Body with more energy (Hot temperature)
      * Also referred to as a __source__, or the body from which energy is transferred
    * Cold Reservoir – Body with less energy (Cold temperature)
      * Also referred to as a __sink__, or the body that absorbs the energy released by the source
* Picture a balloon filled up. If I open it, what happens? (air flows out) Why? (difference in pressures) The difference in pressures pushes the air out. Can we make the air flow out if we get rid of the difference in pressure? No.
  * Similarly, thermal energy flows from high energy (hot source) to low energy (cold sink).
  * Without this difference in temperature, there is no flow of energy. And if we try to remove the cold sink, there is no flow of energy
* Energy is conserved in the energy transfer process

$$E_0=E_f \qquad\to\qquad E_{out}=E_{in} \qquad\to\qquad Q_H=W+Q_C$$

We can utilize this flow of energy to accomplish work:   $W = Q_H - Q_C$

> Demo: Sterling Engine (Leave running until we talk about Entropy)

Can we ever convert 100% of the heat from the hot source to work? (We’ll revisit this question after we talk about the 2nd Law of Thermodynamics)

Examples of Heat Engines
* > Demo: Steam Engine (Leave running until we talk about Entropy)
* A car’s engine
  > Demo: Adiabatic Compression = Spontaneous Combustion
* OTEC

## Second Law of Thermodynamics
All of these heat engines require an exchange of heat from a hot reservoir to a cold reservoir. Why can’t we have energy flow from the cold reservoir to the hot reservoir?
> Bouncy ball – whenever I drop and let it keep going, it bounces to a lower height until it stops bouncing.
> * Where did the energy go?
> *  Why can’t it ever go higher after a bounce?

The __2nd Law of Thermodynamics__ states that,
1. Heat can flow spontaneously (by itself) only from a hot source to a cold sink
2. No heat engine can be constructed in which heat from a hot source is converted entirely to work. Some heat has to be discharged to a sink at a lower temperature

A common term to describe the 2nd law is __entropy__. We commonly say that entropy is a state of disorder, but what does that mean?

Textbook definition: 
* A measure of the unavailability of a system’s thermal energy for conversion to mechanical work. (Still not helpful)

> Demo: Take the balance scale.
> * Imagine one side represents hot objects (lots of energy = lots of blocks/coins/…). The other side represents cold objects (less energy = fewer blocks/coins/…).
> * Over time, energy will naturally flow from hot to cold, and will continue until the energy is in equilibrium (balance)
>   * Occasionally, some energy does flow cold to hot, but more energy will flow hot to cold
> * __The increase in balance of energy is known as entropy__
> * If the energy flows the other way, then the hot side gets hotter, and the cold side gets colder. This is moving away from equilibrium (becomes less balanced). This is a __decrease in entropy__.

Which way does energy flow naturally? (Think of ice in a cup: Ice is the cold side, water is the hot side) The 2nd Law of Thermodynamics explains that entropy will always increase (energy will become more balanced).

Can we ever make the entropy decrease?
* The bouncy ball lost energy over time and eventually remains on the ground. I could put the energy back in, but in order to do that, I would have to use my own energy to pick it up. I can do that because I have more energy then the ball, and energy flows from high sources to cold sinks. The result is that even though energy has been put back into the ball, I have lost energy myself. 
* In the Sterling engine, the energy of the wheel came from the transfer energy from the hot cup to the cold side of the engine. In theory, I could reverse that process and put the energy back into the hot cup. However, in order to do that, I would need to do work on my own to force the energy back.
* As long as I have more energy than the hot cup, I could force energy back into the hot cup. But by doing this, I become part of the system, and after forcing energy back for a certain amount of time, my energy starts to run out. I can only decrease entropy if I increase my own.
* That is what the concept of entropy is describing. The balance of energy. The more that energy is transferred, the less energy we will have that is able to be transferred. At some time in the far distant future, theory states that all objects in the universe will have exactly the same amount of energy. When that happens, energy cannot be converted from one form to another anymore. However, this won't happen for trillions of trillions of trillions of years. 

Examples of how to force entropy to decrease:
* Refrigerator
* Air Conditioner

Can we ever convert 100% of the heat from the hot source to work?
* Often what we think of as “waste heat” is just energy flowing to the cold sink
* 2nd Law of Thermodynamics says energy has to flow hot to cold
* If there is no cold sink, then there is no flow, and if there’s no flow, we can’t get work
  * Think of a bike going downhill with a battery attached to the wheel - as the wheel rotates, the battery charges
  * The larger the slope, the more energy you can extract.
    * Likewise, the larger the difference in temperatures, the more work you can use from the process
  * If you take away the slope, you can't extract any energy.
    * Likewise, if you don't have a cold sink, there isn't anywhere for the energy to start flowing to, and if there is no flow, we can't do any work.

[Image: Heat Engine]

What is the most efficient we can ever get?
* The efficiency of a heat engine is:

$$Efficiency = \frac{Work~Out}{Energy~In}=\frac{W}{Q_H} \times 100\% \qquad Eff = \frac{Q_H-Q_C}{Q_H} \times 100%$$

* The maximum efficiency reduces this heat down to temperatures

$$Eff_max=\frac{T_H-T_C}{T_H}\times 100\%$$
  
*__Note__: To use this equation, the temperatures HAVE to be in Kelvin.*
