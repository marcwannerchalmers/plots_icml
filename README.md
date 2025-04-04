# Preliminary noisy plots

![image](./results.png?raw=true)

Experimental setup with additional baselines and noise 
## Noise model 
With probability $1-p=0.9$ leave the output unchanged and with probability $p=0.1$ return bernoulli ($p=0.5$)-random bitstring as output state (in computational basis).

Note that we chose the threshold to be $0.45$ for the PQC here to account for the change in expected value. QAOA showed good convergence, even without adapting the adapted threshold. Lastly, note that the drop in sample complexity of RR Powell is because many of the respective experiments for 15 qubits were not completed and are missing.
