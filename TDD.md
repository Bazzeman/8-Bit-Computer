# TDD (Technical Design Document)
Voor het bouwen van de 8-bit computer ga ik gebruik maken van bread boards, omdat er op gemakkelijke wijze onderdelen op kunnen worden verbonden. Het nadeel aan het gebruik van breadboards is dat slechte kwalliteit bread boards slechte connecties kunnen hebben of snel kappot gaan, maar dit voorkom ik door alleen gebruik te maken van goede kwalliteit bread boards. Ook kan ik gebruik maken van PCB's (Printable Component Boards), maar aangezien ik voor het eerst een computer ga bouwen en er de mogelijk is om onderdelen niet goed te verbinden ga ik geen gebruik hiervan maken.

## MoSCoW tabel
- Must
  - Clock module
    - Monostable timer
  - 8-bit register modules
    - Store at least 2 8-bit values
    - Write to bus pin
    - Write pin
    - Reset pin
  - Arithmetic logic unit (ALU)
    - Addition
  - Random access memory (RAM) module
    - Able to store at least 5 instructions
  - Program counter
    - Monostable timer
  - 8-bit Ouput register
    - Display the content of the register
    - Read from bus
    - Write pin
    - Reset pin
  - Control logic
    - Load value imidiately to register
    - Store value
    - Add 2 numbers
    - Output value of a register
- Should
  - Clock module
    - Stable timer
  - 8-bit registers
    - Display the content of the registers
  - ALU
    - Subtraction
  - Random access memory (RAM) module
    - Able to store at least 20 instructions
  - Program counter
    - Stable timer
  - 8-bit Ouput register
    - Convert binary signal to decimal
  - Control logic
    - Halt
    - Subtract 2 numbers
- Could
  - 8-bit Ouput register
    - Display output using seven-segment display
  - ALU
    - Multiplication
    - Subtraction
  - Random access memory (RAM) module
    - Able to store at least 50 instructions
  - Control logic
    - Jump to line
    - Multiply 2 numbers
    - Subtract 2 numbers
- Would
  - Random access memory (RAM) module
    - Able to store at least 100 instructions
  - Add a screen display
  - Add user input
    - Button presses
    - Keyboard



