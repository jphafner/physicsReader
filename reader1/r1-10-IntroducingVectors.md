---
layout: ebook
title: Introducing Vectors
author: Banesh Hoffman
exerpt: In his witty and provocative book. 
    About Vectors, from which this opening chapter is taken, Banesh HofFmann confesses that he seeks here &rdquo;to instruct primarily by being disturbing and annoying.&rdquo;
intro: A chapter from his book <em>About Vectors</em>, 1966.
---

Making good definitions is not easy.
The story goes that when the philosopher Plato defined Man as &ldquo;a two-legged animal without feathers,&rdquo; Diogenes produced a plucked cock and said &ldquo;Here is Plato&#39;s man.&rdquo;
Because of this, the definition was patched up by adding the phrase &ldquo;and having broad nails&rdquo;;
    and there, unfortunately, the story ends. 
But what if Diogenes had countered by presenting Plato with the feathers he had plucked?

<dl>
  <dt>Exercise 1.1</dt>
  <dd>What? [Note that Plato would now have feathers.]</dd>
  <dt>Exercise 1.2</dt>
  <dt>Under what circumstances could an elephant qualify as a man according to the above definition?</dt>
</dl>

A vector is often defined as an entity having both magnitude and direction.
But that is not a good definition. 
For example, an arrow-headed line segment like this
\begin{center}
    %% NOTE: add diagram tikz
\end{center}

has both magnitude (its length) and direction, and it is often used as a drawing of a vector;
    yet it is not a vector.
Nor is an archer&#39;s arrow a vector, though it, too, has both magnitude and direction.

To define a vector we have to add to the above definition something analogous to &ldquo;and having broad nails,&rdquo; and even then we shall find ourselves not wholly satisfied with the definition.
But it will let us start, and we can try patching up the definition further as we proceed&mdash;and we may even find ourselves replacing it by a quite different sort of definition later on.
If, in the end, we have the uneasy feeling that we have still not found a completely satisfactory definition of a vector,
    we need not be dismayed, for it is the nature of definitions not to be completely satisfactory,
    and we shall have learned pretty well what a vector is anyway, just as we know,
    without being able to give a satisfactory definition,
    what a man is&mdash;well enough to be able to criticize Plato&#39;s definition.

<dl>
  <dt>Exercise 1.3</dt>
  <dd>Define a door.</dd>
  <dt>Exercise 1.4</dt>
  <dt>Pick holes in your definition of a door.</dt>
  <dt>Exercise 1.5</dt>
  <dt>According to your definition, is a movable partition between two rooms a door?</dt>
</dl>

## The Parallelogram Law

The main thing we have to add to the magnitude-and-direction definition of a vector is the following:

<figure id="fig2-1">
</figure>

