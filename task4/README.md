# Functional Simulation of the RISC-V Core  

To ensure the functional correctness of a **RISC-V Core**, a **functional simulation** must be performed. This involves setting up a simulation environment, running the **Verilog netlist and testbench files**, and analyzing the output signals to verify the core’s behavior.  

## Steps Involved  

### 1. Download the Required Files  
- Obtain the **Verilog netlist** of the RISC-V Core.  
- Download the **testbench files**, which provide the necessary stimulus for testing the core's functionality.  

### 2. Set Up the Simulation Environment  
- Use simulation tools like **Icarus Verilog (iverilog)** for compiling and executing the Verilog code.  
- Utilize **GTKWave** for waveform analysis, allowing visualization of signal transitions and verifying correctness.  

### 3. Run the Functional Simulation  
- Compile the **Verilog netlist and testbench** using `iverilog`.  
- Execute the compiled simulation to generate the **output waveform**.  
- Load the resulting `.vcd` (Value Change Dump) file into **GTKWave** for further inspection.  

### 4. Analyze the Output Signals  
- Check the **waveform signals** to confirm expected behavior.  
- Verify that the **register values, memory interactions, and control signals** align with the intended execution flow.  
- Identify and debug any discrepancies to ensure correctness.  

## Outcome  
Successfully performing this **functional simulation** provides a clear validation of the **RISC-V Core’s behavior**, ensuring that it executes instructions as expected before moving to hardware implementation.
