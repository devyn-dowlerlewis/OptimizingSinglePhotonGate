# OptimizingSinglePhotonGate
Transfer-Level simulations of optical ring-resonator based single-qubit gate optimization to account for simulated manufacturing defects.

Script begins with the optimal all-pass detuning values to implement a Hadamard gate (eg. to transfrom the |0> state vector (0,0,1) to (1,0,0))

Introducing error into the variables that define the stacked ring transformations means that those previous optimal all-pass values no longer apply the transformation correctly.

By defining a loss function that represents the seperation between the applied and intended transforms, this script finds new all-pass detuning values to restore the intended transformation.

Some additional information as well as figures and schematics of the gate can be found in RISQPoster.png 
