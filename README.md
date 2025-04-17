# Git-Rebasin-Weight-Matching-Demo
A demonstration of weight matching permutation coordinate descent from Git Rebasin [Samuel K. Ainsworth, Jonathan Hayase, Siddhartha Srinivasa - ICLR 2023] on simple MLP objects (3 layer MNIST image classifiers).

An implementation of algorithm 2 from their paper on small neural networks with tSNE plots to visualize the rebasin process and qualatatively compare the weight-space locales of model weights before and after applying weight-matching. 

There is also a demo of Git Rebasin (permutation canonicalization) followed by a rescaling such that the greatest valued parameter in the MLPs weight space is 1.0 (scale canonicalization). Since dividing by a constant is a linear transformation, the performance of the MLP on test data remains unaffected. 


Git Rebasin - Arxiv: https://arxiv.org/abs/2209.04836, 
Git Rebasin - GitHub: https://github.com/samuela/git-re-basin

Special thanks to Saumya Gupta (https://www.linkedin.com/in/saumya-gupta-53858915b/) for her critical contributions, and Drs. Ayan Paul and Robin Winters for their mentorship. 
