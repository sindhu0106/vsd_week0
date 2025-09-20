
The Idea (C-Model)/Specifications
o	We start with a simple description of what the chip should do, written like a regular computer program in a language like C.
o	We then use another C program to test this idea, making sure the logic is correct before we move on to building any hardware.
Building Blocks (RTL & Synthesis)
o	The C-program is translated into a hardware blueprint using HDL like  Verilog. This blueprint describes the chip's core parts, like the main processor and other functions.
o	This blueprint is then turned into a list of millions of basic building blocks called "logic gates." This is like turning a house plan into a list of every brick and board needed.
The Final Product (Physical Layout)
o	All the building blocks are physically arranged and connected on a virtual chip. This step involves carefully placing each gate and drawing the wires to connect everything.
o	The final layout is saved as a GDSII file. This file is the finished product that gets sent to the factory. But first, it's double-checked to make sure everything is perfect and ready for manufacturing.

