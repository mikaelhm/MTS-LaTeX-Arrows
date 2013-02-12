MTS-LaTeX-Arcs
==============
This is a set of LaTeX math symbols, for writing transition arrows of modal transition systems in a LaTex document.

Requirements
------------
The arrows are drawn in TikZ, and the arrow tip is a \guilsinglright which is not in the OT1 encoding.
  * <pre>\RequirePackage{tikz}</pre>
  * <pre>\RequirePackage[T1]{fontenc}</pre>

Usage and Example:
--------
After loading the mts-arrows.tec in your preable, writing:

 <pre>$q_0 \may{a} q_1 \must{a} q_2 \mayw{a} q_3 \mustw{a} q_4$</pre>
 <pre>$q_0 \lmay{abcd} q_1 \lmust{abcd} q_2 \lmayw{abcd} q_3 \lmustw{abcd} q_4$</pre>

in your document will result in:

![Example](https://raw.github.com/mikaelhm/MTS-LaTeX-Arrows/master/example.png)

*Note: long arrows should only be used with long action names on top*
