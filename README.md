# MSP430 Assembly Programming Lab 1

This repository contains the solution to **Lab 1** for MSP430 assembly programming. The lab focuses on using the IAR IDE to develop, debug, and test assembly programs for the MSP430 microcontroller. The solution includes theoretical explanations and practical implementations as specified in the lab requirements.

---

## 📋 Description of the Assignment

### Part A: Theoretical Section
1. **Development Environment**: Understanding the IAR IDE and its role in embedded development.
2. **Instruction Types**: Differentiating between core instructions and emulation instructions, including examples and use cases.
3. **Registers in the CPU**: Detailing the working registers in the MSP430 CPU.
4. **Status Flags**: Explanation of the usage of status flags (`V`, `C`, `N`, `Z`) in the `SR` register, with examples.

### Part B: Practical Section
1. **Task Description**:
   - Write an assembly program to compute results based on specific rules and input arrays.
   - Two arrays, each containing eight 16-bit integers, represent the inputs. These arrays correspond to two student IDs.
   - A calculation is performed based on the last digit of the smaller student ID, using a predefined operation (see table below).

2. **Operation Table**:
   Based on the last digit of the smaller ID, the operation for calculating `R4` is selected:
   - `0`: Logical OR of corresponding elements in the arrays.
   - `1`: Maximum sum of array elements.
   - `2`: Element-wise addition.
   - `3`: Element-wise subtraction.
   - `4`: Minimum sum of array elements.
   - `5`: Minimum even sum.
   - `6`: Maximum odd sum.
   - `7`: Logical AND of corresponding elements in the arrays.
   - `8`: Minimum odd sum.
   - `9`: Maximum odd sum.

3. **Simulation Details**:
   - The program must be tested in the simulator.
   - Record program size and runtime cycle count.
   - Calculate runtime in microseconds using the default clock settings.

---
