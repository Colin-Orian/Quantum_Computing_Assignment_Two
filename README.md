# Quantum_Computing_Assignment_Two

This is my impelmentation of a Variational Quantum Linear Solver from the qiskit tutorial here: https://qiskit.org/textbook/ch-paper-implementations/vqls.html

The author suggested that SPSA would be better to sample a noisy circuit. I compared SPSA to SciPy.minimize() and found that SPSA lags slighly behind SciPy.minimize(). I believe this is a statistical outlier as previous tests of SPSA yeiled better results. 


![SPSA_Table](https://github.com/Colin-Orian/Quantum_Computing_Assignment_Two/blob/main/SPSA.PNG "SPSA and minimize Results")
