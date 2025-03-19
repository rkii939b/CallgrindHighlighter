Instruction:
1. Download QT Creator
2. Download all the files including doc and build folders
3. Open the QT Creator GUI
4. Place the callgrind files in any location of your hard drive to for testing. 
5. Find the "Build" button and Run from the QT. The simpleTextViewer will appear which has a unique feature to highlight callgrind files from your local disk. 
 It can also highlight the text based on the format of event types.

  For Example:
# callgrind format


events: Cycles Instructions Flops
fl=file.f
fn=main
15 90 14 2
16 20 12

Here,
To specify a file is callgrind profile, it should add #callgrind format as GREEN.
It will specify event title as BLUE.
All the numbers here are RED
1. 15 = 15th number line of "file.f"
2. 90 = 90 CPU cycles passed
3. 14 = The operations have 14 instructions to be executed.
4. 2 = 2 out of 14 instructions were floating point operations.
5. 16 = 16th number line of "file.f"
6. 20 = Taking 20 CPU cycles.
7. 12 = The operations have 12 instructions to be executed.

Thank you!
