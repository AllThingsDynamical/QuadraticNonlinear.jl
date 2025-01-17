# QuadraticNonlinear.jl

This package is dedicated to the solution of quadratic problems with non-linear equality constraints of the form:
![image](https://github.com/user-attachments/assets/7e50a5ec-2786-444e-b6e5-a7aae1ac5597)

Unlike the traditional problem the quadratic form in our objective does not have a closed form and needs to be estimated implicitly using sparse factorizations. 
$\Theta$ is generally a dense kernel matrix; whose inverse is known to be sparse. Therefore, we make use of sparse Cholesky factorization algorithms to improve the efficiency of these methods.
