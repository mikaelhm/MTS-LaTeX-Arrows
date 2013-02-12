MTS-LaTeX-Arcs
==============
A set of LaTeX math symbols, for writing transition arcs in modal transition systems.

Requirements
============
The arrows are drawn in TikZ, and the arrow tip is a \guilsinglright which is not in the OT1 encoding.
\RequirePackage{tikz} 
\RequirePackage[T1]{fontenc}


Usage:
======
$q \may{a} q'$\\
$q \must{a} q'$\\
$q \mayw{a} q'$\\
$q \mustw{a} q'$
