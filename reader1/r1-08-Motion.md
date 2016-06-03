---
layout: ebook
title: Motion
author: Richard P. Feynman, Robert B. Leighton, and Mathew Sands
excerpt: The treatment of speed and acceleration demonstrates the value of simple calculus in analyzing and describing motion.
intro: Richard P. Feynman, Robert B. Leighton and Matthew Sands A chapter from <em>The Feynman Lectures on Physics&mdash;Volume 1</em>, 1963.
---

## Description of motion

In order to find the laws governing the various changes that take place in bodies as time goes on, we must be able to <em>describe</em> the changes and have some way to record them.
The simplest change to observe in a body is the apparent change in its position with time, which we call motion.
Let us consider some solid object with a permanent mark, which we shall call a point, that we can observe.
We shall discuss the motion of the little marker, which might be the radiator cap of an automobile or the center of a falling ball, and shall try to describe the fact that it moves and how it moves.

These examples may sound trivial, but many subtleties enter into the description of change.
Some changes are more difficult to describe than the motion of a point on a solid object, for example the speed of drift of a cloud that is drifting very slowly, but rapidly forming or evaporating, or the change of a woman&#39;s mind.
We do not know a simple way to analyze a change of mind, but since the cloud can be represented or described by many molecules, perhaps we can describe the motion of the cloud in principle by describing the motion of all its individual molecules.
Likewise, perhaps even the changes in the mind may have a parallel in changes of the atoms inside the brain, but we have no such knowledge yet.

At any rate, that is why we begin with the motion of points;
    perhaps we should think of them as atoms, but it is probably better to be more rough in the beginning and simply to think of some kind of small objects&mdash;small, that is, compared with the distance moved.
For instance, in describing the motion of a car that is going a hundred miles, we do not have to distinguish between the front and the back of the car.
To be sure, there are slight differences, but for rough purposes we say &ldquo;the car,&rdquo; and likewise it does not matter that our points are not absolute points; for our present purposes it is not necessary to be extremely precise.
Also, while we take a first look at this subject we are going to forget about the three dimensions of the world.
We shall just concentrate on moving in one direction, as in a car on one road.
We shall return to three dimensions after we see how to describe motion in one dimension.
Now, you may say, &ldquo;This is all some kind of trivia,&rdquo; and indeed it is.
How can we describe such a one-dimensional motion&mdash;let us say, of a car?
Nothing could be simpler.
Among many possible ways, one would be the following.
To determine the position of the car at different times, we measure its distance from the starting point and record all the observations.

<figure id="tab8-1">
<table >
  <tr>
    <th>
      <i>t</i>(min)
    </th>
    <th>
      <i>s</i>(ft)
    </th>
  </tr>
  <tr><td>0</td><td>0</td></tr>
  <tr><td>1</td><td>1200</td></tr>
  <tr><td>2</td><td>4000</td></tr>
  <tr><td>3</td><td>9000</td></tr>
  <tr><td>4</td><td>9500</td></tr>
  <tr><td>5</td><td>9600</td></tr>
  <tr><td>6</td><td>13000</td></tr>
  <tr><td>7</td><td>18000</td></tr>
  <tr><td>8</td><td>23500</td></tr>
  <tr><td>9</td><td>24000</td></tr>
</table>
<figcaption>
  Table 8-1
</figcaption>
</figure>

<figure id="fig8-1">
[fig8-1]: #fig8-1  "Figure 8-1"
<figcaption>
    Fig. 8-1. Graph of distance versus time for the car.
</figcaption>
</figure>


