# FULL_ADDER
# AIM:
To simulate and synthesis full adder using vivado.

# APPARATUS REQUIRED:
vivado 2023.2 software.

# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)
# Program
```
module full_adder(
    input a,
    input b,
    input cin,
    output sum,
    output cout
);
assign {cout, sum} = a + b + cin;
endmodule
```
# output
![fulladder](https://github.com/THARUN729/FULL_ADDER/assets/161407766/84eb5625-241c-4249-8c11-b44b68106447)

# RESULT:
Thus the verilog program for full adder has been simulated and verified successfully.

