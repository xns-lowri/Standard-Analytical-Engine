# Ruminations on the Design and Development of the Standard Analytical Engine Architecture

Friday 18th January 1861

## Method of Operation

Basic functions of the Standard Engine:

1. Conditional execution of Operations based on Flag states: (Zero) (Sign) (Carry/Borrow) (Overflow) 
2. Movement of values to and from Columns in the Mill, endpoints including:
  * Store Columns
  * Particulars Cards (read only)
  * Operation Card-Immediate (read only)
3. Diversion of pattern flow:
  * Divert: short signed offset jump
  * Transfer: Long jump to marked entry point by identifier
  * Halt: Pause pattern flow

Take (Source -> Mill), Give (Mill -> Destination)

* Emission drive: Define source and destination gearing during emission stroke of rack.
  * Engage source to reduce value to rack. (Not engaging a source is illegal?)
  * Engage destination to take value from rack.
* Restoring drive: Define source and destination gearing during restoring stroke of rack.
  * Source engaged = restore value from rack. Not engaged = clear source.
  * Destination engaged = take value back from destination (undo take, illegal if not engaged during emission?). Not engaged = leave value in destination. 
* Direction: Gearing between Mill/Rack and Rack/(Source/Destination) is reversed based on direction of movement.


## Ideas for pondering

* Pre/post increment/decrement of Accumulating Column by Displacement (paired column holding signed offset)
