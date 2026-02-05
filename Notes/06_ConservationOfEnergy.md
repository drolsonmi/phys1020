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

# Conservation of Energy

Reading:
* Chapter e4

Materials:
* PE cart
* Marble on track for Conservation of Energy
* Meter stick
* Tennis ball and Raquetball

Activities:
* Conservation of energy
    * Materials: Microwave, hot chocolate, cups, spoons

-----
## Law of Conservation of Energy
Two ways that energy can be added to a system:
- Doing work (moving an object)
- Adding heat to it

$$W + Q = \Delta (KE + PE + TE)$$

We often like to consider a system where no heat or work is applied:

$$W + Q = 0$$

When this happens, there will be no change in total energy:

$$\begin{align*}0 &= \Delta (KE + PE) \\ 0 &= KE_f + PE_f - KE_0 - PE_0 \\ KE_0 + PE_0 &= KE_f + PE_f \\ E_{\text{in}} &= E_{\text{out}}\end{align*}$$

The total amount of energy remains the same.

> Consider a pendulum with a mass of 0.050 kg (50 g) set with an initial height of 75 cm (0.75 m).
> * How much PE does it have?
> $$PE = mgh = 0.050~kg \times 9.8 \tfrac{m}{s^2} \times 0.75~m = 0.3675~J$$
> * At the bottom of the swing, how much PE does it have?
> $$PE = mgh = 0.050~kg \times 9.8 \tfrac{m}{s^2} \times (0)=0~J$$
> * Where did the energy go?
> $$\begin{align*}KE_0 + PE_0 &= KE_f + PE_f \\ 0 + mgh &= KE_f + 0 \\ 0.3675~J = KE_f\end{align*}$$
> * At the other side of the swing, it goes to a height of 75 cm and stops. How much PE does it have? How much KE does it have?
> $$PE_f = mgh_f = 0.050~kg \times 9.8 \tfrac{m}{s^2} \times 0.75~m = 0.3675~J$$
> $$\begin{align*}KE_0 + PE_0 &= KE_f + PE_f \\ 0 + 0.3675~J &= KE_f + 0.36775~J \\ 0 = KE_f\end{align*}$$


> Demo Video: [Walter Lewin’s pendulum demonstration](https://www.youtube.com/watch?v=77ZF50ve6rs)

> Water at the top of a 500-m hydroelectric dam goes over the spillway, how fast will the water be going when it reaches the bottom?
>
> $$\begin{align*}E_0 &= E_f \\ KE_0 + PE_0 &= KE_f + PE_f \\ PE_0 &= KE_f \\ mgh &= \frac{1}{2}mv^2 \\ gh &= \frac{1}{2}v^2 \\ \sqrt{2gh} &= v \\ \sqrt{2*9.8*500} &= v \\ 99.0 m/s &= v\end{align*}$$

The bottom line is that energy can be converted from one form to another. We utilize this to harness the energy and apply it to another format, sometimes through multiple steps.

> In-class activity 6: Map out the energy transfers needed to get the energy from the sun to grow an apple to give us energy after we eat it.
> * Solar energy (Nuclear energy) --> Sunlight (Radiant energy) --> ... (students complete)
> * Solar energy (NE) --> Sunlight (RE) --> Warmth in tree (TE) --> Growth of tree and fruit (CE) --> Apple is picked and eaten (KE) --> Once ingested, it provides energy to the body (CE and TE)

---

## Energy Conversion Efficiencies

> Demo: Rubber ball

Sometimes energy is not fully converted into a single type. A rubber ball does not bounce as high as the height it was dropped from.
* Work done by the floor squishes the ball and reintroduces thermal energy (TE)

Other external forces do work on the object, causing some energy to be lost (For example, energy is lost due to Friction/Air Resistance). __Efficiency__ measures how much energy is conserved in a conversion process:

$$\text{Efficiency} = \frac{\text{Energy output}}{\text{Energy input}} \times 100\%$$

> What was the efficiency of the bouncing ball:
>
> $$\text{Output} = PE_f = mgh_f \qquad \text{Input} = PE_0 = mgh_0$$
>
> $$eff = \frac{E_{out}}{E_{in}}*100\% = \frac{KE_f + PE_f}{KE_0 + PE_0}*100\% = \frac{PE_f}{PE_0}*100\%$$
> 

Sometimes we take advantage of energy losses to do work—for example, generating electricity. A fuel releases energy, and part of that energy is converted into useful work. It is impossible to recover 100% of the energy, so efficiency tells us how much we recover.

> A coal-burning power plant burns enough coal to release 650 MJ of energy. The electrical output from this plant is 260 MJ. What is the efficiency of this powerplant?
>
> $$E_{in} = 650 MJ \qquad E_{out} = 260 MJ \qquad eff = \frac{260 MJ}{650 MJ}*100\% = 40.0\%$$

However, it gets more complicated. Energy is often transfered from one form to another. When this happens, energy is often lost during each stage. The total efficiency will be the product of all the other efficiencies:

$$eff_{total} = eff_1 * eff_2 * eff_3 * \dots$$

> The electricity from the coal power plant loses 40% of its energy in the conversion from the coal to electricity. The electricity then has to pass through cables (70% efficiency), then through the converters to make your electricity usable (70% efficiency), then through the coils in your stove (30% efficiency), then through the pan and into your food (50% efficiency). What is the total efficiency? And how much of the original 650 MJ can potentially make it to your food?
>
> *Note*: 40% is "40 per cent" or "40 per 100". So, $40\% = \tfrac{40}{100} = 0.40$
>
> $$eff_{total} = 0.40 * 0.70 * 0.70 * 0.30 * 0.50 = 0.0294 = 2.94\%$$
>
> 2.94% of 650 MJ is,
>
> $$0.0294 * 650 MJ = 19.11 MJ$$