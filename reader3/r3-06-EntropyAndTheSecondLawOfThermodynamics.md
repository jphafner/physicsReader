---
layout: ebook
title: Entropy and the Second Law of Thermodynamics
author: Kenneth W. Ford
exerpt: Changes in the visible world are often the result of the rule of probability at work in the submicroscopic world.
    A survey of principles of probability, reasons why there are no perpetual-motion machines, entropy and time's arrow&mdash;and much else.
intro: An excerpt from his book <em>Basic Physics</em>, 1968.
---


As profound as any principle in physics is the second law of thermodynamics.
Based on uncertainty and probability in the submicroscopic world, it accounts for definite rules of change in the macroscopic world. We shall approach this law, and a new concept, entropy, that goes with it, by considering some aspects of probability.
Through the idea of probability comes the deepest understanding of spontaneous change in nature.

## Probability in nature
\label{sec:14.1}

When a spelunker starts down an unexplored cavern, he does not know how far he will get or what he will find. When a gambler throws a pair of dice, he does not know what number will turn up.
When a prospector holds his Geiger counter over a vein of uranium ore, he does not know how many radioactive particles he will count in a minute, even if he counted exactly the number in a preceding minute.
These are three quite different kinds of uncertainty, and all of them are familiar to the scientist.


The spelunker cannot predict because of total ignorance of what lies ahead.
He is in a situation that, so far as he knows, has never occurred before.
He is like a scientist exploring an entirely new avenue of research.
He can make educated guesses about what might happen, but he can neither say what will happen, nor even assess the probability of any particular outcome of the exploration.
His is a situation of uncertain knowledge and uncertain probability.
The gambler is in a better position. He has uncertain knowledge but certain probability.
He knows all the possible outcomes of his throw and knows exactly the chance that any particular outcome will actually occur.
His ignorance of any single result is tempered by a definite knowledge of average results.

The probability of atomic multitudes, which is the same as the probability of the gambler, is at the heart of this chapter.
It forms the basis for the explanation of some of the most important aspects of the behavior of matter in bulk.
This kind of probability we can call a probability of ignorance&mdash;not the nearly

<figure id="fig14-1">
<figcaption>
    A tray of coins, a system governed by laws of probability.
</figcaption>
</figure>

total ignorance of the spelunker in a new cave or the researcher on a new frontier, but the ignorance of certain details called initial conditions.
If the gambler knew with enough precision every mechanical detail of the throw of the dice and the frictional properties of the surface onto which they are thrown (the initial conditions) he could (in principle) calculate exactly the outcome of the throw.
Similarly, the physicist with enough precise information about the where-abouts and velocities of a collection of atoms at one time could (with an even bigger &ldquo;in principle&rdquo; [^1]) calculate their exact arrangement at a later time.
Because these details are lacking, probability necessarily enters the picture.


The prospector's uncertainty is of still a different kind. 
He is coming up against what is, so far as we now know, a fundamental probability of nature, a probability not connected with ignorance of specific details, but rather connected with the operation of the laws of nature at the most elementary level.
In atomic and nuclear events, such as radioactivity, probability plays a role, even when every possible initial condition is known.
This fundamental probability in nature, an essential part of the theory of quantum mechanics, is pursued in Chapter Twenty-Three.
In thermodynamics&mdash;the study of the average behavior of large numbers of molecules and of the links between the submicroscopic and macroscopic worlds&mdash;the fundamental probability in nature is of only secondary importance.
It influences the details of individual atomic and molecular collisions, but these details are unknown in any case. 
Of primary importance is the probability of ignorance stemming from our necessarily scant knowledge of precise details of molecular motion.


The triumphs of thermodynamics are its definite laws of behavior for systems about which we have incomplete knowledge.
However, it should be no surprise that laws of probability applied to large enough numbers can become laws of near certainty.
The owners of casinos in Nevada are consistent winners.

## Probability in random events

