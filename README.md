MTS-LaTeX-Arcs
==============
This is a set of LaTeX math symbols, for writing transition arcs in modal transition systems.

Requirements
============
The arrows are drawn in TikZ, and the arrow tip is a \guilsinglright which is not in the OT1 encoding.
  * \RequirePackage{tikz} 
  * \RequirePackage[T1]{fontenc}


Usage:
======
  * May arc: $q \may{a} q'$
  * Must arc: $q \must{a} q'$
  * Weak may arc: $q \mayw{a} q'$
  * Weak must arc: $q \mustw{a} q'$
