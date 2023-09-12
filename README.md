# OPAs
some of the sage files I used for computing two variable OPAs and OG polynomials. Written in Sage 9.2 and 9.4, so there may be issues with updates. There are also known issues with trying to compute anything past about 40 OPAs or OG polys, but I never bothered fixing them because 40 terms is already too many to deal with for most things

the files that have OPAs and optimal norms were used in undergraduate research projects to look at rates of decay of optimal norms in the Hardy space of the bidisk.
Somewhere I have files that work for other spaces on the bidisk (eg bergman) and I have something somewhere that plots the facial zeros of optimal approximants; I'll try to find those at some point.

gram-schmidt multivar .... does gram schmidt. In the multivariable setting. Specifically in the Drury-Arveson space on the 2-ball. 
I'll see if I have it in other spaces, but I think I skipped it? The only big change is that you have to change the monomial ordering and the norm (this is harder for some spaces than others)

For the dirichlet series versions of these (they have DS in the name) I'm using the bohr lift to express the dirichlet polynomials as polynomials on the infinite polydisk so they're represented with z_j instead of n^{-s}. (Since they're only polynomials, it's only finitely many dimenions of the infinite dimension, but it's there in spirit.)
