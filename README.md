# Continuum-Removal-Hyperspectral-infrared-imagery
Author: Bardia Yousefi (bardia.yousefi.1@ulaval.ca)  Computer vision and systems laboratory,  Department of Electrical and Computer Engineering,  Laval University, Quebec city, Canada  Date: May 02, 2018   0.Copyright notice      code -- (c) 2018-2029 Bardia Yousefi      This code is provided as is, with no guarantees except that      bugs are almost surely present. Published documents of research      using this code (or a modified version) should cite the      article that describes the algorithm:       Yousefi, B., Sojasi, S., Castanedo, C.I., Beaudoin, G., Maldague, X.P. and Chamberland, M. (2018). Continuum removal for ground-based LWIR 2 hyperspectral infrared imagery applying non-negative matrix factorization. Applied Optics.           Comments and bug reports are welcome.  Email to bardia.yousefi.1@ulaval.ca.      I would also appreciate hearing about how you used this code,      improvements that you have made to it, or translations into other     languages.          You are free to modify, extend or distribute this code, as long      as this copyright notice is included whole and unchanged.     # MATLAB code for mineral identification using Hyperspectral clustering  This is MATLAB programming code for continuum removal in hyperspectral infrared imagery. This code is made free from other copy righted codes. This code just can received the preprocessed input hyperspectral image and performing the preprocess is not possible as this is under the copy right of TELOPS company.  It is possible to use the code directely for any other hyperspectral data. First read your own hyperspectral image cube and then replace the initial  predefined input data with your own data cube.   Instruction:  Please follow the instructions mentioned below:  1. visit: https://speclib.jpl.nasa.gov/search-1/mineral  for completing ASTER folder.  2. Please download the "sparse-nmfv1_4"           3. Change your directory at the first cell of CR_J0_noise.m, and change SNR parameter at your will.       Feel free to contact me whenever you have any problem running this code!

Instructions for provided code
------------------------------


Author: Bardia Yousefi (bardia.yousefi.1@ulaval.ca)


Computer vision and systems laboratory, 
Department of Electrical and Computer Engineering, 
Laval University, Quebec city, Canada


Date: May 02, 2018



0.Copyright notice


    code -- (c) 2018-2029 Bardia Yousefi

    This code is provided as is, with no guarantees except that 
    bugs are almost surely present. Published documents of research 
    using this code (or a modified version) should cite the 
    article that describes the algorithm: 


    Yousefi, B., Sojasi, S., Castanedo, C.I., Beaudoin, G., Maldague, X.P. and Chamberland, M. (2018). Continuum removal for ground-based LWIR hyperspectral infrared imagery applying non-negative matrix factorization. Applied Optics.
    


    Comments and bug reports are welcome.  Email to bardia.yousefi.1@ulaval.ca. 
    I would also appreciate hearing about how you used this code, 
    improvements that you have made to it, or translations into other
    languages.    

    You are free to modify, extend or distribute this code, as long 
    as this copyright notice is included whole and unchanged.  


# MATLAB code for mineral identification using Hyperspectral clustering

This is MATLAB programming code for continuum removal in hyperspectral infrared imagery. This code is made free from other copy righted codes.
This code just can received the preprocessed input hyperspectral image and performing the preprocess is not possible as this is under the copy right of TELOPS company.

It is possible to use the code directely for any other hyperspectral data. First read your own hyperspectral image cube and then replace the initial 
predefined input data with your own data cube.


Instruction:

Please follow the instructions mentioned below:

1. visit: https://speclib.jpl.nasa.gov/search-1/mineral  for completing ASTER folder.

2. Please download the "sparse-nmfv1_4"
    
    
3. Change your directory at the first cell of CR_J0_noise.m, and change SNR parameter at your will.     

Feel free to contact me whenever you have any problem running this code!
