# Grid-Search-to-tune-Hyperparameters-for-SVM
Tuning Hyper-parameters for SVM 

We know that Linear SVM is a pretty good classifier but in some cases it can result in pretty bad result.

One of the reason can be bad choice of Hyperparameters.

To avoid it, there is a need to tune the hyperparameters C(Penalty Value) and Kernel to be used.

Here, we can see in above implemented code that when untuned, SVM gives an accuracy score of 44.87%, that's actually pretty bad.

So, we have tuned C and Kernels so as to get a decent score.

After tuning, we can see that accuracy score has drastically changed and best score reached to 96.99%.

This can easily Justify the need for tuning.

Here we have used 6 different values of Penalty and 4 Kernels namely, Linear, Polynomial, RBF, Sigmoid Kernel.

And, the best score was achieved for c=0.1 and Kernel as Polynomial.

Note: This might not be the case for you, these parameters depend largely on dataset used.

# Happy Coding!
