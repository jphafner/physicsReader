---
title: Space Travel: Problems of Physics and Engineering
author: Harvard Project Physics Staff
excerpt: This article, based on lectures of Edward M. Purcell, distinguishes between sound proposals and unworkable fantasies about space travel. 
intro: Harvard Project Physics Staff 1960 
---



Traveling through empty space. 
After centuries of gazing curiously at stars, moon, and planets from the sanctuary of his own planet with its blanket of lifegiving atmosphere, man has learned to send instruments to some of the nearer celestial objects; and he will no doubt soon try to make such a trip himself. 


Starting with Johannes Kepler&#39;s Somnium, a flood of fanciful stories dealt with journeys to the moon, often in balloons equipped with all the luxuries of a modern ocean liner. 
These stories, of course, ignored something that had already been known for almost a century, namely, that the earth&#39;s atmosphere must be only a thin shell of gas, held in place by gravity, and that beyond it must lie a nearly perfect vacuum. 
In this vacuum of outer space there is no friction to retard the motion of a space ship, and this is a great advantage. 
But the forces of gravity from the sun and other bodies will not always take a vehicle where we want it to go, and we must be able to produce occasional bursts of thrust to change its course from time to time. 
Thus, quite aside from how we may launch such a space vehicle, we must equip it with an engine that can exert a thrust in empty space. 


The only way to obtain a thrust in a completely empty space is to use recoil forces like those actina on a gun when it fires a projectile. 
Indeed, Newton&#39;s third law says that to obtain a thrusting force on the space vehicle an equal and opposite force must be exerted on something else, and in empty space this &ldquo;something else&rdquo; can only be a matter that comes from the space vehicle itself, a matter that we are willing to leave behind us. 
Only by throwing out a part of its own mass can a vehicle achieve recoil forces to change its own velocity&emdash;or at least the velocity of the part of it that remains intact. 


A rocket is a recoil engine of this type. 
It carries its own oxygen (or other oxidizer) with which to burn its fuel, and the mass of the burned fuel and oxygen is ejected from the rear and left behind. 
The rocket is much like a continuously firing gun that constantly sprays out an enormous number of very tinv bullets. 
The recoil from these &ldquo;bullets&rdquo; is precisely the thrusting force on the body of the rocket. 


Obviously there is a limit to the length of time that such a process can continue, for the mass remaining in the space ship qets smaller all the time, except when the engine is turned off entirely. 
In this chapter we will examine this limitation and see what it implies about space travel. 
To be definite, we shall usually speak about rocket engines, but it will be clear that what we have to say applies to any recoil engine whether it is run by chemical power, nuclear power, or any other source of power. 
All such engines, to produce a thrust in empty space, must eject some of the mass that has been carried alonq. 


<em>The rocket equation</em>. 
It turns out, as we shall see, that the only property of a rocket engine that seriously limits its performance is the &ldquo;exhaust velocity&rdquo; of the burned fuel gases, i.e. the velocity of the exhaust material as seen from the rocket. 
This exhaust velocity, which we denote by $v_{ex}$, is determined by the energy released inside the combustion chamber and hence by the fuel (and oxidizer) used by the rocket. 
The same &ldquo;kick&rdquo; backward is given to the exhaust-gas molecule whether or not the rocket is already moving. 
Therefore, to a man standing on the rocket using a specific combustion process, the gases rushing out the exhaust will always appear to have the same velocity relative to the rocket, whatever the motion of the rocket itself with respect to another body. 


Imagine you are watching a rocket coasting along at constant velocity, far away from any other massive bodies. 
Suppose that the engine is ignited briefly and ejects a small mass <span class="math">&Delta;m</span> of burned gases. 
The situation is sketched in Fig. \ref{fig:1}, where we have denoted the initial mass and velocity of the vehicle by <span class="math">m</span> and <span class="math">v</span> respectively. 
The velocity <span class="math">v</span> may be measured with respect to any (unaccelerated) coordinate system, for example, another space ship coasting alongside the first, or the sun-centered coordinate system that we commonly use to analyze the motions of the planets. 
(The actual value of v will cancel out of our final results. 
Why is this expected?) 
After the burst of power, the rocket will move away from us at velocity $v + \Delta v$, having a mass $m - \Delta m$; and the &ldquo;cloud&rdquo; of exhaust gases, of mass <span class="math">&Delta;m</span>, will be moving away from us at a velocity equal to the exhaust velocity diminished by the forward velocity of the rocket, $v_{ex} -v$.


Since no external forces are acting on the system, we know that momentum must be conserved. 
In Fig. \ref{fig:1}(a), before the burst of power, the momentum is <span class="math">mv</span>; right afterwards, in Fig. \ref{fig:1}(b), it is $\left(m-\Delta{}m\right)\left(v+\Delta{}v\right) - \left(\Delta{}m\right)\left(v_{ex}-v\right)$.
These momenta must be the same:

\begin{equation*}
    \left( m - \Delta m \right) \left( v + \Delta v \right) -
    \left(\Delta m\right) \left(v_{ex} - v\right) = mv. 
\end{equation*}

Multiplying out the terms on the left-hand side, we find that all terms containing <span class="math">v</span> cancel out (as they must), and the result can be written in the form, 

\begin{equation*}
    \left(\Delta m\right)v_{ex} + \left(\Delta m\right)\left(\Delta v\right) = m\left(\Delta v\right).
\end{equation*}


If we consider a sufficiently small burst of thrust, we can make <span class="math">&Delta;v</span> as small as we wish compared to $v_{ex}$, the second term on the left-hand side of this equation can be made completely negligible compared to the first term. 
Then we can write (for very small bursts of thrust): 

\begin{equation}
    \label{eq:1}
    \frac{\Delta m}{m} = \frac{\Delta v}{v_{ex}}
\end{equation}


Notice that this relation does not depend in any way on the length of time during which the change <span class="math">&Delta;v</span> occurs. 
The fuel Am may be burned very rapidly or very slowly. 
As long as the exhaust gases emerge with velocity $v_{ex}$ relative to the rocket, the resulting momentum changes will be the same, and will lead to the same relation Eq. (\ref{eq:1}), whenever the changes are sufficiently small. 
Notice also that this result depends only on the conservation of momentum; we have used no other law in deriving it. 


Now, a moderately large burst of power can be divided conceptually into a great many consecutive small bursts, and Eq. (\ref{eq:1}) shows that each small increase in velocity requires ejecting a given fraction of the remaining mass of the rocket. 
The rules of this &ldquo;inverted compound-interest payment&rdquo; are examined in the appendix to this chapter. 
There we find (Eq. \ref{eq:a6}) that any velocity change <span class="math">v_c</span>, large or small, requires reducing the mass of the rocket as follows: 

\begin{align}
    \label{eq:2}
    m &= m_0 e^{-\frac{v_c}{v_{ex}}} \\
    \frac{m}{m_0} &= e^{-\frac{v_c}{v_{ex}}}
\end{align}

Here <span class="math">m_0</span> is the mass before the change, and <span class="math">m</span> is the mass after the change. 
The quantity <span class="math">e</span> is a certain number whose value is 

\begin{equation}
    e = 2.718&hellip; = 10^{0.4343&hellip;}
\end{equation}

<figure>
(a) JUST BEFORE FIRING OFF Am: 
(b) JUST AFTER FIRING OFF Am: 
\label{fig:1}
\caption{
    Analysis of the performance of a rocket. 
    Note that the &ldquo;backwards&rdquo; velocity of the spent fuel, namely $v_{ex}-v$, might actually be negative as seen by an external observer. 
    This would happen if <span class="math">v</span> is larger than $v_{ex}$, in which case the exhaust &ldquo;cloud&rdquo; is seen to move off to the right, too, although at a speed less than that of the rocket. 
}
</figure>

