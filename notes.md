Big O Notation
====================

O(1)
- Doesn't scale with the data size.

O(n)
- Scales proportionally with the data size
- LINEAR for example
  - O(n) if n is the size of the array!

O(n^2)
- if it prints out some numbers form the array.  2,5 or 5,2

O(a) === a = area
- plot of land example.
- You don't have to use n... you could use O(s^2) === sides square === area === O(a)

4 IMPORTANT RULES
1. ADD up the steps!
  - Step one === O(a)
  - Step two === O(b)
    - - - - - - - - - O(a + b)

2. DROP CONSTANTS!
  - O(2N) === O(n)

3. Different INPUTS => Different Variables
  - 2 arrays !== O(n^2)... 2 arrays === O(a * b)
  - - - Because n can't be the size of the array...

4. DROP all NON-DOMINANT TERMS
  - O(n + n^2) === drop n === O(n2)

  
