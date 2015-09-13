
# physicsReader

This is my repository for the Project Physics Reader.

My intentions are to convert them into an easily accessibile format.
I am using ebooks.adelaide.edu as inspiration.


## Useful links

http://www.yellowpipe.com/yis/tools/ASCII-HTML-Characters/

https://www.cs.tut.fi/~jkorpela/indexen.html
.math, {
    word-spacing:-0.07em;
}


https://ebooks.adelaide.edu.au/about/part2.9.html
.math, {
    display:inline-block;
    text-align:center;
    text-indent:0;
    vertical-align:middle;
}

## Style Guides


Use &gt;span class="math"&lt; for all math, &gt;i&lt; for variables in class="math".

Create SVG graphics using Inkscape.

All block element math should be mathml

Use &amp;nbsp; between value and unit, ex. 12&amp;nbsp;&amp;deg;C .

&#8451; for degree Celsius
&#8457; for degree Fahrenheit

For derivatives
&prime; or &#8242; for prime sysmbol in math
&Prime; or &#8243; for double prime symbol
&tprime; or &#8244; for triple prime symbol

&#34; Quotation Mark "
&#39; apostrophe '
&#35; number sign #

Use &thinsp; in long numbers instead of ,?

Replace &amp;InvisibleTimes; with &amp;#8290;

Place hairspace around &amp;mdash;?
NOTE: Chicago style allows hairspace around &amp;mdash;
&amp;hairsp; or &amp;#8202;
&amp;thinsp; or &amp;#8201;

The interpunct: &amp;middot; or &amp;#183;

&gt;wbr&lt; optional line break?

&gt;del&ltl; deleted text, usually rendered as struck out
&gt;ins&ltl; inserted text, usually rendered as underlined


b, i, u for boldface, italics, and underline

## Math

&amp;#8725; division slash
&amp;#47; forward slash
&amp;#92; reverse solidus

&#8800; and &#8804; and &#8805; are \neq, \leq, \geq (appearance on your browser: ≠ ≤ ≥)

&plusmn; is the plus minus symbol

Instead of &thinsp; in numbers,
<span class="number">123 456 789 000 000 000</span>
and the following style sheet:
.number { word-spacing: -0.07em; white-space: nowrap; }

Fraction slash for fractions &amp;frasl; or &amp;#8260;
<p>2<sup>1</sup>&frasl;<sub>2</sub> kilos<p>


&amp;#8730; square root

&#162; cent symbol



!! Ideas for unit representation

<em>    Renders as emphasized text
<strong>    Defines important text
<code>  Defines a piece of computer code
<samp>  Defines sample output from a computer program
<kbd>   Defines keyboard input
<var>   Defines a variable