We turn our attention now to a system that at first sight has little to do with molecules, temperature, or heat.
It is a tray of coins ([Figure 14-1](#fig14-1)).
For the purposes of some specific calculations, let us suppose that the tray contains just five coins. 
For this system we wish to conduct a hypothetical experiment and make some theoretical predictions.
The experiment consists of giving the tray a sharp up-and-down motion so that all the coins flip into the air and land again in the tray, then counting the number of heads and tails displayed, and repeating this procedure many times.
The theoretical problem is to predict how often a particular arrangement of heads and tails will appear.


<figure id="tab14-1">
<table>
  <tr>
    <th>Coin 1</th>
    <th>Coin 2</th>
    <th>Coin 3</th>
    <th>Coin 4</th>
    <th>Coin 5</th>
    <th></th>
  </tr>
  <tr><td>H</td><td>H</td><td>H</td><td>H</td><td>H</td><td>1 way to get 5 heads</td></tr>
  <tr><td>H</td><td>H</td><td>H</td><td>H</td><td>T</td><td>1 way to get 5 heads</td></tr>

Coin 1 & Coin 2 & Coin 3 & Coin 4 & Coin 5 &  \\
\midrule
H & H & H & H & H & 1 way to get 5 heads  \\
\midrule
H & H & H & H & T & 5 ways to get 4 heads and 1 tail \\
H & H & H & T & H & \\
H & H & T & H & H & \\
H & T & H & H & H & \\
T & H & H & H & H & \\
\midrule
H & H & H & T & T & 10 ways to get 3 heads and 2 tails \\
H & H & T & H & T &  \\
H & T & H & H & T &  \\
T & H & H & H & T &  \\
H & H & T & T & H &  \\
H & T & H & T & H &  \\
T & H & H & T & H &  \\
H & T & T & H & H &  \\
T & H & T & H & H &  \\
T & T & H & H & H &  \\
\midrule
H & H & T & T & T & 10 ways to get 2 heads  and 3 tails \\
H & T & H & T & T &  \\
H & T & T & H & T &  \\
H & T & T & T & H &  \\
T & H & H & T & T &  \\
T & H & T & H & T &  \\
T & H & T & T & H &  \\
T & T & H & H & T &  \\
T & T & H & T & H &  \\
T & T & T & H & H &  \\
\midrule
H & T & T & T & T & 5 ways to get 1 head  and 4 tails \\
T & H & T & T & T & \\
T & T & H & T & T & \\
T & T & T & H & T & \\
T & T & T & T & H & \\
\midrule
T & T & T & T & T & 1 way to get 5 tails  \\
</table>
<figcaption>
    Table 14-1 Possible Arrangements of Five Coins
</figcaption>
</figure>

The experiment you can easily carry out yourself.
Be sure that the tray is shaken vigorously enough each time so that at least some of the coins flip over.
Here let us be concerned with the theory.
To begin, we enumerate all possible ways in which the coins can land.
This is done pictorially in [Table 14-1](#tab14-1).
There are 32 possible results of a tray shaking. [^2]
If all we do is count heads and tails without identifying the coins, the number of possible results is 6 instead of 32 ([Table 14-1](#tab14-1)).
Ten of the ways the coins can land yield three heads and two tails.
There are also ten different ways to get three tails and two heads.
Both four heads and one tail and four tails and one head can be achieved in five ways.
Only one arrangement of coins yields five heads, and only one yields five tails.
These numbers do not yet constitute a prediction of the results of the experiment.
We need a postulate about the actual physical process, and a reasonable one is a postulate of randomness: that every coin is equally likely to land heads up or tails up and that every possible arrangement of the five coins is equally Jikely.
This means that after very many trials, every entry in [Table 14-1](#tab14-1) should have resulted about 1/32 of the time.
Note, however, that equal probability for each arrangement of coins is not the same as equal probability for each possible number of heads or tails.
After 3,200 trials, for example, we would expect to have seen five heads about 100 times, but three heads and two tails should have showed up ten times more frequently, about 1,000 times.
The exact number of appearances of five heads or of three heads and two tails or of any other combination cannot be predicted with certainty.
What can be stated precisely (provided the postulate of randomness is correct) are probabilities of each such combination.

<figure id="tab14-2">
<table>
  <tr>
    <th>&#8470; Heads</th>
    <th>&#8470; Tails</th>
    <th>Probability</th>
  </tr>
  <tr> <td>5</td> <td>0</td> <td>1/32 = 0.031</td> </tr>
  <tr> <td>4</td> <td>1</td> <td>5/32 = 0.156</td> </tr>
  <tr> <td>3</td> <td>2</td> <td>10/32 = 0.313</td> </tr>
  <tr> <td>2</td> <td>3</td> <td>10/32 = 0.313</td> </tr>
  <tr> <td>1</td> <td>4</td> <td>5/32 = 0.156</td> </tr>
  <tr> <td>0</td> <td>5</td> <td>1/32 = 0.031</td> </tr>
</table>
<figcaption>
    Probabilities for Different Numbers of Heads and Tails When Five Coins Are Flipped
</figcaption>
</figure>

Shown in [Table 14-2](#tab14-2) are the basic probabilities for all the possible numbers of heads and tails that can appear in a single trial.
It is interesting to present these numbers graphically also, as is done in [Figure 14-2](#fig14-2).
The probability of a certain

<figure id="fig14-2">
<figcaption>
    Probabilities for various results of tray-shaking experiment with five coins.
</figcaption>
</figure>

<figure id="fig14-3">
<figcaption>
    Probabilities for various results of tray-shaking experiment with ten coins.
</figcaption>
</figure>

number of heads plotted vs. the numbers of heads gives a bell-shaped curve, high in the middle, low in the wings.

<figure id="tab14-3">
<table>
  <tr>
    <th>&#8470; Heads</th>
    <th>&#8470; Tails</th>
    <th>Probability</th>
  </tr>
  <tr> <td>10</td> <td>0</td> <td>1/1024 = 0.0010</td> </tr>
  <tr> <td>9</td> <td>1</td> <td>10/1024 = 0.0098</td> </tr>
  <tr> <td>8</td> <td>2</td> <td>45/1024 = 0.0439</td> </tr>
  <tr> <td>7</td> <td>3</td> <td>120/1024 = 0.1172</td> </tr>
  <tr> <td>6</td> <td>4</td> <td>210/1024 = 0.2051</td> </tr>
  <tr> <td>5</td> <td>5</td> <td>252/1024 = 0.2460</td> </tr>
  <tr> <td>4</td> <td>6</td> <td>210/1024 = 0.2051</td> </tr>
  <tr> <td>3</td> <td>7</td> <td>120/1024 = 0.1172</td> </tr>
  <tr> <td>2</td> <td>8</td> <td>45/1024 = 0.0329</td> </tr>
  <tr> <td>1</td> <td>9</td> <td>10/1024 = 0.0098</td> </tr>
  <tr> <td>0</td> <td>10</td> <td>1/1024 = 0.0010</td> </tr>
  <tr> <td> </td> <td> </td> <td>Total Probability = 1.000</td></tr> 
  <!--\multicolumn{2}{l}{Total probability} & $=1.00$ \\ -->
</table>
<figcaption>
    Table 14-3. Probabilities for Different Numbers of Heads and Tails When Ten Coins Are Flipped.
</figcaption>
</figure>


The same kind of calculation, based on the postulate of randomness can be carried out for any number of coins.
For ten coins, the basic probabilities are given in [Table 14-3](#tab14-3) and in [Figure 14-3](#fig14-3). [^3]
Two changes are evident.
First, the probability of all heads or all tails is greatly reduced.
Second, the bell-shaped probability curve has become relatively narrower.
The greater the number of coins, the less likely is it that the result of a single trial will be very different from an equal number of heads and tails.
To make this point clear, the probability curve for a tray of 1,000 coins is shown in [Figure 14-4](#fig14-4).
The chance of shaking all heads with this many coins would be entirely negligible even after a lifetime of trying.
As [Figure 14-4](#fig14-4) shows, there is not even much chance of getting a distribution as unequal as 450 heads and 550 tails.

The tendency of the probabilities to cluster near the midpoint of the graph, where the number of heads and the number of tails are nearly equal, can be characterized by a &ldquo;width&rdquo; of the curve. The width of the curve is defined to be the distance between a pair of points (see [Figure 14-3](#fig14-3) and [Figure 14-4](#fig14-4)) outside of which the probabilities are relatively small and inside of which the probabilities are relatively large.
Exactly where these points are chosen is arbitrary.
One convenient choice is the pair of points where the probability has fallen to about one third of its central value&mdash;more exactly to $\frac{1}{e} = \frac{1}{2.72}$ of its central value.
The reason for defining a width is this: It spans a region of highly probable results.
After the tray is shaken, the number of heads and the number of tails are most likely to correspond to a point on the central part of the curve within its width.
The distribution of heads and tails is unlikely to be so unequal as to correspond to a point on the curve outside of this central region. When the number of coins is reasonably large (more than 100), there is a particularly simple formula for the width of the probability curve.
If <span class="math">C</span> is the number of heads (or tails) at the center of the curve, the width <span class="math">W</span> of the curve is given by

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s=16t^{2}" display="block", id="eq14-1">
  <mrow>
    <mi>W</mi>
    <mo>=</mo>
    <mrow>
      <mn>2</mn>
      <mo>&InvisibleTimes;</mo>
      <msqrt>
        <mi>C</mi>
      </msqrt>
    </mrow>
  </mrow>
</math>


The half-width, that is, the distance from the midpoint to the $\frac{1}{e}$ point of the curve, is equal to VC. This simple square root law is the reason for the particular factor $\frac{1}{e}$ used to define the width.
With this choice the probability for the result of a tray-shaking to lie within the width of the curve is 84 percent.

In [Figure 14-4](#fig14-4) the value of <span class="math">C</span>, the midpoint number of heads, is 500.
The square root of <span class="math">C</span> is roughly 22.
Thus the width of the curve is about 44, extending from

<figure id="fig14-4">
<figcaption>
    Probabilities for various results of tray-shaking experiment with 1,000 coins.
</figcaption>
</figure>

500&minus;22=478 to 500+22=522.
The total chance for a result to lie within this span is 84 percent; to lie outside it, 16%.

An important consequence of the square-root law is to sharpen the probability curve as the number of coins increases.
The ratio of the width to the total number of coins <span class="math">N (N=2C)</span> is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{W}{N} = \frac{2\sqrt{C}}{2C} = \frac{1}{\sqrt{C}}" display="block", id="eq14-2">
  <mrow>
    <mfrac>
      <mi>W</mi>
      <mi>N</mi>
    </mfrac>
  </mrow>
  <mo>=</mo>
  <mrow>
    <mfrac>
      <mrow>
        <mn>2</mn>
        <msqrt>
          <mi>C</mi>
        </msqrt>
      </mrow>
      </mrow>
        <mn>2</mn>
        <mi>C</mi>
      </mrow>
    </mfrac>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mn>1</mn>
        <msqrt>
          <mi>C</mi>
        </msqrt>
      </mfrac>
    </mrow>
  </mrow>
</math>

This ratio decreases as <span class="math">C</span> (or <span class="math">N</span>) increases.
For 100 coins, the width-to-number ratio is about 1/10.
For 1,000 coins, it is about 1/32.
For 1,000,000 coins, it is 1/1,000.
If the number of coins could be increased to be equal to the number of molecules in a drop of water, about 10<sup>22</sup>, the width-to-number ratio of the probability curve would be 1/10<sup>11</sup>.
Then the result of vigorous shaking of the coins would produce a number of heads and a number of tails unlikely to differ from equality by more than one part in one hundred billion.
The probability curve would have collapsed to a narrow spike ([Figure 14-5](#fig14-5)).

Two more points of interest about these head-and-tail probabilities will bring us closer to the connection between trays of coins and collections of molecules.
First is the relation between probability and disorder.
Ten coins arranged as all heads can be considered as perfectly orderly, as can an array of all tails.
Five heads and five tails, on the other hand, arranged for example as HHTHTTTHTH or as TTHTHTHHHT, form a disorderly array.
Evidently a high state of order is associated with low probability, a state of disorder is associated with high probability.
This might be called the housewife's rule: Order is improbable, disorder is probable.
The reason this is so is exactly the same for the household as for the tray of coins.
There are many more different ways to achieve disorder than to achieve order.

The second point of special interest concerns the way probabilities change in time.
If a tray of 1,000 coins is carefully arranged to show all heads, and is then shaken repeatedly, its arrangement will almost certainly shift in the direction of nearly equal numbers of heads and tails.
The direction of spontaneous change will be from an arrangement of low probability to an arrangement of high

<figure id="fig14-5">
<figcaption>
    For 10<sup>22</sup> coins, the probability curve is a spike much narrower even than the line on this graph.
</figcaption>
</figure>

probability, from order to disorder.
The same will be true whenever the initial arrangement is an improbable one, for instance 700 tails and 300 heads.
If instead we start with 498 heads and 502 tails, no amount of shaking will tend to move the distribution to a highly uneven arrangement.
This can be considered an equilibrium situation.
Repeated trials will then produce results not very different from the starting point.
Clearly there is a general rule here&mdash;a rule of probability, to be sure, not an absolute rule: Under the action of random influences, a system tends to change from less probable arrangements to more probable arrangements, from order to disorder.
The generalization of this rule from trays of coins to collections of molecules, and indeed to complex systems of any kind, is the second law of thermodynamics&mdash;a law, as we shall see, with remarkably broad and important consequences.

## Probability of position
\label{sec:14.3}

Most of the large-scale properties of substances are, when examined closely enough, probabilistic in nature.
Heat and temperature are purely macroscopic concepts that lose their meaning when applied to individual atoms and molecules, for any particular molecule might have more or less energy than the average, or might contribute more or less than the average to a process of energy exchange.
Temperature is proportional to an average kinetic energy;
    heat is equal to a total energy transferred by molecular colhsion.
Because of our incomplete knowledge about the behavior of any single molecule, and the consequent necessity of describing molecular motion in probabilistic terms, neither of these thermal concepts is useful except when applied to numbers so large that the laws of probability become laws of near certainty.
The same can be said of other concepts such as pressure and internal energy.


A single molecule is characterized by position, velocity, momentum, and energy.
Of these, position is the simplest concept and therefore the one for which it is easiest to describe the role of probability. Consider, for instance, an enclosure&mdash;perhaps the room you are in&mdash;divided by a screen into two equal parts.
What is the relative number of molecules of air on the two sides of the screen?
Not a hard question, you will say.
It is obvious that the two halves should contain equal, or very nearly equal, numbers of molecules. But here is a harder question.
Why do the molecules divide equally?
Why do they not congregate, at least some of the time, in one corner of the room?
The answer to this question is exactly the same as the answer to the question:
    Why does a tray of coins after being shaken display approximately equal numbers of heads and tails?
The equal distribution is simply the most probable distribution.
Any very unequal distribution is very improbable.


The mathematics of molecules on two sides of a room proves to be identical to the mathematics of coins on a tray.
By the assumption of randomness, every single molecule has an equal chance to be on either side of the room, just as every coin has an equal chance to land as heads or as tails.
There are many different ways to distribute the molecules in equal numbers on the two sides, but only one way to concentrate them all on one side.
If a room contained only five molecules, it would not be surprising to find them sometimes all on a single side.
The probability that they be all on the left is 1/32 (see [Table 14-1](#tab14-1)), and there is an equal probability that they be all on the right.
The chance of a 3-2 distribution is 20/32, or nearly two thirds.
Even for so small a number as five, a nearly equal division is much more likely than a very uneven division.
For 1O<sup>28</sup> molecules, the number in a large room, the distribution is unlikely to deviate from equality by more than one part in 10<sup>14<sup>.
The probability for all of the 10<sup>8</sup> molecules to congregate spontaneously in one half of the room is less than

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="10^{-10^{+27}}" display="block", id="eq14-2">
  <mrow>
    <mn>10</mn>
    <msup>
      <mrow>
        <mo>&minus;</mo>
        <mfenced>
          <msup>
            <mn>10</mn>
            <mn>+27</mn>
          </msup>
        </mfenced>
      </mrow>
    </msup>
  </mrow>
</math>

This number is too small even to think about.
Suddenly finding ourselves gasping for breath in one part of a room while someone in another part of the room is oversupplied with oxygen is a problem we need not be worried about.


The second law of thermodynamics is primarily a law of change.
It states that the direction of spontaneous change within an isolated system is from an arrangement of lower probability to an arrangement of higher probability.
Only if the arrangement is already one of maximal probability will no spontaneous change occur.
Air molecules distributed uniformly in a room are (with respect to their position) in such a state of maximal probability.
This is an equilibrium situation, one that has no tendency for spontaneous change.
Nevertheless it is quite easy through external actions to depart from this equilibrium to a less probable arrangement.
Air can be pumped from one side of the room to the other.
In a hypothetical vacuum-tight room with an impenetrable barrier dividing it in half, almost all of the air can be pumped into one half.
When the barrier is punctured, the air rushes to equalize its distribution in space.
This behavior can be described as the result of higher pressure pushing air into a region of lower pressure.
But it can equally well be described as a simple consequence of the second law of thermodynamics.
Once the barrier is punctured or removed, the air is free to change to an arrangement of higher probability, and it does so promptly.


It is worth noting that frequent molecular colhsions play the same role for the air as tray-shaking plays for the coins.
A stationary tray displaying all heads would stay that way, even though the arrangement is improbable.
If molecules were quiescent, they would remain on one side of a room once placed there.
Only because of continual molecular agitation do the spontaneous changes predicted by the second law of thermodynamics actually occur.

## Entropy and the second law of thermodynamics
\label{sec:14.4}

There are a variety of ways in which the second law of thermodynamics can be stated, and we have encountered two of them so far:
    (1) For an isolated system, the direction of spontaneous change is from an arrangement of lesser probability to an arrangement of greater probability;
    and (2) for an isolated system, the direction of spontaneous change is from order to disorder. Like the conservation laws, the second law of thermodynamics applies only to a system free of external influences.
For a system that is not isolated, there is no principle restricting its direction of spontaneous change.

A third statement of the second law of thermodynamics makes use of a new concept called entropy.
Entropy is a measure of the extent of disorder in a system or of the probability of the arrangement of the parts of a system.
For greater probability, which means greater disorder, the entropy is higher.
An arrangement of less probability (greater order) has less entropy.
This means that the second law can be stated:
    (3) The entropy of an isolated system increases or remains the same.

Specifically, entropy, for which the usual symbol is <span class="math">S</span>, is defined as Boltzmann's constant multiplied by the logarithm of the probability of any particular state of the system:

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="S = k \log{P}" display="block", id="eq14-3">
  <mrow>
    <mi>S</mi>
    <mo>=</mo>
    <mrow>
      <mi>k</mi>
      <mo>&InvisibleTimes;</mo>
      <mo>log</mo>
      <mfenced>
        <mi>P</mi>
      </mfenced>
    </mrow>
  </mrow>
</math>

The appearance of Boltzmann's constant <span class="math">k</span> as a constant of proportionality is a convenience in the mathematical theory of thermodynamics, but is, from a fundamental point of view, entirely arbitrary.
The important aspect of the definition is the proportionality of the entropy to the logarithm of the probability <span class="math">P</span>.
Note that since the logarithm of a number increases when the number increases, greater probability means greater entropy, as stated in the preceding paragraph.

Exactly how to calculate a probability for the state of a system (a procedure that depends on the energies as well as the positions of its molecules) is a complicated matter that need not concern us here.
Even without this knowledge, we can approach an understanding of the reason for the definition expressed by [Equation 14-3](#eq14-3).
At first, entropy might seem to be a superfluous and useless concept, since it provides the same information about a system as is provided by the probability <span class="math">P</span>, and <span class="math">S</span> grows or shrinks as <span class="math">P</span> grows or shrinks.
Technically these two concepts are redundant, so that either one of them might be considered superfluous.
Nevertheless both are very useful.
(For comparison, consider the radius and the volume of a sphere; both are useful concepts despite the fact that they provide redundant information about the sphere.)
The valuable aspect of the entropy concept is that it is additive.
For two or more systems brought together to form a single system, the entropy of the total is equal to the sum of the entropies of the parts.
Probabilities, by contrast, are multiplicative.
If the probability for one molecule to be in the left half of a container is 1/2, the probability for two to be there is I, and the probability for three to congregate on one side is 1/2.
If two containers, each containing three molecules, are encompassed in a single system, the probability that the first three molecules are all on the left side of the first container and that the second three are also on the left side of the second container is 1/8 &times; 1/8 = 1/64.
On the other hand, the entropy of the combination is the sum of the entropies of the two parts.
These properties of addition and multiplication are reflected in the definition expressed by [Equation 14-3](#eq14-3).
The logarithm of a product is the sum of the logarithm of the factors:

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="S_{total} = k \log{P_1P_2} = k \log{P_1} + k \log{P_2} = S_1 + S_2." display="block", id="eq14-4">
  <mrow>
    <msub>
      <mi>S</mi>
      <mtext>total</mtext>
    </msub>
    <mo>=</mo>
    <mrow>
      <mi>k</mi>
      <mo>&InvisibleTimes;</mo>
      <mo>log</mo>
      <mfenced>
        <msub>
          <mi>P</mi>
          <mn>1</mn>
        </msub>
        <msub>
          <mi>P</mi>
          <mn>2</mn>
        </msub>
      </mfenced>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mi>k</mi>
        <mo>&InvisibleTimes;</mo>
        <mo>log</mo>
        <mfenced>
          <msub>
            <mi>P</mi>
            <mn>1</mn>
          </msub>
        </mfenced>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mi>k</mi>
        <mo>&InvisibleTimes;</mo>
        <mo>log</mo>
        <mfenced>
          <msub>
            <mi>P</mi>
            <mn>2</mn>
          </msub>
        </mfenced>
      </mrow>
    </mrow>
    <mo>=</mo>
    <mrow>
      <msub>
        <mi>S</mi>
        <mn>1</mn>
      </msub>
      <mo>+</mn>
      <msub>
        <mi>S</mi>
        <mn>2</mn>
      </msub>
    </mrow>
  </mrow>
</math>

The additive property of entropy is more than a mathematical convenience.
It means that the statement of the second law can be generalized to include a composite system.
To restate it: (3) The total entropy of a set of interconnected systems increases or stays the same.
If the entropy of one system decreases, the entropy of systems connected to it must increase by at least a compensating amount, so that the sum of the individual entropies does not decrease.

Even though the second law of thermodynamics may be re-expressed in terms of entropy or of order and disorder, probability remains the key underlying idea.
The exact nature of this probability must be understood if the second law is to be understood.
Implicit in our discussion up to this point but still requiring emphasis is the a priori nature of the probability that governs physical change.
The statement that physical systems change from less probable to more probable arrangements might seem anything but profound if the probability is regarded as an after-the-fact probability.
If we decided that a uniform distribution of molecules in a box must be more probable than a nonuniform distribution because gas in a box is always observed to spread itself out evenly, the second law would be mere tautology, saying that systems tend to do what they are observed to do.
In fact, the probability of the second law of thermodynamics is not based on experience or experiment.
It is a before-the-fact (a priori) probability, based on coimting the number of different ways in which a particular arrangement could be achieved.
To every conceivable arrangement of a system can be assigned an a priori probability, whether or not the system or that arrangement of it has ever been observed.
In practice there is no reason why the state of a system with the highest a priori probability need be the most frequently observed.
Consider the case of the dedicated housewife.
Almost every time an observant friend comes to call, he finds her house to be in perfect condition, nothing out of place, no dust in sight.
He must conclude that for this house at least, the most probable state is very orderly state, since that is what he most often observes.
This is an after the-fact probability.
As the housewife and the student of physics know, the orderly state has a low a priori probability. Left to itself, the house will tend toward a disorderly state of higher a priori probability.
A state of particularly high a priori probability for a house is one not often observed, a pile of rubble.
Thus an arrangement of high probability (from here on we shall omit the modifier, a priori) need be neither frequently observed nor quickly achieved, but it is, according to the second law of thermodynamics, the inevitable destination of an isolated system.

In comparison with other fundamental laws of nature, the second law of thermodynamics has two special features. First, it is not given expression by any mathematical equation.
It specifies a direction of change, but not a magnitude of change.
The nearest we can come to an equation is the mathematical statement,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="S \leq 0" display="block", id="eq14-5">
  <mrow>
    <mi>S</mi>
    <mo>&le;</mo>
    <mn>0</mn>
  </mrow>
</math>


In words: The change of entropy (for an isolated system or collection of systems) is either positive or zero.
Or, more simply, entropy does not spontaneously decrease.

Every fundamental law of nature is characterized by remarkable generality, yet the second law of thermodynamics is unique among them (its second special feature) in that it finds direct application in a rich variety of settings, physical, biological, and human.
In mentioning trays of coins, molecules of gas, and disorder in the house, we have touched only three of a myriad of applications.
Entropy and the second law have contributed to discussion of the behavior of organisms, the flow of events in societies and economies, communication and information, and the history of the universe.
In much of the physics and chemistry of macroscopic systems, the second law has found a use.
Only at the submicroscopic level of single particles and single events is it of little importance.
It is a startling and beautiful thought that an idea as simple as the natural trend from order to disorder should have such breadth of impact and power of application.


In most of the remainder of this chapter we shall be concerned with the application of the second law of thermodynamics to relatively simple physical situations.
In Section \ref{sec:14.9} we return to some of its more general implications.

## Probability of velocity: heat flow and equipartition
\label{sec:14.5}

Since the velocities as well as the positions of individual molecules are generally unknown, velocity too is subject to considerations of probability.
This kind of probability, like the probability of position, follows the rule of spontaneous change from lower to higher probability.
It should not be surprising to learn that for a collection of identical molecules the most probable arrangement is one with equal molecular speeds (and randomly oriented velocities).
This means that available energy tends to distribute itself uniformly over a set of identical molecules, just as available space tends to be occupied uniformly by the same molecules.
In fact, the equipartition theorem and the zeroth law of thermodynamics can both be regarded as consequences of the second law of thermodynamics.
Energy divides itself equally among the available degrees of freedom, and temperatures tend toward equality, because the resulting homogenized state of the molecules is the state of maximum disorder and maximum probability.
The concentration of all of the energy in a system on a few molecules is a highly ordered and improbable situation analogous to the concentration of all of the molecules in a small portion of the available space.

The normal course of heat flow can also be understood in terms of the second law.
Heat flow from a hotter to a cooler body is a process of energy transfer tending to equalize temperature and thereby to increase entropy.
The proof that equipartition is the most probable distribution of energy is complicated and beyond the scope of this book.
Here we seek only to make it plausible through analogy with the probability of spatial distributions.

Heat flow is so central to most applications of thermodynamics that the second law is sometimes stated in this restricted form: (4) Heat never flows spontaneously from a cooler to a hotter body.
Notice that this is a statement about macroscopic behavior, whereas the more general and fundamental statements of the second law, which make use of the ideas of probability and order and disorder, refer to the submicroscopic structure of matter.
Historically, the first version of the second law, advanced by Sadi Carnot in 1824, came before the submicroscopic basis of heat and temperature was established, in fact before the first law of thermodynamics was formulated.
Despite a wrong view of heat and an incomplete view of energy, Carnot was able to advance the important principle that no heat engine (such as a steam engine) could operate with perfect efficiency.
In modern terminology, Carnot's version of the second law is this: (5) In a closed system, heat flow out of one part of the system cannot be transformed wholly into mechanical energy (work), but must be accompanied by heat flow into a cooler part of the system.
In brief, heat cannot be transformed completely to work.

The consistency of Carnot's form of the second law with the general principle of entropy increase can best be appreciated by thinking in terms of order and disorder.
The complete conversion of heat to work would represent a transformation of disordered energy, a replacement of random molecular motion by orderly bulk motion.
This violates the second law of thermodynamics. As indicated

<figure>
\label{fig:14.6}
\caption{
    Schematic diagram of partial conversion of disordered heat energy to ordered mechanical energy.
    Heat flow out of a hot region decreases the entropy there.
    A compensating increase of entropy in a cold region requires less heat.
    Therefore, some heat can be transformed to work without violating the second law of thermodynamics.
    Any device that achieves this aim is called a heat engine.
}
</figure>

schematically in [Figure 14-6](#fig14-6), a partial conversion of heat to work is possible because a small heat flow into a cool region may increase the entropy there by more than the decrease of entropy produced by a larger heat flow out of a hot region.
At absolute zero, the hypothetically motionless molecules have maximum order.
Greater temperature produces greater disorder.
Therefore heat flow into a region increases its entropy, heat flow out of region decreases its entropy.
Fortunately for the feasibility of heat engines, it takes less heat at low temperature than at high temperature to produce a given entropy change.
To make an analogy, a pebble is enough to bring disorder to the smooth surface of a calm lake.
To produce an equivalent increase in the disorder of an already rough sea requires a boulder.
In Section \ref{sec:14.7}, the quantitative link between heat flow and entropy is discussed.

The reverse transformation, of total conversion of work to heat, is not only possible but is commonplace.
Every time a moving object is brought to rest by friction, all of its ordered energy of bulk motion is converted to disordered energy of molecular motion.
This is an entropy-increasing process allowed by the second law of thermodynamics.
In general, the second law favors energy dissipation, the transformation of energy from available to unavailable form.
Whenever we make a gain against the second law by increasing the order or the available energy in one part of a total system, we can be sure we have lost even more in another part of the system.
Thanks to the constant input of energy from the sun, the earth remains a lively place and we have nothing to fear from the homogenizing effect of the second law.


## Perpetual motion
\label{sec:14.6}

We have given so far five different versions of the second law, and will add only one more.
Of those given, the first three, expressed in terms of probability, of order-disorder, and of entropy, are the most fundamental.
Worth noting in several of the formulations is the recurring emphasis on the negative.
Entropy does not decrease. Heat does not flow spontaneously from a cooler to a hotter region.
Heat can not be wholly transformed to work. Our sixth version is also expressed in the negative.
(6) Perpetual-motion machines cannot be constructed.
This statement may sound more like a staff memorandum in the Patent Office than a fundamental law of nature.
It may be both.
In any event, it is certainly the latter, for from it can be derived the spontaneous increase of probability, of dis- order, or of entropy.
It is specialized only in that it assumes some friction, however small, to be present to provide some energy dissipation.
If we overlook the nearly frictionless motion of the planets in the solar system and the frictionless motion of single molecules in a gas, everything in between is encompassed.

A perpetual-motion machine can be defined as a closed system in which bulk motion persists indefinitely, or as a continuously operating device whose output work provides its own input energy.
Some proposed perpetual-motion machines violate the law of energy conservation (the first law of thermodynamics).
These are called perpetual-motion machines of the first kind.
Although they can be elaborate and subtle, they are less interesting than perpetual-motion machines of the second kind, hypothetical devices that conserve energy but violate the principle of entropy increase (the second law of thermodynamics) .

As operating devices, perpetual-motion machines are the province of crackpot science and science fiction.
As inoperable devices they have been of some significance in the development of science. Carnot was probably led to the second law of thermodynamics by his conviction that perpetual motion should be impossible.
Arguments based on the impossibility of perpetual motion can be used to support Newton's third law of mechanics and Lenz's law of electromagnetic reaction, which will be discussed in Chapter Sixteen.
Any contemporary scientist with a speculative idea can subject it to at least one quick test: Is it consistent with the impossibility of perpetual motion?

<figure>
\label{fig:14.7}
\caption{
    A perpetual-motion machine of the second kind.
    The device labeled MARK II receives heat energy from the coffee and converts this to mechanical energy which turns a paddle wheel, agitating the coffee, returning to the coffee the energy it lost by heat flow.
    It is not patentable.
}
</figure>

Suppose that an inventor has just invented a handy portable coffee warmer ([Figure 14-7](#fig14-7)).
It takes the heat which flows from the coffee container and, by a method known only to him, converts this heat to work expended in stirring the coffee.
If the energy going back into the coffee is equal to that which leaks off as heat, the original temperature of the coffee will be maintained. Is it patentable?
No, for it is a perpetual-motion machine of the second kind.
Although it conserves energy, it performs the impossible task of maintaining a constant entropy in the face of dissipative forces that tend to increase entropy.
Specifically it violates Carnot's version of the second law (No. 5, page 441), for in one part of its cycle it converts heat wholly to work.
Of course it also violates directly our sixth version of the second law.

One of the chief strengths of the second law is its power to constrain the behavior of complex systems without reference to any details.
Like a corporate director, the second law rules the overall behavior of systems or interlocked sets of system in terms of their total input and output and general function.
Given a proposed scheme for the operation of the automatic coffee warmer, it might be quite a complicated matter to explain in terms of its detailed design why it cannot work.
Yet the second law reveals at once that no amount of ingenuity can make it work.

## Entropy on two levels
\label{sec:14.7}

The mathematical roots of thermodynamics go back to the work of Pierre Laplace and other French scientists concerned with the caloric theory of heat in the years aroimd 1800, and even further to the brilliant but forgotten invention of the kinetic theory of gases by Daniel Bernoulli in 1738.
Not until after 1850 did these and other strands come together to create the theory of thermodynamics in something like its modem form.
No other great theory of physics has traveled such a rocky road to success over so many decades of discovery, argumentation, buried insights, false turns, and rediscovery, its paths diverging and finally rejoining in the grand synthesis of statistical mechanics which welded together the macroscopic and submicroscopic domains in the latter part of the nineteenth century.

In the long and complex history of thermodynamics, the generalization of the principle of energy conservation to include heat stands as probably the most significant single landmark.
Joule's careful experiments on the mechanical equivalent of heat in the 1840's not only established the first law of thermodynamics, but cleared the way for a full understanding of the second law, provided a basis for an absolute temperature scale, and laid the groundwork for the submicroscopic mechanics of the kinetic theory.
Progress in the half century before Joule's work had been impeded by a pair of closely related difficulties: an incorrect view of the nature of heat, and an incomplete understanding of the way in which heat engines provide work.
To be sure, there had been important insights in this period, such as Carnot's statement of the second law of thermodynamics in 1824.
But such progress as there was did not fit together into a single structure, nor did it provide a base on which to build.
Not until 1850, when the great significance of the general principle of energy conservation was appreciated by at least a few scientists, was Carnot's work incorporated into a developing theoretical structure.
The way was cleared for a decade of rapid progress.
In the 1850's, the first and second laws of thermodynamics were first stated as general unifying principles, the kinetic theory was rediscovered and refined, the concepts of heat and temperature were given submicroscopic as well as macroscopic definitions, and the full significance of the ideal-gas law was understood.
The great names of the period were James Joule, William Thomson (Lord Kelvin), and James Clerk Maxwell in England, Rudolph Clausius and August Kronig in Germany.

One way to give structure to the historical development of a major theory is to follow the evolution of its key concepts.
This is particularly instructive for the study of thermodynamics, because its basic concepts&mdash;heat, temperature, and entropy — exist on two levels, the macroscopic and the submicroscopic.
The refinement of these concepts led both to a theoretical structure for understanding a great part of nature and to a bridge between two worlds, the large and the small.
Of special interest here is the entropy concept.

Like heat and temperature, entropy was given first a macroscopic definition, later a molecular definition.
Being a much subtler concept than either heat or temperature (in that it does not directly impinge on our senses), entropy was defined only after its need in the developing theory of thermodynamics became obvious.
Heat and temperature were familiar ideas refined and revised for the needs of quantitative understanding.
Entropy was a wholly new idea, formally introduced and arbitrarily named when it proved to be useful in expressing the second law of thermodynamics in quantitative form.
As a useful but unnamed quantity, entropy entered the writings of both Kelvin and Clausius in the early 1850's.
Finally in 1865, it was formally recognized and christened &ldquo;entropy&rdquo; by Clausius, after a Greek word for transformation.
Entropy, as he saw it, measured the potentiality of a system for transformation.

The proportionality of entropy to the logarithm of an intrinsic probability for the arrangement of a system, as expressed by Equation 14.3, was stated first by Ludwig Boltzmann in 1877.
This pinnacle of achievement in what had come to be called statistical mechanics fashioned the last great thermodynamics link between the large-scale and small-scale worlds.
Although we now regard Boltzmann's definition based on the molecular viewpoint as the more fundamental, we must not overlook the earlier macroscopic definition of entropy given by Clausius (which in most applications is easier to use).
Interestingly, Clausius expressed entropy simply and directly in terms of the two already familiar basic concepts, heat and temperature.
He stated that a change of entropy of any part of a system is equal to the increment of heat added to that part of the system divided by its temperature at the moment the heat is added, provided the change is from one equilibrium state to another:


<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta S = \frac{\Delta H}{T}." display="block", id="eq14-6">
  <mrow>
    <mrow>
      <mo>&Delta;</mo>
      <mi>S</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&Delta;</mo>
          <mi>H</mi>
        </mrow>
        <mrow>
          <mi>T</mi>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

Here <span class="math">S</span> denotes entropy, <span class="math">H</span> denotes heat, and <span class="math">T</span> denotes the absolute temperature.
For heat gain, <span class="math">&Delta;H</span> is positive and entropy increases.
For heat loss, <span class="math">&Delta;H</span> is negative and entropy decreases.
How much entropy change is produced by adding or subtracting heat depends on the temperature.
Since the temperature <span class="math">T</span> appears in the denominator in [Equation 14-6](#eq14-6), a lower temperature enables a given increment of heat to produce a greater entropy change.

There are several reasons why Clausius defined not the entropy itself, but the change of entropy.
For one reason, the absolute value of entropy is irrelevant, much as the absolute value of potential energy is irrelevant.
Only the change of either of these quantities from one state to another matters.
Another more important reason is that there is no such thing as &ldquo;total heat.&rdquo;
Since heat is energy transfer (by molecular collisions), it is a dynamic quantity measured only in processes of change.
An increment of heat <span class="math">&Delta;H</span> can be gained or lost by part of a system, but it is meaningless to refer to the total heat <span class="math">H</span> stored in that part.
(This was the great insight about heat afforded by the discovery of the general principle of energy conservation in the 1840's).
What is stored is internal energy, a quantity that can be increased by mechanical work as well as by heat flow. Finally, it should be remarked that Clausius' definition refers not merely to change, but to small change.
When an otherwise inactive system gains heat, its temperature rises.
Since the symbol <span class="math">T</span> in [Equation 14-6](#eq14-6) refers to the temperature at which heat is added, the equation applies strictly only to increments so small that the temperature does not change appreciably as the heat is added.
If a large amount of heat is added, Equation 14.6 must be applied over and over to the successive small increments, each at slightly higher temperature.

To explain how the macroscopic definition of entropy given by Clausius ([Equation 14-6](#eq14-6)) and the submicroscopic definition of entropy given by Boltzmann ([Equation 14-3](#eq14-3)) fit together is a task beyond the scope of this book.
Nevertheless we can, through an idealized example, make it reasonable that these two definitions, so different in appearance, are closely related.
To give the Clausius definition a probability interpretation we need to discuss two facts:
    (1) Addition of heat to a system increases its disorder and therefore its entropy;
    (2) The disordering influence of heat is greater at low temperature than at high temperature.
The first of these facts is related to the apparance of the factor <span class="math">&Delta;H</span> on the right of Equation 14.6; the second is related to the inverse proportionality of entropy change to temperature.

Not to prove these facts but to make them seem reasonable, we shall consider an idealized simple system consisting of just three identical molecules, each one capable of existing in any one of a number of equally spaced energy states.
The overall state of this system can be represented by the triple-ladder diagram of [Figure 14-8](#fig14-8), in which each rung corresponds to a molecular energy state.
Dots on the three lowest rungs would indicate that the system possesses no internal energy.
The pictured dots on the second, third, and bottom rungs indicate that the system has a total of five units of internal energy, two units possessed by the first molecule, three by the second, and none by the third.
The intrinsic probability associated with any given total energy is proportional to the number of different ways in which that energy can be divided.
This is now a probability of energy distribution, not a probability of spatial distribution.
However, the reasoning is much the same as in Section \ref{sec:14.3}.
There the intrinsic (a priori) probability for a distribution of molecules in space was taken to be proportional to the number of different ways in which that distribution could be obtained.
Or, to give another example, the probability of throwing 7 with a pair of dice is greater than the probability of throwing 2, because there are more different ways to get a total of 7 than to get a total of 2.

<figure id="fig14-8}">
<figcation>
    Idealized energy diagram for a system of three molecules, each with equally spaced energy states.
    Each ladder depicts the possible energies of a particular molecule, and the heavy dot specifies the actual energy of that molecule.
</figcation>
</figure>


[Table 14-4](#tab14-4) enumerates all the ways in which up to five units of energy can be divided among our three idealized molecules.
The triplets of numbers in the second column indicate the occupied rungs of the three energy ladders.
It is an interesting and instructive problem to deduce a formula for the numbers in the last column, (hint: The number of ways to distribute 6 units of energy is 28.)
However, since this is a highly idealized picture of very few molecules, precise numerical details are less important than are the qualitative features of the overall pattern.
The first evident feature is that the greater the energy, the more different ways there are to divide the energy.
Thus a higher probability is associated with greater internal energy.
This does not mean that the system, if isolated and left alone, will spontaneously tend toward a higher probability state, for that would violate the law of energy conservation.
Nevertheless, we associate with the higher energy state a greater probability and a greater disorder.
When energy is added from outside via heat flow, the entropy increase is made possible.
This makes reasonable the appearance of the heat increment factor, <span class="math">&Delta;H</span>, in [Equation 14-6](#eq14-6).

\begin{table}
\label{tab:14.4}
\caption{Internal Energy Distribution for Idealized System of Three Molecules}
%\begin{tabu}{ccccc}
%\end{tabu}
\end{table}


Looking further at [Table 14-4](#tab14-4), we ask whether the addition of heat produces a greater disordering effect at low temperature than at high temperature.
For simplicity we can assume that temperature is proportional to total internal energy, as it is for a simple gas, so that the question can be rephrased:
    Does adding a unit of heat at low energy increase the entropy of the system more than adding the same unit of heat at higher energy?
Answering this question requires a little care, because of the logarithm that connects probability to entropy.
The relative probability accelerates upward in [Table 14-6](#tab14-6).
In going from 1 to 2 units of energy, the number of ways to distribute the energy increases by three, from 2 to 3 units it increases by four, from 3 to 4 units it increases by five, and so on.
However, the entropy, proportional to the logarithm of the probability, increases more slowly at higher energy.
The relevant measure for the increase of a logarithm is the factor of growth. [^4]
From to 1 unit of energy, the probability trebles, from 1 to 2 units it doubles, from 2 to 3 units it grows by 67 percent, and so on, by ever decreasing factors of increase.
Therefore the entropy grows most rapidly at low internal energy (low temperature).
This makes reasonable the appearance of the temperature factor &ldquo;downstairs&rdquo; on the right of [Equation 14-6](#eq14-6).

This example focuses attention on a question that may have occurred to you already.
Why is it that energy addition by heat flow increases entropy, but energy addition by work does not?
The definition, [Equation 14-6](#eq14-6), makes reference to only one kind of energy, heat energy.
The difference lies basically in the recoverability of the energy.
When work is done on a system without any accompanying heat flow, as when gas is compressed in a cylinder ([Figure 14-9](#fig14-9)), the energy can be fully recovered, with the system and its surroundings returning precisely to the state they were in before the work was done. No entropy change is involved.
On the other hand, when energy in the form of heat flows from a hotter to a cooler place, there is no mechanism that can cause the heat to flow spontaneously back from the cooler to the hotter place. It is not recoverable.
Entropy has increased.
In a realistic as opposed to an ideal cycle of compression and expansion, there will in fact be some entropy increase because there will be some flow of heat from the compressed gas to the walls of the container.

<figure id="fig14-9">
<figcaption>
    Idealized cycle of compression and expansion of gas, accompanied by no change of entropy.
    If any heat flow occurs in the cycle, entropy does increase.
</figcaption>
</figure>

Another useful way to look at the difference between heat and work is in molecular terms, merging the ideas of position probability and velocity or energy probability.
If a confined gas ([Figure 14.9b](#fig14-9)) is allowed to expand until its volume doubles ([Figure 14-9(c)](#fig14-9)) what we learned about position probability tells us that, so far as its spatial arrangement is concerned, it has experienced an entropy increase, having spread out into an intrinsically more probable arrangement.
In doing so, however, it has done work on its surroundings and has lost internal energy.
This means that, with respect to its velocity and energy, it has approached a state of greater order and lesser entropy.
Its increase of spatial disorder has in fact been precisely canceled by its decrease of energy disorder, and it experiences no net change of entropy.
Had we instead wanted to keep its temperature constant during the expansion, it would have been necessary to add heat (equal in magnitude to the work done).
Then after the expansion, the unchanged internal energy would provide no contribution to entropy change, so that a net entropy increase would be associated with the expansion arising from the probability of position.
This would match exactly the entropy increase &Delta;H/T predicted by the Clausius formula, for this change required a positive addition of heat.


Although the macroscopic entropy definition of Clausius and the submicroscopic entropy definition of Boltzmann are, in many physical situations, equivalent, Boltzmann's definition remains the more profound and the more general.
It makes possible a single grand principle, the spontaneous trend of systems from arrangements of lower to higher probability, that describes not only gases and solids and chemical reactions and heat engines, but also dust and disarray, erosion and decay, the deterioration of fact in the spread of rumor, the fate of mismanaged corporations, and perhaps the fate of the universe.

## Application of the second law
\label{sec:14.8}

That heat flows spontaneously only from a warmer to a cooler place is a fact which can itself be regarded as a special form of the second law of thermodynamics.
Alternatively the direction of heat flow can be related to the general principle of entropy increase with the help of the macroscopic definition of entropy.
If body 1 at temperature <span class="math">T_1</span> loses an increment of heat <span class="math">&Delta;H</span>, its entropy change&mdash;a decrease&mdash;is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta S_1 = - \frac{\Delta H}{T_1}" display="block", id="eq14-7">
  <mrow>
    <mrow>
      <mo>&Delta;</mo>
      <msub>
        <mi>S</mi>
        <mn>1</mn>
      </msub>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&Delta;</mo>
          <mi>H</mi>
        </mrow>
        <mrow>
          <msub>
            <mi>T</mi>
            <mn>1</mn>
          </msub>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

If this heat is wholly transferred to body 2 at temperature <span class="math">T_2</span>, its entropy gain is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta S_2 = - \frac{\Delta H}{T_2}" display="block", id="eq14-8">
  <mrow>
    <mrow>
      <mo>&Delta;</mo>
      <msub>
        <mi>S</mi>
        <mn>2</mn>
      </msub>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&Delta;</mo>
          <mi>H</mi>
        </mrow>
        <mrow>
          <msub>
            <mi>T</mi>
            <mn>2</mn>
          </msub>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

The total entropy change of the system (bodies 1 and 2) is the sum,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta S = \Delta S_1 + \Delta S+_2 = \Delta H \left( \frac{1}{T_2} - \frac{1}{T_1} \right)" display="block", id="eq14-9">
  <mrow>
    <mrow>
      <mo>&Delta;</mo>
      <mi>S</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mo>&Delta;</mo>
        <msub>
          <mi>S</mi>
          <mn>1</mn>
        <msub>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mo>&Delta;</mo>
        <msub>
          <mi>S</mi>
          <mn>2</mn>
        <msub>
      </mrow>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mo>&Delta;</mo>
      <mi>H</mi>
      <mfenced>
        <mfrac>
          <mn>1</mn>
          <msub>
            <mi>T</mi>
            <mn>2</mn>
          </msub>
        <mfrac>
        <mo>&minus;</mo>
        <mfrac>
          <mn>1</mn>
          <msub>
            <mi>T</mi>
            <mn>1</mn>
          </msub>
        <mfrac>
      </mfenced>
    </mrow>
  </mrow>
</math>

This entropy change must, according to the second law, be positive if the heat transfer occurs spontaneously.
It is obvious algebraically from [Equation 14.9](#eq14-9) that this requirement implies that the temperature <span class="math">T_1</span> is greater than the temperature <span class="math">T_2</span>.
In short, heat flows from the warmer to the cooler body.
In the process, the cooler body gains energy equal to that lost by the warmer body but gains entropy greater than that lost by the warmer body.
When equality of temperature is reached, heat flow in either direction would decrease the total entropy.
Therefore it does not occur.

A heat engine is, in simplest terms, a device that transforms heat to mechanical work.
Such a transformation is, <em>by itself</em>, impossible.
It is an entropy-decreasing process that violates the second law of thermodynamics.
We need hardly conclude that heat engines are impossible, for we see them all around us.
Gasoline engines, diesel engines, steam engines, jet engines, and rocket engines are all devices that transform heat to work.
They do so by incorporating in the same system a mechanism of entropy increase that more than offsets the entropy decrease associated with the production of work.
The simple example of heat flow with which this section began shows that one part of a system can easily lose entropy if another part gains more.
In almost all transformations of any complexity, and in particular in those manipulated by man for some practical purpose, entropy gain and entropy loss occur side by side, with the total gain inevitably exceeding the total loss.


The normal mechanism of entropy gain in a heat engine is heat flow.
Carnot's great insight that provided the earliest version of the second law was the realization that a heat engine must be transferring heat from a hotter to a cooler place at the same time that it is transforming heat to work.
How this is accomplished varies from one heat engine to another, and the process can be quite complicated and indirect.
Nevertheless, without reference to details, it is possible to discover in a very simple way what fraction of the total energy supplied by fuel can be transformed into usable work.
This fraction is called the efficiency of the engine.
Refer to [Figure 14-6](#fig14-6), which shows schematically a process of partial transformation of heat to work.
From the hotter region, at temperature <span class="math">T_1</span>, flows an increment of heat <span class="math">&Delta;H</span>.
Into the cooler region, at temperature <span class="math">T_2</span>, flows heat <span class="math">H_2</span>.
The output work is <span class="math">W</span>.
The first and second laws of thermodynamics applied to this idealized heat engine can be given simple mathematical expression.

<ol type="1">
  <li>Energy conservation:
    <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="H_1 = H_2 + W" display="inline", id="eq14-10">
      <mrow>
        <msub>
          <mi>H</mi>
          <mn>1</mn>
        </msub>
        <mo>=</mo>
        <mrow>
          <msub>
            <mi>H</mi>
            <mn>2</mn>
          </msub>
          <mo>+</mo>
          <mi>W</mi>  
        </mrow>
      </mrow>
    </math>
  </li>
  <li>Entropy increase:
    <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="S = \frac{H_2}{T_2} - \frac{H_1}{T_1} > 0" display="inline", id="eq14-11">
      <mrow>
        <mrow>
          <mi>S</mi>
        </mrow>
        <mo>=</mo>
        <mrow>
          <mfrac>
            <msub>
              <mi>H</mi>
              <mn>2</mn>
            </msub>
            <msub>
              <mi>T</mi>
              <mn>2</mn>
            </msub>
          </mfrac>
          <mo>&minus;</mo>
          <mfrac>
            <msub>
              <mi>H</mi>
              <mn>1</mn>
            </msub>
            <msub>
              <mi>T</mi>
              <mn>1</mn>
            </msub>
          </mfrac>
        </mrow>
        <mo>&gt;</mo>
        <mrow>
          <mn>0</mn>
        </mrow>
      </mrow>
    </math>
  </li>
</ol> 

If this heat engine were &ldquo;perfect&rdquo;&mdash;free of friction and other dissipative effects&mdash;the entropy would remain constant instead of increasing.
Then the right side of [Equation 14-11](#fig14-11) could be set equal to zero, and the ratio of output to input heat would be H<sub>2</sub>/T<sub>2</sub>.

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{H_2}{H_1} = \frac{T_2}{T_1}" display="block", id="eq14-12">
  <mrow>
    <mrow>
      <mfrac>
        <msub>
          <mi>H</mi>
          <mn>2</mn>
        </msub>
        <msub>
          <mi>H</mi>
          <mn>1</mn>
        </msub>
      </mfrac>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <msub>
          <mi>T</mi>
          <mn>2</mn>
        </msub>
        <msub>
          <mi>T</mi>
          <mn>1</mn>
        </msub>
      </mfrac>
    </mrow>
  </mrow>
</math>

From [Equation 14-10](#fig14-10) follows another equation containing the ratio H<sub>2</sub>/H<sub>1</sub>,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{W}{H_1} =  1- \frac{H_2}{H_1}" display="block", id="eq14-13">
  <mrow>
    <mrow>
      <mfrac>
        <msub>
          <mi>W</mi>
        </msub>
        <msub>
          <mi>H</mi>
          <mn>1</mn>
        </msub>
      </mfrac>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mn>1</mn>
      <mo>&minux;</mo>
      <mfrac>
        <msub>
          <mi>H</mi>
          <mn>2</mn>
        </msub>
        <msub>
          <mi>H</mi>
          <mn>1</mn>
        </msub>
      </mfrac>
    </mrow>
  </mrow>
</math>

Substitution of [Equation 14-12](#fig14-12) into [Equation 14-13](#fig14-13) gives for the ratio of output work to initial heat supply,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{W_{\mathrm{max}}}{H_1} =  1- \frac{T_2}{T_1}" display="block", id="eq14-14">
  <mrow>
    <mrow>
      <mfrac>
        <msub>
          <mi>W</mi>
          <mtext>max</mtext>
        </msub>
        <msub>
          <mi>H</mi>
          <mn>1</mn>
        </msub>
      </mfrac>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mn>1</mn>
      <mo>&minux;</mo>
      <mfrac>
        <msub>
          <mi>T</mi>
          <mn>2</mn>
        </msub>
        <msub>
          <mi>T</mi>
          <mn>1</mn>
        </msub>
      </mfrac>
    </mrow>
  </mrow>
</math>

Here we have written <span class="math">W<sub>max</sub></span> instead of <span class="math">W</span>, since this equation gives the maximum possible efficiency of the idealized heat engine.
If the temperatures <span class="math">T_1</span> and <span class="math">T_2</span> are nearly the same, the efficiency is very low.
If <span class="math">T_2</span> is near absolute zero, the theoretical efficiency can be close to 1&mdash;that is, almost perfect.

The modern marvels of technology that populate our present world&mdash;auto-mobiles, television, airplanes, radar, pocket radios— all rest ultimately on basic prmciples of physics.
Nevertheless they are usually not instructive as illustrations of fundamental laws, for the chain of connection from their practical function to the underlying principles is complex and sophisticated.
The refrigerator is such a device.
Despite its complexity of detail, however, it is worth considering in general terms.
Because it transfers heat from a cooler to a warmer place, the refrigerator appears at first to violate the second law of thermodynamics.
The fact that it must not do so allows us to draw an important conclusion about the minimum expenditure of energy required to run it.
The analysis is quite similar to that for a heat engine.
Suppose that the mechanism of the refrigerator is required to transfer an amount of heat <span class="math">H_1</span> out of the refrigerator each second.
If the interior of the refrigerator is at temperature <span class="math">T_1</span>, this heat loss contributes an entropy decrease equal to <span class="math">H<sub>1</sub>/T<sub>1</sub></span>.
This heat is transferred to the surrounding room at temperature <span class="math">T_2</span> (higher than <span class="math">T_1</span>), where it contributes an entropy increase equal to <span class="math">H<sub>1</sub>/T<sub>2</sub></span>.
The sum of these two entropy changes is negative.
Some other contribution to entropy change must be occurring in order that the total change may be positive, in consonance with the second law.
This extra contribution comes from the degradation of the input energy that powers the refrigerator.


The energy supplied by electricity or by the combustion of gas eventually reaches the surrounding room as heat.
If the external energy (usually electrical) supplied in one second is called <span class="math">W</span>, and the total heat added to the room in the same time is called <span class="math">H_2</span>, energy conservation requires that H2 be the sum of <span class="math">H_1</span> and <span class="math">W</span>:

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="H_2 = H_1 + W" display="block", id="eq14-15">
  <mrow>
    <mrow>
      <msub>
        <mi>H</mi>
        <mn>2</mn>
      </msub>
    </mrow>
    <mo>=</mo>
    <mrow>
      <msub>
        <mi>H</mi>
        <mn>1</mn>
      </msub>
      <mo>+</mo>
      <mi>W</mi>
    </mrow>
  </mrow>
</math>

The energy flow is shown schematically in [Figure 14-10](#fig14-10).
At the same time the total entropy change is given by

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta S = \frac{H_2}{T_2} - \frac{H_1}{T_1}" display="block", id="eq14-16">
  <mrow>
    <mrow>
      <mo>&Delta;</mo>
      <mi>S</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <msub>
            <mi>H</mi>
            <mn>2</mn>
          </msub>
        </mrow>
        <mrow>
          <msub>
            <mi>T</mi>
            <mn>2</mn>
          </msub>
        </mrow>
      </mfrac>
      <mo>&minus;</mo>
      <mfrac>
        <mrow>
          <msub>
            <mi>H</mi>
            <mn>1</mn>
          </msub>
        </mrow>
        <mrow>
          <msub>
            <mi>T</mi>
            <mn>1</mn>
          </msub>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

Since <span class="math">&Delta;S</span> must be zero or greater, the ratio <span class="math">H<sub>2</sub>/H<sub>1</sub></span> [= (heat added to room) /(heat extracted from refrigerator)] must be at least equal to <span class="math">T<sub>2</sub>/T<sub>1</sub></span>.
If the energy conservation equation is written in the form

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="W = H_1 \left[\frac{H_2}{H_1} -1 \right]" display="block">
  <mrow>
    <mrow>
      <mi>W</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <msub>
        <mi>H</mi>
        <mn>1</mn>
      </msub>
      <mfenced>
        <mfrac>
          <mrow>
            <msub>
              <mi>H</mi>
              <mn>2</mn>
            </msub>
          </mrow>
          <mrow>
            <msub>
              <mi>H</mi>
              <mn>1</mn>
            </msub>
          </mrow>
        </mfrac>
        <mo>&minus;</mo>
        <mn>1</mn>
      </mfenced>
    </mrow>
  </mrow>
</math>

we can conclude that

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="W \geq H_1 \left[\frac{T_2}{T_1} -1 \right]," display="block" id="eq14-17">
  <mrow>
    <mrow>
      <mi>W</mi>
    </mrow>
    <mo>&ge;</mo>
    <mrow>
      <mfenced>
        <mfrac>
          <mrow>
            <msub>
              <mi>T</mi>
              <mn>2</mn>
            </msub>
          </mrow>
          <mrow>
            <msub>
              <mi>T</mi>
              <mn>1</mn>
            </msub>
          </mrow>
        </mfrac>
        <mo>&minus;</mo>
        <mn>1</mn>
      </mfenced>
    </mrow>
  </mrow>
</math>


The right side of this inequality gives the minimum amount of external energy input required in order to transfer an amount of heat <span class="math">H_1</span> &ldquo;uphill&rdquo; from temperature <span class="math">T_1</span> to temperature <span class="math">T_2</span>.
As might be expected, the input energy requirement increases as the temperature difference increases.
If the temperature <span class="math">T_1</span> is near absolute zero, as it is in a helium liquefier, the external energy expended is much greater than the heat transferred.


The real beauty of the result expressed by [Equation 14-17](#eq14-17) is its generality for all refrigerators regardless of their construction and mode of operation.
The input energy <span class="math">W</span> could be supplied by an electric motor, a gas flame, or a hand crank.
It is characteristic of the second law of thermodynamics, just as it is characteristic of the fundamental conservation laws, that it has something important to say about the overall behavior of a system without reference to details, perhaps without knowledge of details.
In the small-scale world, our inability to observe precise features of individual events is one reason for the special importance of conservation laws.
In the large-scale world, the elaborate complexity of many systems is one reason for the special importance of the second law of thermodynamics.
Like the conservation laws, it provides an overall constraint on the system as a whole.

<figure>
    \label{fig:14.10}
    \caption{Energy and heat flow in the operation of a refrigerator.}
</figure>

In many applications of the second law, the concept of available energy is the easiest key to understanding.
In general, the trend of nature toward greater disorder is a trend toward less available energy.
A jet plane before takeoff has a certain store of available energy in its fuel.
While it is accelerating down the runway, a part of the energy expended is going into bulk kinetic energy (ordered energy), a part is going into heat that is eventually dissipated into unavailable energy.
At constant cruising speed, all of the energy of the burning fuel goes to heat the air.
Thermodynamically speaking, the net result of a flight is the total loss of the available energy originally present in the fuel.
A rocket in free space operates with greater efficiency.
Being free of air friction, it continues to accelerate as long as the fuel is burning.
When its engine stops, a certain fraction (normally a small fraction) of the original available energy in the fuel remains available in the kinetic energy of the vehicle.
This energy may be &ldquo;stored&rdquo; indefinitely in the orbital motion of the space vehicle.
If it re-enters the atmosphere, however, this energy too is transformed into the disordered and unavailable form of internal energy of the air.
To get ready for the next launching, more rocket fuel must be manufactured.
The energy expended in the chemical factory that does this job is inevitably more than the energy stored in the fuel that is produced.


In general the effect of civilization is to encourage the action of the second law of thermodynamics.
Technology greatly accelerates the rate of increase of entropy in man's immediate environment.
Fortunately the available energy arriving each day from the sun exceeds by a very large factor the energy degraded by man's activity in a day. Fortunately too, nature, with no help from man, stores in usable form some of the sun's energy&mdash;for periods of months or years in the cycle of evaporation, precipitation, and drainage; for decades or centuries in lumber; for millennia in coal and oil.
In time, as we deplete the long-term stored supply of available energy, we shall have to rely more heavily on the short-term stores and probably also devise new storage methods to supplement those of nature.


## The arrow of time
\label{sec:14.9}


Familiarity breeds acceptance.
So natural and normal seem the usual events of our everyday life that it is difficult to step apart and look at them with a scientific eye.


Men with the skill and courage to do so led the scientific revolution of the seventeenth century.
Since then, the frontiers of physics have moved far from the world of direct sense perception, and even the study of our immediate environment more often than not makes use of sophisticated tools and controlled experiment.
Nevertheless, the ability to take a fresh look at the familiar and to contrast it with what would be the familiar in a different universe with different laws of nature remains a skill worth cultivating.
For the student, and often for the scientist as well, useful insights come from looking at the familiar as if it were unfamiliar.


Consider the second law of thermodynamics.
We need not go to the laboratory or to a machine or even to the kitchen to witness its impact on events.
It is unlikely that you get through any five minutes of your waking life without seeing the second law at work. The way to appreciate this fact is by thinking backward.
Imagine a motion picture of any scene of ordinary life run backward.
You might watch a student untyping a paper, each keystroke erasing another letter as the keys become cleaner and the ribbon fresher.
Or bits of hair clippings on a barber-shop floor rising to join the hair on a customer's head as the barber unclips.
Or a pair of mangled automobiles undergoing instantaneous repair as they back apart.
Or a dead rabbit rising to scamper backward into the woods as a crushed bullet reforms and flies backward into a rifle while some gunpowder is miraculously manufactured out of hot gas.
Or something as simple as a cup of coffee on a table gradually becoming warmer as it draws heat from its cooler surroundings.
All of these backward-in-time views and a myriad more that you can quickly think of are ludicrous and impossible for one reason only&mdash;they violate the second law of thermodynamics.
In the actual sequence of events, entropy is increasing. In the time reversed view, entropy is decreasing.
We recognize at once the obvious impossibility of the process in which entropy decreases, even though we may never have thought about entropy increase in the everyday world.
In a certain sense everyone &ldquo;knows&rdquo; the second law of thermodynamics.
It distinguishes the possible from the impossible in ordinary affairs.


In some of the examples cited above, the action of the second law is obvious, as in the increasing disorder produced by an automobile colUsion, or the increasing entropy associated with heat flow from a cup of coffee.
In others, it is less obvious.
But whether we can clearly identify the increasing entropy or not, we can be very confident that whenever a sequence of events occurs in our world in one order and not in the other, it is because entropy increase is associated with the possible order, entropy decrease with the impossible order.
The reason for this confidence is quite simple.
We know of no law other than the second law of thermodynamics that assigns to processes of change in the large-scale world a preferred direction in time.
In the submicroscopic world too, time-reversal invariance is a principle governing all or nearly all fundamental processes. [^5]
Here we have an apparent paradox.
In order to understand the paradox and its resolution, we must first understand exactly what is meant by time-reversal invariance.


The principle of time-reversal invariance can be simply stated in terms of hypothetical moving pictures.
If the filmed version of any physical process, or sequence of events, is shown backward, the viewer sees a picture of something that could have happened.
In slightly more technical language, any sequence of events, if executed in the opposite order, is a physically possible sequence of events.
This leads to the rather startling conclusion that it is, in fact, impossible to tell by watching a moving picture of events in nature whether the film is running backward or forward.
How can this principle be reconciled with the gross violations of common sense contained in the backward view of a barber cutting hair, a hunter firing a gun, a child breaking a plate, or the President signing his name?
Does it mean that time-reversal invariance is not a valid law in the macroscopic world?
No.
As far as we know, time-reversal invariance governs every interaction that underlies processes of change in the large-scale world.
The key to resolving the paradox is to recognize that possibility does not mean probability.
Although the spontaneous reassembly of the fragments of an exploded bomb into a whole, unexploded bomb is wildly, ridiculously improbable, it is not, from the most fundamental point of view, impossible.


At every important point where the macroscopic and submicroscopic descriptions of matter touch, the concept of probability is crucial.
The second law of thermodynamics is basically a probabilistic law whose approach to absolute validity increases as the complexity of the system it describes increases.
For a system of half a dozen molecules, entropy decrease is not only possible, it is quite likely, at least some of the time.
All six molecules might cluster in one comer of their container, or the three less energetic molecules might lose energy via collisions to the three more energetic molecules (&ldquo;uphill&rdquo; heat flow).
%% TODO
For a system of $lO^o$ molecules, on the other hand, entropy decrease becomes so improbable that it deserves to be called impossible.
We could wait a billion times the known lifetime of the universe and still never expect to see the time-reversal view of something as simple as a piece of paper being torn in half.
Nevertheless, it is important to realize that the time-reversed process is possible in principle.


Even in the world of particles, a sequence of events may occur with much higher probability in one direction than in the opposite direction.
In the world of human experience, the imbalance of probabilities is so enormous that it no longer makes sense to speak of the more probable direction and the less probable direction.
Instead we speak of the possible and the impossible.
The action of molecular probabilities gives to the flow of events in the large-scale world a unique direction.
The (almost complete) violation of time-reversal invariance by the second law of thermodynamics attaches an arrow to time, a one-way sign for the unfolding of events.
Through this idea, thermodynamics impinges on philosophy.


In the latter part of the nineteenth century, long before time-reversal invariance was appreciated as a fundamental law of submicroscopic nature, physicists realized that the second law had something quite general to say about our passage through time.
There are two aspects of the idea of the arrow of time: first, that the universe, like a wound-up clock, is running down, its supply of available energy ever dwindling; second, that the spontaneous tendency of nature toward greater entropy is what gives man a conception of the unique one-way direction of time.


The second law of thermodynamics had not long been formulated in a general way before men reflected on its implications for the universe at large.
In 1865, Clausius wrote, without fanfare, as grand a pair of statements about the world as any produced by science: &ldquo;We can express the fundamental laws of the universe which correspond to the two fundamental laws of the mechanical theory of heat in the following simple form.

<ol type="1">
  <li>The energy of the universe is constant.</li>
  <li>The entropy of the universe tends toward a maximum.</li>
</ol> 

These are the first and second laws of thermodynamics extended to encompass all of nature.
Are the extensions justifiable?
If so, what are their implications?
We know in fact no more than Clausius about the constancy of energy and the steady increase of entropy in the universe at large.
We do know that energy conservation has withstood every test since he wrote, and that entropy increase is founded on the very solid principle of change from arrangements of lesser to those of greater probability.
Nevertheless, all that we have learned of nature in the century since Clausius leaped boldly to the edge of existence should make us cautious about so great a step.
In 1865, the single theory of Newtonian mechanics seemed to be valid in every extremity of nature, from the molecular to the planetary.
A century later we know instead that it fails in every extremity&mdash;in the domain of small sizes, where quantum mechanics rules; in the domain of high speed, where special relativity changes the rules; and in the domain of the very large, where general relativity warps space and time.


The logical terminus of the imiverse, assuming it to be a system obeying the same laws as the macroscopic systems accessible to experiment, is known as the &ldquo;heat death,&rdquo; a universal soup of uniform density and uniform temperature, devoid of available energy, incapable of further change, a perfect and featureless final disorder.
If this is where the universe is headed, we have had no hints of it as yet. Over a time span of ten billion years or more, the imiverse has been a vigorously active place, with new stars still being born as old ones are dying.
It is quite possible that the long-range fate of the universe will be settled within science and need not remain forever a topic of pure speculation.
At present, however, we have no evidence at all to confirm or contradict the applicability of thermodynamics to the universe as a whole.
Even if we choose to postulate its applicability, we need not be led inevitably to the idea of the ultimate heat death.
The existence of a law of time-reversal invariance in the world of the small and the essential probabilistic nature of the second law leave open the possibility that one grand improbable reversal of probability could occur in which disorder is restored to order.
Finally, we can link this line of thought to the second aspect of the arrow of time, the uniqueness of the direction of man's course through time, with this challenging thought.
If it is the second law that gives to man his sense of time's direction, the very construction of the human machine forces us to see the universe running down.
In a world that we might look in upon from the outside to see building order out of disorder, the less probable from the more probable, we would see creatures who remembered their future and not their past.
For them the trend of events would seem to be toward disorder and greater probability and it is we who would seem to be turned around.


In the three centuries since Newton, time has evolved from the obvious to the mysterious.
In the Principia, Newton wrote, &ldquo;Absolute, true, and mathematical time, of itself, and from its own nature flows equably without regard to anything external, and by another name is called duration.&rdquo;
This view of time as something flowing constantly and inexorably forward, carrying man with it, persisted largely intact imtil the revolution of relativity at the beginning of this century.
The nineteenth century brought only hints of a deeper insight, when it was appreciated that the second law of thermodynamics differentiated between forward and backward in time, as the laws of mechanics had failed to do.
If time were run backward, the reversed planetary orbits would be reasonable and possible, obeying the same laws as the actual forward-in-time orbits.
But the reversal of any entropy changing transformation would be neither reasonable nor possible.
The second law of thermodynamics points the way for Newton's equable flow.


Relativity had the most profound effect on our conception of time.
The merger of space and time made unreasonable a temporal arrow when there was no spatial arrow.
More recently, time-reversal invariance has confirmed the equal status of both directions in time.
Relativity also brought time to a stop.
It is more consistent with the viewpoint of modern physics to think of man and matter moving through time (as they move through space) than to think of time itself as flowing.


All of the new insights about time make clear that we must think about it in very human terms&mdash;its definition, its measurement, its apparently unique direction stem not from &ldquo;absolute, true and mathematical time&rdquo; but from psychological time.
These insights also reinforce the idea that the second law of thermodynamics must ultimately account for our sense of time.


It is a stimulating idea that the only reason man is aware of the past and not the future is that he is a complicated and highly organized structure.
Unfortunately, simpler creatures are no better off.
They equalize future and past by remembering neither.
An electron, being precisely identical with every other electron, is totally unmarked by its past or by its future.
Man is intelligent enough to be scarred by his past.
But the same complexity that gives him a memory at all is what keeps his future a mystery.

### Exercises

<ol type="1">
  <li>Section \ref{sec:14.1} describes three kinds of uncertainty, associated respectively with a spelunker, a gambler, and a uranium prospector. Which of these kinds of uncertainty characterizes each of the following situations?</li>
  <ol type="1">
    <li>A pion of known energy enters a bubble chamber. The number of bubbles formed along its first centimeter of track is measured. The number of bubbles along its second centimeter of track can then be predicted approximately, but not exactly.</li>
    <li>Another pion is created in the chamber. How long it will live before decaying is uncertain.</li>
    <li>Still another pion, of energy higher than any previously studied, strikes a nucleus. The result of the collision is uncertain. Which, if any, of these examples of uncertainty is governed by thermodynamic probability (the probability of atomic multitudes)?</li>
  </ol>
  <li>Suppose that a small cylinder (see figure) could be so nearly perfectly evacuated that only 100 molecules remained within it.</li>
  <ol type="1">
    <li>Using [Figure 14-3](#fig14-3) and [Figure 14-4](#fig14-4) and [Equation 14-1](#eq14-1) as guides, sketch a curve of relative probability for any number of these molecules to be found in region A, A B which is half of the container.</li>
    <li>If you placed a bet at even money that a measurement would reveal exactly 50 molecules in region <span class="math">A</span>, would this be, from your point of view, a good bet or a poor bet?</li>
    <li>If you bet, also at even money, that a series of measurements would show less than 60 molecules in region <span class="math">A</span> more often than not, would you be making a good bet or a poor bet?</li>
  </ol>
</ol> 

<!--
\begin{enumerate}
    \item Section \ref{sec:14.1} describes three kinds of uncertainty, associated respectively with a spelunker, a gambler, and a uranium prospector.
        Which of these kinds of uncertainty characterizes each of the following situations?
        \begin{enumerate}
            \item A pion of known energy enters a bubble chamber.
                The number of bubbles formed along its first centimeter of track is measured.
                The number of bubbles along its second centimeter of track can then be predicted approximately, but not exactly.
            \item Another pion is created in the chamber.
                How long it will live before decaying is uncertain.
            \item Still another pion, of energy higher than any previously studied, strikes a nucleus.
                The result of the collision is uncertain.
                Which, if any, of these examples of uncertainty is governed by thermodynamic probability (the probability of atomic multitudes)?
        \end{enumerate}

    \item Suppose that a small cylinder (see figure) could be so nearly perfectly evacuated that only 100 molecules remained within it.
        \begin{enumerate}
            \item Using Figures \ref{fig:14.3} and \ref{fig:14.4} and Equation \ref{eq:14.1} as guides, sketch a curve of relative probability for any number of these molecules to be found in region A, A B which is half of the container.
            \item) If you placed a bet at even money that a measurement would reveal exactly 50 molecules in region <span class="math">A</span>, would this be, from your point of view, a good bet or a poor bet?
            \item If you bet, also at even money, that a series of measurements would show less than 60 molecules in region <span class="math">A</span> more often than not, would you be making a good bet or a poor bet?
        \end{enumerate}
\end{enumerate}
-->

<figure>
<figcaption>
    diagram of tube split into region <span class="math">A</span> and <span class="math">B</span>
</figcaption>
</figure>


[^1]: Because classical mechanics does not suffice to calculate exactly the outcome of an atomic collision, this hypothetical forecast of future atomic positions and velocities could be extended but a moment forward in time.

[^2]: Since each coin can land in two ways, the total number of ways in which five coins can land is 2 &times; 2 &times; 2 &times; 2 &times; 2 &times; = 2<sup>5</sup> = 32. Three coins could land in 8 different ways (2<sup>3</sup>), four coins in 16 ways (2<sup>3</sup>), and so on. In how many ways could 10 coins land?

[^3]: The reader familiar with binomial coefficients may be interested to know that the number of arrangements of <span class="math">n</span> coins to yield <span class="math">m</span> heads is the binomial coefficient <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\binom{n}{m} = \frac{n!}{m! (n-m)!}" display="block"><mrow><mfenced><mfrac linethickness="0"><mrow><mi>n</mi></mrow><mrow><mi>m</mi></mrow></mfrac></mfenced><mo>=</mo><mrow><mfrac><mrow><mi>n</mi><mo>!</mo></mrow><mrow><mi>m</mi><mo>!</mo><mo>&InvisibleTimes;</mo><mfenced><mi>n</mi><mo>&minus;</mo><mi>m</mi></mfenced><mo>!</mi></mrow></mfrac></mrow></mrow></math> Thus the probabilities in [Table 14-3](#tab14-3) are proportional to <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\binom{n}{m} = \frac{n!}{m! (n-m)!}" display="block"><mrow><mfenced><mfrac linethickness="0"><mrow><mn>10</mn></mrow><mrow><mn>0</mn></mrow></mfrac></mfenced><ms>,</ms><mspace width="1em"><mfenced><mfrac linethickness="0"><mrow><mn>10</mn></mrow><mrow><mn>1</mn></mrow></mfrac></mfenced><ms>,</ms><mspace width="1em"><mfenced><mfrac linethickness="0"><mrow><mn>10</mn></mrow><mrow><mn>2</mn></mrow></mfrac></mfenced><ms>,</ms></mrow></math> and so on.

[^4]: Logarithms are defined in such a way that the logarithms of 10, 100, 1,000, and 10,000 or of 5, 10, 20, 40, and 80 differ by equal steps. It is this feature which makes the multiphcation of a pair of numbers equivalent to the addition of their logarithms.

[^5]: For the first time in 1964, some doubt was cast on the universal validity of time-reversal invariance, which had previously been supposed to be an absolute law of nature. In 1968 the doubt remains unresolved. Even if found to be imperfect, the principle will remain valid to a high degree of approximation, since it has already been tested in many situations. In particular, since all interactions that have any effect on the large-scale world do obey the principle of time-reversal invariance, the discussion in this section will be unaffected.


