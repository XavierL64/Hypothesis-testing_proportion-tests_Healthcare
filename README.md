# Hypothesis-testing_proportion-tests_Healthcare

**Description **

This project leverages the statsmodel and pingouin packages to determine if the adverse effects of a drug are significant using proportion tests. We seek to determine if the proportion of adverse effects differs significantly between the treatment (Drug) and control (Placebo) groups. The null hypothesis is that adverse effects do not differ between the two groups. We set the signigicance level at 0.5 to test this hypothesis.  

After running a ztest and compare the resulting p value to the significance level, we perform a Chi-square test of independence to determine if the number of adverse effects is independent of the Drug and Placebo groups. Finally, we examine if there is the age of individuals differs significantly between the Drug and Placebo groups. We use a non-parametric test as the age of the sample doesn't appear to be normally distributed.

