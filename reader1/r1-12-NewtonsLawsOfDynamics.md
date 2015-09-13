---
layout: ebook
title: Newton&#39;s Laws of Dynamics
author: Richard P. Feynman, Robert B. Leighton and Matthew Sands
exerpt: This chapter from a beginning college physics text is not simple, but the reward of this numerical approach to Newtonian mechanics is a more powerful understanding of how the laws of motion work.
intro: A chapter from their textbook <em>The Feynman Lectures on Physics</em>, Volume 1, 1963.
---

## Momentum and force

The discovery of the laws of dynamics, or the laws of motion, was a dramatic moment in the history of science.
Before Newton&#39;s time, the motions of things like the planets were a mystery, but after Newton there was complete understanding.
Even the slight deviations from Kepler&#39;s laws, due to the perturbations of the planets, were computable.
The motions of pendulums, oscillators with springs and weights in them, and so on, could all be analyzed completely after Newton&#39;s laws were enunciated.
So it is with this chapter: before this chapter we could not calculate how a mass on a spring would move; much less could we calculate the perturbations on the planet Uranus due to Jupiter and Saturn.
After this chapter we will be able to compute not only the motion of the oscillating mass, but also the perturbations on the planet Uranus produced by Jupiter and Saturn!

Galileo made a great advance in the understanding of motion when he discovered the principle of inertia: if an object is left alone, is not disturbed, it continues to move with a constant velocity in a straight line if it was originally moving, or it continues to stand still if it was just standing still. Of course this never appears to be the case in nature, for if we slide a block across a table it stops, but that is because it is not left to itself&mdash;it is rubbing against the table.
It required a certain imagination to find the right rule, and that imagination was supplied by Galileo.

Of course, the next thing which is needed is a rule for finding how an object changes its speed if something is affecting it.
That is the contribution of Newton.
Newton wrote down three laws: The First Law was a mere restatement of the Galilean principle of inertia just described.
The Second Law gave a specific way of determining how the velocity changes under different influences called forces.
The Third Law describes the forces to some extent, and we shall discuss that at another time.
Here we shall discuss only the Second Law, which asserts that the motion of an object is changed by forces in this way: the time-rate-of-change of a quantity called momentum is proportional to the force.
We shall state this mathematically shortly, but let us first explain the idea.

Momentum is not the same as velocity.
A lot of words are used in physics, and they all have precise meanings in physics, although they may not have such precise meanings in everyday language.
Momentum is an example, and we must define it precisely.
If we exert a certain push with our arms on an object that is light, it moves easily; if we push just as hard on another object that is much heavier in the usual sense, then it moves much less rapidly.
Actually, we must change the words from &ldquo;light&rdquo; and &ldquo;heavy&rdquo; to less massive and more massive, because there is a difference to be understood between the weight of an object and its inertia.
(How hard it is to get it going is one thing, and how much it weighs is something else.)
Weight and inertia are proportional, and on the earth&#39;s surface are often taken to be numerically equal, which causes a certain confusion to the student.
On Mars, weights would be different but the amount offeree needed to overcome inertia would be the same.

We use the term mass as a quantitative measure of inertia, and we may measure mass, for example, by swinging an object in a circle at a certain speed and measuring how much force we need to keep it in the circle.
In this way we find a certain quantity of mass for every object.
Now the momentum of an object is a product of two parts: its mass and its velocity.
Thus Newton&#39;s Second Law may be written mathematically this way:

\begin{equation}
    F = \frac{d}{dt}\left(mv\right)
    \label{eq:9.1}
\end{equation}

Now there are several points to be considered.
In writing down any law such as this, we use many intuitive ideas, implications, and assumptions which are at first combined approximately into our &ldquo;law.&rdquo;
Later we may have to come back and study in greater detail exactly what each term means, but if we try to do this too soon we shall get confused.
Thus at the beginning we take several things for granted.
First, that the mass of an object is constant; it isn&#39;t really, but we shall start out with the Newtonian approximation that mass is constant, the same all the time, and that, further, when we put two objects together, their masses add.
These ideas were of course implied by Newton when he wrote his equation, for otherwise it is meaningless.
For example, suppose the mass varied inversely as the velocity; then the momentum would never change in any circumstance, so the law means nothing unless you know how the mass changes with velocity.
At first we say, it does not change.

Then there are some implications concerning force.
As a rough approximation we think of force as a kind of push or pull that we make with our muscles, but we can define it more accurately now that we have this law of motion.
The most important thing to realize is that this relationship involves not only changes in the magnitude of the momentum or of the velocity but also in their direction.
If the mass is constant, then Eq. \ref{eq:9.1} can also be written as

\begin{equation}
    F = m \frac{dv}{dt} = ma
    \label{eq:9.2}
\end{equation}

The acceleration a is the rate of change of the velocity, and Newton&#39;s Second Law says more than that the effect of a given force varies inversely as the mass;
    it says also that the direction of the change in the velocity and the direction of the force are the same.
