# TIBASIC-Formulas

A collection of math/physics formulas for the various classes I've taken over the years.  
All programs work on the TI-84+ v2.55, other versions probably work but are untested.

As of now, this is just an archive of my borderline-cheating shenanigans.
Everything in here is released under the ["Don't Be a Dick"](https://dbad-license.org) public license. Have fun.

***

Note: Every program, when done calculating, will have the result put into the `Ans` variable. This is to avoid overwriting anything.  
***However***, inputted variables *are* overwritten. So if you input 5 for ΔT, then T will be set to 5.  
Sub-note: 

***

## PHYS.8xp

Calculator for velocities, acceleration, etc..

### Variables
- &Delta;D=Change in distance/height above ground
- &Delta;T=Change in time
- V1=Start velocity
- V2=End velocity
- A=Acceleration

### Formulas

- Calculate &Delta;T, &Delta;T, A, V1, and V2 given the others. (Ex: &Delta;T given V1, &Delta;D, and D)
- Calculate the maximum height of an object given V1, &Delta;d, and A

## SEQ.8xp

Calculator for arithmetic and geometric sequences

### Variables
- A=Initial value (T1)
- D=Difference between terms (Arithmetic)/Ratio between terms (Geometric)
- N=Index of term (Starts at 1)
- TN (T)=Value of the Nth term
- SN (S)=Sum of the first N terms

### Formulas
- Calculate A, D, N, TN, and SN given the others. (Ex: TN given A, D, and N & SN given A, D, and N)


## LENS

Calculator for lenses. (Focus, magnification, image/object distance, etc.)

### Variables
- F=Focus length
- M=Magnification
- DI (I)=Distance from lens to image
- DO (O)=Distance from lens to object
- HI (I)=Height of image
- HO (O)=Height of object

### Formulas

- Calculate F, DI, and DO given the other two
- Calculate M, HI, and HO given the other two
- Calculate M, DI, and DO given the other two
