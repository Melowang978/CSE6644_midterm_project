In computational mathematics, people define iterative method as a mathematical procedure that uses an initial value to generate a sequence of improving approximate solutions for a class of problems, in which the n-th approximation is derived from the previous ones. Iterative method also contains terminating criteria, which is designed by different purposes.  10^−6
  is usually a reasonal terminating critrion. Iterative method used for getting convergency in order to abate the direct method's computational complexity. In terms of applying iterative method into numerical linear algebra, we can implement matrix vector multiplications way faster than directly solve them.  𝐶𝐺
  algorithm a one of classic iteration methods. The main idea of  𝐶𝐺
  is to reduce the residual by iterations and get a convergence.

Preconditioners are used to decrease the condition number in order to make the iteration number independant of matrix size. There are different ways to deisng preconditioners. In this project, we area dealing with a special case. We would have toeplitz matrix as the multiplier, a toeplitz matrix contains constant on the diagonal. In addition, we will design circulant matrix as our preconditioner. In the end, according to the property of circulant matrix, it is able to design a fast fourier transform of the first column to improve our  𝐶𝐺
  algorithm in another level.
  
  The theoratical and coding details are illustrated in the Jupyter notebook file.