Thus we must understand that a change in a velocity, or an acceleration, has a wider meaning than in common language:
    The velocity of a moving object can change by its speeding up, slowing down (when it slows down, we say it accelerates with a negative acceleration), or changing its direction of motion.
An acceleration at right angles to the velocity was discussed in Chapter 7.
There we saw that an object moving in a circle of radius <span class="math">R</span> with a certain speed <span class="math">v</span> along the circle falls away from a straightline path by a distance equal to $\frac{1}{2}\left(\frac{v^2}{R}\right)t^2$ if <span class="math">t</span> is very small. Thus the formula for acceleration at right angles to the motion is

\begin{equation}
    a = \frac{v^2}{R},
    \label{eq:9.3}
\end{equation}

and a force at right angles to the velocity will cause an object to move in a curved path whose radius of curvature can be found by dividing the force by the mass to get the acceleration, and then using (\ref{eq:9.3}).

<figure>
\label{fig:9-1}
\caption{A small displacement of an object.}
</figure>

## Speed and velocity

In order to make our language more precise, we shall make one further definition in our use of the words speed and velocity.
Ordinarily we think of speed and velocity as being the same, and in ordinary language they are the same.
But in physics we have taken advantage of the fact that there are two words and have chosen to use them to distinguish two ideas.
We carefully distinguish velocity, which has both magnitude and direction, from speed, which we choose to mean the magnitude of the velocity, but which does not include the direction.
We can formulate this more precisely by describing how the <span class="math">x</span>-, <span class="math">y</span>-, and <span class="math">z</span>-coordinates of an object change with time.
Suppose, for example, that at a certain instant an object is moving as shown in Fig. \ref{fig:9-1}.
In a given small interval of time <span class="math">&Delta;t</span> it will move a certain distance <span class="math">&Delta;x</span> in the <span class="math">x</span>-direction,
    <span class="math">&Delta;y</span> in the <span class="math">y</span>-direction, and <span class="math">&Delta;z</span> in the <span class="math">z</span>-direction.
The total effect of these three coordinate changes is a displacement <span class="math">&Delta;s</span> along the diagonal of a parallelepiped whose sides are <span class="math">&Delta;x</span>, <span class="math">&Delta;y</span>, and <span class="math">&Delta;z</span>.
In terms of the velocity, the displacement <span class="math">&Delta;x</span> is the <span class="math">x</span>-component of the velocity times <span class="math">&Delta;t</span>, and similarly for <span class="math">&Delta;y</span> and <span class="math">&Delta;z</span>:

\begin{align}
    \Delta x = v_x \Delta t, & \Delta y = v_y \Delta t,  & \Delta z = v_z \Delta t.
    \label{eq:9.4}
\end{align}

## Components of velocity, acceleration, and force

In Eq. (\ref{eq:9.4}) we have resolved the velocity into components by telling how fast the object is moving in the <span class="math">x</span>-direction, the <span class="math">y</span>-direction, and the <span class="math">z</span>-direction.
The velocity is completely specified, both as to magnitude and direction, if we give the numerical values of its three rectangular components:

\begin{align}
    v_x = \frac{dx}{dt}, & v_y = \frac{dy}{dt}, & v_z = \frac{dz}{dt}.
    \label{eq:9.5}
\end{align}

On the other hand, the speed of the object is

\begin{equation}
    \frac{ds}{dt} = \|v\| = \sqrt{ v_x^2 + v_y^2 + v_z^2 }
    \label{eq:9.6}
\end{equation}

Next, suppose that, because of the action of a force, the velocity changes to some other direction and a different magnitude, as shown in Fig. \ref{fig:9-2}.
We can analyze this apparently complex situation rather simply if we evaluate the changes in the <span class="math">x</span>-, <span class="math">y</span>-, and <span class="math">z</span>-components of velocity.
The change in the component of the velocity in the <span class="math">x</span>-direction in a time <span class="math">&Delta;t</span> is <span class="math">&Delta;r = a<sub>x</sub> &Delta;t</span>,
    where <span class="math">a<sub>x</sub></span> is what we call the <span class="math">x</span>-component of the acceleration.
Similarly, we see that <span class="math">&Delta;r = a<sub>y</sub> &Delta;t</span> and <span class="math">&Delta;r<sub>z</sub> = a<sub>z</sub>&Delta;t</span>.
In these terms, we see that Newton&#39;s Second Law, in saying that the force is in the same direction as the acceleration, is really three laws, in the sense that the component of the force in the <span class="math">x</span>-. <span class="math">y</span>-, or <span class="math">z</span>-direction is equal to the mass times

<figure id="fig9-2">
<figcaption>
    A change in velocity in which both the magnitude and direction change.
</figcaption>
</figure>

the rate of change of the corresponding component of velocity:

\begin{align}
    F_x &= m \frac{dv_x}{dt} = m \frac{d^2x}{dt^2} = ma_x  \\
    F_y &= m \frac{dv_y}{dt} = m \frac{d^2y}{dt^2} = ma_y  \\
    F_z &= m \frac{dv_z}{dt} = m \frac{d^2z}{dt^2} = ma_z
    \label{eq:9.7}