Let us think of vectors as having definite locations.
And let the arrow-headed line segments <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> in [Figure 2-1](#fig2-1) represent the magnitudes,
directions, and locations of two vectors starting at a common point <span class="math">O</span>.
Complete the parallelogram formed by <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>, and draw the diagonal <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>.
Then, when taken together, the two vectors represented by <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> are equivalent to a single vector represented by the arrow-headed line segment <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>.
This vector is called the resultant of the vectors represented by <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>, and the above crucial property of vectors is called the parallelogram law of combination of vectors.

\begin{description}
    \item[Exercise 2.1] Find (a) by drawing and measurement, and (b) by calculation using Pythagoras&#39; theorem, the magnitude and direction of the resultant of two vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> if each has magnitude 3, and <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> points thus &rarr; while <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> points perpendicularly, thus &uparrow;.
    [<em>Ans</em>. The magnitude is <span class="math">3 \sqrt{2}</span>, or approximately <span class="math">4.2</span>, and the direction bisects the right angle between <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>.]
    \item[Exercise 2.2] Show that the resultant of two vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> that point in the same direction is a vector pointing in the same direction and having a magnitude equal to the sum of the magnitudes of <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>.
        [Imagine the parallelogram in [Figure 2-1](#fig2-1) squashed flat into a line.]
    \item[Exercise 2.3] Taking a hint from Exercise 2.2, describe the resultant of two vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> that point in opposite directions.
    \item[Exercise 2.4] In Exercise 2.3, what would be the resultant if <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> had equal magnitudes?
        [Do you notice anything queer when you coropare this resultant vector with the definition of a vector?]
    \item[Exercise 2.5] Observe that the resultant of <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> is the same as the resultant of <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>.
        [This is trivially obvious, but keep it in mind nevertheless. We shall return to it later.]
\end{description}

<dl>
  <dt>Exercise 2.1</dt>
  <dd>Find (a) by drawing and measurement, and (b) by calculation using Pythagoras&#39; theorem, the magnitude and direction of the resultant of two vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> if each has magnitude 3, and <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> points thus <span
      class="math">&rarr;</span> while <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> points perpendicularly, thus <span class="math">&uparrow;</span>.
  [<em>Ans</em>. The magnitude is <span class="math">3\sqrt{2}</span>, or approximately <span class="math">4.2</span>, and the direction bisects the right angle between <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>.]</dd>
  <dt>Exercise 2.2</dt>
  <dt>Pick holes in your definition of a door.</dt>
  <dt>Exercise 2.3</dt>
  <dt>According to your definition, is a movable partition between two rooms a door?</dt>
</dl>

In practice, all we need to draw is half the parallelogram in [Figure 2-1](#fig2-1)&mdash;either triangle <span class="math">OPR</span> or triangle <span class="math">OQR</span>.
When we do this it looks as if we had combined two vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>P</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math> (or <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>Q</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>) end-to-end like this, even
\begin{figure}
    %% NOTE: add tikz diagram
    \label{fig:2.2}
    \caption{For clarity, the arrow heads meeting at <span class="math">R</span> have been slightly displaced.
        We shall occasionally displace other arrow heads under similar circumstances.}
\end{figure}

though they do not have the same starting point.
Actually, though, we have merely combined OP and OQ by the parallelogram law. [^1]
But suppose we were dealing with what are called free vectors&mdash;vectors having the freedom to move from one location to another,
    so that <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>Q</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math> in [Figure 2-2](#fig2-2),
    for example, which have the same magnitude and the same direction,
    are officially counted not as distinct vectors but as the same free vector.
Then we could indeed combine free vectors that were quite far apart by bringing them end-to-end,
    like <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>P</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math> in [Figure 2-2](#fig2-2).
But since we could also combine them according to the parallelogram law by moving them so that they have a common starting point,
    like <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math> in [Figure 2-1](#fig2-1),
    the parallelogram law is the basic one.
Note that when we speak of the same direction we mean just that,
    and not opposite directions&mdash;north and south are not the same direction.

\begin{description}
    \item[Exercise 2.6] Find the resultant of the three vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math>, <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math>, and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> in the diagram.
        \begin{tikzpicture}
            %% NOTE: add diagram
        \end{tikzpicture}
        <em>Solution</em> We first form the resultant, <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>, of <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math> like this:
        \begin{tikzpicture}
            %% NOTE: add diagram
        \end{tikzpicture}
        and then we form the resultant, <math displa="inline"><mover><mrow><mi>O</mi><mi>S</mi></mrow><mo>&rarr;</mo></mover></math>, of <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> like this :
        \begin{tikzpicture}
            %% NOTE: add diagram
        \end{tikzpicture}
        This figure looks complicated.
        We can simplify it by drawing only half of each parallelogram, and then even omitting the line OR,
            like this:
        \begin{tikzpicture}
            %% NOTE: add diagram
        \end{tikzpicture}
        From this we see that the resultant <math displa="inline"><mover><mrow><mi>O</mi><mi>S</mi></mrow><mo>&rarr;</mo></mover></math> can be found quickly by thinking of the vectors as free vectors and combining them by placing them end-to-end;
            <math displa="inline"><mover><mrow><mi>A</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>, which has the same magnitude and direction as <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math>,
            starts where <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math> ends; and then <math displa="inline"><mover><mrow><mi>R</mi><mi>S</mi></mrow><mo>&rarr;</mo></mover></math>,
            which has the same magnitude and direction as <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math>,
            starts where <math displa="inline"><mover><mrow><mi>A</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math> ends.
    \item[Exercise 2.7] Find, by both methods, the resultant of the vectors in Exercise 2.6, but by combining <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> first, and then combining their resultant with <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math>.
        Prove geometrically that the resultant is the same as before.
    \item[Exercise 2.8]
        \begin{tikzpicture}
            %% NOTE: add diagram
        \end{tikzpicture}
        The above diagram looks like a drawing of a box.
        Show that if we drew only the lines <span class="math">OA</span>, <span class="math">AR</span>, <span class="math">RS</span>, and <span class="math">OS</span> we would have essentially the last figure in Exercise 2.6;
            that if we drew only the lines <span class="math">OB</span>, <span class="math">BT</span>, <span class="math">TS</span>, and <span class="math">OS</span> we would have a corresponding figure for Exercise 2.7;
            and that if we drew only <span class="math">OA</span>, <span class="math">AU</span>, <span class="math">US</span>, and <span class="math">OS</span> we would have a figure corresponding to our having first combined OA with OC and then their resultant with OB.
    \item[Exercise 2.9] In Exercises 2.6, 2.7, and 2.8, is it essential that the three vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math>, <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math>, and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> lie in a plane?
        Give a rule for finding the resultant of three noncoplanar vectors <mat displa="inline"h><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math>, <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math>, and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> that is analogous to the parallelogram law, and that might well be called the parallelepiped law.
        Prove that their resultant is the same regardless of the order in which one combines them.
    \item[Exercise 2.10] Find the resultant of the three vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math>, <math displa="inline"><mover><mrow><mi>O</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math>, and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> below by combining them in three different orders, given that vectors <math displa="inline"><mover><mrow><mi>O</mi><mi>A</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>O</mi><mi>C</mi></mrow><mo>&rarr;</mo></mover></math> have equal magnitudes and opposite directions.
        Draw both the end-to-end diagrams and the full parallelogram diagrams for each case.
\end{description}


## Jounneys Are Not Vectors

It is all very well to start with a definition.
But it is not very enlightening.
Why should scientists and mathematicians be interested in objects that have magnitude and direction and combine according to the parallelogram law?
Why did they even think of such objects?
Indeed, do such objects exist at all&mdash;outside of the imaginations of mathematicians?

There are, of course, many objects that have both magnitude and direction.
And there are, unfortunately, many books about vectors that give the reader the impression that such objects obviously and inevitably obey the parallelogram law.
It is therefore worthwhile to explain carefully why most such objects do not obey this law, and then, by a process of abstraction, to find objects that do.


Suppose that I live at <span class="math">A</span> and my friend lives 10 miles away at <span class="math">B</span>.
I start from <span class="math">A</span> and walk steadily at 4 m.p.h. for 2.5 hours.
Obviously, I walk 10 miles.
But do I reach 5?

You may say that this depends on the direction I take.
But what reason is there to suppose that I keep to a fixed direction?
The chances are overwhelming that I do not&mdash;unless I am preceded by a bulldozer or a heavy tank.
Most likely I walk in all sorts of directions;
    and almost certainly, I do not arrive at <span class="math">B</span>.
I may even end up at home.

\begin{description}
    \item[Exercise 3.1] Where are all the possible places at which I can end, under the circumstances?
\end{description}

Now suppose that I start again from <span class="math">A</span> and this time end up at <span class="math">B</span>.
I may take four or five hours, or I may go by bus or train and get there quickly.
Never mind how I travel or how long I take.
Never mind how many times I change my direction, or how tired I get, or how dirty my shoes get, or whether it rained.
Ignore all such items, important though they be, and consider the abstraction that results when one concentrates solely on the fact that I start at A and end at B. Let us give this abstraction a name. What shall we call it?
Not a &ldquo;journey.&rdquo;
That word reminds us too much of everyday life&mdash;of rain, and umbrellas, and vexations, and lovers meeting, and all other such items that we are ignoring here;
    besides, we want to preserve the word &ldquo;journey&rdquo; for just such an everyday concept.
For our abstraction we need a neutral, colorless word. Let us call it a shift.
Here are routes of four journeys from A to B:

\begin{figure}
\label{fig:3.1}
\end{figure}

All four journeys are different&mdash;with the possible but highly improbable exception of (b) and (c).

\begin{description}
    \item[Exercise 3.2] Why &ldquo;highly improbable&rdquo;?
\end{description}

But though the four journeys are not all the same, they yield the same shift.
We can represent this shift by the arrow-headed line segment <span class="math">AB</span>.
It has both magnitude and direction.
Indeed, it seems to have little else.
Is it a vector?
Let us see.

Consider three places <span class="math">A</span>, <span class="math">B</span>, and <span class="math">C</span> as in Figure 3.2.
If I walk in a straight

\begin{figure}
\label{fig:3.2}
\end{figure}

line from <span class="math">A</span> to <span class="math">B</span> and then in a straight line from <span class="math">B</span> to <span class="math">C</span>,
    I make a journey from <span class="math">A</span> to <span class="math">C</span>,
    but it is not the same as if I walked directly in a straight line from A to C: the scenery is different,
    and so is the amount of shoe leather consumed,
    most likely, and we can easily think of several other differences.

\begin{description}
    \item[Exercise 3.3] Why &ldquo;most likely&rdquo;?
\end{description}

Thus, though we could say that the walks from <span class="math">A</span> to <span class="math">B</span> and from <span class="math">B</span> to <span class="math">C</span> combine to give a &ldquo;resultant&rdquo; journey from <span class="math">A</span> to <span class="math">C</span>,
    it is not a journey in a straight line from <span class="math">A</span> to <span class="math">C</span>:
    the walks do not combine in a way reminiscent of the way in which vectors combine;
    they combine more in the tautological sense that $2+1=2+1$ than $2+1=3$.

Journeys, then, are not vectors.
But when we deal with shifts we ignore such things as the scenery and the amount of shoe leather consumed.
A shift from <span class="math">A</span> to <span class="math">B</span> followed by a shift from <span class="math">B</span> to <span class="math">C</span> is indeed equivalent to a shift from <span class="math">A</span> to <span class="math">C</span>.
And this reminds us so strongly of the vectorial situation in [Figure 2-2](#fig2-2) that we are tempted to conclude that shifts are vectors.
But there is a crucial difference between the two situations.
We cannot combine the above shifts in the reverse order (compare Exercise 2.5).
There is no single equivalent to the shift from 5 to C followed by the shift from <span class="math">A</span> to <span class="math">B</span>.
We can combine two shifts only when the second begins where the first ends.
Indeed, in [Figure 2-1](#fig2-1), just as with journeys, we cannot combine a shift from <span class="math">O</span> to <span class="math">P</span> with one from <span class="math">O</span> to <span class="math">Q</span> in either order.
Thus shifts are not vectors.


## Displacements Are Vectors

Now that we have discovered why shifts are not vectors,
    we can easily see what further abstraction to make to obtain entities that are.
From the already abstract idea of a shift,
    we remove the actual starting point and end point and retain only the relation between them:
    that B lies such and such a distance from A and in such and such a direction. [^2]
Shifts were things we invented in order to bring out certain distinctions.
But this new abstraction is an accepted mathematical concept with a technical name:
    it is called a displacement.
And it is a vector, as we shall now show.

In Figure 4.1, the arrow-headed line segments AB and LM are parallel and

\begin{figure}
%% NOTE: add tikz diagram
\label{fig:4.1}
\end{figure}

of equal length.
Any journey from <span class="math">A</span> to <span class="math">B</span> is bound to be different from a journey from <span class="math">L</span> to <span class="math">M</span>.
Also, the shift from <span class="math">A</span> to <span class="math">B</span> is different from that from <span class="math">L</span> to <span class="math">M</span> because the starting points are different, as are the end points.
But the two shifts, and thus also the various journeys, yield the same displacement:
    if, for example, <span class="math">B</span> is 5 miles north-northeast of <span class="math">A</span>, so too is <span class="math">M</span> 5 miles north-northeast of <span class="math">L</span>, and the displacement is one of 5 miles in the direction north-northeast.

\begin{description}
    \item[Exercise 4.1] Starting from a point <span class="math">A</span>, a man bicycles 10 miles due east to point B, stops for lunch, sells his bicycle, and then walks 10 miles due north to point <span class="math">C</span>.
        Another man starts from <span class="math">B</span>, walks 4 miles due north and 12 miles due east and then, feeling tired, and having brought along a surplus of travellers&#39; checks, buys a car and drives 6 miles due north and 2 miles due west, ending at point D in the pouring rain.
        What displacement does each man undergo? [<em>Ans</em>. $10\sqrt{2}$ miles to the northeast.]
\end{description}

Now look at [Figure 2-1](#fig2-1).
The shift from <span class="math">O</span> to <span class="math">P</span> followed by the shift from <span class="math">P</span> to <span class="math">R</span> is equivalent to the shift from <span class="math">O</span> to <span class="math">R</span>.
The shift from <span class="math">P</span> to <span class="math">R</span> gives a displacement <span class="math">PR</span> that is the same as the displacement <span class="math">OQ</span>.
Therefore the displacement <span class="math">OP</span> followed by the displacement <span class="math">OQ</span> is equivalent to the displacement <span class="math">OR</span>.

\begin{description}
    \item[Exercise 4.2] Prove, similarly, that the displacement <span class="math">OQ</span> followed by the displacement <span class="math">OP</span> is also equivalent to the displacement <span class="math">OR</span>.
\end{description}

Thus, displacements have magnitude and direction and combine according to the parallelogram law.
According to our definition, they are therefore vectors.
Since displacements such as <math displa="inline"><mover><mrow><mi>A</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>L</mi><mi>M</mi></mrow><mo>&rarr;</mo></mover></math> in [Figure 4-1](#fig4-1) are counted as identical, displacements are free vectors, and thus are somewhat special.
In general, vectors such as AB and LM are not counted as identical.


## Why Vectors Are Important

From the idea of a journey we have at last come,
    by a process of successive abstraction,
    to a specimen of a vector.
The question now is whether we have come to anything worthwhile.
At first sight it would seem that we have come to so pale a ghost of a journey that it could have little mathematical significance.
But we must not underestimate the potency of the mathematical process of abstraction.
Vectors happen to be extremely important in science and mathematics.
A surprising variety of things happen to have both magnitude and direction and to combine according to the parallelogram law;
    and many of them are not at all reminiscent of journeys.

This should not surprise us.
The process of abstraction is a powerful one.
It is, indeed, a basic tool of the mathematician.
Take whole numbers, for instance.
Like vectors, they are abstractions.
We could say that whole numbers are what is left of the idea of <em>apples</em> when we ignore not only the apple trees,
    the wind and the rain, the profits of cider makers,
    and other such items that would appear in an encyclopedia article,
    <em>but also ignore even the apples themselves</em>,
    and concentrate solely on how many there are.
After we have extracted from the idea of apples the idea of whole numbers,
    we find that whole numbers apply to all sorts of situations that have nothing to do with apples.
Much the same is true of vectors.
They are more complicated than whole numbers&mdash;so are fractions,
    for example&mdash;but they happen to embody an important type of mathematical behavior that is widely encountered in the world around us.

To give a single example here: forces behave like vectors.
This is not something obvious.
A force has both magnitude and direction, of course.
But this does not mean that forces necessarily combine according to the parallelogram law.
That they do combine in this way is inferred from experiment.

It is worthwhile to explain what is meant when we say that forces combine according to the parallelogram law.
Forces are not something visible, though their effects may be visible.
They are certainly not arrow-headed line segments,
    though after one has worked with them mathematically for a while,
    one almost comes to think they are.
A force can be represented by an arrow-headed line segment <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math> that starts at the point of application <span class="math">O</span> of the force, points in the direction of the force, and has a length proportional to the magnitude of the force&mdash;for example, a length of <span class="math">x</span> inches might represent a magnitude of <span class="math">x</span> pounds.
When a force is represented in this way, we usually avoid wordiness by talking of &ldquo;the force <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$.&rdquo;
But let us be more meticulous in our wording just here.
To verify experimentally that forces combine according to the parallelogram law, we can make the following experiment.
We arrange stationary weights and strings, and pulleys <span class="math">A</span> and <span class="math">B</span>, as shown, the weight <span class="math">W</span> being the


\begin{figure}
    %% NOTE: add diagram
    \label{fig:5.1}
\end{figure}

sum of the weights <span class="math">W<sub>1</sub></span> and <span class="math">W<sub>2</sub></span>.
Then along <span class="math">OA</span> we mark off a length <span class="math">OP</span> of <span class="math">W<sub>1</sub></span> inches,
    where <span class="math">W<sub>1</sub></span> is the number of pounds in the weight on the left and, thus,
    a measure of the force with which the string attached to it pulls on the point <span class="math">O</span> where the three pieces of string meet. Similarly, we mark off on <span class="math">OB</span> a length <span class="math">OQ</span> of <span class="math">W<sub>2</sub></span> inches.
We then bring a vertical piece of paper up to the point <span class="math">O</span>,
    and on it complete the parallelogram defined by <span class="math">OP</span> and <span class="math">OQ</span>.
We find that the diagonal <span class="math">OR</span> is vertical and that its length in inches is <span class="math">W</span>,
    the number of pounds in the weight in the middle.
We conclude that the resultant of the forces <span class="math">W<sub>1</sub></span> and <span class="math">W<sub>2</sub></span> in the strings would just balance the weight <span class="math">W</span>.
Since the forces <span class="math">W<sub>1</sub></span> and <span class="math">W<sub>2</sub></span> also just balance the weight <span class="math">W</span>,
    we say that the resultant is equivalent to the two forces.
We then do the experiment over again, with different weights, and reach a similar conclusion.
After that, we do it yet again;
    and we keep at it till our lack of patience overcomes our skepticism,
    upon which we say that we have proved experimentally that forces combine according to the parallelogram law.
And we bolster our assertion by pointing to other experiments,
    of the same and different types, that indicate the same thing.

We all know that it is much easier to get through a revolving door by pushing near the outer edge than by pushing near the central axis.
The effect of a force depends on its location.
Home runs are scarce when the bat fails to make contact with the ball.
Thus forces do not behave like free vectors.
Unlike displacements, vectors representing forces such as <math displa="inline"><mover><mrow><mi>A</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math>$ and <math displa="inline"><mover><mrow><mi>L</mi><mi>M</mi></mrow><mo>&rarr;</mo></mover></math>$ in [Figure 4-1](#fig4-1),
    though they have the same magnitude and the same direction, are not counted as equivalent.
Such vectors are called bound vectors.

Perhaps it worries us a little that there are different kinds of vectors.
Yet we have all, in our time, survived similar complications.
Take numbers, for example.
There are whole numbers and there are fractions.
Perhaps you feel that there is not much difference between the two.
Yet if we listed the properties of whole numbers and the properties of fractions we would find considerable differences.
For instance, if we divide fractions by fractions the results are always fractions, but this statement does not remain true if we replace the word &ldquo;fractions&rdquo; by &ldquo;whole numbers.&rdquo;
Worse, every whole number has a next higher one, but no fraction has a next higher fraction,
    for between any two fractions we can always slip infinitely many others.
Even so, when trying to define number we might be inclined to insist that,
    given any two different numbers, one of them will always be the smaller and the other the larger.
    Yet when we become more sophisticated and expand our horizons to include complex numbers like $2 + 3\sqrt{-1}$,
    we have to give up even this property of being greater or smaller, which at first seemed an absolutely essential part of the idea of number.
With vectors too, not only are there various types,
    but we shall learn that not every one of their attributes that seems at this stage to be essential is in fact so.
One of the things that gives mathematics its power is the shedding of attributes that turn out not to be essential, for this, after all, is just the process of abstraction.

\begin{description}
    \item[Exercise 5.1] Find the resultants of the following displacements:
        \begin{enumerate}[label=(\alph*)]
            \item 3 ft due east and 3 ft. due north. [Ans. 3yfY ft. to the northeast.]
            \item 5 ft due north and 5 ft. due east.
            \item 9 cm to the right and $9\sqrt{3}$ cm vertically upwards.
                [<em>Ans</em>. 18 cm in an upward direction making $60^{\circ}$ with the horizontal towards the right.]
            \item 9 cm to the left and $9\sqrt{3}$ cm vertically downward.
            \item the resultants in parts (c) and (d).
            \item <span class="math">x</span> units positively along the <span class="math">x</span>-axis and y units positively along the <span class="math">y</span>-axis.
                [<em>Ans</em>, $\sqrt{x^2 + y^2}$ units in the direction making an angle $\arctan\frac{y}{x}$ with the positive <span class="math">x</span>-axis.]
        \end{enumerate}
    \item[Exercise 5.2] Like Exercise 5.1 for the following:
        \begin{enumerate}[label=(\alph*)]
            \item 8 km. to the left and 3 km. to the left.
            \item 5 fathoms vertically downward and 2 fathoms vertically upward.
            \item a units to the right and $\beta$ units to the left.
                [There are three different cases. What are they?
                    Show how they can be summed up in one statement.]
            \item <span class="math">h</span> miles $60^{\circ}$ north of east and <span class="math">h</span> miles $60^{\circ}$ south of east.
        \end{enumerate}
    \item[Exercise 5.3] What single force is equivalent to the following three horizontal forces acting on a particle at a point O?
        \begin{enumerate*}[label=(\alph*)]
            \item magnitude 1 lb. pulling to the north
            \item magnitude 1 lb. pulling to the east
            \item magnitude $\sqrt{2}$ lb. pulling to the northwest
        \end{enumerate*}.
        [<em>Ans</em>. 2 lbs. acting at point <span class="math">O</span> and pulling to the north.]
    \item[Exercise 5.4] What force combined with a force at a point of 1 lb.
        pulling to the east will yield a resultant force of 2 lbs. pulling in a direction $60^{\circ}$ north of east?
    \item[Exercise 5.5] Vector <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$ has magnitude $2a$ and points to the right in a direction $30^{\circ}$ above the horizontal.
        What vector combined with it will yield a vertical resultant, <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>$,
        of magnitude $2\sqrt{3}$?
    \item[Exercise 5.6] Find two forces at a point <span class="math">O</span>,
        one vertical and one horizontal,
        that have a resultant of magnitude <span class="math">h</span>, making $45^{\circ}$ with the horizontal force.
        [Ans. The forces have magnitude $\frac{h}{\sqrt{2}}$.]
    \item[Exercise 5.7] Find two forces at a point <span class="math">O</span>,
        one vertical and one horizontal,
        that have a resultant of magnitude <span class="math">h</span> that makes an angle of $30^{\circ}$ with the horizontal force.
    \item[Exercise 5.8] Find two displacements, one parallel to the <span class="math">x</span>-axis and the other to the <span class="math">y</span>-axis,
        that yield a resultant displacement of magnitude <span class="math">h</span> ft. making a positive acute angle $\alpha$ with the positive <span class="math">x</span>-direction.
    \item[Exercise 5.9] What is the resultant of <span class="math">n</span> vectors, each starting at the point <span class="math">O</span>,
        each having magnitude <span class="math">h</span>, and each pointing to the pole star?
        [We could have shortened this by asking for the resultant of <span class="math">n</span> equal vectors.
        But we have not yet defined &ldquo;equal&rdquo; vectors&mdash;even though we have already spoken of the equality of free vectors!
        You may find it instructive to try to do so here; but be warned that it is not as easy as it seems, and that there is something lacking in the wording of the question.]
    \item[Exercise 5.10] A particle is acted on by two forces, one of them to the west and of magnitude 1 dyne, and the other in the direction $60^{\circ}$ north of east and of magnitude 2 dynes.
        What third force acting on the particle would keep it in equilibrium
        (i. e., what third force would make the resultant of all three forces have zero magnitude)?
        [Ans. Magnitude $\sqrt{3}$ dynes pointing due south.]
\end{description}


## The Singular Incident Of The Vectorial Tribe

It is rumored that there was once a tribe of Indians who believed that arrows are vectors.
To shoot a deer due northeast, they did not aim an arrow in the northeasterly direction;
    they sent two arrows simultaneously, one due north and the other due east, relying on the powerful resultant of the two arrows to kill the deer.

Skeptical scientists have doubted the truth of this rumor, pointing out that not the slightest trace of the tribe has ever been found.
But the complete disappearance of the tribe through starvation is precisely what one would expect under the circumstances;
    and since the theory that the tribe existed confirms two such diverse things as the Nonvectorial Behavior of Arrows and the Darvv&#39;inian Principle of Natural Selection, it is surely not a theory to be dismissed lightly.

<dl>
  <dt>Exercise 6.1</dt>
  <dd>Arrow-headed line segments have magnitude and direction and are used to represent vectors. Why are they nevertheless not vectors?</dd>
  <dt>Exercise 6.2</dt>
  <dd>Given the three vectors represented by <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>, <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>, and <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math> in [Figure 2-1](#fig2-1),
        form three new entities having the same respective directions, but having magnitudes equal to five times the magnitudes of the respective vectors.
        Prove geometrically that these new entities are so related that the third is a diagonal of the parallelogram having the other two as adjacent sides.</dd>
  <dt>Exercise 6.3</dt>
  <dd>If in Exercise 6.2 the new entities had the same respective directions as the vectors represented by <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>, <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>, and <math displa="inline"><mover><mrow><mi>O</mi><mi>R</mi></mrow><mo>&rarr;</mo></mover></math>,
        but had magnitudes that were one unit greater than the magnitudes of the corresponding vectors,
        show that the new entities would not be such that the third was a diagonal of the parallelogram having the other two as adjacent sides. </dd>
  <dt>Exercise 6.4</dt>
  <dd>Suppose we represented vectors by arrow-headed line segments that had the same starting points and directions as the vectors, but had lengths proportional to the squares of the magnitudes of the vectors, so that, for example, if a force of 1 lb. were represented by a segment of length 1 inch, then a force of 2 lbs. would be represented by one of 4 inches.
        Show that, in general, these representations of vectors would not obey the parallelogram law.
        Note that the statement of the parallelogram law in Section 2 therefore needs amending, and amend it accordingly.
        [If you think carefully, you will realize that this is a topsy-turvy question since, in proving the required result, you will assume that the vectors, when &ldquo;properly&rdquo; represented, obey the parallelogram law; and thus, in a sense, you will assume the very amendment you are seeking.
        But since you have probably been assuming the amendment all this while, you will be able to think your way through.
        The purpose of this exercise is to draw your attention to this rarely mentioned, usually assumed amendment.]</dt>
</dl>

## Some Awkward Questions

When are two vectors equal?
The answer depends on what we choose to mean by the word &ldquo;equal&rdquo;&mdash;we are the masters, not the word.
But we do not want to use the word in an outrageous sense:
    for example, we would not want to say that two vectors are equal if they are mentioned in the same sentence.

Choosing a meaning for the word &ldquo;equal&rdquo; here is not as easy as one might imagine.
For example, we could reasonably say that two vectors having the same magnitudes, identical directions, and a common starting point are equal vectors.
And if one of the vectors were somehow pink and the other green, we would probably be inclined to ignore the colors and say that the vectors were still equal.
But what if one of the vectors represented a force and the other a displacement? There would then be two difficulties.

The first difficulty is that the vector representing a displacement would be a free vector, but the one representing the force would not.
If, in Figure 4.1, we counted free vectors represented by <math displa="inline"><mover><mrow><mi>A</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>L</mi><mi>M</mi></mrow><mo>&rarr;</mo></mover></math> as equal,
    we might find ourselves implying that forces represented by <math displa="inline"><mover><mrow><mi>A</mi><mi>B</mi></mrow><mo>&rarr;</mo></mover></math> and <math displa="inline"><mover><mrow><mi>L</mi><mi>M</mi></mrow><mo>&rarr;</mo></mover></math> were also equal, though actually they have different effects.
    [Even so, it is extremely convenient to say such things as &ldquo;a force acts at <span class="math">A</span> and an equal force acts at <span class="math">L</span>.&rdquo;
We shall not do so in this book.
But one can get by with saying such things once one has explained what is awkward about them, just as, in trigonometry one gets by with writing <span class="math">sin<sup>2</sup>&theta;</span> after one has explained that this does not stand for <span class="math">sin(&theta;)</span> but <span class="math">(sin&theta;)<sup>2</sup>.]

As for the second difficulty about the idea of the equality of vectors, it takes us back to the definition of a vector.
For if, in Figure 2.1, <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$ represents a force and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>$ a displacement, the two vectors will not combine by the parallelogram law at all. 
We know this from experiments with forces.
But we can appreciate the awkwardness of the situation by merely asking ourselves what the resultant would be if they did combine in this way.
A &ldquo;disforcement&rdquo;? [^3]
[Compare Exercise 5.9.]


If two vectors are to be called equal, it seems reasonable to require that they be able to combine with each other.
The situation is not the same as it is with numbers.
Although 3 apples and 3 colors are different things,
    we can say that the numbers 3 are equal in the sense that,
    if we assign a pebble to each of the apples,
    these pebbles will exactly suffice for doing the same with the colors.
    And in this sense we can indeed combine 3 apples and 3 colors&mdash;not to yield 6 apples, or 6 colors, or 6 colored apples [it would surely be only 3 colored apples], but 6 <em>items</em>.
There does not seem to be a corresponding sense in which we could reasonably combine a vector representing a force with one representing a displacement, quite apart from the question of bound versus free vectors:
    there does not seem to be a vectorial analogue of the numerical concept of a countable item. [^4]

Though <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$ and <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$ do not combine according to the parallelogram law if, for example, <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$ represents a force and <math displa="inline"><mover><mrow><mi>O</mi><mi>Q</mi></mrow><mo>&rarr;</mo></mover></math>$ a  displacement, they nevertheless represent vectors.
Evidently our definition of a vector needs even further amendment.
We might seek to avoid trouble by retreating to the definition of a vector as &ldquo;an entity having both magnitude and direction,&rdquo;
    without mentioning the parallelogram law.
But once we start retreating, where do we stop?
Why not be content to define a vector as &ldquo;an entity having direction,&rdquo; or as &ldquo;an entity having magnitude,&rdquo; or, with Olympian simplicity, as just &ldquo;an entity&rdquo;?
Alternatively, we could make the important distinction between the abstract mathematical concept of a vector and entities,
    such as forces, that behave like these abstract vectors and are called vector quantities.
This helps, but it does not solve the present problem so much as sweep it under the rug.
We might amend our definition of a vector by saying that vectors combine according to the parallelogram law only with vectors of the same kind:
    forces with forces, displacements with displacements, accelerations (which are vectors) with accelerations, and so on. But even that is tricky since, for example, in dynamics we learn that force equals mass times acceleration.
So we would have to allow for the fact that though a force does not combine with an acceleration, it does combine with a vector of the type mass-times-acceleration in dynamics.

We shall return to this matter.
(See Section 8 of Chapter 2.)
But enough of such questions here.
If we continue to fuss with the definition we shall never get started.
Even if we succeeded in patching up the definition to meet this particular emegency, other emergencies would arise later.
The best thing to do is to keep an open mind and learn to live with a flexible situation, and even to relish it as something akin to the true habitat of the best research.


[^1]: Have you noticed that we have been careless in sometimes speaking of &ldquo;the vector represented by OP,&rdquo; at other times calling it simply &ldquo;the vector <math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$,&rdquo; and now calling it just &ldquo;<math displa="inline"><mover><mrow><mi>O</mi><mi>P</mi></mrow><mo>&rarr;</mo></mover></math>$&rdquo;? This is deliberate&mdash;and standard practice among mathematicians. Using meticulous wording is sometimes too much of an effort once the crucial point has been made.}

[^2]: We retain, too, the recollection that we are still linked, however tenuously, with journeying, for we want to retain the idea that a movement has occurred, even though we do not care at all how or under what circumstances it occurred.

[^3]: Actually, of course, lack of a name proves no more than that if the resultant exists, it has not hitherto been deemed important enough to warrant a name.

[^4]: Even with numbers there are complications. For example, 3 ft. and 3 inches can be said to yield 6 items; yet in another sense they yield 39 inches, 3&#188;<!--vulgar 1/4--> ft. and so on&mdash;and each of these can also be regarded as a number of items, though the 3&#188;<!--vulgar 1/4--> involves a further subtlety. Consider also 3 ft. and 3 lbs., and then 2.38477 ft. and 2.38477 lbs.


