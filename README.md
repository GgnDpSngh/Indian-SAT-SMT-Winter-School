# Indian SAT+SMT Winter School

We provide a virtual machine with ERAN installed running Ubuntu which can be downloaded [here](https://uofi.box.com/s/s4mbdh49k608i7m8co9apkyi39dpae7d). 

# System Requirements
1. Make sure you have 64-bit VirtualBox from Oracle.
2. The virtual machine requires at least 20 GB of disk space.
3. We recommend allocating at least 8 GB RAM to the virtual machine and 4 threads.

# Instructions
1. Import the virtual machine in VirtualBox. More information on importing virtual machine in VirtualBox can be found [here](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-import-vm.html).
2. The login credentials for the Virtual Machine are:
```
   username: eran
   password: eran2021
   ```
# Using code from this repository
1. Please copy the files "run_eran.py" and "mnist_0.1.onnx" to "/ERAN/tf_verify" directory.
2. Run "python3 run_eran.py", this will verify the mnist network with the deeppoly domain on L_oo-norm based perturbations with $\epsilon=0.1$. 
