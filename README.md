# Feature-Selection
Using Feature selection on simulated dataset of single nucleotide polymorphism (SNP) genotype data containing 29623 SNPs (total features) to improve the accuracy and predict the labels for the test data.
Amongst all SNPs are 15 causal ones which means they and neighboring ones discriminate between case and controls while remainder are noise.
In the training are 4000 cases and 4000 controls. Task is to predict the labels of 2000 test individuals.

Training dataset - https://web.njit.edu/~usman/courses/cs675_summer18/traindata.gz
Training labels - https://web.njit.edu/~usman/courses/cs675_summer18/trueclass
Test dataset - https://web.njit.edu/~usman/courses/cs675_summer18/testdata.gz

## Python Libraries
### Pandas, Scikit-learn
