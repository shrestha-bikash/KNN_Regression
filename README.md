Consider a single dimension. Obtain N = 100 iid samples of x uniformly randomly between
1 and 10. The corresponding y values are obtained as the logarithm of x plus a Gaussian
noise (mean 0, standard deviation 0.1). Now use K-NN regression (for each of the following
three schemes, and with K = 1, 3, 50 for each scheme) to obtain estimates of y at x-values of
1, 3, 5, 7 and 9:
• the K neighbors contribute equally
• each of the K neighbors has an influence that is inversely proportional to the distance
from the point
1 2
• all the N points contribute, with each contribution proportional to e − 2 d , where d
represents distance.
Use Python/Java/C/C++ as the implementation language. (If you do not know any
of these languages, please contact me immediately. I teach Python CS 4200 every Fall.)
Please do not use an off-the-shelf implementation of K-NN regression from any package or
library. Use of packages/libraries for standard, simple tasks such as sorting or sampling from
a distribution is fine. Set the seed at the beginning of your program so that your results are
reproducible.
This is a group project, with three students per group. There will be only one submission
from a group (it doesn’t matter which member submits it; the submissions of the other
members will remain blank on Canvas.) Please write the names of the group members at the
top of the very first page (or cell) of the submission. Form your own groups by interacting
amongst yourselves but please do NOT use Canvas’s features to store group compositions.
A student may choose to be in different groups for different projects. Working in groups is
highly recommended but not mandatory; a student may choose to work independently.
Please submit on Canvas a single doc/docx/pdf/ipynb file (no other file type, please,
with the following exception: if you are submitting an ipynb file, please ALSO submit the
corresponding html) containing the source code and all output. Submission of multiple files
is discouraged but may be resorted to only if you absolutely cannot manage to produce a
single file.
