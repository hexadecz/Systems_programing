# Systems_programing
Extended Architecture:

Retains the SIC/XE instruction set and data management techniques.
Introduces a new Format 4F for conditional execution, reducing the need for branching instructions.
Memory Segmentation:

Supports up to four blocks: DEFAULT, DEFAULTB, CDATA, and CBLKS.
Segregates code and data efficiently for logical program organization.
Passes of Assembly:

Pass 1: Generates memory location information (out_pass1.txt) and a symbol table (symbTable.txt).
Pass 2: Converts assembly instructions into machine code (out_pass2.txt) and organizes object code into the HTME format (HTME.txt).
Error Handling:

Detects and reports undefined symbols and unrecognized block names.
Validates correctness within program declarations and scope.
Support for Literals:

Automatically identifies and allocates memory for literals at the end of the pass.