\end{align}.

Just as the velocity and acceleration have been resolved into components by projecting a line segment representing the quantity and its direction onto three coordinate axes,
    so, in the same way, a force in a given direction is represented by certain components in the <span class="math">x</span>-, <span class="math">y</span>-, and <span class="math">z</span>-directions:

\begin{align}
    F_x &= F\cos\left(x,F\right),  \\
    F_y &= F\cos\left(x,F\right),  \\
    F_z &= F\cos\left(x,F\right),  \\
    \label{eq:9.8}
\end{align}

where <span class="math">F</span> is the magnitude of the force and $\left(x, F\right)$ represents the angle between the <span class="math">x</span>-axis and the direction of <span class="math">F</span>, etc.

Newton&#39;s Second Law is given in complete form in Eq. (\ref{eq:9.7}).
If we know the forces on an object and resolve them into <span class="math">x</span>-, <span class="math">y</span>-, and <span class="math">z</span>-components, then we can find the motion of the object from these equations.
Let us consider a simple example.
Suppose there are no forces in the <span class="math">y</span>- and <span class="math">z</span>-directions, the only force being in the x-direction, say vertically.
Equation (\ref{eq:9.7}) tells us that there would be changes in the velocity in the vertical direction, but no changes in the horizontal direction.
This was demonstrated with a special apparatus in Chapter 7 (see Fig. \ref{fig:7-3}).
A falling body moves horizontally without any change in horizontal motion, while it moves vertically the same way as it would move if the horizontal motion were zero.
In other words, motions in the <span class="math">x</span>-, <span class="math">y</span>-, and <span class="math">z</span>-directions are independent if the <em>forces</em> are not connected.

## What is the force?

In order to use Newton&#39;s laws, we have to have some formula for the force;
    these laws say <em>pay attention to the forces</em>.
If an object is accelerating, some agency is at work; find it.
Our program for the future of dynamics must be Xo find the laws for the force.
Newton himself went on to give some examples.
In the case of gravity he gave a specific formula for the force.
In the case of other forces he gave some part of the information in his Third Law, which we will study in the next chapter, having to do with the equality of action and reaction.

Extending our previous example, what are the forces on objects near the earth&#39;s surface?
Near the earth&#39;s surface, the force in the vertical direction due to gravity is proportional to the mass of the object and is nearly independent of height for heights small compared with the earth&#39;s radius <span class="math">R</span>:
    <span class="math">F = GmM/R<sup>2</sup> = mg</span>, where <span class="math">g = GM/R<sup>2</sup></span> is called the acceleration of gravity.
Thus the law of gravity tells us that weight is proportional to mass;
    the force is in the vertical direction and is the mass times <span class="math">g</span>.
Again we find that the motion in the horizontal direction

<figure id="fig9-3">
<figcaption>
    A mass on a spring.
</figcaption>
</figure>

is at constant velocity.
The interesting motion is in the vertical direction, and Newton&#39;s Second Law tells us

\begin{equation}
    mg = m\left(\frac{d^2x}{dt^2}\right).
    \label{eq:9.9}
\end{equation}

Cancelling the <span class="math">m</span>&#39;s, we find that the acceleration in the <span class="math">x</span>-direction is constant and equal to <span class="math">g</span>.
This is of course the well known law of free fall under gravity, which leads to the equations

\begin{align}
    v_x &= v_0 + gt, \\
    x   &= x_0 + v_0 t + \frac{1}{2} g t^2.
    \label{eq:9.10}
\end{align}

As another example, let us suppose that we have been able to build a gadget (Fig. \ref{fig:9-3}) which applies a force proportional to the distance and directed oppositely&mdash;a spring.
If we forget about gravity, which is of course balanced out by the initial stretch of the spring, and talk only about excess forces, we see that if we pull the mass down, the spring pulls up, while if we push it up the spring pulls down.
This machine has been designed carefully so that the force is greater, the more we pull it up, in exact proportion to the displacement from the balanced condition, and the force upward is similarly proportional to how far we pull down.
If we watch the dynamics of this machine, we see a rather beautiful motion&mdash;up, down, up, down, &hellip; The question is, will Newton&#39;s equations correctly describe this motion?
Let us see whether we can exactly calculate how it moves with this periodic oscillation, by applying Newton&#39;s law (\ref{eq:9.7}).
In the present instance, the equation is

\begin{equation}
    -kx = m\left(\frac{dv_x}{dt}\right).
    \label{eq:9.11}
\end{equation}

Here we have a situation where the velocity in the <span class="math">x</span>-direction changes at a rate proportional to <span class="math">x</span>.
Nothing will be gained by retaining numerous constants,
    so we shall imagine either that the scale of time has changed or that there is an accident in the units,
    so that we happen to have <span class="math">k/m = 1</span>.
Thus we shall try to solve the equation

\begin{equation}
    \frac{dv_z}{dt} = x.
    \label{eq:9.12}
\end{equation}

