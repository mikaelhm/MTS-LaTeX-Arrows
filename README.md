MTS-LaTeX-Arrows
==============
This is a set of LaTeX math symbols, for writing transition arrows of modal transition systems in a LaTex document.

Requirements
============
The arrows are drawn in TikZ, and the arrow tip is a \guilsinglright which is not in the OT1 encoding.
  * <pre>\RequirePackage{tikz}</pre>
  * <pre>\RequirePackage[T1]{fontenc}</pre>


Usage:
======
  * May arc: <pre>$q \may{a} q'$v
  * Must arc: <pre>$q \must{a} q'$</pre>
  * Weak may arc: <pre>$q \mayw{a} q'$</pre>
  * Weak must arc: <pre>$q \mustw{a} q'$</pre>

Example:
========
After loading the mts-arrows.tex in your preable, writing:

 <pre>$q_0 \may{a} q_1 \must{a} q_2 \mayw{a} q_3 \mustw{a} q_4$</pre>

in your document will result in:

![Example](https://raw.github.com/mikaelhm/MTS-LaTeX-Arrows/master/example.png)

