# Hash-tables

## Simple hashing

Generally hashing is a way to organise large data sets using a unique address and the MOD function. You would divide the number by the number of items in the table, and the MOD would be where you sort it. If two items have the same address, this is known as a **collison**. Usually, it is stored in the next free space. This can be resolved by having a prime number as the amount of spaces. Otherwise, places can be skipped. If the skip factor is 2 sometimes a free space cannot be found. 

## Mid-square hashing method

 This method squares the number to be stored, and the middle 2 digits are then divided by the table size to giuve you the address. In the case of an odd number of digits, the digit before the middle item, and the middle item are used. Collisions are handled by storing the item in the next available free space.

