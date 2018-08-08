# Masiello_group
This repository contains program packages that are often used by the Masiello group members. 

All "src*" program packages are written in Fortran, "tDDA*" are in-house program packages written in C, and "MNPBEM17" is a toolbox 
written in MATLAB.

Toolbox "MNPBEM", http://physik.uni-graz.at/mnpbem/#2, is developed by Ulrich Hohenester (http://physik.uni-graz.at/~uxh/) and Andreas Trügler (http://physik.uni-graz.at/~atr/), which is used for the simulation of metallic nanoparticles (MNP) with a boundary element method (BEM) approach developed by F. J. Garcia de Abajo and A. Howie (Phys. Rev. B 65, 115418 (2002)). The 2017 version of "MNPBEM" can be downloaded at http://physik.uni-graz.at/mnpbem/download.php. To respect the authors, we only put a "GetBEM.sh" script in the "MNPBEM17" folder to let users download "MNPBEM17" from the developer's website directly.

Program packages "srcEELS", "srcPW_background", "srcPW_background_psf", and "srcPW_tDDAb" are the modified versions of the DDSCAT 7.1 from https://www.astro.princeton.edu/~draine/DDSCAT.7.1.html. Note that the 7.1 version is no longer supported by the DDSCAT team, however, details about it can be found at  https://arxiv.org/pdf/1002.1505.pdf and the following reference:
  Draine, B.T., & Flatau, P.J., "Discrete dipole approximation for scattering calculations", J. Opt. Soc. Am. A, 11, 1491-1499 (1994). 
