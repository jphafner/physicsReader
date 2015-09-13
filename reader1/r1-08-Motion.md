---
layout: ebook
title: Motion
author: Richard P. Feynman, Robert B. Leighton, and Mathew Sands
excerpt: The treatment of speed and acceleration demonstrates the value of simple calculus in analyzing and describing motion.
intro: Richard P. Feynman, Robert B. Leighton and Matthew Sands A chapter from <em>The Feynman Lectures on Physics&mdash;Volume 1</em>, 1963.
image:
    title: title_image.jpg
    thumb: thumbnail_image.jpg
    homepage: header_homepage_13.jpg
    caption: Image by Phlow
    caption_url: "http://phlow.de/"
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
<table>
  <tr>
    <th>
      <span class="math">t</span>(min)
    </th>
    <th>
      <span class="math">s</span>(ft)
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


In [Table 8-1](#tab8-1), <span class="math">s</span> represents the distance of the car, in feet, from the starting point, and <span class="math">t</span> represents the time in minutes.
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

meaning that <span class="math">s</span> is some quantity depending on <span class="math">t</span> or, in mathematical phraseology,

<figure id="tab8-2">
<table>
  <tr>
    <th><span class="math">t</span>(sec)</th>
    <th><span class="math">s</span>(ft)</th>
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

<span class="math">s</span> is a function of <span class="math">t</span>.
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
Suppose that in a short time, <span class="math">&epsilon;</span>, the car or other body goes a short distance <span class="math">x</span>; then the velocity, <span class="math">v</span>, is defined as

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

an approximation that becomes better and better as the <span class="math">&epsilons;</span> is taken smaller and smaller.
If a mathematical expression is desired,
we can say that the velocity equals the limit as the <span class="math">&epsilon;</span> is made to go smaller and smaller in the expression <span class="math">x/&epsilon;</span>, or

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
At 5.1 sec, the distance that it has gone all together is 16(5.1)<sup>2</sup> = 416.16 ft (see [Equatoin 8-1](#eq8-1).
At 5 sec it had already fallen 400 ft;
    in the last tenth of a second it fell 416.16&minus;400=16.16 ft.
Since 16.16 ft in 0.1 sec is the same as 161.6 ft/sec,
    that is the speed more or less, but it is not exactly correct.
Is that the speed at 5 sec, or at 5.1 sec,
or halfway between at 5.05 sec, or when <em>is</em> that the speed?
Never mind&mdash;the problem was to find the speed at 5 seconds,
    and we do not have exactly that;
    we have to do a better job.
So, we take one-thousandth of a second more than 5 sec,
    or 5.001 sec, and calculate the total fall as

\begin{equation}
    s = 16 \left(5.001\right)^2 = 16 \left( 25.010001 \right) = 400.160016\, \text{ft}.
\end{equation}

In the last 0.001 sec the ball fell 0.160016 ft,
    and if we divide this number by 0.001 sec we obtain the speed as 160.016 ft/sec.
That is closer, very close, but it is still not exact.
It should now be evident what we must do to find the speed exactly.
To perform the mathematics we state the problem a little more abstractly:
    to find the velocity at a special time, to, which in the original problem was 5 sec.
    Now the distance at <span class="math">t<sub>0</sub></span>, which we call <span class="math">s<sub>0</sub></span>, is 16<span class="math">t<sub>0</sub></span>, or 400 ft in this case.
    In order to find the velocity, we ask, &ldquo;At the time <span class="math">t<sub>0</sub></span> + (a little bit), or <span class="math">t<sub>0</sub> + &epsilon;</span>, where is the body?&rdquo;
The new position is <span class="math">16(t<sub>0</sub> + &epsilon;)<sup>2</sup> = 16t<sub>0</sub><sup>2</sup> + 32 t<sub>0</sub> &epsilon; + 16&epsilon;<sup>2</sup></span>.
So it is farther along than it was before, because before it was only <span class="math">16t<sub>0</sub></span>.
This distance we shall call <span class="math">s<sub>0</sub></span> + (a little bit more), or <span class="math">s<sub>0</sub> + x</span> (if <span class="math">x</span> is the extra bit).
Now if we subtract the distance at to from the distance at <span class="math">t<sub>0</sub> + &epsilon;</span>,
we get <span class="math">x</span>, the extra distance gone, as <span class="math">x = 32t<sub>0</sub>&middot;&epsilon; + 16&epsilon;<sup>2</sup></span>.
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


The true velocity is the value of this ratio, <span class="math">x/&epsilon;</span>,
    when <span class="math">&epsilon;</span> becomes vanishingly small.
In other words, after forming the ratio,
    we take the limit as e gets smaller and smaller, that is, approaches <span class="math">0</span>.
The equation reduces to,

<math xmlns="http://www.w3.org/1998/Math/MathML" alttext="v(at time t_0)=32 t_{0}" display="block">
  <mrow>
    <mi>v</mi>
    <mfenced>
      <mtext>at time <span class="math">t<sub>0</sub></span></mtext>
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


In our problem, <span class="math">t</span><sub>0</sub> = 5 sec,
so the solution is <span class="math">v</span>=32&times;5 = 160 ft/sec.
A few lines above, where we took <span class="math">&epsilon;</span> as 0.1 sec and 0.01 sec successively,
    the value we got for <span class="math">v</span> was a little more than this,
    but now we see that the actual velocity is precisely 160 ft/sec.

## Speed as a derivative

The procedure we have just carried out is performed so often in mathematics that for convenience special notations have been assigned to our quantities <span class="math">&epsilon;</span> and <span class="math">x</span>.
In this notation, the <span class="math">&epsilon;</span> used above becomes <span class="math">&Delta;t</span> and <span class="math">x</span> becomes <span class="math">&Delta;s</span>.
This <span class="math">&Delta;t</span> means &ldquo;an extra bit of <span class="math">t</span>,&rdquo; and carries an implication that it can be made smaller.
The prefix <span class="math">&Delta;</span> is not a multiplier,
    any more than sin &theta; means s&middot;i&middot;n&middot;&theta;&mdash;it simply defines a time increment,
    and reminds us of its special character.
As has an analogous meaning for the distance <span class="math">s</span>.
Since <span class="math">&Delta;</span> is not a factor,
    it cannot be cancelled in the ratio <span class="math">&Delta;s/&Delta;t</span> to give <span class="math">s/t</span>,
    any more than the ratio sin &theta;/sin 2&theta; can be reduced to 1/2 by cancellation.
In this notation, velocity is equal to the limit of
    <span class="math">&Delta;s/&Delta;t</span> when <span class="math">&Delta;t</span> gets smaller, or

\begin{equation}
    v = \lim_{\Delta t \to 0} \frac{\Delta s}{\Delta t}
    \label{eq:8.5}
\end{equation}

This is really the same as our previous expression ([Equation 8.3](#eq8-3)) with <span class="math">&epsilon;</span> and <span class="math">x</span>,
    but it has the advantage of showing that something is changing,
    and it keeps track of what is changing.

Incidentally, to a good approximation we have another law,
    which says that the change in distance of a moving point is the velocity times the time interval,
    or <span class="math">&Delta;s = v&Delta;t</span>.
This statement is true only if the velocity is not changing during that time interval,
and this condition is true only in the limit as <span class="math">&Delta;t</span> goes to <span class="math">0</span>.
Physicists like to write it <span class="math">ds = v dt</span>,
because by <span class="math">dt</span> they mean <span class="math">&Delta;t</span> in circumstances in which it is very small;
    with this understanding, the expression is valid to a close approximation.
    If <span class="math">&Delta;t</span> is too long, the velocity might change during the interval,
    and the approximation would become less accurate.
    For a time <span class="math">dt</span>, approaching zero, <span class="math">ds = v dt</span> precisely.
In this notation we can write ([Equation 8-5](eq8-5)) as

\begin{equation}
    \lim_{\Delta t \to 0} \frac{\Delta s}{\Delta t}
\end{equation}

The quantity <span class="math">ds/dt</span> which we found above is called the &ldquo;derivative of <span class="math">s</span> with respect to?&rdquo;
(this language helps to keep track of what was changed), and the complicated process of finding it is called finding a derivative, or differentiating.
The <span class="math">ds</span>&#39;s and <span class="math">dt</span>&#39;s which appear separately are called <em>differentials</em>.
To familiarize you with the words, we say we found the derivative of the function 16 <span class="math">t</span><sup>2</sup>,
or the derivative (with respect to <span class="math">t</span>) of 16<span class="math">t</span><sup>2</sup> is 32<span class="math">t</span>.
When we get used to the words, the ideas are more easily understood.
For practice, let us find the derivative of a more complicated function. 
We shall consider the formula <span class="math">s = At<sup>3</sup> + Bt + C</span>, which might describe the motion of a point.
The letters <span class="math">A</span>, <span class="math">B</span>, and <span class="math">C</span> represent constant numbers, as in the familiar general form of a quadratic equation.
Starting from the formula for the motion, we wish to find the velocity at any time.
To find the velocity in the more elegant manner, we change <span class="math">t</span> to <span class="math">t + &Delta;t</span> and note that s is then changed to <span class="math">s</span> + some <span class="math">&Delta;s</span>;
then we find the <span class="math">&Delta;s</span> in terms of <span class="math">&Delta;t</span>.
That is to say,

\begin{align}
    s + \Delta s &= A \left(t + \Delta t\right)^3 + B \left( t + \Delta t\right) + C  \\
                 &= A t^3 + Bt + C + 3At^2\Delta{}t + B\Delta{}t + 3At(\Delta t)^2 + A (\Delta t)^3
\end{align}

but since

\begin{equation}
    s =  At^3 + B t + C,
\end{equation}

we find that

\begin{equation}
   \Delta s = 3At^2 \Delta t + B\Delta t + 3At \Delta t + A(\Delta t)^3
\end{equation}

But we do not want <span class="math">&Delta;s</span>&mdash;we want <span class="math">&Delta;s</span> divided by <span class="math">&Delta;t</span>.
We divide the preceding equation by <span class="math">&Delta;t</span>, getting

\begin{equation}
    \frac{\Delta s}{\Delta t} = 3 \Delta t^2 + B + 3At(\Delta t) + A(\Delta t)^2.
\end{equation}

As <span class="math">&Delta;t</span> goes toward the limit of <span class="math">&Delta;s/&Delta;t</span> is <span class="math">ds/dt</span> and is equal to

\begin{equation}
    \frac{ds}{dt} = 3At^2 + B.
\end{equation}

This is the fundamental process of calculus, differentiating functions.
The process is even more simple than it appears.
Observe that when these expansions contain any term with a square or a cube or any higher power of <span class="math">&Delta;t</span>,
    such terms may be dropped at once,
    since they will go to when the limit is taken.
After a little practice the process gets easier because one knows what to leave out.
There are many rules or formulas for differentiating various types of functions.
These can be memorized,
    or can be found in tables.
A short list is found in [Table 8-3](tab8-3).

<figure id="tab8-3">
<table>
  <tr>
    <th>Function</th>
    <th>Derivative</th>
  </tr>
  <!--Row 1-->
  <tr>
    <td><span class="math">s = t<sup>n</sup></span></td>
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
    <td><span class="math">s = cu</span></td>
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
    <td><span class="math">s = u + v + w + &middot;</span></td>
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
    <td><span class="math">s = c</span></td>
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
      <td><span class="math">s = u<sup>a</sup> v<sup>b</sup> w<sup>c</sup> &hellip;</span></td>
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
    <span class="math">s</span>, <span class="math">u</span>, <span class="math">v</span>, <span class="math">w</span> are arbitrary functions of <span class="math">t</span>; <span class="math">a</span>, <span class="math">b</span>, <span class="math">c</span>, and <span class="math">n</span> are arbitrary constants.
</figcaption>
</figure>

<figure id="tab8-4">
<table>
  <tr>
    <th>
      <span class="math">t</span>(sec)
    </th>
    <th>
      <span class="math">v</span>(ft/sec)
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
and from the formula <span class="math">&Delta; s = v &Delta; t</span> we can calculate how far the car went the first second at that speed.&rdquo;
Now in the next second her speed is nearly the same, but slightly different;
    we can calculate how far she went in the next second by taking the new speed times the time.
We proceed similarly for each second, to the end of the run.
We now have a number of little distances,
    and the total distance will be the sum of all these little pieces.
That is, the distance will be the sum of the velocities times the times,
or <span class="math">s = &sum; v&Delta;t</span>, where the Greek letter <span class="math">&Sigma;</span> (sigma) is used to denote addition.
To be more precise, it is the sum of the velocity at a certain time,
let us say the <span class="math">i</span><sup>th</sup> time, multiplied by <span class="math">&Delta;t</span>.

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


The rule for the times is that <span class="math">t<sub>i+i</sub> = t<sub>i</sub> + &Delta;t</span>.
However, the distance we obtain by this method will not be correct,
because the velocity changes during the time interval <span class="math">&Delta;t</span>.
If we take the times short enough, the sum is precise,
    so we take them smaller and smaller until we obtain the desired accuracy.
The true <span class="math">s</span> is

\begin{equation}
    s = \lim_{\Delta t \to 0} \sum_i  v(t_i) \Delta t
    \label{eq:8.7}
\end{equation}
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
The <span class="math">&Delta;</span> turns into a <span class="math">d</span> to remind us that the time is as small as it can be;
    the velocity is then called <span class="math">v</span> at the time <span class="math">t</span>,
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
The derivative of this integral is <span class="math">v</span>, so one operator (<span class="math">d</span>) undoes the other (&int;).
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
and then doing it again with a finer interval <span class="math">&Delta;t</span> and again with a finer interval until you have it nearly right.
In general, given some particular function, it is not possible to find,
    analytically, what the integral is.
One may always try to find a function which, when differentiated, gives some desired function;
    but one may not find it, and it may not exist,
    in the sense of being expressible in terms of functions that have already been given names.

## Acceleration

The next step in developing the equations of motion is to introduce another idea which goes beyond the concept of velocity to that of change of velocity, and we now ask, "How does the velocity change?&rdquo;
In previous chapters we have discussed cases in which forces produce changes in velocity.
You may have heard with great excitement about some car that can get from rest to 60 miles an hour in ten seconds flat.
From such a performance we can see how fast the speed changes, but only on the average.
What we shall now discuss is the next level of complexity,
    which is how fast the velocity is changing.
In other words, by how many feet per second does the velocity change in a second,
    that is, how many feet per second, per second?
    We previously derived the formula for the velocity of a falling body as <span class="math">y = 32t</span>,
    which is charted in [Table 8-4](tab8-4),
    and now we want to find out how much the velocity changes per second;
    this quantity is called the acceleration.

Acceleration is defined as the time rate of change of velocity.
From the preceding discussion we know enough already to write the acceleration as the derivative <span class="math">dv/dt</span>,
    in the same way that the velocity is the derivative of the distance.
    If we now differentiate the formula <span class="math">v=32t</span> we obtain,
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

[To differentiate the term <span class="math">32t</span> we can utilize the result obtained in a previous problem, where we found that the derivative of <span class="math">Bt</span> is simply <span class="math">B</span> (a constant).
So by letting <span class="math">B = 32</span>, we have at once that the derivative of <span class="math">32t</span> is 32.]
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

we obtained, for <span class="math">v = ds/dt</span>,

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
To differentiate the first of these terms, instead of going through the fundamental process again we note that we have already differentiated a quadratic term when we differentiated <span class="math">16t<sup>2</sup></span>,
and the effect was to double the numerical coefficient and change the <span class="math">t<sup>2</sup></span> to <span class="math">t</span>;
    let us assume that the same thing will happen this time, and you can check the result yourself.
    The derivative of <span class="math">3At<sup>2</sup></span> will then be <span class="math">6At</span>.
Next we differentiate <span class="math">B</span>, a constant term; but by a rule stated previously,
    the derivative of <span class="math">B</span> is zero; hence this term contributes nothing to the acceleration.
The final result, therefore, is <span class="math">a = dv/dt = 6At</span>.

For reference, we state two very useful formulas, which can be obtained by integration.
If a body starts from rest and moves with a constant acceleration, <span class="math">g</span>,
    its velocity <span class="math">v</span> at any time <span class="math">t</span> is given by

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
Since velocity is <span class="math">ds/dt</span> and acceleration is the time derivative of the velocity,
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
This is just the opposite of <span class="math">a = dv/dt</span>;
    we have already seen that distance is the integral of the velocity,
    so distance can be found by twice integrating the acceleration.

In the foregoing discussion the motion was in only one dimension,
    and space permits only a brief discussion of motion in three dimensions.
Consider a particle <span class="math">P</span> which moves in three dimensions in any manner whatsoever.
At the beginning of this chapter,
    we opened our discussion of the one-dimensional case of a moving car by observing the distance of the car from its starting point at various times.
We then discussed velocity in terms of changes of these distances with time,
    and acceleration in terms of changes in velocity.
We can treat three-dimensional motion analogously.
It will be simpler to illustrate the motion on a two-dimensional diagram,
    and then extend the ideas to three dimensions.
We establish a pair of axes at right angles to each other,
    and determine the position of the particle at any moment by measuring how far it is from each of the two axes.
Thus each position is given in terms of an <span class="math">x</span>-distance and a <span class="math">y</span>-distance,
    and the motion can be described by constructing a table in which both these distances are given as functions of time.
(Extension of this process to three dimensions requires only another axis,
at right angles to the first two, and measuring a third distance, the <span class="math">z</span>-distance.
The distances are now measured from coordinate planes instead of lines.)
Having constructed a table with <span class="math">x</span>- and <span class="math">y</span>-distances,
    how can we determine the velocity?
We first find the components of velocity in each direction.
The horizontal part of the velocity, or <span class="math">x</span>-component,
    is the derivative of the <span class="math">x</span>-distance with respect to the time, or


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

Similarly, the vertical part of the velocity, or <span class="math">y</span>-component, is

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
    separated by a short distance A5 and a short time interval <span class="math">t<sub>2</sub>&minus;t<sub>1</sub> = &Delta;t</span>.
    In the time <span class="math">&Delta;t</span> the particle moves horizontally a distance <span class="math">&Delta;x &sim; v<sub>x</sub> &Delta;t</span>,
    and vertically a distance <span class="math">&Delta;y &sim; v<sub>y</sub>&Delta;t</span>.
(The symbol &ldquo;&sim;&rdquo; is read &ldquo;is approximately.&rdquo;)
The actual distance moved is approximately

<!-- NOTE: TODO: start here-->
\begin{equation}
    \Delta s \propto \sqrt{ \left(\Delta x\right)^2 + \left(\Delta y\right)^2 }
    \label{eq:8.14}
\end{equation}

as shown in [Figure 8-3](fig8-3).
The approximate velocity during this interval can be obtained by dividing by <span class="math">&Delta;t</span> and by letting <span class="math">&Delta;t</span> go to <span class="math">0</span>,
    as at the beginning of the chapter.
We then get the velocity as

\begin{equation}
    v = \frac{ds}{dt} = \sqrt{ \left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2 } = \sqrt{ v_x^2 + v_y^2 }
    \label{eq:8.15}
\end{equation}

For three dimensions the result is

\begin{equation}
    v = \sqrt{ v_x^2 + v_y^2 + v_z^2 }
    \label{eq:8.16}
\end{equation}

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
we have an <span class="math">x</span>-component of acceleration <span class="math">a<sub>x</sub></span>, which is the derivative of <span class="math">v<sub>x</sub></span>,
        the <span class="math">x</span>-component of the velocity (that is, <span class="math">a<sub>x</sub> = d<sup>2</sup>x/dt<sup>2</sup></span>,
    the second derivative of <span class="math">x</span> with respect to <span class="math">t</span>), and so on.

Let us consider one nice example of compound motion in a plane.
We shall take a motion in which a ball moves horizontally with a constant velocity <span class="math">u</span>,
    and at the same time goes vertically downward with a constant acceleration <span class="math">&minus;g</span>;
    what is the motion?
We can say <span class="math">dx/dt = v<sub>x</sub> = u</span>.
Since the velocity <span class="math">v<sub>x</sub></span> is constant,

\begin{equation}
    x = ut
    \label{eq:8.17}
\end{equation}

and since the downward acceleration <span class="math">&minus;g</span> is constant,
    the distance <span class="math">y</span> the object falls can be written as

\begin{equation}
    y = -\frac{1}{2} g t^2
    \label{eq:8.18}
\end{equation}

What is the curve of its path, i.e., what is the relation between <span class="math">y</span> and <span class="math">x</span>?
We can eliminate <span class="math">t</span> from [Equation 8-18](eq8-18), since <span class="math">t = x/u</span>.
When we make this substitution we find that

\begin{equation}
    y = -\frac{g}{2\mu^2} x^2,
    \label{eq:8.19}
\end{equation}

This relation between <span class="math">y</span> and <span class="math">x</span> may be considered as the equation of the path of the moving ball.
When this equation is plotted we obtain a curve that is called a parabola;
any freely falling body that is shot out in any direction will travel in a parabola,
    as shown in [Figure 8-4](fig8-4).


