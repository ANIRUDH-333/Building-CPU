# Building-CPU
We are building CPU in HDL and also implementing storage allocation strategies like heap, stack and static in Jack.

# How to run and check

### Executing in VM Emulator

1. Load the whole folder named MemoryTest in the VM Emulator and click Yes for the message popped up in the VM Emulator.
2. Load the script provided in the same folder MemoryTest namely MemoryTest.tst
3. Click the run button
4. Again click Yes for the pop up message.
5. Now, after the program is executed, it shows a pop up message telling the program is executed.
6. Then it will show "Comparison ended successfully".

### Checking the CPU

1. Load the CPU file in the Hardware Simulator from the folder CPU.
2. Load the script CPU.tst in the same folder named CPU.
3. Run it and see the message "Comparison ended successfully" to confirm the correctness of the CPU chip.

### Running ASM file on our CPU (Computer Chip)

1. Load the Computer.hdl file from the folder CPU.
2. Check if the view option is set to screen.
3. In the right bottom corner, you will find a icon of folder in the ROM section.
4. Click on that and add the asm file (either from built in projects, or memory.asm provided in the MemoryTest folder).
5. Now, run it and see the outcome on the screen.
