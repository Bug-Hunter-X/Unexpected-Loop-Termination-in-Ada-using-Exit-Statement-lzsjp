# Ada Exit Statement Bug
This example demonstrates a potential issue with the `exit` statement in Ada loops.  The loop might terminate earlier than intended if the exit condition is not carefully considered within the loop's logic.

## Bug Description
The provided Ada code snippet uses an `exit` statement inside a `for` loop.  While functional, it's easy to misinterpret the termination condition, potentially leading to errors if the intended loop behavior is not precisely defined in relation to the exit condition.

## Solution
The solution involves a clearer definition of the loop's termination condition.