 Universal Gates (NAND & NOR) - Theory & Truth Tables**

### Concept Overview
NAND and NOR are known as **universal gates** because they can be combined to create any other logic gate. Understanding these gates is vital for efficient circuit design.

### Detailed Explanation

#### ✅ NAND Gate (NOT AND)
- **Definition:** The NAND gate is the complement of the AND gate. It outputs `0` only when **both** inputs are `1`. In all other cases, the output is `1`.
- **Symbol:** Represented by an AND gate symbol with a small circle (inversion bubble) at the output.
- **Boolean Expression:** `Y = (A • B)'`
- **Truth Table:**

| A | B | Y (NAND) |
|:-:|:-:|:-----------|
| 0 | 0 | 1           |
| 0 | 1 | 1           |
| 1 | 0 | 1           |
| 1 | 1 | 0           |

**Example Application:** Used in flip-flops, memory elements, and complex gate designs.

#### ✅ NOR Gate (NOT OR)
- **Definition:** The NOR gate is the complement of the OR gate. It outputs `1` only when **both** inputs are `0`. In all other cases, the output is `0`.
- **Symbol:** Represented by an OR gate symbol with a small circle (inversion bubble) at the output.
- **Boolean Expression:** `Y = (A + B)'`
- **Truth Table:**

| A | B | Y (NOR) |
|:-:|:-:|:----------|
| 0 | 0 | 1          |
| 0 | 1 | 0          |
| 1 | 0 | 0          |
| 1 | 1 | 0          |

**Example Application:** Used in digital latches, control systems, and simplified gate networks.


### Code Explanation
- **`assign` Statements:** Used to define NAND and NOR logic using the `~` (NOT), `&` (AND), and `|` (OR) operators.
- **`$monitor` Task:** Displays input combinations and corresponding outputs.
- **Test Cases:** Each input combination verifies correct gate behavior.

### Execution Steps
1. Copy the Verilog code into your simulator (e.g., ModelSim, Xilinx Vivado, etc.).
2. Compile the code and fix syntax errors if any.
3. Run the simulation and verify the output against the truth tables.

### Real-World Example for Practice
- Design a **2-bit multiplier circuit** using only NAND gates.

Would you like to proceed with **Day 5: Combinational Circuits - Multiplexer (MUX) and Demultiplexer (DEMUX)** next?

