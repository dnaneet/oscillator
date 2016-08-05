# oscillator
Feel free to use these mathematica files that solve non-linear oscillator differential equations.  I do not promise anything with these files and the onus is on you to check their correctness for your application.

Note 29/07/2016:

duffing_rp_v5.nb is a much more refined duffing oscillator simulation. It allows for clarity in multimode forcing, and the use of recurrence plots in quantifying the multimode forcing and their dissipation for a non zero damping term (when introduced into duffing osci equation).

Note 30/07/2016:

film.nb and film_v2.nb are *incomplete* versions of mathematica code that try to compare recurrence plots for cases with and w/out porosity to determine when they start differing from each other.  As of 30/07/2016, the plot command within the Module is failing.

Note 04/08/2016:
multimode-osci_v2.nb compares the use of DFT with RP.  It also includes film dynamics equation and film stability.  Initial work on film stability bifurcation/response diagram has also been included.

Note 04/08/2016:
bif_examples.nb: Mathematica file that can accompany: http://www.math.colostate.edu/~shipman/47/volume3b2011/M640_MunozAlicea.pdf

Note 05/08/2016:
With multimode-osci_v3.nb, the hope is to start probing the bifurcation and response diagrams for the "growth rate of instabilities" equation and the corresponding "maximizing wavelength" (i.e. roots of dw/dq=0).

Note 05/08/2016:
film_saddlenode.nb depicts saddlenode bifurcation of the derivative of the "growth rate of long wave instabilities" equation.  
