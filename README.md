# Simulation of CMOS Circuits Using TSMC Model Files(350nm/250nm180nm/any technology model file) using LTspice

1. Download cmosn.asy and cmosp.asy from https://sanjayvidhyadharan.in/Downloads/tsmc_180_nm/ and save in the location C://Program Files (x86)/LTC/LTspiceIV/lib/sym (This locatio may change depending on the location inwhich LTspice is saved.)
2. Download tsmc018.lib model filw from  https://sanjayvidhyadharan.in/Downloads/tsmc_180_nm/ or other model files like TSMC250nm/350nm/or any other technology model files from http://ptm.asu.edu/ and save in the location C://Program Files (x86)/LTC/LTspiceIV/lib/sub
3. Open LTspice. Access cmosn and cmosp transistors for making the circuit.
4. In the .op Spice directive, add the following - .include tsmc025.lib (I hve used 250 nm technology model file.
