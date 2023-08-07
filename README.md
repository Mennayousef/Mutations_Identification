# Mutations Identification
## A-Pipeline-for-the-Analysis-of-Gene-Expression-RNA-seq-Data
1- The function dna_comparison that takes two string (not filename) arguments, the wild type sequence and a single mutated sequence, compares them and returns the number of transitions and transversions (in that order) between the two.
2- The function checks for the following issues and if found, return zero transitions and transversions as well as printing an error message:
> The two DNA sequences being different lengths
> Characters not representing a DNA base
3- The function is used to investigate the population of mutations and give the total number of transitions and transversions across all the 200 files
4- The function protein_comparison takes two string arguments, the protein string of the wild type and the protein string of a single mutated sequence, compares them and returns the number of silent, missense and nonsense mutations (in that order) between the two.
5- It checks for unknown characters in the protein string and if found, returns zero mutations and prints an error.
6- The function is used to investigate the population of mutations and return the total number of silent, missense and nonsense mutations across all the 200 files
