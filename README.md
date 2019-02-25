# TIBASIC-Formulas

A collection of math/physics formulas for the various classes I've taken over the years.  
All programs work on the TI-84+ v2.55, other versions probably work but are untested.

As of now, this is just an archive of my borderline-cheating shenanigans.
Everything in here is released under the ["Don't Be a Dick"](https://dbad-license.org) public license. Have fun.

## About all of the programs

- When you open the program, the menu options with formulas will be formatted like so: `[SOLVE FOR] (GIVEN [VARS])`. For example: `ΔT (V1 ΔT ΔD)`
- Note: The result of every calculation is put into `Ans`. If there's more than one answer, it'll be a list. Otherwise it'll be a number (Either real or complex depending on the inputs).
- There is a non-zero chance that some of these formulas are wrong. I take no responsibility for lost points caused by you using these programs on a test. Furthermore, I take no responsibility if your teacher catches you using these and counts it as cheating.

### Acknowledgements/thanks

Thank you to Spencer Putt, Chris Shappell, and James Montelongo for making [Wabbit EMU](http://wabbitemu.org/) which let me test the programs on my laptop instead of having to transfer it over to my calculator.  
A big thank you to Shaun McFall for creating [TokenIDE](https://www.ticalc.org/archives/files/fileinfo/433/43315.html), allowing me to create the programs on my laptop instead of using the TI-84 keypad.  
And finally, thank you to [James Taylor](https://github.com/jbt) for creating  [the only good markdown editor I know of](https://jbt.github.io/markdown-editor/).

This wouldn't be *nearly* as easy without any of you awesome people!

## PHYS.8xp

Calculator for velocities, acceleration, etc..

### Variables
- V1 (V)=Start velocity
- V2 (V[1])=End velocity
- &Delta;T (T)=Change in time
- &Delta;D (D)=Change in distance/height above ground
- A (A)=Acceleration

### Formulas

- Calculate &Delta;T, &Delta;T, A, and V1 given the others. (Ex: &Delta;T given V1, &Delta;D, and D)
- Calculate &Delta;T, &Delta;T, A, and V2 given the others. (Ex: &Delta;T given V2, &Delta;D, and D)
- Calculate V1 given V2, &Delta;T, and A
- Calculate V2 given V1, &Delta;T, and A
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
- Calculate A, D, N, and TN given the other three.
- Calculate A, D, N, and SN given the other three.

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

## LINEAR.8xp

Calculator for solving/converting standard, point-slope, and point-intersect form lines/linear systems

### Variables

- Since there's a lot of 'em and I'm lazy, just remember that the first var you input is set to A, the second to B, etc..

### Formulas

- Solve standard, point-slope, and point-intercept linear systems (find where two lines intersect)
- Convert standard, point-slope, and point-intercept line equations into either of the other two

## QUAD.8xp

Program for solving standard/vertex forms and converting one into the other

### Variables

- Same as above, the first number you input is A, then B, etc..

### Formulas

- Find the roots of a standard form parabola
- Convert a standard parabola into vertex form
- Find the roots of a vertex form parabola
- Convert a vertex parabola into standard form

***

**Footnotes**

[1]: When both V1 and V2 are used, V2 is set to W