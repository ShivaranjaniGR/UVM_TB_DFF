# Introductory UVM Testbench for D Flip-Flop

This is a beginner-level verification project where I built a basic UVM testbench for a Verilog D Flip-Flop.  
The main goal of this project was to get introductory exposure to SystemVerilog and understand the structure of a UVM verification environment.

## Project Overview

The design under test is a simple D Flip-Flop written in Verilog.  
A UVM-based testbench was created to verify the clocked behavior of the D Flip-Flop by comparing the expected output with the actual output.

## Tools and Technologies Used

- Verilog
- SystemVerilog
- UVM
- Simulation tool: Add your simulator name here

## Design Under Test

The D Flip-Flop captures the input `d` on the active clock edge and updates the output `q`.

Basic behavior:

```verilog
always @(posedge clk) begin
  q <= d;
end
