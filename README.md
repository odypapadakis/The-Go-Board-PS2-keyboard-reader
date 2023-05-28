# The-Go-Board-PS2-keyboard-reader
 This is a project that connects a ps/2 keyboard to a " Go Board ".

 The "Go board" from nandland.com, is a small system that includes an FPGA, some peripherals and connectors on a circuit board,  allowing for easy creation of projects using an HDL such as Verilog or VHDL.

 This project will be initially created in Verilog. 
 
 
 The FPGA ( Lattice ice40HX1k ) on the go board operates at 3.3V Logic.
 The PS/s keyboard operates at 5.0 V .
  therefore a logic level converter circuit is included in the design.

### A photo of the implementation
![Photo of the Deisgn ](Photo1.jpg)


The Design Flow will be as folows : 

 #### 1. Keyboard and logic level converter Verification.    
    This will be accomplished by connecting the keyboard to the logic level converter   
    and probing  the outputs of the converted signals with a Logic Analyzer.    

#### 2. HDL and Simulation.    
    Before attemptin to run the project on the FPGA, a the design will be simulated using modelsim,
    in order to perform the first round of debugging 

#### 3. 



