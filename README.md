# soft-margin-SVM-to-handwritten-digits-from-the-processed-US-Postal-Service-Zip-Code-data-set



We will train a one-versus-one (one digit is class +1 and another digit is class -1) classifier
for the digits ‘1’ (+1) and ‘5’ (-1).
(a) Consider the linear kernel  Train using the provided training data
and test using the provided test data, and report your accuracy over the entire test set,
and the number of support vectors.

(b) In continuation, train only using the first {50, 100, 200, 800} points with the linear
kernel. Report the accuracy over the entire test set, and the number of support vectors
in each of these cases.

(c) Consider the polynomial kernel Comparing Q = 2 with Q = 5, comment whether each of the following
statements is TRUE or FALSE.
i. When C = 0.0001, training error is higher at Q = 5.
ii. When C = 0.001, the number of support vectors is lower at Q = 5.
iii. When C = 0.01, training error is higher at Q = 5.
iv. When C = 1, test error is lower at Q = 5.

(d) Consider the radial basis function (RBF) kernel withsoft-margin SVM approach. 
Which value of C ∈ {0.01, 1, 100, 104, 106} results in the
lowest training error? The lowest test error? Show the error values for all the C values
