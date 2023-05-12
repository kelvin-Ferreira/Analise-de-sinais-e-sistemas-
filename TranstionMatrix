import numpy as np
from sympy import symbols

A = np.array([[-3.0,1.0,0.0],[1.0,-3.0,0.0],[0.0,0.0,-3.0]])
I= np.identity(3)
A2 = np.matmul(A,A)
A4 = np.matmul(A2,A2)
t = symbols('t')

Tmat = I+A*t+(A2*((t**2)/np.math.factorial(2)))+(np.matmul(A,A2)*((t**3)/np.math.factorial(3)))+(A4*((t**4)/np.math.factorial(4)))+(np.matmul(A,A4)*((t**5)/np.math.factorial(5)))
print(Tmat)