One use of Eq. (\ref{eq:2}) is in computing the final velocity <span class="math">v_f</span> of a rocket that has initial mass <span class="math">m_0</span>, initial speed <span class="math">v_0</span> final mass <span class="math">m_f</span>, and exhaust velocity $v_{ex}$.
The result is 

\begin{equation*}

"^f -(^f/^ex^ 

fir = ^ 
\end{equation*}

as shown graphically in Fig. \ref{fig:2}. 


<figure>
\label{fig:2}
\caption{
}
</figure>

Eq. (\ref{eq:2}) is the <em>rocket equation</em>.
Unless a table of powers of <span class="math">e</span> happens to be handy, the most convenient way to write this equation is the following:

\begin{equation*}
    m_0 = \left( m \right) 10^{\left(\frac{0.4343 v_c}{v_{ex}}}
\end{equation*}

or

\begin{equation*}
    \log_{10}\left(\frac{m_0}{m}\right) = 0.4343\left(\frac{v_c}{v_{ex}}\right)
\end{equation*}


This relation is based only on the conservation of momentum and on the concept of a constant exhaust velocity Vex (constant with respect to the body of the rocket) for the spent part of the fuel. 
(But the relation is idealized in the sense that we have not taken into account any accelerations due to gravity.) 


As an example, suppose that we wish to give a rocket a final velocity equal to twice the exhaust velocity of its engines, starting with the rocket at rest. 
Then $v_c = 2v_{ex}$, and we have: 

\begin{equation*}
    m_0 = \left(m\right) 10^{0.8686} = 7.39 \left(m\right)
\end{equation*}


That is, the original takeoff mass <span class="math">m</span> must be over 7 times the final mass. 
In other words, about 87 percent of the initial mass must be expelled to achieve a velocity of $2v_{ex}$. 
The useful payload must be somewhat less than the remaining 13 percent of the takeoff mass, because the rocket casing, its fuel tanks, and the like will constitute much of this remaining mass. 


<em>Practical rockets</em>.
The rocket equation shows that the most important feature of a rocket is $v_{ex}$, the velocity with which the spent fuel gases are expelled. 
When chemical fuels are used, there is a limit to how large this exhaust velocity can be. 
We can see this by applying the law of energy conservation to the interior of the rocket. 


Consider what happens when a given mass m of fuel and oxidizer are combined, with the fuel burning in the oxidizer. 
Let the total energy produced by this chemical reaction be <span class="math">E</span>. Obviously, the ratio $\frac{E}{m}$, which is the energy per unit mass of fuel and oxidizer, will be a constant that depends only on the chemical nature of the fuel and the oxidizer. 
After the materials have reacted, the total mass <span class="math">m</span> is ejected from the rocket with velocity $v_{ex}$, and the kinetic energy of the ejected mass is just $\frac{1}{2}m\left(v_{ex}\right^2$.
Since this energy comes from burning the fuel, it can be no greater than the chemical energy liberated, namely <span class="math">E</span>:

\begin{equation*}
    \frac{1}{2} m \left( v_{ex} \right)^2 \leq E.
\end{equation*}


Dividing by km and taking square roots, we find: 

\begin{equation}
    \label{eq:6}
    v_{ex} \sqrt{2\frac{E}{m}}.
\end{equation}


These relations are not simple equalities because much of the released energy will be wasted, primarily as internal (random motion) heat energy in the still-hot exhaust gases. 


Chemists have measured the &ldquo;heats of reaction&rdquo; (which determines $\frac{E}{m}$) for almost all chemical reactions. 
For example, for typical hydrocarbons such as fuel oil, gasoline, kerosene, and the like, they have found that about \SI{1.1e4}{\kilo\calorie} are given off for each kilogram of fuel burned. 
When we add the mass of oxygen required (about \SI{3.4}{\kilo\gram} per \si{\kilo\gram} of fuel) and convert to mechanical units, we find that $\frac{E}{m}$ for all of these fuels is very nearly \SI{e7}{\joule\per\kilo\gram}.
Therefore, according to Eq. (\ref{eq:6}), 

\begin{equation}
    \label{eq:7}
    %% TODO
    %v_{ex} \SI{2.5}{\kilo\meter\per\second}.
\end{equation}

for hydrocarbon fuels burned in oxygen. 
This, of course, is the largest value that could possibly be obtained, even if the exhaust gases emerged ice-cold. 
In actual practice, many current rockets using kerosene and liquid oxygen (called LOX) obtain roughly: 

\begin{equation}
    \label{eq:7}
    v_{ex} \SI{2.5}{\kilo\meter\per\second}.
\end{equation}


Even liquid hydrogen and liquid fluorine will yield exhaust velocities only about 20 percent greater than this in practice.
\footnote{
    <em>Specific impulse</em> is a term often used by rocket engineers who use the symbol I for it. 
    It is essentially impulse per unit weight of fuel and equals the exhaust velocity divided by the acceleration of gravity at the earth&#39;s surface: $I = \frac{v_{ex}}{q}$. 
    Typical practical values are therefore about \SI{250}{\second}. 
}
Consequently whenever the speed of the rocket has to be substantially more than this value of $v_{ex}$&emdash;and we shall see in the next section that this is indeed so even for orbital flights&emdash;the useful payload is in practice only a small fraction of the original mass, by Eq. (\ref{eq:2}). 

In view of this limitation on the fundamental quantity $v_{ex}$ for chemical rockets, a number of proposals and experimental models have been made for nonchemical rockets where $v_{ex}$ ay not have these limitations. 
To date, none of these has offered any real advantage, although they may do so in the future. 
The difficulty is that today the auxiliary apparatus for ion-beam engines, nuclear reactors, and the like, always contains too much mass relative to the mass allowance needed for any significant payload. 
Eventually, of course, we might be able to do much better with nonchemical engines. 


<em>Artificial satellites</em>.
Now let us see what velocities we need to perform the simplest task of space engineering, namely placing an artificial satellite in orbit above the surface of the earth. 
Since the radius of the earth is about \SI{4000}{\mile}, the force of gravity on a satellite moving perhaps a few hundred miles above the earth&#39;s surface will be not very different from that on the surface. 
Thus, the satellite will experience an acceleration of approximately <span class="math">g</span> toward the center of the earth. 
As we saw in Chapter 5 if it is travelling in a circular orbit with speed <span class="math">v</span>, its centripetal acceleration must be $\frac{v^2}{R}$ where <span class="math">R</span> is the radius of the orbit. 
For these two facts to be consistent, 

\begin{equation*}
    \frac{v^2}{R} = g \quad\text{or}\quad v = \sqrt{Rg}. 
\end{equation*}

Since the satellite is assumed to be fairly close to the earth, the radius of its orbit <span class="math">R</span> will be about the same as the radius of the earth, or about \SI{6400}{\kilo\meter}.
Substituting this value, along with $g=\SI{9.8}{\meter\per\second\squared}=\SI{0.0098}{\kilo\meter\per\second\squared}$, into our formula, we obtain 

\begin{equation}
    v = \SI{8}{\kilo\meter\per\second}\quad \text{(close orbit).}
\end{equation}

This is the approximate speed an object must have if it is to remain in orbit. 
Eq. (\ref{eq:7}) displays the rocket-exhaust velocities achieved when chemical engines are used. 
Are these velocities adequate? 
From Eqs. (\ref{eq:7}) and (\ref{eq:8}), we have 

\begin{equation}
    \frac{v_c}{v_{cx}} = \frac{8}{2.5} = 3.2 . 
\end{equation}

Substituting this value into the rocket equation (4) or (5), we find: 

\begin{equation}
    m_0 = \left( m \right) 10^{1.39} = 24.5\left( m\right).
\end{equation}

That is, the takeoff mass mo must be almost 25 times the mass <span class="math">m</span> of the satellite and all other non-fuel structures; thus only about 4 percent of the initial mass can actually go into orbit (even ignoring the problem of lifting it to orbit altitude, which we shall examine shortly). 

But the situation is even worse than these numbers may seem to imply at first. 
The &ldquo;other nonfuel structures&rdquo;&emdash;the rocket&#39;s casing, framework, fuel tanks, fuel pumps, and the like&emdash;have much more mass than the payload, the satellite. 
In fact even with the best of modern structural materials and techniques, there is so far no rocket mechanism with a mass less than about 1/10 of the mass of the fuel it can carry (rather than $\frac{1}{25}$). 
According to our foregoing result, a rocket of this sort could not be put into orbit at all. 


The way out of these difficulties is to use the technique of staging, which essentially amounts to putting a small rocket onto a larger rocket (and this combination onto a third, still larger rocket, and so on as necessary). 
The fundamental rocket equation is not circumvented by this strategem; it remains valid. 
Eut heavy casings and fuel tanks can be thrown away as soon as their fuel is used up, and the remaining fuel in the remaining rocket then need only accelerate the remaining mass, which can be much smaller. 
In this way, the remaining fuel is used more efficiently toward the end of the process, and the ideal limit expressed by the rocket equation can be more nearly approached. 
It cannot be exceeded, for that would violate the conservation of momentum, upon which the rocket equation is based. 


There is one further matter that we should look into. 
We have neglected to compute the work we must do to lift the payload up into its orbit against the downward force of gravity. 
(Anyone who has watched pictures of a big rocket taking off has seen how, at the start, thrust must be increased until the rocket&#39;s own weight on the launching pad is balanced and the net acceleration upward can begin.) 
This work, however, is not terribly large, relatively speaking, for a close-in orbit, as we can easily show. 
In obtaining Eq. (\ref{eq:8}), we derived the relation $v^2 = Rg$ for the orbital velocity. 
If we multiply this equation by $\frac{1}{2}m$, we find that the orbital kinetic energy is $\frac{1}{2}mv^2=\frac{1}{2}mgR$.
The potential energy change in lifting the mass <span class="math">m</span> to height <span class="math">h</span> above the surface of the earth is <span class="math">mgh</span>.
Since <span class="math">h</span> is only a few hundred miles while <span class="math">R</span> is \SI{4000}{\mile} or more, the work (<span class="math">mgh</span>) required to raise the satellite will be only about $\frac{1}{10}$ to $\frac{1}{5}$ of the work (<span class="math">mgh</span>) required to give it orbiting speed in a close-in orbit. 
(Naturally, this is not true for a very large orbit with a height of, say, \SI{4000}{\mile} or more above the earth&#39;s surface.) 


<em>Interplanetary travel</em>.
To send instruments to other planets, we must first free them from the gravitational attraction of the earth. 
This requires that the payload be given a velocity sufficient to prevent it from, returning close to the earth of its own accord. 
The smallest such velocity is called the escape velocity.
A vehicle with this velocity will just barely escape, and its final velocity will be nearly zero relative to the earth. 


As might be expected, the escape velocity is not enormously greater than orbital velocity, and in the appendix to this chapter, we show that it is about: 

\begin{align}
    v &(\text{for escape}) = \SI{11.2}{\kilo\meter\per\second},
    \text{as compared to } v&(\text{for close orbit}) = \SI{8}{\kilo\meter\per\second}.
\end{align}

Even this moderately greater (than orbital) velocity for escape requires a rather large increase in the ratio of takeoff mass to payload mass. 
With $v_{ex}$ equal to \SI{2.5}{\kilo\meter\per\second} as in Eq. (\ref{eq:7}), we have $\frac{v_c}{v_{ex}}=\frac{11.2}{2.5}=4.48$, and the rocket equation (Eq. \ref{eq:4}) yields: 
\begin{equation}
    m_0 = \left(m\right) 10^{1.95} = 89 \left(m\right).
\end{equation}

So, despite the seemingly modest change in velocity (\SI{11.2}{\kilo\meter\per\second} instead of \SI{8}{\kilo\meter\per\second}), freeing a payload from the earth with chemically fueled rockets (even in stages) requires about $3\frac{1}{2}$ times as much fuel as required for placing the same payload into a close-in orbit.

Once essentially free of the earth, a body will still be under the direct influence of the sun&#39;s gravitational forces. 
Here it is necessary to recall that the earth already has a rather large orbital velocity around the sun, and that any body launched from the earth will continue to have that orbital velocity if it has been merely freed from the earth with no additional accelerations. 
This velocity is about 30 km/sec and clearly represents a very substantial bonus for interplanetary travel. Even so, the Mariner 4 probe to Mars, for example, actually required a takeoff mass 400 times as large as the mass of the probe itself, The rocket was an Atlas-Agena with an initial mass of about \SI{200 000}{\pound} and a payload of \SI{500}{\pound}.
It was designed to cover the \SI{3e8}{\mile} trip in the solar system in about 7 months (this works out at about \SI{16}{\mile\per\second}). 


<figure>
\label{fig:3}
\caption{Fig. 3}
</figure>

<em>Travel to a star?</em>
When we think of sending a payload to examine a star, we find once more that the necessary velocity is the crucial factor, but the origin of the needed velocity is different. 
The velocity required to escape from the solar system is about \SI{45}{\kilo\meter\per\second}, but even the nearest stars are enormously far away, and the payload must travel much faster than this if it is to complete its journey within a century. 


The distances to the nearest stars have been measured by observing the shift in their apparent positions in, say, summer and winter as the earth moves from one side of its orbit to the other. 
Even with this very large baseline (\num{186} million miles), the apparent shift in direction&emdash;the parallax — is extremely small, and the corresponding distances are found to be several million million miles, i.e., several trillion miles. 
Such large distances are more conveniently expressed in light years, a light year being the distance that light will travel in one year.
A simple multiplication shows that one light year is about \SI{e13}{\kilo\meter}. 


The two nearest stars are in the constellation Centaurus. 
The nearest one, Proxima Centauri, is \num{4.2} light years away but is very dim and emits only about \num{e-4} times as much light as our sun. 
The next-to-nearest star.
Alpha Centauri, is \num{4.3} light years away and is actually a double star, consisting of two stars similar to our sun and separated by about the distance between the sun and Jupiter. 
The brighter of the two emits energy at about the same rate as our sun, and the other at about $\frac{1}{5}$ that rate. 


While none of these particular stars seems likely to have habitable planets comparable to our own, it might be very interesting to send instruments in close to one of them and take pictures of it. 
To see just what problems such a project might entail, let us examine this simplest of all interstellar journeys a little more closely. 


The first question to be answered is how long we would be willing to wait for the results of the journey. 
Although an unmanned instrument package need not return to the earth within a man&#39;s lifespan, it nevertheless seems that we would be unlikely to plan today for a very expensive project whose results would be known later than, say, a century from now. 


If the payload is to travel \num{4.2} light years during \num{100} years, its speed must be \num{0.042} times the speed of light (\SI{3e5}{\kilo\meter\per\second}). 
This speed <span class="math">v_c</span> is \SI{12.6e3}{\kilo\meter\per\second}.
Let us optimistically assume that we can soon design rockets with exhaust velocities twice as high as the ones we now have, even though it is difficult to see now how this could be done with chemical fuels. 
Thus, we assume $v_{ex}=\SI{5}{\kilo\meter\per\second}$.
Then we have $\frac{v_c}{v_{ex}}=\num{2.52e3}$, which we substitute into the rocket equation. 
(Both speeds are small enough so that we can use this nonrelativistic equation; actually the relativistic one gives slightly more pessimistic results.) 


When we make this substitution in Eq. (\ref{eq:4}) , we find a result that can only be described as ridiculous: 

\begin{equation*}
    m_0 = \left(m\right) 10^{1094}. 
\end{equation*}

To see just how impossibly large this mass ratio is, we might note that the total number of atoms in the entire solar system has been estimated to be less than \num{e58}.
There is not enough chemical fuel in the entire solar system to send even one atom on such a journey! 
In fact, we are short of having enough fuel for even that trivial task by a factor of over \num{e1000}! 


These numbers are so large that the mind can not really form an adequate picture of their hugeness. 
To reduce them, let us throw caution to the winds and allow a much longer time for the journey, for example, \num{5000} years or \num{50} centuries&emdash;a terribly long wait. 
Retracing the arithmetic we find that we then obtain 

\begin{equation*}
    m_0 = \left(m\right) 10^{21.9} = \num{8e21}\left(m\right). 
\end{equation*}

Even this more familiar sort of number is still absurdly large. 
The mass of the entire earth is only \SI{6e21}{\ton}, less than enough (even if it were all good fuel&emdash;and to be so used!) to send a one-ton payload on a journey of \num{5000} years to the nearest star. 

There is only one sensible conclusion: <em>interstellar travel is impossible if chemical fuels are used for propulsion.</em>


<em>Future star travel?</em>
Perhaps one of the conceivable nonchemical rockets might someday offer an escape from this pessimistic conclusion. 
To look at this possibility, let us return to our simplest of interstellar journeys, a trip to the nearest star in \num{100} years. 
As we saw, we need a velocity <span class="math">v_c</span> of \SI{12.6e3}{\kilo\meter\per\second} for such a journey. 
(With this velocity, the payload arrives at Alpha Centauri after \num{100} years; it must contain either a very powerful radio transmitter, or enough fuel to return in another \num{100} years or so.) 


The various &ldquo;plasma&rdquo; engines and &ldquo;magnetohydrodynamic&rdquo; engines that have been proposed are essentially electric &ldquo;guns&rdquo; that shoot out ionized gases. 
It is difficult to set limiting numbers on the best possible performance from such engines, partly because the exhaust gases are usually accelerated by some separate source of power. 
Certainly, they can be no better than nuclear engines, which we shall examine later. 
It is probably fair to say that exhaust velocities much larger than \num{1/300} the velocity of light could not be expected when very large masses of ionized gas must be expelled. 


If we adopt this estimate, then a value of $v_{ex}$ of \SI{1000}{\kilo\meter\per\second} is about the best that could ever be expected from such non-nuclear engines. 
With this value we obtain the ratio $\frac{v_c}{v_{ex}}=\num{12.6}$, and by inserting this into the rocket equation, Eq. (\ref{eq:4}), we get the result, 

\begin{equation*}
    m_0 = \left(m\right) 10^{5.47}=\num{3e5}\left(m\right). 
\end{equation*}

Thus, a \SI{3}{ton} payload would require at least a million tons of &ldquo;fuel&rdquo; (material to be expelled as ionized gas).
If the payload is to contain a sufficiently powerful radio transmitter, it is likely to weigh at least \SI{3}{tons}.
To form some picture of what a million tons of material might look like, we may note that a million tons of water would cover a football field to a depth of \num{200} yards. 


Abandoning the radio transmitter and waiting another \num{100} years for the payload to return would be no way to avoid this large mass of &ldquo;fuel,&rdquo; because the effective payload on the outward journey would then have to in- clude all the &ldquo;fuel&rdquo; for reversing the velocity for the return trip. 
This essentially squares the mass ratio, making mo/m equal to \num{e11}, which is far worse: even only one pound of true payload then requires 50 million tons of takeoff mass. 


These results are not quite so ridiculous as the ones we obtained when we tried to use chemical fuels, but they clearly show that ion-beam engines will not be very practical for interstellar travel unless they can consistently give an exhaust velocity significantly greater than \num{1/300} the velocity of light. 

Nuclear fission yields about \SI{8.2e13}{\joule\per\kilo\gram} of fissionable material. 
According to Eq. (\ref{eq:6}), this will result in a maximum exhaust velocity of the products of fission of \SI{12.8e6}{\meter\per\second}, or \SI{12.8e3}{\kilo\meter\per\second}, about \num{1/23} the velocity of light.
\footnote{
    The best possible nuclear fusion reaction, converting 4 hydrogen nuclei into a helium nucleus, gives about \num{1/8} the velocity of light. 
    But non-explosive &ldquo;slow&rdquo; fusion reactors are far from being available on the earth, not to speak of the availability of a portable model for use in rockets! 
}


These exhaust velocities at last begin to approach what we need for the simplest of interstellar journeys. 
For the \SI{100}{year}, one-way trip to Alpha Centauri, the necessary <span class="math">v</span> is just about exactly equal to the $v_{ex}$ that we might hope to obtain for nuclear fission products, and the rocket equation then gives $\frac{m_o}{m}=\numrange{2.7}{3}$. 
This, in itself, is so clearly practical that we might begin to consider making the elapsed time somewhat shorter or journeying further to a few of the slightly more distant stars. 
Note, however, that a \SI{20}{year}, one-way trip to Alpha Centauri would still require $\frac{m_o}{m}=\num{200}$ approximately. 


But present day engineering is a long way from being able to put a small nuclear reactor on a rocket to provide these exhaust velocities for fission products. 
Today&#39;s nuclear reactors involve so much additional mass besides their fuel that they would be even less useful than engines working with chemical fuels&emdash;and the latter are hopeless for interstellar journeys, as we have seen. 
It was only by ignoring these auxiliary difficulties that we have made nuclear power appear to be the answer for interstellar travel. 
What <em>is</em> likely, however, is the development of nuclear reactors that do not emit the relatively heavy fission products, but that provide heat to a supply of hydrogen that is pumped over the reactor, heated by it, and ejected at correspondingly higher speed (see Eq. (\ref{eq:6}); $v_{ex}$ is proportional to $\sqrt{\frac{1}{m}}$. 


If we are ever going to send instruments, let alone men, to even the nearest stars, we must first develop an almost ideal nuclear rocket (or an ion-beam rocket virtually equivalent to it).
Even then, the simplest such trip will require many decades. 


<em>The perfect rocket</em>.
If we agree to ignore questions of engineering knowhow, is there any absolute limit to how effective any rocket could possibly be? 
There is indeed such a limit and it is imposed by the facts of physics; physical energy cannot leave the rocket at an exhaust velocity greater than <span class="math">c</span>, the velocity of light. 
And when any energy (say of amount <span class="math">E</span>) is lost by the rocket, it also loses a (rest) mass of $m=\frac{E}{c^2}$, This is true whether the energy <span class="math">E</span> is carried off in the exhaust of some gas or in the form of a beam of light that escapes from the back of the rocket. 
This last possibility is suggested by certain reactions between elementary particles, reactions known as annihilations.
When an electron ($e^-$) and a positron ($e^+$) react sufficiently strongly, both particles disappear and in their place appear two gamma rays; the latter are photons, like light or x-ray photons, that travel at the speed of light and together carry all of the energy represented by the masses of the vanished electron and positron. 
The reaction suggests that one may call the electron a particle of matter and the positron a particle of anti-matter. 


This annihilation of positrons with electrons was the first reaction of this kind that was observed; but in the late 1950&#39;s, anti-protons and anti-neutrons were also discovered, and each was observed to annihilate with its ordinary counterpart, the usual proton or neutron respectively, producing two energetic gamma rays in each case. 
Thus, it became clear that a whole system of anti-matter&emdash;anti-hydrogen, anti-helium, and so on&emdash;could be constructed from the elementary anti-particles. 
We do not yet know how to do this to any significant extent, but we know of no physical law that would f orbit it. 


Since we have already agreed to ignore practical manufacturing problems in this discussion, let us assume that large amounts of anti-matter might be made available. 
What could we do with such a material if we had it? 
It would not be an inexpensive supply, because to manufacture it would require at least as much energy as it would later give back. 
But it would represent a very efficient way of storing energy. 
Indeed, antimatter, plus ordinary matter to &ldquo;burn&rdquo; it with, would have the smallest ratio of stored energy to total mass that is physically possible, namely $\frac{E}{m} = c^2$.
Moreover, because the released (photon) energy will depart at the speed of light, such a &ldquo;fuel&rdquo; would constitute the best possible rocket fuel (provided we could find a way of making the photons travel backwards from the rocket). 


Naturally, we must use relativistic mechanics to derive the equations for such an exotic rocket. 
We shall not do so here, but will merely quote the result: if the exhaust velocity equals the velocity of light, then 

\begin{equation}
\label{eq:10}
    \frac{m_0}{m} = \sqrt{\frac{c+v_c}{c-v_c}}
\end{equation}

where all the symbols have the same meanings as before. 
This is the mass equation for a perfect rocket. 


[Note, by the way, that a man on the rocket sees the exhaust energy leaving the rocket at the velocity of light; at the same time a man on the earth, say, will see the rocket traveling at the velocity of light relative to the earth. 
This is one of those paradoxes (seeming contradictions) of relativity that cannot be reconciled with our ordinary experience.]


Would such a &ldquo;perfect&rdquo; rocket make it easier for us to travel to the stars? 
One answer is: &ldquo;A little, perhaps, but not much.&rdquo; 
Even this small degree of optimism is justifiable only if we may ignore a number of serious practical difficulties in addition to that of creating the necessary anti-matter for fuel. 


Let us analyze a &ldquo;typical&rdquo; journey, preferably a rather simple one. 
As stated before, the nearest stars are about 4 light years away, but an ideal nuclear rocket would suffice for such a trip, so let us consider a slightly longer journey. 
Within a distance of \num{12} to \num{13} light years from the earth there are about \num{20} stars. 
(Of these, only Alpha Centauri is closely similar to our sun; two others emit about \num{1/3} as much energy as does the sun and one other emits about 5 times as much. 
The remaining ones are either very much brighter or very much dimmer than the sun.) 


Accordingly, let us consider a round trip from the earth to a star 12 light years away and back. 
Since we would have to wait 24 years for light rays to make the round trip, the top speed of the rocket must be close to the speed of light if the rocket is to return to the base on earth during our lifetime. 
But we would not want the rocket to fly past its distant goal at nearly the speed of light, and it will take about as long to slow the rocket down as it did to speed it up in the first place. 
Thus the velocity of the rocket would have to vary approximately as shown in Fig. \ref{fig:4}. 


To avoid imposing unduly large forces on the men inside the rocket, we must keep the accelerations and decelerations small; at an average acceleration of \SI{1}{g}, one can calculate that about a year will be required to reach full speed, and another year to stop. 
To keep the total time for the journey reasonably small, we shall choose a top speed of $0.8c$, that is, only \SI{20}{\percent} less than the speed of light. 


Journeys of this type involve, therefore, four separate steps: acceleration, deceleration, reacceleration, and a final deceleration. 
The mass equation applies to each one, but we must remember that, during each step, we must accelerate (or decelerate) all of the fuel mass that will be needed for all the succeeding steps. 
For one step of the journey in Fig. \ref{fig:4}, the mass equation Eq. (\ref{eq:1}) yields 

\begin{equation*}
    \frac{m_0}{m} = \sqrt{\frac{c+0.8c}{c-0.8c} = \sqrt{\frac{1+0.8}{1-0.8}} = 3.
\end{equation*}

But if <span class="math">m</span> represents the true pay load, this result applies only to the final deceleration. 
For example, the mass at the beginning of this final step must be $m_0=3$, and this must be the &ldquo;payload&rdquo; for the next-to-last step, the acceleration for the return trip. 
Thus, the return trip must begin with a total mass of $3m_0=\left((3^2m\right)$.
It is easy to show in the same way that the two steps of the outward leg of the journey will introduce two more factors of 3. 
Thus, if <span class="math">m_0</span> denotes the take-off mass when the rocket leaves the earth (and m denotes the true payload, as before), we find: 

\begin{equation*}
    \frac{m_{00}}{m} = 3^4 = 81.
\end{equation*}

That is, each ton of payload requires 81 tons of combined take-off mass. 
A 10-ton payload would require almost a thousand tons of fuel for the journey we have considered&emdash;and half of this fuel must be anti-matter. 
Obviously, we would have to learn how to manufacture anti-matter in very large amounts indeed. 


<figure>
\label{fig:4}
\caption{A modest interstellar journey.}
</figure>


With these assumptions about the trip, it is possible to show that the journey we have discussed would take 32 years as measured on the earth. 
But because of relativistic time-dilation for the inhabitants of the moving systems, it turns out that the crew of the rocket would age by only 20 years. 
That is, as measured by the crew, the journey would require only 20 years. 


The perfect rocket has further difficulties that we have not yet mentioned. 
First, the energy flux of gamma rays from such a rocket, with a 10-ton payload, can be shown to be \SI{2.4e15}{\watt}, a power that is equivalent to a 1-kilo bomb once every \num{1.7} seconds! 
And all of this energy flux is in the form of very penetrating, deadly gamma rays. 
The payload would have to be shielded very well indeed from even the slightest leakage of all this energy&emdash;to say nothing of the difficulties of shielding the earth and its inhabitants as the rocket takes off. 
Figure \ref{fig:5} indicates how the rocket might look in principle. 


Secondly, a glance at Fig. \ref{fig:5} reveals another very serious difficulty. 
Anti-matter would act as a &ldquo;universal solvent,&rdquo; reacting readily with any ordinary matter that it contacts. 
Then, in what can we store it?  
Within our present knowledge, this problem has no solution. 


Thus, we have found that a perfect rocket probably cannot be built, and that, even if it could be built, it would not extend the range of possible space travel very much beyond the meager capabilities of an ideal nuclear rocket. 
Even the nuclear rocket is presently a long way from being practical. 
For the time being, of course, there are many exciting possibilities for exploring our own solar system with the chemically fueled rockets we already know how to build. 
The dreams of space travel are coming true, but only on a &ldquo;local&rdquo; basis. 


<em>Communicating through space</em>.
This final section is closely based on, and copiously cites from, E. M, Purcell&#39;s article &ldquo;Radioastronomy and Communication through Space.&rdquo; 
Brookhaven National Lecture series \#BNL 658 &endash;(T-214); we wish to thank Dr. Purcell and the BNL for permission to use this material. 


Now we shall discuss a very different aspect of space engineering, namely, sending signals, rather than physical hardware, across the huge distances of space. 
The signals that we know how to send most efficiently are coded radio waves, but our discussion will also apply to the light beam from a laser or to any other type of electromagnetic radiation if the necessary engineering &ldquo;know-how&rdquo; can be developed. 
Radio signals suitable for communicating over a distance of a few hundred miles require relatively little energy, but a large amount of energy is needed in communicating across the vast reaches of space. 


The simplest possible radio signal is just the presence or absence of a radio wave&emdash;or equally well, the presence or absence of a small shift in its frequency (so-called &ldquo;frequency-shift keying&rdquo;). 
Correspondingly, the simplest possible sign that can be written on a piece of paper is the presence or absence of a black dot in some agreed-upon location. 
Newspaper photographs are arrays of such dots. 
Television pictures are built up in much the same way. 


The simplest possible signal, then, expresses a two-fold (&ldquo;binary&rdquo;) choice, a simple &ldquo;yes or no,&rdquo; a &ldquo;something or nothing&rdquo; signal. 
More complicated codes can always be broken down into such signals.
For example, a Morse code dot might be called a &ldquo;yes&rdquo; and the space between two dots a &ldquo;no&rdquo;; then the dash becomes two successive &ldquo;yesses,&rdquo; and the longer space between two letters is represented by two successive &ldquo;noes,&rdquo; and so on. 

<figure>
\label{fig:5}
\caption{A perfect rocket?}
</figure>


This way of analyzing signals was first suggested by the American radio engineer R. V. L. Hartley in 1928, and it was further developed by C. E. Shannon at Bell Telephone Laboratories in 1948. 
Shannon called the simplest yes-no signal a bit (for &ldquo;binary digit&rdquo;), and he first developed much of the analysis that we shall be using in this section. 
This analysis is a part of &ldquo;information theory.&rdquo; 


For space communication, the important fact is that each bit (each yes-no signal) requires a very small amount of energy. 
Just as space is filled with very faint light rays from the stars, it is filled also with a background of weak radio waves of all types. 
If we are to detect a signal from outer space against this &ldquo;noise,&rdquo; we must receive enough energy to be sure that the supposed signal is not just one of the random mutterings of space itself. 
Near our solar system, a received signal energy of at least \num{e-21} joule per bit is required. 
This requirement is essentially independent of the radio frequency or the manner in which the signal is coded in the radio wave, and presumably it remains about the same in many parts of empty space. 


As an example, let us consider the task of the Mariner IV space probe, namely to send good television pictures of Mars back to the earth. 
Since such a picture contains an array of about 1000-by-1000 dots, one picture can be transmitted by a signal consisting of about \num{e6} bits. 
The signal can be detected if, on reaching the earth, it delivers (to our receiving antenna) $\num{e6}\times\num{e-21}\,\text{joule}=\num{e-15}\,\text{joule}$ for each picture that is to be transmitted. 


But what the transmitter emits must be much more energy than what we intercept and receive at a distance. 
A simple radio antenna sends the energy outward more or less equally in all directions. 
A properly designed complex antenna can concentrate most of the energy into a narrow beam, but such an antenna must be large (compared to the wavelength of the radio waves) , and it must be very accurately shaped. 
Not only is this difficult to do, but once it is done, the antenna must be pointed toward the receiver, accurately enough to be sure that the receiver lies inside the radio beam, and this pointing operation in turn requires additional machinery and sensors that must be equally accurate.  
Thus, a space probe such as Mariner must contain either a rather large radio transmitter or else a smaller transmitter and a lot of complex, rather heavy machinery. 


The best compromise amongst all the possibilities will depend on the purpose of the space probe and on the status of various engineering arts at the time the probe is designed. 
But we can obtain a rough idea of the weight of the necessary equipment by analyzing the situation when a simple antenna is used. 


Fig. \ref{fig:6} summarizes the situation. 
Notice that the receiving antenna on the earth can be quite large, and we shall assume that it has a diameter of \SI{100}{\meter} (about 100 yards).
Only the radio energy that happens to strike the receiving antenna will be useful. 
Thus, the fraction of the energy that is useful will be given by the ratio of the area of the receiving antenna to the area of a sphere whose radius is equal to the distance from Mars to the earth, about $\SI{e8}{\kilo\meter}=\SI{e11}{\meter}$ (see Fig. \ref{fig:6}). 
The ratio of these areas is 

\begin{equation*}
    \frac{\pi\left(50\right)^2}{4\pi\left(\num{e11}\right)^2} = \num{6e-20}
\end{equation*}


<figure>
\label{fig:6}
\caption{Sending television pictures from Mars to the earth. (The diagram is not to scale!)}
</figure>


We have seen that the received energy must be at least \num{e-15} joule per picture. 
The energy that must be transmitted for each picture, however, must be 

\begin{equation*}
    \frac{\num{e-15}}{\num{6e-20}} = \num{16e3}\,\text{joule per picture}.
\end{equation*}


Although this amounts to only about \SI{0.005}{\kilo\watt\hour}, a rather small amount of energy by our normal standards, it does represent something of a burden to a space probe. 
To compare it with something familiar, we might note that the average automobile battery could store only enough energy for sending about 100 such pictures. 
Actually, this is a very optimistic estimate because we have computed it by using the minimum possible energy per bit of &ldquo;information,&rdquo; namely \num{e-21} joules per bit. 
If we are going to go to all the trouble of sending a probe to Mars, we would want the signal that it sends back to be quite strong, not just barely detectable, lest we miss it entirely. 
Thus, it would be more realistic to say that an automobile battery can store enough energy to send about 10 television pictures from Mars to the earth. 


Since such a battery would weigh about 35 lb, and since the ratio of take-off mass to payload mass was about 400 for Mariner IV, the energy storage for 10 television pictures of Mars would add about 7 tons to the take-off mass of such a probe, if a nondirection antenna were used to send the pictures back to the earth. 
Actually, Mariner IV used a rather highly directional &ldquo;dish&rdquo; antenna, but note that the antenna and its pointing equipment must have weighed less than 35 lb if it was to economize on take-off weight. 


Although these energies and masses are perhaps surprisingly large when we consider that they all arose from the very small number of joules per bit (\num{e-21}, see p. 16), they are nevertheless small compared to the masses and energies that would be necessary to send physical hardware back from Mars. 
For example, even a small canister of exposed photographic film might weigh \SI{1}{\pound}, but we would have to send along with it enough fuel to start it on its return journey, namely about \SI{400}{\pound} of fuel. 
This would add $\num{400}\times\num{400}\,text{lb}$ or no less than \SI{80}{tons} to the original take-off mass when the probe leaves the earth&emdash;and we have completely ignored the extra equipment that would be needed to ensure both a proper return orbit and a safe re-entry through the earth&#39;s atmosphere. 


When we consider the very much greater distances to the nearer stars, the economy of sending signals rather than hardware becomes even more marked. 
We have seen that nothing short of an ideal nuclear rocket can send a physical payload to the nearest star, and that even then the trip would require several tens of years. 
On the other hand, if we consider distances as great as 12 light years (containing 20 to 30 stars), it is possible to show that, with \SI{300}{\foot} antennas at the transmitter and receiver, a ten-word telegram can be sent with about a kilowatt-hour of radiated energy (Fig. \ref{fig:7}).
This is less than one dollar&#39;s worth of energy at current prices. 


Of course, the trouble is that there is no body at the other end to communicate to. 
Or is there? 
In the remainder of this section, we shall discuss the question of communicating with other people out there&emdash;if there are any. 


<figure>
\label{fig:7}
\caption{Fig. \ref{fig:7} from E. M. Purcell, &ldquo;Radioastronomy and Communication through Space&rdquo; [BNL lecture series \#BNL 658 (T-214) ] 1960 , p. 9.}
</figure>


Let us look at just our own galaxy. 
There are some \num{e11} stars in the galaxy. 
Double stars are by no means uncommon, and in fact, there appear to be almost as many double stars as single stars. 
Astronomers take this as a hint that planetary systems around stars may not be very uncommon either. 
Moreover, a large number of stars are not rapidly spinning. 
One good way for a star to lose most of its spin is by interacting with its planets; that is what probably happened in our own solar system. 
So the chances that there are hundreds of millions of planetary systems among the hundred billion stars in our galaxy seem good. 
One can elaborate on this, but we shall not try to estimate the probability that a planet occurs at a suitable distance from a star, that it has an atmosphere in which life is possible, that life developed, and so on. 
Very soon in such speculation, the word &ldquo;probability&rdquo; loses any practical meaning. 
On the other hand, one can scarcely escape the impression that it would be rather remarkable if only one planet in a billion (to speak only of our own galaxy) had become the home of intelligent life. 


Since we can communicate so easily over such vast distances, it ought to be easy to establish communication with a society (if we may use that word) in a remote spot. 
It would be even easier for them to initiate communication with us if they were technologically ahead of us. 
Should we try to listen for such communications, or should we broadcast a message and hope that someone will hear it? 
If you think about this a little, you will probably agree that we want to listen before we transmit. 
The historic time scale of our galaxy is very long, whereas wireless telegraphy on Earth is only 50 years old, and really sensitive receivers are much more recent. 
If we bank on people who are able to receive our signals but have not surpassed us technologically, that is, people who are not more than 20 years behind us but still not ahead, we are exploring a very thin slice of history. 
On the other hand, if we listen instead of transmitting, we might hear messages from people anywhere who are ahead of us and happen to have the urge to send out signals. 
Also, being technologically more advanced than we are, they can presumably transmit much better than we can. 
So it would not be sensible for us to transmit until we have listened for a long time. 


If you want to transmit to someone&emdash;and you and he cannot agree on what radio frequency to use&emdash;the task is nearly hopeless. 
To search the entire radio spectrum for a feeble signal entails a vast waste of time. 
It is like trying to meet someone in New York when you have been unable to communicate and agree on a meeting place. 
Still, you know you want to meet him and he wants to meet you. 
Where do you end up? 
There are only a few likely places: at the clock of Grand Central Station, in the lobby of the Metropolitan Museum, and so on. 
Here, there is only one Grand Central Station, namely the 1420-megacycle/sec frequency emitted by hydrogen, which is the most prominent radio frequency in the whole galaxy (by a factor of at least 1000).
There is no question as to which frequency to use if you want the other fellow to hear: you pick out the frequency that he knows. 
Conversely, he will pick out the frequency that he knows we know, and that must surely be 1420-megacycle/sec frequency. 


Let us assume rhat his transmitter can radiate a megawatt of power within a 1-cycle/sec bandwidth. 
This is something that we could do ourselves if we wished to; it is just a modest stretch of the present state of the art. 
If we receive with a \SI{300}{\foot} dish-antenna and he transmits with a similar one, we should be able to recognize his signal even if it comes from several hundred light years away. 
With the new maser receivers, which are now being used in radioastronomy, 500 light years ought to be easy. 
But even a sphere only 100 light years in radius contains about 400 stars of roughly the same brightness as the sun. 
And the volume accessible to coiranunication increases as the cube of the range.
We have previously argued that it is hopelessly difficult to travel even a few light years, and we now see that it is in principle quite easy to coinmunicate over a few hundreds of light years. 
The ratio of the volumes is about one million. (Fig. \ref{fig:8}) 


<figure>
\label{fig:8}
\caption{(From Purcell, op. cit.)}
</figure>


There are other interesting questions. 
When we get a signal, how do we know it is real and not just some accident of cosmic static? 
This might be called the problem of the axe head: an archeologist finds a lump of stone that looks vaguely like an axe head; how does he know it is an axe head and not an oddly shaped lump of stone?
Actually, the archeologist is usually very sure. 
An arrowhead can look rather like an elliptical pebble, and still there is no doubt that it is an arrowhead. 
Our axe head problem can be solved in many ways. 
Perhaps the neatest suggestion for devising a message having the unmistakable hallmark of intelligent beings is the suggestion made by G. Cocconi and P. Morrison. 
They would have the sender transmit a few prime numbers, i.e., 1, 3, 5, 7, 11, 13, 17 &hellip; .
There are no magnetic storms that send messages like this. 


What can we talk about with our remote friends? 
We have a lot in common. To start with, we have mathematics in common, and physics, chemistry, and astronomy. 
We have the galaxy in which we are near neighbors. 
So we can open our discourse on common ground before we move into the more exciting exploration of what is not common experience. 
Of course, the conversation has the peculiar feature of a very long builtin delay. 
The answer comes back decades later. 
But it gives one&#39;s children something to look forward to. 


## Appendix A

### Appendix A: The rocket equation

In Eq, (\ref{eq:1}), we showed that, during very small changes of velocity <span class="math">&Delta;v</span>, the following relation is required by the conservation of momentum: 

\begin{equation}
    \frac{\Delta m}{m} = \frac{\Delta v}{v_{ex}}
\end{equation}

Now we want to extend this relation to arbitrarily large changes of velocity. 

A large change of velocity can be conceptually divided into a great many steps with a small change in each. 
Let us choose these in such a manner that all of them involve the same fractional change in the mass of the rocket. 
For example, we may choose 

\begin{equation}
    \frac{\Delta m}{m} = \frac{1}{n}
\end{equation}

where <span class="math">n</span> is a large number that we will leave unspecified for the moment, but it is to be the same for each small step. 

Then if <span class="math">m</span> is the original mass of the rocket and <span class="math">m_1</span> is its mass after the first small step of velocity change, we will have: 

\begin{equation}
    m_1 = \left(1-\frac{1}{n}\right) m_0.
\end{equation}

After the second step, the mass will become: 

\begin{equation}
    m_2 = \left(1-i\right) m_1 = \left(1-\frac{1}{n}\right)^2 m_0.
\end{equation}

After the third step, it will be: 

\begin{equation}
    m_3 = \left(1-i\right)^3 m_0
\end{equation}

and it is easy to see that after <span class="math">k</span> of our very small changes in velocity, the mass of the rocket will be 

\begin{equation}
    m_k = \left(1-i\right)^k m_0
\end{equation}

Now, what will be the change in the rocket&#39;s velocity during these <span class="math">k</span> steps of acceleration? 
By substituting Eq. (\ref{eq:a2}) into Eq. (\ref{eq:a1}), we find that during each step the velocity change will be: 

\begin{equation}
    \Delta v = \frac{1}{n} v_{ex}.
\end{equation}

Since these are all the same, the total change in velocity during <span class="math">k</span> steps will be just $k(\Delta v)$. 
If we denote this total change in the rocket&#39;s velocity by <span class="math">v</span>, we have: 

\begin{equation}
    v_c = \frac{k}{n} v_{ex}.
\end{equation}


Now solve this relation for k; 

\begin{equation}
    k = n \left( \frac{v_c}{v_{ex}}\right).
\end{equation}

And substitute into Eq. (\ref{eq:a3}): 

\begin{equation}
    m_k = m_0 \left(1-\frac{1}{n}\right)^{n\frac{v_c}{v_{ex}}}
\end{equation}


If we write <span class="math">m</span> in place of <span class="math">m_k</span>, with the understanding that <span class="math">m</span> now represents the rocket&#39;s mass after its velocity has changed by <span class="math">v_c</span>, and if we use the multiplication rule for exponents, we can write our result in the following form: 

\begin{equation}
    m = m_0 \left[\left(1-\frac{1}{n}\right)^n\right]^{\frac{v_c}{v_{ex}}}
\end{equation}

We have eliminated <span class="math">k</span> from our relations, by expressing it in terms of the velocity change <span class="math">v</span>. 
Can we eliminate n? In a sense, we cannot, but we can replace it by a less arbitrary quantity. 


As we noted earlier, the simple relation Eq. (\ref{eq:a1}) is valid only for very small bursts of thrust. 
The smaller the burst, the more accurate Eq. (\ref{eq:a1}) becomes. 
In view of Eq. (\ref{eq:a2}) , then our relations will all become more and more accurate as we choose <span class="math">n</span> larger and larger. 
Obviously, the best thing to do is to choose <span class="math">n</span> so very large that the quantity in square brackets in Eq. (\ref{eq:a4}) approaches a steady value and no longer changes significantly. 
Better still, we should take the limit of the square brackets as <span class="math">n</span> &ldquo;approaches infinity.&rdquo; 

Perhaps it is not obvious that this limit exists in the sense that it is a well-defined number, but this fact can be shown by methods that we cannot pursue in this book. 
To agree with standard mathematical notation, we shall define a number e by the relation: 

\begin{equation}
    \frac{1}{e} = \lim_{n \to \infty} \left[1-\frac{1}{n}\right]^n
\end{equation}

The number <span class="math">e</span> has been evaluated to very many decimal places, but in physics we seldom need more than a few places: $e=\num{2.718}$ is usually quite sufficient. 
Another way of stating the value is often more convenient: 

\begin{equation}
    e = 10^{0.4343}.
\end{equation}

Now, if we let <span class="math">n</span> approach infinity in Eq. (\ref{eq:a4}) and substitute the definition (A5), we obtain the result:

\begin{equation}
    m = m_0 \left(\frac{1}{e}\right)^{\frac{v_c}{v_{ex}}}
\end{equation}

This final relation can be rewritten in many ways. 
Eq. (\ref{eq:2}) of this chapter is the same as Eq. (\ref{eq:a6});
and Eqs. (\ref{eq:4}) and (\ref{eq:5}) are other forms obtained by solving Eq. (\ref{eq:a6}) for <span class="math">m</span> and substituting a numerical value for <span class="math">e</span>.

    
## Appendix B

### Appendix B. Escape velocity

If a body is projected away from the earth with sufficient velocity, it will never return. 
The smallest such velocity is called the escape velocity, and we shall derive it in this section from the law of conservation of energy. 


The initial kinetic energy of a body of mass m that has been projected out from the earth with velocity <span class="math">v</span> is equal to $\frac{1}{2}mv^2$. 
If this is just equal to the work that must be done against the earth&#39;s gravitational force on the body as it travels away, then the body will slow down greatly when it gets very far away, but it will never entirely stop, as it would if its initial kinetic energy were less than the work that must be done against the gravitational attraction. 


Thus, our main task is to evaluate the work that is done against the earth&#39;s gravitational force by a body that moves from the earth&#39;s surface to a very large distance away. 
But to simplify the language of our arguments, we shall evaluate the work done <em>on</em> the body <em>by</em> the earth&#39;s gravitational field. 


Newton&#39;s law of gravitation states that the force on a body of mass <span class="math">m</span> due to the earth (mass <span class="math">M</span>) is 

\begin{equation}
    \label{eq:b1}
    F = G \frac{mM}{R^2}
\end{equation}

where <span class="math">G</span> is Newton&#39;s gravitational constant and <span class="math">R</span> is the distance from the body to the center of the earth. 
When the body moves a small distance 
AR further away from the earth, the work done on it by the gravitational force will be 

\begin{equation}
    \label{eq:b2}
    \Delta W = -F\left(\Delta R\right) = \left(GmM\right)\frac{-\Delta R}{R^2}
\end{equation}

where the minus sign arises because the force opposes the increase in <span class="math">R</span>. 


Now we must add up all the <span class="math">&Delta;W</span>&#39;s for all the <span class="math">&Delta;R</span>&#39;s as the body moves from the earth&#39;s surface to a very great distance. 
In Eq. (\ref{eq:b2}), the quantity $(GmM)$ is a simple constant, but $1/R^2$ changes continually as the body moves away, and we must find some way to express the ratio $-\left(\Delta R\right)/R^2$ as a change in some other quantity. 
One way to find this desired quantity is to guess at it and then try to prove that the guess is correct. 
From the fact that $-\left(\Delta R\right)/R^2$ has the units of a reciprocal length, we might guess that it could equal $\Delta\left(1/R\right)$. 
The change in $1/R$, as <span class="math">R</span> itself changes by <span class="math">&Delta;R</span>, will be: 

\begin{equation}
    \Delta \left( \frac{1}{R} \right) = \frac{1}{R+\Delta R} - \frac{1}{R} = \frac{-\Delta R}{R\left(R+\Delta R\right)}
\end{equation}

This is almost the result we were seeking, and now we note that we are free to make the individual steps AR as small as we like. 
Thus, we can make $-\left(\Delta R\right)/R^2$ equal to $\Delta\left(1/R\right)$ to any accuracy that we may wish to choose. 
In the limit as the steps are made smaller and smaller, the relation becomes exact, although we cannot go into the proof of this here. 

Accordingly, we can rewrite Eq. (\ref{eq:b2}) as follows: 

\begin{equation}
    \label{eq:b3}
    \Delta W = \left(GmM\right) \Delta\left(\frac{1}{R}\right) 
\end{equation}

This equation states that the steps AW in the total work done are just equal to the constant $(GmM)$ times the corresponding changes in the quantity $1/R$. 
The sum of all the AW&#39;s, therefore, will be equal to the total change in the quantity $GmM/R$.
If the body moves far enough from the earth, we may take the final value of this quantity as zero (because <span class="math">R</span> &ldquo;approaches infinity&rdquo;), and the initial value was $GmM/R$, where <span class="math">R</span> is the radius of the earth. 
The total net change is the final value minus the initial one: 

\begin{equation}
    W = -G \frac{Mm}{R_e}
\end{equation}

We can simplify this result and eliminate the factor <span class="math">GM</span> by observing that, when $R=R_e$, Eq. (\ref{eq:b1}) will give the gravitational force on the body when it is at tne earth&#39;s surface and that this force must be simply <span class="math">mg</span>.

\begin{equation}
    \frac{GM}{R_e^2} m = F \text{(at surface)} = mg.
\end{equation}

Thus, $GM=gR^2$, and when this is substituted into Eq. (\ref{eq:b3}), we obtain: 

\begin{equation}
    \label{eq:b4}
    W = -m g R_e
\end{equation}

The work done by the body against the gravitational attraction of the earth will be just the negative of this quantity, and we have already observed that, if <span class="math">v</span> is equal to the escape velocity, this work must equal the initial kinetic energy of the body: 

\begin{equation*}
    m g R_e = \frac{1}{2} mv^2
\end{equation*}

Multiplying through by $2/m$ and taking the square root of both sides of this equation, we obtain the final formula for the escape velocity: 

\begin{equation*}
    v \text{(escape)} = \sqrt{2gR_e}
\end{equation*}

Notice that this is independent of the mass of the body. 
Inserting the numerical values $R=\SI{6400}{\kilo\meter}$, $g=\SI{0.0098}{\kilo\meter\per\second\squared}$, we arrive at the value we have been seeking: 

\begin{equation*}
    v \text{(escape)} = \SI{11.2}{\kilo\meter\per\second}
\end{equation*}




