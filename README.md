# oscillator
Feel free to use these mathematica files that solve non-linear oscillator differential equations.  I do not promise anything with these files and the onus is on you to check their correctness for your application.

***********************
Date format: dd/mm/yyy*
***********************
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

Note 06/08/2016:
dynamic_module_pitchfork_bif.nb explores the pitchfork bifurcation through the MATHEMATICA DynamicModule and Manipulate functionality.

Note 08/08/2016:
film_pitchfork.nb Has pitchfork bifurcation for all effects included.  Currently working on trying to set up a dynamic module that shows pitchfork bifurcation and growth rates as the value of either mu or lambda are changed.

Note 09/08/2016:
bif_examples.nb: Included solved examples from Strogatz.  Particularly useful are the examples that plot the potential well for different linear systems.  This may be used for film evolution growth rate equation as well.

Note 09/08/2016 (3.45pm ET)
film_bif_09082016.nb: shows bifurcation for growth rate equation for both with and without Porosity

Note 09/08/2016 (7.30pm ET)
film_pitchfork_v31.nb and film_pitchfork_v32.nb explore the pitchfork bifurcation f(x,mu,lambda) = mu x^2 - x^4 + lambda.  For lambda=0, we have Krishnamoorthy's case (may have Ga=0 or Ga>0).  With lambda=-0.1, we have a Porous substrate.
