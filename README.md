# systolic_array_matrix_multiplier
This is a verilog implementation of 4x4 systolic array multiplier

# files
This has a file called block.v which has all the individual blocks of the systolic array
The file systolic_array.v is the main module
The file sys_array_tb.v is the testbench

# Output
Output can be seen by checking the Result0 to Result15 vectors in the systolic_array uut using gtkwave

# steps to execute
iverilog block.v
iverilog systolic_array.v
iverilog sys_array_tb.v
vvp a.out
gtkwave wave.vcd
