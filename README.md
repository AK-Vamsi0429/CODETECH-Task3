Name: PARUSU KRISHNA VAMSI 
Company: CODETECH SOLUTIONS 
ID:CT06DG1294
Domain:VLSI
Duration:14June to 29July 2025
Mentor: Neela Santhosh Kumar 

🔍 Project Overview: 4-Stage Pipelined Processor
This project involves the design and simulation of a 4-stage pipelined processor using Verilog HDL. The processor is capable of executing basic instructions—namely ADD, SUB, and LOAD—and is designed to demonstrate instruction-level parallelism through pipelining.

The processor consists of the following 4 pipeline stages:

Fetch (IF) – Instruction retrieval from memory.

Decode (ID) – Instruction decoding and register fetch.

Execute (EX) – ALU operations for arithmetic/logical tasks.

Write Back (WB) – Writing results back to the register file or memory.

Each instruction progresses through these stages over multiple clock cycles, enabling the processor to handle one instruction per clock cycle after the pipeline is filled.

🔧 Key Deliverables
Functional Verilog Design

Modular design with separate units for ALU, Register File, Instruction Memory, and Control Unit.

Pipeline registers between stages to store intermediate values and control signals.

Simulation

A detailed Verilog testbench simulates instruction execution through all four stages.

Simulation includes clock and reset logic, initial memory loading, and instruction scheduling.

Stage-by-Stage Visibility

Internal signals for each stage are monitored using $display or waveform tools.

Enables step-by-step tracing of how each instruction moves through the pipeline.

✅ Results Summary
The simulation verifies that:

The processor correctly fetches, decodes, executes, and writes back basic instructions.

Pipelining is functioning properly, with overlapping execution stages.

Output results match expected values for ADD, SUB, and LOAD instructions.

