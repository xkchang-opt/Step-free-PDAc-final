# Step-free-PDAc-final

This code was written for testing numerical performance of splitting preconditioned PDA, proposed by Xiaokai Chang, Long Xu and Jianxiong Cao.

Xiaokai Chang 
xkchang@lut.edu.cn
School of Science, Lanzhou University of Technology, Lanzhou, Gansu, P. R. China 


The paper has been accepted by Numerical Algorithms.

Abstract: Both the popular primal-dual algorithms of Chambolle-Pock and Chang-Yang are full-splitting and efficient for solving bilinear saddle point problem. However, their step sizes depend on the spectral norm of the linear transform or are estimated by using linesearch, which are usually overconservative from the spectral norm or require extra computing from linesearch. By using sequence interpolation and extrapolation, a novel primal-dual algorithm with larger stepsizes is proposed. Moreover for this scheme, we introduce a splitting preconditioned strategy by solving matrix inversion problem for the dual variable, where the preconditioning is separable from the evaluations of proximal operators and then avoids the difficulty of computing complicated preconditioned proximal operator in the existing methods. The preconditioned primal-dual algorithm not only does not require the spectral norm of the linear transform or linesearch to estimate stepsizes, but also holds cheap computation on the matrix inversion problem for the cases with primal or dual variable being modest, as the matrix decomposition is involved only once. Global iterative convergence and O(1/N) ergodic convergence rate results measured by the function value residual and constraint violation are established, where N denotes the iteration counter. Finally, we demonstrate the performance of the proposed primal-dual algorithm and preconditioning strategy via preliminary numerical experiments.
