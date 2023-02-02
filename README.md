# OPAs
some of the sage files I used for computing two variable OPAs and OG polynomials. not efficient, but fine. Written in Sage 9.2 and 9.4, so there may be issues with updates. There are also known issues with trying to compute anything past about 40 OPAs or OG polys, but I never bothered fixing them because 40 terms is already too many to deal with for most things

the files with OPAs in the name use the grammian method to compute optimal polynomial approximants in 2 variables in both the bidisk and ball (Drury-Arveson) cases, as well as some preliminary work in computing them for Dirichlet polynomials

gram-schmidt multivar .... does gram schmidt. In the multivariable setting. Specifically in the Drury-Arveson space. I'll see if I have it in other spaces, but I think I skipped it? The only big change is that you have to change the monomial ordering and the norm (this is harder for some spaces than others)
