# 4-bit ALU in Verilog Using Xlink Vivado (Adder, Subtractor, NAND, NOR)

## What this does
- 4-bit **adder**, **subtractor**, **NAND**, **NOR**
- Structural top: `alu_struct` (or your module name)
- Testbench: `alu_struct_tb`

## How to simulate (ModelSim)
1. `vlog src/vlsiintern.v src/alu_struct_tb.v`
2. `vsim alu_struct_tb`
3. `add wave -r *`
4. `run -all`

## Files
- `src/vlsiintern.v` – DUT + submodules  
- `src/alu_struct_tb.v` – testbench  
- `screenshots/` – waveforms & console outputs

## waveforms
![Waveform](waveforms/Screenshot_2025-08-17_105829.png)
![Console](waveforms/Screenshot_2025-08-17_105844.png)