In [Table 8-1](#tab8-1), <i>s</i> represents the distance of the car, in feet, from the starting point, and <i>t</i> represents the time in minutes.
The first line in the table represents zero distance and zero time&mdash;the car has not started yet.
After one minute it has started and has gone 1200 feet.
Then in two minutes, it goes farther&mdash;notice that it picked up more distance in the second minute&mdash;it has accelerated;
    but something happened between 3 and 4 and even more so at 5&mdash;it stopped at a light perhaps?
Then it speeds up again and goes 13,000 feet by the end of 6 minutes, 18,000 feet at the end of 7 minutes, and 23,500 feet in 8 minutes; at 9 minutes it has advanced to only 24,000 feet, because in the last minute it was stopped by a cop.

That is one way to describe the motion.
Another way is by means of a graph.
If we plot the time horizontally and the distance vertically, we obtain a curve something like that shown in [Figure 8-1](fig8-1).
As the time increases, the distance increases, at first very slowly and then more rapidly, and very slowly again for a little while at 4 minutes;
    then it increases again for a few minutes and finally, at 9 minutes, appears to have stopped increasing.
These observations can be made from the graph, without a table.
Obviously, for a complete description one would have to know where the car is at the half-minute marks, too, but we suppose that the graph means something, that the car has some position at all the intermediate times.

The motion of a car is complicated.
For another example we take something that moves in a simpler manner, following more simple laws: a falling ball.
[Table 8-2](#tab8-2} gives the time in seconds and the distance in feet for a falling body.
At zero seconds the ball starts out at zero feet, and at the end of 1 second it has fallen 16 feet.
At the end of 2 seconds, it has fallen 64 feet, at the end of 3 seconds, 144 feet, and so on; if the tabulated numbers are plotted, we get the nice parabolic curve shown in [Figure 8-2](#fig8-2).
The formula for this curve can be written as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s=16t^{2}" display="block" id="eq8-1">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <mn>16</mn>
      <mo>⁢</mo>
      <msup>
        <mi>t</mi>
        <mn>2</mn>
      </msup>
    </mrow>
  </mrow>
</math>

This formula enables us to calculate the distances at any time.
You might say there ought to be a formula for the first graph too.
Actually, one may write such a formula abstractly, as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s=f(t)" display="block" id="eq8-2">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <mi>f</mi>
      <mo>⁢</mo>
      <mrow>
        <mo>(</mo>
        <mi>t</mi>
        <mo>)</mo>
      </mrow>
    </mrow>
  </mrow>
</math>

meaning that <i>s</i> is some quantity depending on <i>t</i> or, in mathematical phraseology,

<figure id="tab8-2">
<table style="width:100%">>
  <tr>
    <th><i>t</i>(sec)</th>
    <th><i>s</i>(ft)</th>
  </tr>
  <tr><td>0</td><td>0</td></tr>
  <tr><td>1</td><td>16</td></tr>
  <tr><td>2</td><td>64</td></tr>
  <tr><td>3</td><td>144</td></tr>
  <tr><td>4</td><td>256</td></tr>
  <tr><td>5</td><td>400</td></tr>
  <tr><td>6</td><td>576</td></tr>
</table>
<figcaption>
  Table 8-2
</figcaption>
</figure>


<figure id="fig8-2">
[fig8-2]: #fig8-2  "Figure 8-2"
<figcaption>
    Fig. 8-2. Graph of distance versus time for a falling body.
</figcaption>
</figure>

<i>s</i> is a function of <i>t</i>.
Since we do not know what the function is, there is no way we can write it in definite algebraic form.

We have now seen two examples of motion, adequately described with very simple ideas, no subtleties.
However, there *are* subtleties&mdash;several of them.
In the first place, what do we mean by *time* and *space*?
It turns out that these deep philosophical questions have to be analyzed very carefully in physics, and this is not so easy to do.
The theory of relativity shows that our ideas of space and time are not as simple as one might think at first sight.
However, for our present purposes, for the accuracy that we need at first, we need not be very careful about defining things precisely.
Perhaps you say, &ldquo;That&#39;s a terrible thing&mdash;I learned that in science we have to define *everything* precisely.&rdquo;
We cannot define *anything* precisely!
If we attempt to, we get into that paralysis of thought that comes to philosophers, who sit opposite each other, one saying to the other, &ldquo;You don&#39;t know what you are talking about!&rdquo;
The second one says, &ldquo;What do you mean by *know*?
What do you mean by *talking*?
What do you mean by *you*?,&rdquo; and so on.
In order to be able to talk constructively, we just have to agree that we are talking about roughly the same thing.
You know as much about time as we need for the present, but remember that there are some subtleties that have to be discussed; we shall discuss them later.

Another subtlety involved, and already mentioned, is that it should be possible to imagine that the moving point we are observing is always located somewhere.
(Of course when we are looking at it, there it is, but maybe when we look away it isn&#39;t there.)
It turns out that in the motion of atoms, that idea also is false&mdash;we cannot find a marker on an atom and watch it move.
That subtlety we shall have to get around in quantum mechanics.
But we are first going to learn what the problems are before introducing the complications, and *then* we shall be in a better position to make corrections, in the light of the more recent knowledge of the subject.
We shall, therefore, take a simple point of view about time and space.
We know what these concepts are in a rough way, and those who have driven a car know what speed means.

## Speed

Even though we know roughly what &ldquo;speed&rdquo; means, there are still some rather deep subtleties; consider that the learned Greeks were never able to adequately describe problems involving velocity.
The subtlety comes when we try to comprehend exactly what is meant by &ldquo;speed.&rdquo;
The Greeks got very confused about this, and a new branch of mathematics had to be discovered beyond the geometry and algebra of the Greeks, Arabs, and Babylonians.
As an illustration of the difficulty, try to solve this problem by sheer algebra:
A balloon is being inflated so that the volume of the balloon is increasing at the rate of 100 cm<sup>3</sup>;
at what speed is the radius increasing when the volume is 1000 cm<sup>3</sup>?
The Greeks were somewhat confused by such problems, being helped, of course, by some very confusing Greeks.
To show that there were difficulties in reasoning about speed at the time, Zeno produced a large number of paradoxes, of which we shall mention one to illustrate his point that there are obvious difficulties in thinking about motion.
&ldquo;Listen,&rdquo; he says, &ldquo;to the following argument: Achilles runs 10 times as fast as a tortoise, nevertheless he can never catch the tortoise.
For, suppose that they start in a race where the tortoise is 100 meters ahead of Achilles;
    then when Achilles has run the 100 meters to the place where the tortoise was, the tortoise has proceeded 10 meters, having run one-tenth as fast.
Now, Achilles has to run another 10 meters to catch up with the tortoise, but on arriving at the end of that run, he finds that the tortoise is still 1 meter ahead of him; running another meter, he finds the tortoise 10 centimeters ahead, and so on, *ad infinitum*.
Therefore, at any moment the tortoise is always ahead of Achilles and Achilles can never catch up with the tortoise.&rdquo;
What is wrong with that?
It is that a finite amount of time can be divided into an infinite number of pieces, just as a length of line can be divided into an infinite number of pieces by dividing repeatedly by two.
And so, although there are an infinite number of steps (in the argument) to the point at which Achilles reaches the tortoise, it doesn&#39;t mean that there is an infinite amount of time.
We can see from this example that there are indeed some subtleties in reasoning about speed.

In order to get to the subtleties in a clearer fashion, we remind you of a joke which you surely must have heard.
At the point where the lady in the car is caught by a cop, the cop comes up to her and says, &ldquo;Lady, you were going 60 miles an hour!&rdquo;
She says, &ldquo;That&#39;s impossible, sir, I was travelling for only seven minutes.
It is ridiculous&mdash;how can I go 60 miles an hour when I wasn&#39;t going an hour?&rdquo;
How would you answer her if you were the cop?
Of course, if you were really the cop, then no subtleties are involved;
    it is very simple: you say, &ldquo;Tell that to the judge!&rdquo;
But let us suppose that we do not have that escape and we make a more honest, intellectual attack on the problem, and try to explain to this lady what we mean by the idea that she was going 60 miles an hour.
Just what *do* we mean?
We say, &ldquo;What we mean, lady, is this: if you kept on going the same way as you are going now, in the next hour you would go 60 miles.&rdquo;
She could say, &ldquo;Well, my foot was off the accelerator and the car was slowing down, so if I kept on going that way it would not go 60 miles.&rdquo;
Or consider the falling ball and suppose we want to know its speed at the time three seconds if the ball kept on going the way it is going. What does that mean&mdash;kept on *accelerating*, going faster?
No&mdash;kept on going with the same *velocity*.
But that is what we are trying to define!
For if the ball keeps on going the way it is going, it will just keep on going the way it is going.
Thus we need to define the velocity better. What has to be kept the same?
The lady can also argue this way: &ldquo;If I kept on going the way I&#39;m going for one more hour, I would run into that wall at the end of the street!&rdquo;
It is not so easy to say what we mean.

Many physicists think that measurement is the only definition of anything.
Obviously, then, we should use the instrument that measures the speed&mdash;the speedometer&mdash;and say, &ldquo;Look, lady, your speedometer reads 60.&rdquo;
So she says, &ldquo;My speedometer is broken and didn&#39;t read at all.&rdquo;
Does that mean the car is standing still?
We believe that there is something to measure before we build the speedometer.
Only then can we say, for example, &ldquo;The speedometer isn&#39;t working right,&rdquo; or &ldquo;the speedometer is broken.&rdquo;
That would be a meaningless sentence if the velocity had no meaning independent of the speedometer.
So we have in our minds, obviously, an idea that is independent of the speedometer, and the speedometer is meant only to measure this idea.
So let us see if we can get a better definition of the idea.
We say, &ldquo;Yes, of course, before you went an hour, you would hit that wall, but if you went one second, you would go 88 feet; lady, you were going 88 feet per second, and if you kept on going, the next second it would be 88 feet, and the wall down there is farther away than that.&rdquo;
She says, &ldquo;Yes, but there&#39;s no law against going 88 feet per second!
There is only a law against going 60 miles an hour.&rdquo;
&ldquo;But,&rdquo; we reply, &ldquo;it&#39;s the same thing.&rdquo;
If it is the same thing, it should not be necessary to go into this circumlocution about 88 feet per second.
In fact, the falling ball could not keep going the same way even one second because it would be changing speed, and we shall have to define speed somehow.

Now we seem to be getting on the right track; it goes something like this:
If the lady kept on going for another 1/1000 of an hour, she would go 1/1000 of 60 miles.
In other words, she does not have to keep on going for the whole hour;
    the point is that for a moment she is going at that speed.
Now what that means is that if she went just a little bit more in time,
    the extra distance she goes would be the same as that of a car that goes at a *steady* speed of 60 miles an hour.
Perhaps the idea of the 88 feet per second is right;
    we see how far she went in the last second, divide by 88 feet,
    and if it comes out 1 the speed was 60 miles an hour.
In other words, we can find the speed in this way:
    We ask, how far do we go in a very short time?
We divide that distance by the time, and that gives the speed.
But the time should be made as short as possible, the shorter the better, because some change could take place during that time.
If we take the time of a falling body as an hour, the idea is ridiculous.
If we take it as a second, the result is pretty good for a car, because there is not much change in speed, but not for a falling body; so in order to get the speed more and more accurately, we should take a smaller and smaller time interval.
What we should do is take a millionth of a second, and divide that distance by a millionth of a second.
The result gives the distance per second, which is what we mean by the velocity, so we can define it that way. That is a successful answer for the lady, or rather, that is the definition that we are going to use.

The foregoing definition involves a new idea,
    an idea that was not available to the Greeks in a general form.
That idea was to take an infinitesimal distance and the corresponding infinitesimal time,
    form the ratio, and watch what happens to that ratio as the time that we use gets smaller and smaller and smaller.
In other words, take a limit of the distance travelled divided by the time required,
    as the time taken gets smaller and smaller, ad infinitum.
This idea was invented by Newton and by Leibnitz, independently,
    and is the beginning of a new branch of mathematics, called the differential calculus.
Calculus was invented in order to describe motion,
    and its first application was to the problem of defining what is meant by going &ldquo;60 miles an hour.&rdquo;

Let us try to define velocity a little better.
Suppose that in a short time, <i>&epsilon;</i>, the car or other body goes a short distance <i>x</i>; then the velocity, <i>v</i>, is defined as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v=\frac{x}{\epsilon}" display="block">
  <mrow>
    <mi>v</mi>
    <mo>=</mo>
    <mfrac>
      <mi>x</mi>
      <mi>&epsilon;</mi>
    </mfrac>
  </mrow>
</math>

an approximation that becomes better and better as the <i>&epsilons;</i> is taken smaller and smaller.
If a mathematical expression is desired,
we can say that the velocity equals the limit as the <i>&epsilon;</i> is made to go smaller and smaller in the expression <i>x&#8725;&epsilon;</i>, or

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v=\lim_{\epsilon\to 0}\frac{x}{\epsilon}" display="block" id="eq8-3">
  <mrow>
    <mi>v</mi>
    <mo>=</mo>
    <mrow>
      <munder>
        <mo movablelimits="false">lim</mo>
        <mrow>
          <mi>&epsilon;</mi>
          <mo>→</mo>
          <mn>0</mn>
        </mrow>
      </munder>
      <mo>⁡</mo>
      <mfrac>
        <mi>x</mi>
        <mi>&epsilon;</mi>
      </mfrac>
    </mrow>
  </mrow>
</math>

We cannot do the same thing with the lady in the car,
    because the table is incomplete.
We know only where she was at intervals of one minute;
    we can get a rough idea that she was going 5000 feet per minute during the 7th minute,
    but we do not know, at exactly the moment 7 minutes,
    whether she had been speeding up and the speed was 4900 feet per minute at the beginning of the 6th minute, and is now 5100 feet per minute, or something else, because we do not have the exact details in between.
So only if the table were completed with an infinite number of entries could we really calculate the velocity from such a table.
On the other hand, when we have a complete mathematical formula, as in the case of a falling body ([Equation 8-1](#eq8-1), then it is possible to calculate the velocity, because we can calculate the position at any time whatsoever.

Let us take as an example the problem of determining the velocity of the falling ball at the particular time 5 seconds.
One way to do this is to see from [Table 8-2](#tab8-2) what it did in the 5<sup>th</sup> second; it went 400&minus;256=144 ft, so it is going 144 ft/sec;
    however, that is wrong, because the speed is changing; on the average it is 144 ft/sec during this interval, but the ball is speeding up and is really going faster than 144 ft/sec.
We want to find out <em>exactly how fast</em>.
The technique involved in this process is the following: We know where the ball was at 5 sec.
At 5.1 sec, the distance that it has gone all together is 16 (5.1)<sup>2</sup> = 416.16 ft (see [Equation 8-1](#eq8-1).
At 5 sec it had already fallen 400 ft;
    in the last tenth of a second it fell 416.16 &minus; 400 = 16.16 ft.
Since 16.16 ft in 0.1 sec is the same as 161.6 ft/sec,
    that is the speed more or less, but it is not exactly correct.
Is that the speed at 5 sec, or at 5.1 sec,
or halfway between at 5.05 sec, or when <em>is</em> that the speed?
Never mind&mdash;the problem was to find the speed at 5 seconds,
    and we do not have exactly that;
    we have to do a better job.
So, we take one-thousandth of a second more than 5 sec,
    or 5.001 sec, and calculate the total fall as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext=" s = 16 \left(5.001\right)^2 = 16 \left( 25.010001 \right) = 400.160016\, \text{ft}." display="block" id="eq8-3">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <mn>16</mn>
      <mn>&InvisibleTimes;</mn>
      <msup>
        <mfenced>
          <mn>5.001</mn>
        </mfenced>
        <mn>2</mn>
      </msup>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mn>16</mn>
      <mo>&InvisibleTimes;</mo>
      <mfenced>
        <mn>25.010001</mn>
      </mfenced>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mn>400.160016</mn>
      <mo>&InvisibleTimes;</mo>
      <mtext>ft</mtext>
    </mrow>
  </mrow>
</math>

In the last 0.001 sec the ball fell 0.160016 ft,
    and if we divide this number by 0.001 sec we obtain the speed as 160.016 ft/sec.
That is closer, very close, but it is still not exact.
It should now be evident what we must do to find the speed exactly.
To perform the mathematics we state the problem a little more abstractly:
    to find the velocity at a special time, to, which in the original problem was 5 sec.
    Now the distance at <i>t</i><sub>0</sub>, which we call <i>s</i><sub>0</sub>, is 16<i>t</i><sub>0</sub>, or 400 ft in this case.
    In order to find the velocity, we ask, &ldquo;At the time <span class="math"><i>t</i><sub>0</sub> + (a little bit)</span>, or <span class="math"><i>t</i><sub>0</sub> + <i>&epsilon;</i></span>, where is the body?&rdquo;
The new position is <span class="math">16(<i>t</i><sub>0</sub> + <i>&epsilon;</i>)<sup>2</sup> = 16t<sub>0</sub><sup>2</sup> + 32 t<sub>0</sub> &epsilon; + 16&epsilon;<sup>2</sup></span>.
So it is farther along than it was before, because before it was only 16<i>t</i><sub>0</sub>.
This distance we shall call <i>s</i><sub>0</sub> + (a little bit more), or <i>s</i><sub>0</sub> + <i>x</i> (if <i>x</i> is the extra bit).
Now if we subtract the distance at to from the distance at <i>t</i><sub>0</sub> + <i>&epsilon;</i>,
we get <i>x</i>, the extra distance gone, as <span class="math"><i>x</i> = 32<i>t</i><sub>0</sub>&middot;<i>&epsilon;</i> + 16<i>&epsilon;</i><sup>2</sup></span>.
Our first approximation to the velocity is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v=\frac{x}{\epsilon}=32t_{0}+16\epsilon" display="block" id="eq8-4">
  <mrow>
    <mi>v</mi>
    <mo>=</mo>
    <mfrac>
      <mi>x</mi>
      <mi>&epsilon;</mi>
    </mfrac>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mn>32</mn>
        <mo>⁢</mo>
        <msub>
          <mi>t</mi>
          <mn>0</mn>
        </msub>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mn>16</mn>
        <mo>⁢</mo>
        <mi>&epsilon;</mi>
      </mrow>
    </mrow>
  </mrow>
</math>


The true velocity is the value of this ratio, <i>x&#8725;&epsilon;</span>,
    when <i>&epsilon;</i> becomes vanishingly small.
In other words, after forming the ratio,
    we take the limit as e gets smaller and smaller, that is, approaches 0.
The equation reduces to,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v(at time t_0)=32 t_{0}" display="block">
  <mrow>
    <mi>v</mi>
    <mfenced>
      <mtext>at time <i>t</i><sub>0</sub></mtext>
    </mfenced>
    <mo>=</mo>
    <mrow>
      <mn>32</mn>
      <mo>&InvisibleTimes;</mo>
      <msub>
        <mi>t</mi>
        <mn>0</mn>
      </msub>
    <mrow>
  </mrow>
</math>


In our problem, <i>t</i><sub>0</sub> = 5 sec,
so the solution is <i>v</i>=32&times;5 = 160 ft/sec.
A few lines above, where we took <i>&epsilon;</i> as 0.1 sec and 0.01 sec successively,
    the value we got for <i>v</i> was a little more than this,
    but now we see that the actual velocity is precisely 160 ft/sec.

## Speed as a derivative

The procedure we have just carried out is performed so often in mathematics that for convenience special notations have been assigned to our quantities <i>&epsilon;</i> and <i>x</i>.
In this notation, the <i>&epsilon;</in> used above becomes <i>&Delta;t</i> and <i>x</i> becomes <i>&Delta;s</i>.
This &Delta;<i>t</i> means &ldquo;an extra bit of <i>t</i>,&rdquo; and carries an implication that it can be made smaller.
The prefix &Delta; is not a multiplier,
    any more than sin &theta; means s&middot;i&middot;n&middot;&theta;&mdash;it simply defines a time increment,
    and reminds us of its special character.
As has an analogous meaning for the distance <i>s</i>.
Since &Delta; is not a factor,
    it cannot be cancelled in the ratio &Delta;<i>s</i>&#8725;&Delta;<i>t</i> to give <i>s&#8725;t</i>,
    any more than the ratio sin &theta;/sin 2&theta; can be reduced to 1/2 by cancellation.
In this notation, velocity is equal to the limit of
    &Delta;<i>s</i>&#8725;&Delta;<i>t</i> when &Delta;<i>t</i> gets smaller, or

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v=\lim_{\Delta t\to 0}\frac{\Delta s}{\Delta t}" display="block" id="eq8-5">
  <mrow>
    <mi>v</mi>
    <mo>=</mo>
    <mrow>
      <munder>
        <mo movablelimits="false">lim</mo>
        <mrow>
          <mrow>
            <mi mathvariant="normal">&Delta;</mi>
            <mo>&InvisibleTimes;⁢</mo>
            <mi>t</mi>
          </mrow>
          <mo>&rarr;</mo>
          <mn>0</mn>
        </mrow>
      </munder>
      <mo>⁡</mo>
      <mfrac>
        <mrow>
          <mi mathvariant="normal">&Delta;</mi>
          <mo>&InvisibleTimes;⁢</mo>
          <mi>s</mi>
        </mrow>
        <mrow>
          <mi mathvariant="normal">&Delta;</mi>
          <mo>&InvisibleTimes;⁢</mo>
          <mi>t</mi>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

This is really the same as our previous expression ([Equation 8.3](#eq8-3)) with <i>&epsilon;</i> and <i>x</i>,
    but it has the advantage of showing that something is changing,
    and it keeps track of what is changing.

Incidentally, to a good approximation we have another law,
    which says that the change in distance of a moving point is the velocity times the time interval,
    or &Delta;<i>s</i> = <i>v</i>&Delta;<i>t</i>.
This statement is true only if the velocity is not changing during that time interval,
and this condition is true only in the limit as &Delta;<i>t</i> goes to 0.
Physicists like to write it d<i>s</i> = <i>v</i> d<i>t</i>,
because by d<i>t</i> they mean &Delta;<i>t</i> in circumstances in which it is very small;
    with this understanding, the expression is valid to a close approximation.
    If &Delta;<i>t</i> is too long, the velocity might change during the interval,
    and the approximation would become less accurate.
    For a time d<i>t</i>, approaching zero, d<i>s</i> = <i>v</i> d<i>t</i> precisely.
In this notation we can write ([Equation 8-5](eq8-5)) as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v = \lim_{\Delta t \to 0} \frac{\Delta s}{\Delta t} = \frac{ds}{dt}" display="block">
  <mrow>
    <mi>v</mi>
  <mrow>
  <mo>=</mo>
  <mrow>
    <munder>
      <mo movablelimits="false">lim</mo>
      <mrow>
        <mrow>
          <mi mathvariant="normal">&Delta;</mi>
          <mo>&InvisibleTimes;⁢</mo>
          <mi>t</mi>
        </mrow>
        <mo>&rarr;</mo>
        <mn>0</mn>
      </mrow>
    </munder>
    <mfrac>
      <mrow>
        <mi mathvariant="normal">&Delta;</mi>
        <mo>&InvisibleTimes;⁢</mo>
        <mi>s</mi>
      </mrow>
      <mrow>
        <mi mathvariant="normal">&Delta;</mi>
        <mo>&InvisibleTimes;⁢</mo>
        <mi>t</mi>
      </mrow>
    </mfrac>
  <mrow>
  <mo>=</mo>
  <mrow>
    <mfrac>
      <mrow>
        <msub>
          <mo>&dd;</mo>
          <mi>s</mi>
        </msub>
        <mi>s</mi>
      </mrow>
      <mrow>
        <mo>&dd;</mo>
        <mi>t</mi>
      </mrow>
    </mfrac>
  </mrow>
</math>

The quantity d<i>s</i>&#8725;d<i>t</i> which we found above is called the &ldquo;derivative of <i>s</i> with respect to?&rdquo;
(this language helps to keep track of what was changed), and the complicated process of finding it is called finding a derivative, or differentiating.
The d<i>s</i>&#39;s and d<i>t</i>&#39;s which appear separately are called <em>differentials</em>.
To familiarize you with the words, we say we found the derivative of the function 16 <i>t</i><sup>2</sup>,
or the derivative (with respect to <i>t</i>) of 16<i>t</i><sup>2</sup> is 32<i>t</i>.
When we get used to the words, the ideas are more easily understood.
For practice, let us find the derivative of a more complicated function.
We shall consider the formula <i>s</i> = <i>At</i><sup>3</sup> + <i>Bt</i> + <i>C</i>, which might describe the motion of a point.
The letters <i>A</i>, <i>B</i>, and <i>C</i> represent constant numbers, as in the familiar general form of a quadratic equation.
Starting from the formula for the motion, we wish to find the velocity at any time.
To find the velocity in the more elegant manner, we change <i>t</i> to <span class="math"><i>t</i> + &Delta;<i>t</i></span> and note that s is then changed to <i>s</i> + some &Delta;<i>s</i>;
then we find the &Delta;<i>s</i> in terms of &Delta;<i>t</i>.
That is to say,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s + \Delta s &= A \left(t + \Delta t\right)^3 + B \left( t + \Delta t\right) + C  &= A t^3 + Bt + C + 3At^2\Delta{}t + B\Delta{}t + 3At(\Delta t)^2 + A (\Delta t)^3" display="block">
  <mrow>
    <mtable>
      <mtr>
        <mrow>
          <mrow>
            <mi>s</mi>
          <mrow>
          <mo>+</mo>
          <mrow>
            <mo>&Delta;</mo>
            <mi>s</mi>
          <mrow>
        </mrow>
        <mo>=</mo>
        <mrow>
          <mrow>
            <mi>A</mi>
            <msup>
              <mfenced>
                <mi>t</mi>
                <mo>+</mo>
                <mrow>
                  <mo>&Delta;</mo>
                  <mi>t</mi>
                </mrow>
              </mfenced>
              <mn>3</mn>
            </msup>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mi>B</mi>
            <mfenced>
              <mi>t</mi>
              <mo>+</mo>
              <mrow>
                <mo>&Delta;</mo>
                <mi>t</mi>
              </mrow>
            </mfenced>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mi>C</mi>
          </mrow>
        </mrow>
      </mtr>
      <mtr>
        <mo>=</mo>
        <mrow>
          <mrow>
            <mi>A</mi>
            <msup>
              <mi>t</mi>
              <mn>3</mn>
            </msup>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mi>B</mi>
            <mi>t</mi>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mi>C</mi>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mn>3</mn>
            <mi>A</mi>
            <msup>
              <mi>t</mi>
              <mn>2</mn>
            </msup>
            <mo>&Delta;</mo>
            <mi>t</mi>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mi>B</mi>
            <mo>&Delta;</mo>
            <mi>t</mi>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mn>3</mn>
            <mi>A</mi>
            <mi>t</mi>
            <msup>
              <mfenced>
                <mo>&Delta;</mo>
                <mi>t</mi>
              </mfenced>
              <mn>2</mn>
            </msup>
          </mrow>
          <mo>+</mo>
          <mrow>
            <mi>A</mi>
            <msup>
              <mfenced>
                <mo>&Delta;</mo>
                <mi>t</mi>
              </mfenced>
              <mn>3</mn>
            </msup>
          </mrow>
        </mrow>
      </mtr>
    </mtable>
  <mrow>
</math>

but since

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s = At^3 + Bt + C" display="block">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mi>A</mi>
        <mo>&InvisibleTimes;⁢</mo
        <msup>
          <mi>t</mi>
          <mn>3</mn>
        </msup>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mi>B</mi>
        <mo>&InvisibleTimes;⁢</mo>
        <mi>t</mi>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mi>C</mi>
      </mrow>
    </mrow>
  </mrow>
</math>

we find that

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta s = 3At^2 \Delta t + B\Delta t + 3At \Delta t + A(\Delta t)^3" display="block">
  <mrow>
    <mo>&Delta;</mo>
    <mo>&InvisibleTimes;</mo>
    <mi>s</mi>
  </mrow>
  <mo>=</mo>
  <mrow>
    <mrow>
      <mn>3</mn>
      <mi>A</mi>
      <msup>
        <mi>t</mi>
        <mn>3</mn>
      </msup>
      <mo>&Delta;</mo>
      <mi>t</mi>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mi>B</mi>
      <mo>&Delta;</mo>
      <mi>t</mi>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mn>3</mn>
      <mi>A</mi>
      <msup>
        <mfenced>
          <mo>&Delta;</mo>
          <mi>t</mi>
        </mfenced>
        <mn>2</mn>
      </msup>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mi>A</mi>
      <msup>
        <mfenced>
          <mo>&Delta;</mo>
          <mi>t</mi>
        </mfenced>
        <mn>3</mn>
      </msup>
    </mrow>
  </mrow>
</math>

But we do not want &Delta;<i>s</i>&mdash;we want &Delta;<i>s</i> divided by &Delta;<i>t</i>.
We divide the preceding equation by &Delta;<i>t</i>, getting

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{\Delta s}{\Delta t} = 3 \Delta t^2 + B + 3At(\Delta t) + A(\Delta t)^2" display="block">
  <mrow>
    <mfrac>
      <mrow>
        <mo>&Delta;</mo>
        <mi>s</mi>
      </mrow>
      <mrow>
        <mo>&Delta;</mo>
        <mi>t</mi>
      </mrow>
    </mfrac>
  </mrow>
  <mo>=</mo>
  <mrow>
    <mrow>
      <mn>3</mn>
      <mi>A</mi>
      <msup>
        <mi>t</mi>
        <mn>3</mn>
      </msup>
      <mo>&Delta;</mo>
      <mi>t</mi>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mi>B</mi>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mn>3</mn>
      <mi>A</mi>
      <msub>
        <mfenced>
          <mo>&Delta;</mo>
          <mi>t</mi>
        </mfenced>
        <mn>2</mn>
      </msub>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mi>A</mi>
      <msup>
        <mfenced>
          <mo>&Delta;</mo>
          <mi>t</mi>
        </mfenced>
        <mn>2</mn>
      </msup>
    </mrow>
  </mrow>
</math>

As &Delta;<i>t</i> goes toward the limit of &Delta;<i>s</i>&#8725;&Delta;<i>t</i> is d<i>s</i>&#8725;d<i>t</i> and is equal to

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{ds}{dt} = 3At^2 + B" display="block">
  <mrow>
    <mfrac>
      <mrow>
        <mo>&Delta;</mo>
        <mi>s</mi>
      </mrow>
      <mrow>
        <mo>&Delta;</mo>
        <mi>t</mi>
      </mrow>
    </mfrac>
  </mrow>
  <mo>=</mo>
  <mrow>
    <mrow>
      <mn>3</mn>
      <mi>A</mi>
      <msup>
        <mi>t</mi>
        <mn>3</mn>
      </msup>
      <mo>&Delta;</mo>
      <mi>t</mi>
    </mrow>
    <mo>+</mo>
    <mrow>
      <mi>B</mi>
    </mrow>
  </mrow>
</math>

This is the fundamental process of calculus, differentiating functions.
The process is even more simple than it appears.
Observe that when these expansions contain any term with a square or a cube or any higher power of &Delta;<i>t</i>,
    such terms may be dropped at once,
    since they will go to when the limit is taken.
After a little practice the process gets easier because one knows what to leave out.
There are many rules or formulas for differentiating various types of functions.
These can be memorized,
    or can be found in tables.
A short list is found in [Table 8-3](tab8-3).

<figure id="tab8-3">
<table style="width:100%">>
  <tr>
    <th>Function</th>
    <th>Derivative</th>
  </tr>
  <!--Row 1-->
  <tr>
    <td><i>s</i> = <i>t</i><sup>n</sup></td>
    <td>
      <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{ds}{dt}=nt^{n-1}" display="inline">
        <mrow>
          <mfrac>
            <mrow>
              <mo>&dd;</mo>
              <mi>s</mi>
            </mrow>
            <mrow>
              <mo>&dd;</mo>
              <mi>t</mi>
            </mrow>
          </mfrac>
          <mo>=</mo>
          <mrow>
            <mi>n</mi>
            <mo>&InvisibleTimes;</mo>
            <msup>
              <mi>t</mi>
              <mrow>
                <mi>n</mi>
                <mo>&minus;</mo>
                <mn>1</mn>
              </mrow>
            </msup>
          </mrow>
        </mrow>
      </math>
    </td>
  </tr>
  <!--Row 2-->
  <tr>
    <td><i>s</i> = <i>cu</i></td>
    <td>
      <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{ds}{dt}=nt^{n-1}" display="inline">
        <mrow>
          <mfrac>
            <mrow>
              <mo>&dd;</mo>
              <mi>s</mi>
            </mrow>
            <mrow>
              <mo>&dd;</mo>
              <mi>t</mi>
            </mrow>
          </mfrac>
          <mo>=</mo>
          <mrow>
            <mi>c</mi>
            <mo>&InvisibleTimes;</mo>
            <mfrac>
              <mrow>
                <mo>&dd;</mo>
                <mi>u</mi>
              </mrow>
              <mrow>
                <mo>&dd;</mo>
                <mi>t</mi>
              </mrow>
            </mfrac>
          </mrow>
        </mrow>
      </math>
    </td>
  </tr>
  <!--Row 3-->
  <tr>
    <td><i>s</i> = <i>u</i> + <i>v</i> + <i>w</i> + &middot;</td>
    <td>
      <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{ds}{dt}=nt^{n-1}" display="inline">
        <mrow>
          <mfrac>
            <mrow>
              <mo>&dd;</mo>
              <mi>s</mi>
            </mrow>
            <mrow>
              <mo>&dd;</mo>
              <mi>t</mi>
            </mrow>
          </mfrac>
          <mo>=</mo>
          <mrow>
            <mfrac>
              <mrow>
                <mo>&dd;</mo>
                <mi>u</mi>
              </mrow>
              <mrow>
                <mo>&dd;</mo>
                <mi>t</mi>
              </mrow>
            </mfrac>
            <mo>+</mo>
            <mfrac>
              <mrow>
                <mo>&dd;</mo>
                <mi>v</mi>
              </mrow>
              <mrow>
                <mo>&dd;</mo>
                <mi>t</mi>
              </mrow>
            </mfrac>
            <mo>+</mo>
            <mfrac>
              <mrow>
                <mo>&dd;</mo>
                <mi>w</mi>
              </mrow>
              <mrow>
                <mo>&dd;</mo>
                <mi>t</mi>
              </mrow>
            </mfrac>
            <mo>+</mo>
            <ms>&middot;</ms>
          </mrow>
        </mrow>
      </math>
    </td>
  </tr>
  <!--Row 4-->
  <tr>
    <td><i>s</i> = <i>c</i></td>
    <td>
      <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{ds}{dt}=nt^{n-1}" display="inline">
        <mrow>
          <mfrac>
            <mrow>
              <mo>&dd;</mo>
              <mi>s</mi>
            </mrow>
            <mrow>
              <mo>&dd;</mo>
              <mi>t</mi>
            </mrow>
          </mfrac>
          <mo>=</mo>
          <mrow>
            <mn>0</mn>
          </mrow>
        </mrow>
      </math>
    </td>
  </tr>
  <!--Row 5-->
  <tr>
      <td><i>s</i> = <i>u</i><sup>a</sup> <i>v</i><sup>b</sup> <i>w</i><sup>c</sup> &hellip;</td>
    <td>
      <math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\frac{ds}{dt}=nt^{n-1}" display="inline">
        <mrow>
          <mfrac>
            <mrow>
              <mo>&dd;</mo>
              <mi>s</mi>
            </mrow>
            <mrow>
              <mo>&dd;</mo>
              <mi>t</mi>
            </mrow>
          </mfrac>
          <mo>=</mo>
          <mrow>
            <mi>s</mi>
            <mfenced>
              <mrow>
                <mfrac>
                  <mrow>
                    <mi>a</mi>
                  </mrow>
                  <mrow>
                    <mi>u</mi>
                  </mrow>
                </mfrac>
                <mfrac>
                  <mrow>
                    <mo>&dd;</mo>
                    <mi>u</mi>
                  </mrow>
                  <mrow>
                    <mo>&dd;</mo>
                    <mi>t</mi>
                  </mrow>
                </mfrac>
              </mrow>
              <mo>+</mo>
              <mrow>
                <mfrac>
                  <mrow>
                    <mi>b</mi>
                  </mrow>
                  <mrow>
                    <mi>v</mi>
                  </mrow>
                </mfrac>
                <mfrac>
                  <mrow>
                    <mo>&dd;</mo>
                    <mi>v</mi>
                  </mrow>
                  <mrow>
                    <mo>&dd;</mo>
                    <mi>t</mi>
                  </mrow>
                </mfrac>
              </mrow>
              <mo>+</mo>
              <mrow>
                <mfrac>
                  <mrow>
                    <mi>c</mi>
                  </mrow>
                  <mrow>
                    <mi>w</mi>
                  </mrow>
                </mfrac>
                <mfrac>
                  <mrow>
                    <mo>&dd;</mo>
                    <mi>w</mi>
                  </mrow>
                  <mrow>
                    <mo>&dd;</mo>
                    <mi>t</mi>
                  </mrow>
                </mfrac>
              </mrow>
              <mo>+</mo>
              <ms>&middot;</ms>
            </mfenced>
          </mrow>
        </mrow>
      </math>
    </td>
  </tr>
</table>
<figcaption>
    Table 8-3. A Short Table of Derivatives:
    <i>s</i>, <i>u</i>, <i>v</i>, <i>w</i> are arbitrary functions of <i>t</i>; <i>a</i>, <i>b</i>, <i>c</i>, and <i>n</i> are arbitrary constants.
</figcaption>
</figure>

<figure id="tab8-4">
<table style="width:100%">>
  <tr>
    <th>
      <i>t</i>(sec)
    </th>
    <th>
      <i>v</i>(ft/sec)
    </th>
  </tr>
  <tr><td>0</td><td>0</td></tr>
  <tr><td>1</td><td>32</td></tr>
  <tr><td>2</td><td>64</td></tr>
  <tr><td>3</td><td>96</td></tr>
  <tr><td>4</td><td>128</td></tr>
</table>
<figcaption>
    Table 8-4: Velocity of a Falling Ball
</figcaption>
</figure>

## Distance as an integral

Now we have to discuss the inverse problem.
Suppose that instead of a table of distances,
    we have a table of speeds at different times,
    starting from zero.
For the falling ball, such speeds and times are shown in [Table 8-4](tab8-4).
A similar table could be constructed for the velocity of the car,
    by recording the speedometer reading every minute or half-minute.
If we know how fast the car is going at any time,
    can we determine how far it goes?
This problem is just the inverse of the one solved above; we are given the velocity and asked to find the distance.
How can we find the distance if we know the speed?
If the speed of the car is not constant, and the lady goes sixty miles an hour for a moment,
    then slows down, speeds up, and so on, how can we determine how far she has gone?
That is easy.
We use the same idea, and express the distance in terms of infinitesimals.
Let us say, &ldquo;In the first second her speed was such and such,
and from the formula &Delta;<i>s</i> = <i>v</i> &Delta;<i>t</i> we can calculate how far the car went the first second at that speed.&rdquo;
Now in the next second her speed is nearly the same, but slightly different;
    we can calculate how far she went in the next second by taking the new speed times the time.
We proceed similarly for each second, to the end of the run.
We now have a number of little distances,
    and the total distance will be the sum of all these little pieces.
That is, the distance will be the sum of the velocities times the times,
or <i>s</i> = &sum; <i>v</i>&Delta;<i>t</i>, where the Greek letter &Sigma; (sigma) is used to denote addition.
To be more precise, it is the sum of the velocity at a certain time,
let us say the <i>i</i><sup>th</sup> time, multiplied by &Delta;<i>t</i>.

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s=\sum_{i} v(t_i) \Delta t" display="block", id="eq8-6">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <munder>
        <mo>&sum;</mo>
        <mi>i</mi>
      </munder>
      <mrow>
        <mi>v</mi>
        <mfenced>
          <msub>
            <mi>t</mi>
            <mi>i</mi>
          </msub>
        </mfenced>
        <mo>&Delta;</mo>
        <mi>t</mi>
      </mrow>
    </mrow>
  </mrow>
</math>


The rule for the times is that <i>t</i><sub>i+i</sub> = <i>t</i><sub>i</sub> + &Delta;<i>t</i>.
However, the distance we obtain by this method will not be correct,
because the velocity changes during the time interval &Delta;<i>t</i>.
If we take the times short enough, the sum is precise,
    so we take them smaller and smaller until we obtain the desired accuracy.
The true <i>s</i> is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s = \lim_{\Delta t \to 0} \sum_i  v(t_i) \Delta t" display="block", id="eq8-7">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <munder>
        <mo moveablelimits="false">lim</mo>
        <mrow>
          <mrow>
            <mo>&Delta;</mo>
            <mi>t</mi>
          </mrow>
          <mo>&rarr;</mo>
          <mn>0</mn>
        </mrow>
      </munder>
      <mrow>
        <munder>
          <mo largeop="true" moveablelimits="false" symmetric="true">&sum;</mo>
          <mi>i</mi>
        </munder>
        <mrow>
          <mi>v</mi>
          <mfenced>
            <msub>
              <mi>t</mi>
              <mi>i</mi>
            </msub>
          </mfenced>
        </mrow>
        <mo>&Delta;</mo>
        <mi>t</mi>
      </mrow>
    </mrow>
  </mrow>
</math>

The mathematicians have invented a symbol for this limit,
    analogous to the symbol for the differential.
The &Delta; turns into a <i>d</i> to remind us that the time is as small as it can be;
    the velocity is then called <i>v</i> at the time <i>t</i>,
    and the addition is written as a sum with a great &ldquo;s,&rdquo; &int; (from the Latin <em>summa</em>),
    which has become distorted and is now unfortunately just called an integral sign.
Thus we write

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s = \int v(t) dt" display="block" id="eq8-8">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <mo>&int;</mo>
      <mrow>
        <mi>v</mi>
        <mfenced>
          <mi>t</mi>
        </mfenced>
        <mrow>
          <mo>&dd;</mo>
          <mi>t</mi>
        </mrow>
      </mrow>
    </mrow>
  </mrow>
</math>

This process of adding all these terms together is called integration,
    and it is the opposite process to differentiation.
The derivative of this integral is <i>v</i>, so one operator (<i>d</i>) undoes the other (&int;).
One can get formulas for integrals by taking the formulas for derivatives and running them backwards,
    because they are related to each other inversely.
Thus one can work out his own table of integrals by differentiating all sorts of functions.
For every formula with a differential,
    we get an integral formula if we turn it around.

Every function can be differentiated analytically,
    i.e., the process can be carried out algebraically,
    and leads to a definite function.
But it is not possible in a simple manner to write an analytical value for any integral at will.
You can calculate it, for instance, by doing the above sum,
and then doing it again with a finer interval &Delta;<i>t</i> and again with a finer interval until you have it nearly right.
In general, given some particular function, it is not possible to find,
    analytically, what the integral is.
One may always try to find a function which, when differentiated, gives some desired function;
    but one may not find it, and it may not exist,
    in the sense of being expressible in terms of functions that have already been given names.

## Acceleration

The next step in developing the equations of motion is to introduce another idea which goes beyond the concept of velocity to that of change of velocity, and we now ask, &ldquo;How does the velocity change?&rdquo;
In previous chapters we have discussed cases in which forces produce changes in velocity.
You may have heard with great excitement about some car that can get from rest to 60 miles an hour in ten seconds flat.
From such a performance we can see how fast the speed changes, but only on the average.
What we shall now discuss is the next level of complexity,
    which is how fast the velocity is changing.
In other words, by how many feet per second does the velocity change in a second,
    that is, how many feet per second, per second?
    We previously derived the formula for the velocity of a falling body as <i>y</i> = 32<i>t</i>,
    which is charted in [Table 8-4](tab8-4),
    and now we want to find out how much the velocity changes per second;
    this quantity is called the acceleration.

Acceleration is defined as the time rate of change of velocity.
From the preceding discussion we know enough already to write the acceleration as the derivative d<i>v</i>&#8725;d<i>t</i>,
    in the same way that the velocity is the derivative of the distance.
    If we now differentiate the formula <i>v</i>=32<i>t</i> we obtain,
    for a falling body,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="a = \frac{dv}{dt} = 32" display="block" id="eq8-9">
  <mrow>
    <mi>a</mi>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&dd;</mo>
          <mi>v</mi>
        </mrow>
        <mrow>
          <mo>&dd;</mo>
          <mi>t</mi>
        </mrow>
      </mfrac>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mn>32</mn>
    </mrow>
  </mrow>
</math>

[To differentiate the term 32<i>t</i> we can utilize the result obtained in a previous problem, where we found that the derivative of <i>Bt</i> is simply <i>B</i> (a constant).
So by letting <i>B</i> = 32, we have at once that the derivative of 32<i>t</i> is 32.]
This means that the velocity of a falling body is changing by 32 feet per second, per second always.
We also see from [Table 8-4](tab8-4) that the velocity increases by 32 feet per second in each second.
This is a very simple case, for accelerations are usually not constant.
The reason the acceleration is constant here is that the force on the falling body is constant,
    and Newton&#39;s law says that the acceleration is proportional to the force.

As a further example,
    let us find the acceleration in the problem we have already solved for the velocity.
Starting with

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="x = At^3 + Bt + C" display="block">
  <mrow>
    <mi>x</mi>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mi>A</mi>
        <mo>&InvisibleTimes;</mo>
        <msup>
          <mi>t</mi>
          <mn>3</mn>
        </msup>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mi>B</mi>
        <mo>&InvisibleTimes;</mo>
        <mi>t</mi>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mi>C</mi>
      </mrow>
    </mrow>
  </mrow>
</math>

we obtained, for <i>v</i> = d<i>s</i>&#8725;d<i>t</i>,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="x = 3 At^2 + B" display="block">
  <mrow>
    <mi>v</mi>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mn>3</mn>
        <mo>&InvisibleTimes;</mo>
        <mi>A</mi>
        <mo>&InvisibleTimes;</mo>
        <msup>
          <mi>t</mi>
          <mn>2</mn>
        </msup>
      </mrow>
      <mo>+</mo>
      <mrow>
        <mi>B</mi>
      </mrow>
    </mrow>
  </mrow>
</math>

Since acceleration is the derivative of the velocity with respect to the time,
    we need to differentiate the last expression above.
Recall the rule that the derivative of the two terms on the right equals the sum of the derivatives of the individual terms.
To differentiate the first of these terms, instead of going through the fundamental process again we note that we have already differentiated a quadratic term when we differentiated 16<i>t</i><sup>2</sup>,
and the effect was to double the numerical coefficient and change the <i>t</i><sup>2</sup> to <i>t</i>;
    let us assume that the same thing will happen this time, and you can check the result yourself.
    The derivative of 3<i>At</i><sup>2</sup> will then be 6<i>At</i>.
Next we differentiate <i>B</i>, a constant term; but by a rule stated previously,
    the derivative of <i>B</i> is zero; hence this term contributes nothing to the acceleration.
The final result, therefore, is <i>a</i> = d<i>v</i>&#8725;d<i>t</i> = 6<i>At</i>.

For reference, we state two very useful formulas, which can be obtained by integration.
If a body starts from rest and moves with a constant acceleration, <i>g</i>,
    its velocity <i>v</i> at any time <i>t</i> is given by

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v = g t" display="block">
  <mrow>
    <mi>v</mi>
    <mo>=</mo>
    <mrow>
      <mrow>
        <mi>g</mi>
        <mo>&InvisibleTimes;</mo>
        <mi>t</mi>
      </mrow>
    </mrow>
  </mrow>
</math>

The distance it covers in the same time is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="s = \frac{1}{2} gt^2" display="block">
  <mrow>
    <mi>s</mi>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mn>1</mn>
        </mrow>
        <mrow>
          <mn>2</mn>
        </mrow>
      </mfrac>
    </mrow>
    <mrow>
      <mi>g</mi>
      <mo>&InvisibleTimes;</mo>
      <msub>
        <mi>t</mi>
        <mn>2</mn>
      </msub>
    </mrow>
  </mrow>
</math>

Various mathematical notations are used in writing derivatives.
Since velocity is d<i>s</i>&#8725;d<i>t</i> and acceleration is the time derivative of the velocity,
    we can also write

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="a = \frac{d}{dt} \left(\frac{ds}{dt}\right) = \frac{d^2 s}{dt^2}" display="block" id="eq8-10">
  <mrow>
    <mi>a</mi>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&dd</mo>
        </mrow>
        <mrow>
          <mo>&dd</mo>
          <mi>t</mi>
        </mrow>
      </mfrac>
      <mfenced>
        <mfrac>
          <mrow>
            <mo>&dd;</mo>
            <mi>s</mi>
          </mrow>
          <mrow>
            <mo>&dd;</mo>
            <mi>t</mi>
          </mrow>
        </mfrac>
      </mfenced>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <msub>
            <mo>&dd;</mo>
            <mn>2</mn>
          </msub>
          <mi>s</mi>
        </mrow>
        <mrow>
          <mo>&dd;</mo>
          <msub>
            <mi>t</mi>
            <mn>2</mn>
          </msub>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

which are common ways of writing a second derivative.

We have another law that the velocity is equal to the integral of the acceleration.
This is just the opposite of <i>a</i> = d<i>v</i>&#8725;d<i>t</i>;
    we have already seen that distance is the integral of the velocity,
    so distance can be found by twice integrating the acceleration.

In the foregoing discussion the motion was in only one dimension,
    and space permits only a brief discussion of motion in three dimensions.
Consider a particle <i>P</i> which moves in three dimensions in any manner whatsoever.
At the beginning of this chapter,
    we opened our discussion of the one-dimensional case of a moving car by observing the distance of the car from its starting point at various times.
We then discussed velocity in terms of changes of these distances with time,
    and acceleration in terms of changes in velocity.
We can treat three-dimensional motion analogously.
It will be simpler to illustrate the motion on a two-dimensional diagram,
    and then extend the ideas to three dimensions.
We establish a pair of axes at right angles to each other,
    and determine the position of the particle at any moment by measuring how far it is from each of the two axes.
Thus each position is given in terms of an <i>x</i>-distance and a <i>y</i>-distance,
    and the motion can be described by constructing a table in which both these distances are given as functions of time.
(Extension of this process to three dimensions requires only another axis,
at right angles to the first two, and measuring a third distance, the <i>z</i>-distance.
The distances are now measured from coordinate planes instead of lines.)
Having constructed a table with <i>x</i>- and <i>y</i>-distances,
    how can we determine the velocity?
We first find the components of velocity in each direction.
The horizontal part of the velocity, or <i>x</i>-component,
    is the derivative of the <i>x</i>-distance with respect to the time, or


<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v_y = \frac{dx}{dt}" display="block" id="eq8-11">
  <mrow>
    <msub>
      <mi>v</mi>
      <mi>y</mi>
    </msub>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&dd</mo>
          <mi>x</mi>
        </mrow>
        <mrow>
          <mo>&dd</mo>
          <mi>t</mi>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

Similarly, the vertical part of the velocity, or <i>y</i>-component, is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v_y = \frac{dy}{dt}" display="block" id="eq8-12">
  <mrow>
    <msub>
      <mi>v</mi>
      <mi>y</mi>
    </msub>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&dd</mo>
          <mi>y</mi>
        </mrow>
        <mrow>
          <mo>&dd</mo>
          <mi>t</mi>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

In the third dimension,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v_z = \frac{dy}{dt}" display="block" id="eq8-13">
  <mrow>
    <msub>
      <mi>v</mi>
      <mi>z</mi>
    </msub>
    <mo>=</mo>
    <mrow>
      <mfrac>
        <mrow>
          <mo>&dd</mo>
          <mi>z</mi>
        </mrow>
        <mrow>
          <mo>&dd</mo>
          <mi>t</mi>
        </mrow>
      </mfrac>
    </mrow>
  </mrow>
</math>

Now, given the components of velocity,
    how can we find the velocity along the actual path of motion?
In the two-dimensional case, consider two successive positions of the particle,
    separated by a short distance A5 and a short time interval <i>t</i><sub>2</sub>&minus;<i>t</i><sub>1</sub> = &Delta;<i>t</i>.
    In the time &Delta;<i>t</i> the particle moves horizontally a distance &Delta;<i>x</i> &sim; <i>v</i><sub>x</sub> &Delta;<i>t</i>,
    and vertically a distance &Delta;<i>y</i> &sim; <i>v</i><sub>y</sub>&Delta;<i>t</i>.
(The symbol &ldquo;&sim;&rdquo; is read &ldquo;is approximately.&rdquo;)
The actual distance moved is approximately

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="\Delta s \propto \sqrt{ \left(\Delta x\right)^2 + \left(\Delta y\right)^2 }" display="block" id="eq8-14">
  <mrow>
    <mrow>
      <mo>&Delta;</mo>
      <mi>s</mi>
    </mrow>
    <mo>&sim;</mo>
    <mrow>
      <msqrt>
        <msup>
          <mfenced>
            <mo>&Delta;</mo>
            <mi>x</mi>
          </mfenced>
          <mn>2</mn>
        <msup>
        <mo>+</mo>
        <msup>
          <mfenced>
            <mo>&Delta;</mo>
            <mi>y</mi>
          </mfenced>
          <mn>2</mn>
        <msup>
      </msqrt>
    </mrow>
  </mrow>
</math>

as shown in [Figure 8-3](fig8-3).
The approximate velocity during this interval can be obtained by dividing by &Delta;<i>t</i> and by letting &Delta;<i>t</i> go to 0,
    as at the beginning of the chapter.
We then get the velocity as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v = \frac{ds}{dt} = \sqrt{ \left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2 } = \sqrt{ v_x^2 + v_y^2 }" display="block" id="eq8-15">
  <mrow>
    <mrow>
      <mi>v</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <msqrt>
        <msup>
          <mfenced>
            <mfrac>
              <mrow>
                <mo>&dd;</mo>
                <mi>x</mi>
              </mrow>
              <mrow>
                <mo>&dd;</mo>
                <mi>t</mi>
              </mrow>
            </mfrac>
          </mfenced>
          <mn>2</mn>
        <msup>
        <mo>+</mo>
        <msup>
          <mfenced>
            <mfrac>
              <mrow>
                <mo>&dd;</mo>
                <mi>y</mi>
              </mrow>
              <mrow>
                <mo>&dd;</mo>
                <mi>t</mi>
              </mrow>
            </mfrac>
          </mfenced>
          <mn>2</mn>
        <msup>
      </msqrt>
    </mrow>
    <mo>=</mo>
    <mrow>
      <msqrt>
        <msupsub>
          <mi>v</mi>
          <mn>2</mn>
          <mi>x</mi>
        </msupsub>
        <mo>+</mo>
        <msupsub>
          <mi>v</mi>
          <mn>2</mn>
          <mi>y</mi>
        </msupsub>
      </msqrt>
    </mrow>
  </mrow>
</math>

For three dimensions the result is

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v = \sqrt{ v_x^2 + v_y^2 + v_z^2 }" display="block" id="eq8-16">
  <mrow>
    <mrow>
      <mi>v</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <msqrt>
        <msupsub>
          <mi>v</mi>
          <mn>2</mn>
          <mi>x</mi>
        </msupsub>
        <mo>+</mo>
        <msupsub>
          <mi>v</mi>
          <mn>2</mn>
          <mi>y</mi>
        </msupsub>
        <mo>+</mo>
        <msupsub>
          <mi>v</mi>
          <mn>2</mn>
          <mi>z</mi>
        </msupsub>
      </msqrt>
    </mrow>
  </mrow>
</math>

<figure id="fig8-3">
<!-- Insert SVG graph -->
<figcaption>
    Description of the motion of a body in two dimensions and the computation of its velocity.
</figcaption>
</figure>

<figure id="fig8-4">
<!-- Insert SVG graph -->
<figcaption>
    The parabola described by a falling body with an initial horizontal velocity.
</figcaption>
</figure>

In the same way as we defined velocities, we can define accelerations:
we have an <i>x</i>-component of acceleration <i>a</i><sub>x</sub>, which is the derivative of <i>v</i><sub>x</sub>,
        the <i>x</i>-component of the velocity (that is, <i>a</i><sub>x</sub> = d<sup>2</sup><i>x</i>&#8725;d<i>t</i><sup>2</sup>,
    the second derivative of <i>x</i> with respect to <i>t</i>), and so on.

Let us consider one nice example of compound motion in a plane.
We shall take a motion in which a ball moves horizontally with a constant velocity <i>u</i>,
    and at the same time goes vertically downward with a constant acceleration &minus;<i>g</i>;
    what is the motion?
We can say d<i>x</i>&#8725;d<i>t</i> = <i>v</i><sub>x</sub> = <i>u</i>.
Since the velocity <i>v</i><sub>x</sub> is constant,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="x = ut" display="block" id="eq8-17">
  <mrow>
    <mrow>
      <mi>x</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mi>u</mi>
      <mi>t</mi>
    </mrow>
  </mrow>
</math>

and since the downward acceleration &minus;<i>g</i> is constant,
    the distance <i>y</i> the object falls can be written as

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="y = -\frac{1}{2} g t^2" display="block" id="eq8-18">
  <mrow>
    <mrow>
      <mi>x</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mo>&minus;</mo>
      <mfrac>
        <mn>1</mn>
        <mn>2</mn>
      </mfrac>
      <mi>g</mi>
      <msup>
        <mi>t</mi>
        <mn>2</mn>
      </msup>
    </mrow>
  </mrow>
</math>

What is the curve of its path, i.e., what is the relation between <i>y</i> and <i>x</i>?
We can eliminate <i>t</i> from [Equation 8-18](eq8-18), since <span class="math"><i>t</i> = <i>x&#8725;u</i></span>.
When we make this substitution we find that

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="y = -\frac{g}{2\mu^2} x^2" display="block" id="eq8-19">
  <mrow>
    <mrow>
      <mi>y</mi>
    </mrow>
    <mo>=</mo>
    <mrow>
      <mo>&minus;</mo>
      <mfrac>
        <mrow>
          <mi>g</mi>
        </mrow>
        <mrow>
          <mn>2</mn>
          <msup>
            <mi>u</mi>
            <mn>2</mn>
          </msup>
        </mrow>
      </mfrac>
      <msup>
        <mi>x</mi>
        <mn>2</mn>
      </msup>
    </mrow>
  </mrow>
</math>

This relation between <i>y</i> and <i>x</i> may be considered as the equation of the path of the moving ball.
When this equation is plotted we obtain a curve that is called a parabola;
any freely falling body that is shot out in any direction will travel in a parabola,
    as shown in [Figure 8-4](fig8-4).


