# Uncommon Assembly Errors: Segmentation Fault and Out of Bounds Array Access

This repository demonstrates two uncommon errors that can occur in assembly code:

1. **Segmentation Fault:** Accessing memory at an invalid address.
2. **Out of Bounds Array Access:** Accessing an array element outside its defined bounds.

The `bug.asm` file contains code that exhibits these errors. The `bugSolution.asm` file shows how to correct them by adding appropriate checks and bounds validation.

The solution involves validating the addresses and array indices before performing memory access operations.  This validation is crucial to ensure the robustness and security of assembly programs.
