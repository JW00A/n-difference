# n-difference

If i is an odd number, then i/2 and i/2-1 are its numbers(for as long as they aren't fractions, it requires another situation described below). The difference n = j - 1 holds if j is a number which those 2 numbers are multiplyed by. To prove this we can subtract these numbers as follows: 

 n = ((i/2)*j + (i/2-1)) - ((i/2-1)*j + (i/2)) 

 Additionally:

  if j > 1, then n>0, 

  if j = 1,nthen n = 0, 

  if j < 1, then n < 0. 

 However, when i is even or a fraction, the numbers are: i/2. 

 E.g. 7 is i, (4,3) are its numbers(i/2, i/2-1), then:

  if j = 2, n = 1, or n = (4 * 2 + 3) - (3 * 2 + 4), 

  if j = 1, then n = 0, or n = (4 + 3) - (3 + 4), 

  if j = 0, then n = -1, or |1|, or n = (0 + 3) - (0 + 4). 

 If i = 8, then i/2 = 4 or both numbers are equal in all cases of j. If i = 3.5 or its numbers are fractions, then both numbers are i/2 and are equal.

 This rule holds for all odd integers (i). In other words, if i is an odd integer, then this rule applies, and i/2 and i/2-1 are its numbers. However if (i) is real or rational number, this rule no longer applies, and i/2 is considered as both its numbers.

 Note: n = j works seemingly for all odd i numbers. E.g. 101 is i, (51, 50) are its numbers, if j = 4, then n = 4 or n = (51 * 4)-(50 * 4)

 Upon further discovery and research I came to the conclusion that difference of any 2 given numbers and consecutive added numbers could be found by this formula: n = k * j + ( n1 + nN), where k is the first difference between two terms(the first and second one), j is the multiplyer or how many times the two terms were multiplyed, n1 is the first difference of two added terms and nN is the last difference of any two added terms or N is the the number of all added terms. The k term can also be expressed as n or n = k when k = a - b, however, as difference n found differently here, k term is used. The two terms a and b could be equated to i/2 and i/2-1.

 E.g. 7 is our number, a and b will be 3 and 4 for the first equation and 4 and 3 for the second one. If these terms are added together, then, we can find n if j = 1 or multiplyer isn't important in the given case since nothing is multiplyed. Then equations will be:
 1. n = (3 - 4) * 1 + (4 - 3) = -1 + 1 = 0
 2. n = (4 - 3) * 1 + (3 - 4) = 1 - 1 = 0

 In order to check if it still works with multiplyers, let's j be equal to 42:
 1. n = (3 - 4) * 42 + (4 - 3) = - 42 + 1 = -41
 2. n = (4 - 3) * 42 + (3 - 4) = 42 - 1 = 41

 Since we can express k as a - b, then we can find the difference of any number being multiplyed in these two ways: 1. n = (a * j - b) + (n1 + nN), 2. n = (a - b * j) + (n1 + nN), which depends on which number is being multiplyed, a or b.
 
 Additionally, n1 and nN represent additional differences and could be negated if no numbers are being added to the initial ones. Any 2 numbers could be represented as a = a1 + aN and/or b = b1 + bN, or we could find the difference easier if we separate big numbers, in this case n = (a1 - b1)*j1 + (aN - bN)*jN, where j could be an equal multiplyer of these numbers.
