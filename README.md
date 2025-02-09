# VHDL Counter Bug
This repository demonstrates a common off-by-one error in VHDL code for a simple counter. The counter is designed to count from 0 to 15, but due to an error in the comparison, it stops incrementing at 15 instead of looping back to 0 after reaching 15.  The solution demonstrates the corrected code.

## Bug Description
The `bug.vhdl` file contains a VHDL counter that has an off-by-one error. The counter incorrectly stops at 15 instead of incrementing to 16 before resetting to 0.  This is a subtle but common mistake when designing counters or other sequential circuits in VHDL.

## Solution
The `bugSolution.vhdl` file provides a corrected version of the VHDL code.  The comparison in the `if` statement is fixed to correctly handle the upper bound of the count.

## How to Use
1. Clone the repository.
2. Open the VHDL files in your preferred VHDL simulator/IDE.
3. Simulate the designs to observe the behavior of the buggy and corrected versions.
