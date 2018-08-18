Sample: binomialOptions
Minimum spec: SM 3.0

This sample evaluates fair call price for a given set of European options under binomial model.

binomialOptions.exe
Starting...
GPU Device 0: "GeForce GTX 1050 Ti with Max-Q Design" with compute capability 6.1

Generating input data...
Running GPU binomial tree...
Options count            : 1024
Time steps               : 2048
binomialOptionsGPU() time: 11.165222 msec
Options per second       : 91713.356402
Running CPU binomial tree...
Comparing the results...
GPU binomial vs. Black-Scholes
binomialOptionsCPU() time: 4847.532715 msec
L1 norm: 2.161186E-04
CPU binomial vs. Black-Scholes
L1 norm: 2.160735E-04
CPU binomial vs. GPU binomial
L1 norm: 6.658159E-07
Shutting down...
