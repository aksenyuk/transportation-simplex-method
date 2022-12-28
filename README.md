# The Transportation Simplex Method solver

Co-authored-by: [@giminosk](https://github.com/Giminosk)

## Implementation Details

- The problem is represented using matrix form of different problem sizes;

- Tested on one concrete example as well as using random data generator funciton; 

- The effectiveness/quickness is checked by tracking amount of iterations (the info is provided in the output);

- Concrete sample contains so-called "M" cost values (infinitely large numbers) as well as zero ones;

- The correctness of obtained Z-score (total score) is verified by applying PuLP library to th same input;

- However, for solution feasibility total supply and demand are considered to be equal.
