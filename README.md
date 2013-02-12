MTS-LaTeX-Arcs
==============
This is a set of LaTeX math symbols, for writing transition arrows of modal transition systems in a LaTex document.

Requirements
------------
The arrows are drawn in TikZ, and the arrow tip is a \guilsinglright which is not in the OT1 encoding.
  * <pre>\RequirePackage{tikz}</pre>
  * <pre>\RequirePackage[T1]{fontenc}</pre>


Usage:
------

  * May arrow: <pre>$q \may{a} q'$v
  * Must arrow: <pre>$q \must{a} q'$</pre>
  * Weak may arrow: <pre>$q \mayw{a} q'$</pre>
  * Weak must arrow: <pre>$q \mustw{a} q'$</pre>

  * Long may arrow: <pre>$q \lmay{abcd} q'$v
  * Long must arrow: <pre>$q \lmust{abcd} q'$</pre>
  * Long weak may arrow: <pre>$q \lmayw{abcd} q'$</pre>
  * Long weak must arrow: <pre>$q \lmustw{abcd} q'$</pre>

*Note: long arrows should only be used with long action names on top*

Example:
--------
After loading the mts-arcs.tec in your preable, writing:

 <pre>$q_0 \may{a} q_1 \must{a} q_2 \mayw{a} q_3 \mustw{a} q_4$</pre>
 <pre>$q_0 \lmay{abcd} q_1 \lmust{abcd} q_2 \lmayw{abcd} q_3 \lmustw{abcd} q_4$</pre>

in your document will result in:

![Example](https://raw.github.com/mikaelhm/MTS-LaTeX-Arrows/master/example.png)

