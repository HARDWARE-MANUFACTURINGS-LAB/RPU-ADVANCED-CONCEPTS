# RPU-ADVANCED-CONCEPTS

RPU, the rust processing unit is the unit of the rust code to innate processable hardware. It is the secure cpu. Cause of the rust immediately run on it.
And, the Cache must be Bigger than traditional CPU.
It has the drop logics(voltage is drop to 0v, when the operantion done.
And, the natural-decimal numeric operation is available in this cpu.
Translate into binaries are next steps.


*Diagram*
---------------------------------------------------------------------------
| controlling unit |  CACHE |  Register(Integer)   ||     | DMA || MEMORY |
---------------------------------------------------------------------------
|      ALU         |  CACHE |  Register (Floating) ||      |              |
---------------------------------------------------------------------------
|    Accumulator   |  CACHE | REGISTER (char)      ||      |              |
---------------------------------------------------------------------------
|       DROP-Gate  |  DROP |  DROP                ||      |              |
---------------------------------------------------------------------------
