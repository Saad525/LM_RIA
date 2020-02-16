# LM_RIA
LM RISC-V Inverse Assembler (Version 1.1)

LM RISC-V Inverse Assembler (LM RIA) is an open source software which converts RISC-V machine instructions from hexadecimal format to assembly format. 
LM RIA (Version 1.1) supports all the instructions of RV32I (except Fence instruction) and RV32/RV64 Zicsr Standard Extension CSR Instructions based on the Latest Official RISC-V Specifications Document.

#########################################################################

Please follow the below steps to convert instructions in Hexadecimal format into RISC-V Assembly format:

1. Run 'LM_RIA_v1_1_win' for Windows and 'LM_RIA_v1_1_linux' for Linux OS.
2. Click 'Open .txt file'.
3. Select the file containing instructions in Hexadecimal format.
4. When 'File successfully generated!' message will appear, see the generated file in the same directory.

You can generate multiple files one after the other, each generated file will be named according to time and date of its generation. 

In case of any error, check the format of instructions in the input .txt file. It must be the same as mentioned below in 'Format' section. 

Please note that the message 'File successfully generated!' will appear the first time only when the output file is generated, after that it remains there (will not indicate the status of second generated file). If there is any confusion about the status of next generated file, please close the application and re-run it. 

#########################################################################

Format:

Input File  - A text file with one instruction per new line in hexadecimal format with no special characters/spaces in between or at start/end.

Output File - A text file with one instruction per new line in three formats (Hexadecimal, Binary, Assembly).

#########################################################################

Note:

Please see the license file also.
