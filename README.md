# CS 4560 SOFTWARE WAlK-THROUGH
Used for software walk-through

# Participants and Roles

## Leader - 1 person conducts walk-through (ensuring done orderly) and handles administrative tasks (e.g., document distribution)
-Ashley Gearheart

## Recorder - 1 person takes notes including anomalies found, decisions/actions arising form meeting, etc.
-Michael Prothero

## Team Members - remaining actively participate to identify and describe anomalies
-Devin Waldon     
-Caleb Courtney  
  



==========================================================================================

# FAULTS     
None Found






# INCONSISTENCIES     
file srcSAXEVENTDispatcher.hpp lne 757-771 (problem with inconsistent commenting)







# REQUIREMENTS VIOLATIONS
None Found 





# IMPROVEMENTS     
file srcSAXEVENTDispatcher.hpp line 153 (could be improved. assign each variable explicity to false) 
file srcSAXEVENTDispatcher.hpp line 167 (could be improved. assign each variable explicity to false) 
file srcSAXEVENTDispatcher.hpp line 174-203 (possibly use boolean True/False instead of void) 
file srcSAXEVENTDispatcher.hpp line 312 (get rid of commented out code.)
file srcSAXEVENTDispatcher.hpp line 205 (possibly refactor this map into own file) 
file srcSAXEVENTDispatcher.hpp line 475 (possibly refactor this map2 into own file) 
file srcSAXEVENTDispatcher.hpp line 541-550 (cant tell if problem is resolved or not code is still commented out)
file srcSAXEVENTDispatcher.hpp line 772-774 (code smell can use a object in place of too many arguments)
file srcSAXEVENTDispatcher.hpp line 778-800 (code smell can use a object in place of too many arguments)
file srcSAXEVENTDispatcher.hpp line 849-857 (remove deprecated code)
file srcSAXEVENTDispatcher.hpp line 942-945 (very confusing way of writing a conditional and the ternary should be factored out)
file srcSAXEVENTDispatcher.hpp line 952-955 (very confusing way of writing a conditional and the ternary should be factored out)

file srcSAXSingleEventDisptcher.hpp line 57-75 (inconsistent whitespace could be improved)

file srcSAXEventDisptcherUtilities.hpp line 32-33 (inconsistent programming style)
file srcSAXEventDisptcherUtilities.hpp line 110-112 (code smell can use a object in place of too many arguments)
file srcSAXEventDisptcherUtilities.hpp line 206 {dispatcher class} (inconsistent code spacing)
file srcSAXEventDisptcherUtilities.hpp line 233-252 (switch statement might need refactoring)
file srcSAXEventDisptcherUtilities.hpp line 437 (refactoring)
file srcSAXEventDisptcherUtilities.hpp line 438 (commented out code should be removed)








### Source-code Walk-through Checklist

#### Data Reference Errors
- [N] Are any containers accessed outside their bounds?
- [Y] Are all references through a pointer variable currently allocated?

#### Computation Errors
- [N] Is there any use of integer division with floating point devision is required?
- [N] Is there a possibility of overflow or underflow during computation?
- [N] Is there a possibility of a divide by zero?
- [Y] Are the order of operations in computations assumed correctly?

#### Comparison Errors
- [N] Are any = operator used when == is needed?
- [Y] Are comparison operators correct?
- [Y] Are boolean operators and the operands they are used on correct?
- [Y] Are comparisons to floating point numbers handled correctly?

#### Control-Flow Errors
- [Y] All loops/recursive will terminate?
- [N] Are there any off-by-one errors?
- [Y] Are no do-while-statements used?

#### Function Errors
- [Y] Are all arguments passed in the correct order?
- [Y] Are all by-value parameters never modified?

#### I/O Errors
- [Y] Are all inputs to the system validated?
- [Y] Are all opened files are closed?
- [Y] Are end-of-file conditions handled correctly?
- [Y] Are I/O error conditions handled correctly?

#### Other Errors
- [Y] Are all constant literals assigned a constant variable?
- [N] Are returned error codes/states checked and handled correctly? (some should be changed to boolean)
- [N] Are all exceptions caught and handled correctly?
- [Y] Are there no uses of using namespace std;
