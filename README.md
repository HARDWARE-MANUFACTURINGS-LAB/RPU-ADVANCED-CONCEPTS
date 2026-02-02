# RPU-ADVANCED-CONCEPTS

RPU, the rust processing unit is the unit of the rust code to innate processable hardware. It is the secure cpu. Cause of the rust immediately run on it.
And, the Cache must be Bigger than traditional CPU.
It has the drop logics(voltage is drop to 0v, when the operantion done.
And, the natural-decimal numeric operation is available in this cpu.
Translate into binaries are next steps.

summarize: 

RPU has the 
1. Drop-logic gate
2. Borrowing and Lifetime checker and  Flags.
3. Error Bit Flags
4. control unit
5. Ownership checker  and  flags.
6. hardware-innate assembler(text mapper).
7. value ownership  tracker
8. Overflows  checker
9. DMA
10. Data  register
11. Opcode register
12. Data and Opcode classifier
13. Arithmetic  and  Logical  Unit
14. Accumulator
15. private space.
16. Result flags
    etc.


example  :
**CISC  VERSION**
mov  rax ,  rbx, 3, 4 ,  0x2063e, 0x26893; 3  and  4  is  rax  and  rbx  value,   and  its  memory  position  explicitly
**RISC  VERSION:**
mov  rax  , rbx ,  3  , 4  , 0x345e,  0x2543,   0x7654 0x2543  ; LAST  TWO PARAMS  ARE  THE  WHICH  VALUE OWNED  WHERE THE  MEMORY.
