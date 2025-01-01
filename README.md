# VHDL Integer Overflow Bug

This repository demonstrates a common but subtle bug in VHDL: integer overflow in a counter.  The `buggy_counter.vhdl` file contains a counter that increments until it reaches its maximum value (15).  However, it lacks proper handling of the case where it reaches the upper bound, potentially leading to an unpredictable integer overflow.

The `fixed_counter.vhdl` file shows the corrected code which properly handles the boundary condition to avoid the overflow.

This example highlights the importance of careful consideration of boundary conditions and potential overflows when working with integer types in hardware description languages like VHDL.