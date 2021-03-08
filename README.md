This code is the Fortran 77 version of the UMAT, FLOW, and SDVINI subroutines of the cartilage model, I firstly proposed in my Master's thesis. The model with some minor modifications was used in several publications.

If you use part of this code in your work, please cite its corresponding article:

Sajjadinia, Seyed Shayan, Mohammad Haghpanahi, and Mohammad Razi. "Computational simulation of the multiphasic degeneration of the bone-cartilage unit during osteoarthritis via indentation and unconfined compression tests." Proceedings of the Institution of Mechanical Engineers, Part H: Journal of Engineering in Medicine 233.9 (2019): 871-882. https://doi.org/10.1177/0954411919854011

Please note that for the DDSDDE array, I used two different equations, one for debugging of the code and the other is based on equations in the appendix of the above paper. The latter should work better if it is used together with the right linearization method, otherwise use the former.
