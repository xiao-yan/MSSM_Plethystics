# MSSM_Plethystics
Collection of MMA codes and results for the Plethystic Programme of MSSM
The files are as follows:
1. Plethystic.nb: This is the MMA notebook file for the main calculation. The detailed steps are recorded and commented accordingly.
2. ExtSynDiv.nb: This is the MMA notebook for the unrefinment and simplification for obtaining the degree of the final Hilbert series.
3. xPoles.m: This file contains all of the poles in variable y for for the Plethystic exponent.
4. xRes.m: This file contains the residue from the contour integral in variable x within the contour prescribed in the article.
5. yPoles.m: This file contains all of the poles in variable y for for the Plethystic exponent.
6. yRes.m: This file contains the residue from the contour integral in variable y within the contour prescribed in the article.
7. z1Poles.m: This file contains all of the poles in variable z1 for for the Plethystic exponent.
8. z1Res.m: This file contains the residue from the contour integral in variable z1 within the contour prescribed in the article.
9. z2Poles.m: This file contains all of the poles in variable z2 for for the Plethystic exponent.
10. z2Res.m: This file contains the residue from the contour integral in variable z2 within the contour prescribed in the article.
11. finalnum-MMA.txt: This file contains the numerator of the final unrefined Hilbert series in MMA syntax. Due to size of this file (approx. 80MB), it is not uploaded here. Please contact the authors for further usage.
12. DenomFactors.txt: This file contains the denominator with each factor being an instance inside a list in Mathematica syntax.
13. DenomFactorListNew-MMA.txt: This file gives the denominator presented in the form of a MMA list object. Each instance is a factor in the form of (x,y) which translates to (x^y).
14. factorlist-MMA.txt: This list contains instance of the form (x,z) with x being the same object in "DenomFactorListNew-MMA.txt" and z being the number of times x divides the numerator.
15. SimpDenom.sage: This file gives the simplified denominator as explained in the file 'ExtSynDiv.nb'