To proceed, we must know what <span class="math">v<sub>x</sub></span>, is,
    but of course we know that the velocity is the rate of change of the position.

## Meaning of the dynamical equations

Now let us try to analyze just what Eq. (9.12) means.
Suppose that at a given time <span class="math">t</span> the object has a certain velocity <span class="math">v<sub>x</sub></span> and position <span class="math">x</span>.
What is the velocity and what is the position at a slightly later time $t + \epsilon$?
If we can answer this question our problem is solved, for then we can start with the given condition and compute how it changes for the first instant, the next instant, the next instant, and so on, and in this way we gradually evolve the motion. 
To be specific, let us suppose that at the time <span class="math">t=0</span> we are given that <span class="math">x=1</span> and <span class="math">v<sub>x</sub>=0</span>.
Why does the object move at all?
Because there is a force on it when it is at any position except <span class="math">x=0</span>.
If <span class="math">x&gt;0</span>, that force is upward.
Therefore the velocity which is zero starts to change, because of the law of motion.
Once it starts to build up some velocity the object starts to move up, and so on.
Now at any time <span class="math">t</span>, if <span class="math">&epsilon;</span> is very small,
we may express the position at time <span class="math">t+&epsilon;</span> in terms of the position at time / and the velocity at time <span class="math">t</span> to a very good approximation as
\begin{equation}
    x\left(t + \epsilon\right) = x(t) + \epsilon v_x(t)
    \label{eq:9.13}
\end{equation}

The smaller the <span class="math">&epsilon;</span>, the more accurate this expression is, but it is still usefully accurate even if e is not vanishingly small.
Now what about the velocity?
In order to get the velocity later, the velocity at the time <span class="math">t + &epsilon;</span>,
    we need to know how the velocity changes, the acceleration. And how are we going to find the acceleration?
That is where the law of dynamics comes in.
The law of dynamics tells us what the acceleration is. It says the acceleration is <span class="math">&minus;x</span>.

\begin{align}
    v_x \left( t + \epsilon \right) &= v_x (t) + \epsilon a_x(t)
                                    &= v_x (t) - \epsilon a_x(t)
\end{align}

Equation (\ref{eq:9.14}) is merely kinematics;
    it says that a velocity changes because of the presence of acceleration.
But Eq. (\ref{eq:9.14}) is dynamics, because it relates the acceleration to the force;
it says that at this particular time for this particular problem, you can replace the acceleration by <span class="math">&minus;x(t)<span>.
Therefore, if we know both the <span class="math">x</span> and <span class="math">y</span> at a given time,
    we know the acceleration, which tells us the new velocity,
    and we know the new position&mdash;this is how the machinery works.
The velocity changes a little bit because of the force, and the position changes a little bit because of the velocity.

## Numerical solution of the equations

Now let us really solve the problem.
Suppose that we take $\epsilon = 0.100\,\text{sec}$.
After we do all the work if we find that this is not small enough we may have to go back and do it again with $\epsilon=0.010\,\text{sec.}$
Starting with our initial value $x(0) = 1.00$, what is $x(0.1)$?
It is the old position $x(0)$ plus the velocity (which is zero) times 0.10 sec.
Thus $x(0.1)$ is still $1.00$ because it has not yet started to move.
But the new velocity at 0.10 sec will be the old velocity $v(0)=0$ plus $\epsilon$ times the acceleration.
The acceleration is $-x(0)=-1.00$.
Thus
\begin{equation}
    r(O.1) = 0.00 - 0.10 \times 1. 00 = -0.10.
\end{equation}

Now at 0.20 sec

\begin{align}
    x(0.2) &= x(0.1) + \epsilon v(0.1)
           &= 1.00 - 0.10 \times 0.10 = 0.99
\end{align}
and
\begin{align}
    r(0.2) &= v(0.1) + \epsilon a(0.1)  \\
           &= -0.10 - 0.10 \times 1.00 = -0.20.
\end{align}

And so, on and on and on, we can calculate the rest of the motion, and that is just what we shall do.
However, for practical purposes there are some little tricks by which we can increase the accuracy.
If we continued this calculation as we have started it, we would find the motion only rather crudely because $\epsilon=0.100\,\text{sec}$ is rather crude, and we would have to go to a very small interval, say $e=0.01$.
Then to go through a reasonable total time interval would take a lot of cycles of computation.
So we shall organize the work in a way that will increase the precision of our calculations, using the same coarse interval $e=0.10\,\text{sec}$.
This can be done if we make a subtle improvement in the technique of the analysis.

Notice that the new position is the old position plus the time interval $\epsilon$ times the velocity.
But the velocity when?
The velocity at the beginning of the time interval is one velocity and the velocity at the end of the time interval is another velocity.
Our improvement is to use the velocity halfway between.
If we know the speed now, but the speed is changing, then we are not going to get the right answer by going at the same speed as now.
We should use some speed between the &ldquo;now&rdquo; speed and the &ldquo;then&rdquo; speed at the end of the interval.
The same considerations also apply to the velocity: to compute the velocity changes, we should use the acceleration midway between the two times at which the velocity is to be found.
Thus the equations that we shall actually use will be something like this: the position later is equal to the position before plus e times the velocity at the time in the middle of the interval.
Similarly, the velocity at this halfway point is the velocity at a time e before (which is in the middle of the previous interval) plus $\epsilon$ times the acceleration at the time <span class="math">t</span>.
That is, we use the equations

\begin{align}
    x\left((t + \epsilon\right)         &= x(t) + \epsilon v\left(t + \frac{\epsilon}{2}\right), \\
    v\left(t + \frac{\epsilon}{2}\right)&= v\left( t - \frac{\epsilon}{2} \right) + \epsilon a(t), \\
    a(t)                                &= -x(t).
    \label{eq:9.16}
\end{align}

There remains only one slight problem: what is $v(\frac{\epsilon}{2})$?
At the start, we are given $v(0)$, not $v(-\frac{\epsilon}{2})$.
To get our calculation&#39; started, we shall use a special equation,
    namely, $v(\frac{\epsilon}{2}) = v(0) + \frac{\epsilon}{2} a(0)$.

Now we are ready to carry through our calculation.
For convenience, we may arrange the work in the form of a table, with columns for the time, the position, the velocity, and the acceleration, and the in-between lines for the velocity, as shown in Table \ref{tab:9-1}.
Such a table is, of course, just a convenient way of representing the numerical values obtained from the set of equations (9.16), and in fact the equations themselves need never be written.
We just fill in the various spaces in

\begin{table}
\label{tab:9-1}
%Solution of c^yi/J/ = —x
%Interval: e = 0.10 sec
\begin{tabu}{cccc}
    <span class="math">t</span> & <span class="math">x</span>   & <span class="math">v<sub>x</sub></span> & <span class="math">a<sub>x</sub></span> \\
    0.0 & 1.000 & 0.000 & -1.000  \\
        &       & -0.050    &   \\
    0.1 & 0.995 &       & -0.995  \\
        &       & -0.150    & \\
    0.2 & 0.980 &       & -0.980  \\
        &       & -0.248    & \\
    0.3 & 0.955 &       & -0.955  \\
        &       & -0.343    & \\
    0.4 & 0.921 &       & -0.921  \\
        &       & -0.435    & \\
    0.5 & 0.877 &       & -0.877  \\
        &       & -0.523    & \\
    0.6 & 0.825 &       & -0.825  \\
        &       & -0.605    & \\
    0.7 & 0.764 &       & -0.764  \\
        &       & -0.682    & \\
    0.8 & 0.696 &       & -0.696  \\
        &       & -0.751    & \\
    0.9 & 0.621 &       & -0.621  \\
        &       & -0.814    & \\
    1.0 & 0.540 &       & -0.540  \\
        &       & -0.868    & \\
    1.1 & 0.453 &       & -0.453  \\
        &       & -0.913    & \\
    1.2 & 0.362 &       & -0.362 \\
        &       & -0.949    & \\
    1.3 & 0.267 &       & -0.267  \\
        &       & -0.976    & \\
    1.4 & 0.169 &       & -0.169  \\
        &       & -0.993    & \\
    1.5 & 0.070 &       &  -0.070  \\
        &       & -1.000    & \\
    1.6 & -0.030&       & +0.030  \\
\end{tabu}
\end{table}


the table one by one.
This table now gives us a very good idea of the motion:
    it starts from rest, first picks up a little upward (negative) velocity and it loses some of its distance.
The acceleration is then a little bit less but it is still gaining speed.
But as it goes on it gains speed more and more slowly, until as it passes $x = 0$ at about $t=1.50\,\text{sec}$ we can confidently predict that it will keep going,
    but now it will be on the other side; the position x will become negative, the acceleration therefore positive. Thus the speed decreases.
It is interesting to compare these numbers with the function $x=\cos\left(t\right)$,
    which is done in Fig. \ref{fig:9-4}.
The agreement is within the three significant figure accuracy of our calculation!
We shall see later that $x=\cos\left(t\right)$ is the exact mathematical solution of our equation of motion,
    but it is an impressive illustration of the power of numerical analysis that such an easy calculation should give such precise results.

<figure>
\caption{Graph of the motion of a mass on a spring}
\label{fig:9-4}
</figure>

<figure>
\caption{The force of gravity on a planet}
\label{fig:9-5}
</figure>

## Planetary motions

The above analysis is very nice for the motion of an oscillating spring, but can we analyze the motion of a planet around the sun? Let us see whether we can arrive at an approximation to an ellipse for the orbit.
We shall suppose that the sun is infinitely heavy, in the sense that we shall not include its motion.
Suppose a planet starts at a certain place and is moving with a certain velocity;
    it goes around the sun in some curve, and we shall try to analyze, by Newton&#39;s laws of motion and his law of gravitation, what the curve is.
How?
At a given moment it is at some position in space.
If the radial distance from the sun to this position is called <span class="math">r</span>,
    then we know that there is a force directed inward which,
    according to the law of gravity,
    is equal to a constant times the product of the sun&#39;s mass and the planet&#39;s mass divided by the square of the distance.
To analyze this further we must find out what acceleration will be produced by this force.
We shall need the components of the acceleration along two directions,
    which we call <span class="math">x</span> and <span class="math">y</span>.
Thus if we specify the position of the planet at a given moment by giving <span class="math">x</span> and <span class="math">y</span>
    (we shall suppose that <span class="math">z</span> is always zero because there is no force in the <span class="math">z</span>-direction and,
    if there is no initial velocity <span class="math">v<sub>z</sub></span>,
    there will be nothing to make z other than zero),
    the force is directed along the line joining the planet to the sun,
    as shown in Fig. \ref{fig:9-5}.

From this figure we see that the horizontal component of the force is related to the complete force in the same manner as the horizontal distance x is to the complete hypotenuse <span class="math">r</span>, because the two triangles are similar.
Also, if <span class="math">x</span> is positive, <span class="math">F<sub>x</sub></span> is negative.
That is, $\frac{F_x}{|F|} = -\frac{x}{r}$, or $F_x = -\frac{|F|x}{r} = \frac{GMmx}{r^3}$.
Now we use the dynamical law to find that this force component is equal to the mass of the planet times the rate of change of its velocity in the x-direction.
Thus we find the following laws:

\begin{align}
    m\left(\frac{dv_x}{dt}\right) &= \frac{GMmx}{r^3}, \\
    m\left(\frac{dv_y}{dt}\right) &= \frac{GMmx}{r^3}, \\
    r &= \sqrt{ x^2 + y^2 }.
    \label{eq:9.17}
\end{align}

This, then, is the set of equations we must solve.
Again, in order to simplify the numerical work, we shall suppose that the unit of time, or the mass of the sun, has been so adjusted (or luck is with us) that GM = I.
For our specific example we shall suppose that the initial position of the planet is at $x=0.500$ and $y=0.000$,
    and that the velocity is all in the <span class="math">x</span>-direction at the start, and is of magnitude 1.6300.
Now how do we make the calculation?
We again make a table with columns for the time,
    the <span class="math">x</span>-position, the <span class="math">x</span>-velocity <span class="math">r<sub>x</sub></span>, and the x-acceleration <span class="math">a<sub>x</sub></span>;
    then, separated by a double line, three columns for position, velocity,
    and acceleration in the <span class="math">y</span>-direction.
In order to get the accelerations we are going to need Eq. (\ref{eq:9.17});
    it tells us that the acceleration in the <span class="math">x</span>-direction is $\frac{-x}{r^3}$,
    and the acceleration in the <span class="math">y</span>-direction is $\frac{-y}{r^3}$ and that <span class="math">r</span>
    is the square root of $x^2 + y^2$.
Thus, given <span class="math">x</span> and <span class="math">y</span>, we must do a little calculating on the side,
    taking the square root of the sum of the squares to find <span class="math">r</span> and then,
    to get ready to calculate the two accelerations, it is useful also to evaluate $\frac{1}{r^3}$.
This work can be done rather easily by using a table of squares,
cubes, and reciprocals: then we need only multiply <span class="math">x</span> by $\frac{1}{r^3}$,
    which we do on a slide rule.

<figure id="fig9-6">
<figcaption>
    The calculated motion of a planet around the sun.
</figcaption>
</figure>



Our calculation thus proceeds by the following steps,
    using time intervals $\epsilon = 0.100$: Initial values at $t=0$:


\begin{table}
\begin{tabu}{cc}
    $x(0) = 0.500$      & $y(0)=0.000$ \\
    $v_x(0) = 0.000$    & $v_y(0) = +1.630$ \\
\end{tabu}
\end{table}

From these we find:

\begin{table}
\begin{tabu}{cc}
    $r(0) = 0.500$      & $\frac{1}{r^3}(0) = 8.000$ \\
    $a_x(0) = -4.000$   & $a_y = 0.000$ \\
\end{tabu}
\end{table}


Thus we may calculate the velocities y;c(0.05) and Vy(0.05):

\begin{align}
    v_x(0.05) = 0.000 - 4.000 \times 0.050 = -0.200; \\
    v_y(0.05) = 1.630 + 0.000 \times 0.100 = 1.630.
\end{align}

Now our main calculations begin:

\begin{align}
    x(0.1)      &= 0.500 - 0.20 \times 0.1      &= 0.480  \\
    y(0.1)      &= 0.0 + 1.63 \times 0.1        &= Q.163  \\
    r           &= \sqrt{0.480^2 + 0.163^2}     &= 0.507  \\
    \frac{1}{r^3} &= 7.67                       & \\
    a_x(0.1)    &= 0.480 \times 7.67            &= -3.68  \\
    a_y(0.1)    &= -0.163 \times 7.70           &= -1.256  \\
    v_x(0.15)   &= -0.200 - 3.68 \times 0.1     &= -0.568  \\
    r_y(0.15)   &= 1.630 - 1.26 \times 0.1      &= 1.505  \\
    x(0.2)      &= 0.480 - 0.568 \times 0.1     &= 0.423  \\
    y(0.2)      &= 0.163 + 1.50 \times 0.1      &= 0.313  \\
\end{align}
etc.

In this way we obtain the values given in Table~\ref{tab:9-2},
    and in 20 steps or so we have chased the planet halfway around the sun!
In Fig.~\ref{fig:9-6} are plotted the <span class="math">x</span>- and <span class="math">y</span>-coordinates given in Table~\ref{tab:9-2}.
The dots represent the positions at the succession of times a tenth of a unit apart;
    we see that at the start the planet moves rapidly and at the end it moves slowly,
    and so the shape of the curve is determined.
Thus we see that we really do know how to calculate the motion of planets!

Now let us see how we can calculate the motion of
    Neptune, Jupiter, Uranus, or any other planet.
If we have a great many planets, and let the sun move too,
    can we do the same thing?
Of course we can. We calculate the force on a particular planet,
    let us say planet number <span class="math">i</span>, which has a position <span class="math">x<sub>i</sub></span>, <span class="math">y<sub>i</sub></span>, <span class="math">z<sub>i</sub></span>
    ($i=1$ may represent the sun, $i=2$ Mercury, $i=3$ Venus, and so on).
We must know the positions of all the planets.
The force acting on one is due to all the other bodies which are located,
    let us say, at positions <span class="math">x<sub>j</sub></span>, <span class="math">y<sub>j</sub></span>, <span class="math">z<sub>j</sub></span>.
Therefore the equations are

\begin{align}
    m_i \frac{dv_{ix}}{dt} = \sum_{j=1}^N -\frac{Gm_i m_j \left(x_i - x_j\right)}{r^3_{ij}} \\
    m_i \frac{dv_{iy}}{dt} = \sum_{j=1}^N -\frac{Gm_i m_j \left(y_i - y_j\right)}{r^3_{ij}} \\
    m_i \frac{dv_{iz}}{dt} = \sum_{j=1}^N -\frac{Gm_i m_j \left(z_i - z_j\right)}{r^3_{ij}} \\
    \label{eq:9.18}
\end{align}

\begin{table}
\label{tab:9-2}
\caption{
    Solution of ($\frac{dv_x}{dt} = \frac{-x}{r^3}$, $\frac{dv_y}{dt} = \frac{-y}{r^3}$, $r=\sqrt{x^2+y^2}$.
    Interval: $\epsilon = 0.100$
    Orbit $v_y =1.63$, $v_x=0$, $x=0.5$, $y=0$ at $t=0$
}
\begin{longtabu}{c|ccc|ccc|cc}
    \toprule
    <span class="math">t</span>     &
    <span class="math">x</span>     &
    <span class="math">v<sub>x</sub></span>   &
    <span class="math">a<sub>x</sub></span>   &
    <span class="math">y</span>     &
    <span class="math">v<sub>y</sub></span>   &
    <span class="math">a<sub>y</sub></span>   &
    <span class="math">r</span>     &
    $\frac{1}{r^3}$ \\
    \midrule
    0.0 & 0.500 &       & -4.00 & 0.000 &       &  0.00 & 0.500 & 8.000 \\
        &       &-0.200 &       &       & 1.630 &       &       & \\
    0.1 & 0.480 &       & -3.68 & 0.163 &       & -1.25 & 0.507 & 7.675 \\
        &       &-0.568 &       &       & 1.505 &       &       & \\
    0.2 & 0.423 &       & -2.91 & 0.313 &       & -2.15 & 0.526 & 6.873 \\
        &       &-0.859 &       &       & 1.290 &       &       & \\
    0.3 & 0.337 &       & -1.96 & 0.442 &       & -2.57 & 0.556 & 5.824 \\
        &       &-1.055 &       &       & 1.033 &       &       & \\
    0.4 & 0.232 &       & -1.11 & 0.545 &       & -2.62 & 0.592 & 4.81 \\
        &       &-1.166 &       &       & 0.771 &       &       & \\
    0.5 & 0.115 &       & -0.453& 0.622 &       & -2.45 & 0.633 & 3.942 \\
        &       &-1.211 &       &       & 0.526 &       &       & \\
    \midrule
    0.6 &-0.006 &       & +0.020& 0.675 &       & -2.20 & 0.675 & 3.252 \\
        &       &-1.209 &       &       & 0.306 &       &       & \\
    0.7 &-0.127 &       & +0.344& 0.706 &       & -1.91 & 0.717 & 2.712 \\
        &       &-1.175 &       &       & 0.115 &       &       & \\
    0.8 &-0.245 &       & +0.562& 0.718 &       & -1.64 & 0.758 & 2.296 \\
        &       &-1.119 &       &       &-0.049 &       &       & \\
    0.9 &-0.357 &       & +0.705& 0.713 &       & -1.41 & 0.797 & 1.975 \\
        &       &-1.048 &       &       &-0.190 &       &       & \\
    1.0 &-0.462 &       & +0.796& 0.694 &       & -1.20 & 0.824 & 1.723 \\
        &       &-0.968 &       &       &-0.310 &       &       & \\
    \midrule
    1.1 &-0.559 &       & +0.858& 0.663 &       & -1.02 & 0.867 & 1.535 \\
        &       &-0.882 &       &       &-0.412 &       &       & \\
    1.2 &-0.647 &       & +0.90 & 0.622 &       & -0.86 & 0.897 & 1.385 \\
        &       &-0.792 &       &       &-0.449 &       &       & \\
    1.3 &-0.726 &       & +0.92 & 0.572 &       & -0.72 & 0.924 & 1.267 \\
        &       &-0.700 &       &       &-0.570 &       &       & \\
    1.4 &-0.796 &       & +0.93 & 0.515 &       & -0.60 & 0.948 & 1.173 \\
        &       &-0.607 &       &       &-0.630 &       &       & \\
    1.5 &-0.857 &       & +0.94 & 0.452 &       & -0.50 & 0.969 & 1.099 \\
        &       &-0.513 &       &       &-0.680 &       &       & \\
    \midrule
    1.6 &-0.908 &       & +0.95 & 0.384 &       & -0.40 & 0.986 & 1.043 \\
        &       &-0.418 &       &       &-0.720 &       &       & \\
    1.7 &-0.950 &       & +0.95 & 0.312 &       & -0.31 & 1.000 & 1.000 \\
        &       &-0.323 &       &       &-0.751 &       &       & \\
    1.8 &-0.982 &       & +0.95 & 0.237 &       & -0.23 & 1.010 & 0.970 \\
        &       &-0.228 &       &       &-0.773 &       &       & \\
    1.9 &-1.005 &       & +0.95 & 0.160 &       & -0.15 & 1.018 & 0.948 \\
        &       &-0.113 &       &       &-0.778 &       &       & \\
    2.0 &-1.018 &       & +0.96 & 0.081 &       & -0.08 & 1.021 & 0.939 \\
        &       &-0.037 &       &       &-0.796 &       &       & \\
    \midrule
    2.1 &-1.022 &       & +0.95 & 0.001 &       &  0.00 & 1.022 & 0.936 \\
        &       &+0.058 &       &       &-0.796 &       &       & \\
    2.2 &-1.016 &       & +0.96 &-0.079 &       & +0.07 & 1.019 & 0.945 \\
        &       &       &       &       &-0.789 &       &       & \\
    \bottomrule
\end{longtabu}
%Crossed <span class="math">x</span>-axis at 2.101 sec, period = 4.20 sec, <span class="math">v<sub>x</sub></span> = at 2.086 sec.
%1.022 + 0.500
%Cross X at 1.022, . . semimajor axis =
%f„ = 0.796.
%= 0.761.
%Predicted time 7r(0.761)^&#39; 2 = ir(0.663) = 2.082.
\end{table}


Further, we define $r_{ij}$ as the distance between the two planets <span class="math">i</span> and <span class="math">j</span>;
    this is equal to

\begin{equation}
    r_{ij} = \sqrt{ \left(x_i-x_j\right)^2 + \left(y_i-y_j\right)^2 + \left(z_i-z_j\right)^2 }
    \label{eq:9.19}
\end{equation}

Also, $\sum$ means a sum over all values of <span class="math">j</span>&mdash;all other bodies&mdash;except, of course, for $j=i$.
Thus all we have to do is to make more columns, lots more columns.
We need nine columns for the motions of Jupiter, nine for the motions of Saturn, and so on.
Then when we have all initial positions and velocities we can calculate
    all the accelerations from Eq.~(\ref{eq:9.18}) by first calculating all the distances,
    using Eq.~(\ref{eq:9.19}).
How long will it take to do it?
If you do it at home, it will take a very long time!
But in modern times we have machines which do arithmetic very rapidly;
    a very good computing machine may take 1 microsecond, that is, a millionth of a second,
    to do an addition.
To do a multiplication takes longer, say 10 microseconds.
It may be that in one cycle of calculation, depending on the problem,
    we may have 30 multiplications, or something like that, so one cycle will take 300 microseconds.
That means that we can do 3000 cycles of computation per second.
In order to get an accuracy, of, say, one part in a billion, we would need $4\times{}10^5$ cycles to correspond to one revolution of a planet around the sun.
That corresponds to a computation time of 130 seconds or about two minutes.
Thus it take only two minutes to follow Jupiter around the sun, with all the perturbations of all the planets correct to one part in a billion, by this method!
(It turns out that the error varies about as the square of the interval $\epsilon$.
If we make the interval a thousand times smaller, it is a million times more accurate.
So, let us make the interval $10\,000$ times smaller.)

So, as we said, we began this chapter not knowing how to calculate even the motion of a mass on a spring.
Now, armed with the tremendous power of Newton&#39;s laws,
    we can not only calculate such simple motions but also,
    given only a machine to handle the arithmetic,
    even the tremendously complex motions of the planets,
    to as high a degree of precision as we wish!



