###1. Is it an odd number?###
```boolean isOdd(int n)```
Return whether n is an odd number

###2. Is N prime?###
```boolean isPrime(int N)```

###3. Find the minimum element of an array###
```int min(int... array)```

###4. Find the kth minimal element of an array###
```int kthMin(int k, int[] array)```

###5. Find the average of the elements of an array###
```int getAverage(int[] array);```

###6. Double factorial###
```long doubleFac(int n);```
return 
E.g. if n=3, => (3!)! = 6! = 720 

###7. Kth factorial###
```long kthFac(int k, int n);```
Get the kthFactorial of n. k is guaranteed to be positive. 
*Bonus* no "helper" methods, no recursion :)

###8. Smallest multiple###
```long getSmallestMultiple(int upperBound);```

Find the smallest (positive) number, that can be divided by each of the numbers from 1 to *upperBound*.

###9. Find the largest integer palindrome number up to N###
```long getLargestPalindrome(long N);```

1234321 is a palindrome. You are given a number => *N*. 
Find the largest number < N, that is a palindrome.

*Bonus* do this without using Collections.sort

###10. Find the greatest product of N consecutive digits###
```long getGreatestProduct(long N, short K);```

You are given a large number => N. You are given a small number, K.
Find the biggest product of K consecutive digits in N.
E.g. K=98612, N=3, result = 9*8*6 = 432;

###11. Grayscale image histogram###
```int[] histogram(short[][] image)``` 

A histogram is a representation of distribution of some data.

Here you receive a grayscale image matrix (*image*). Each of the matrix's values will be between 0 and 255.
Return an array *result*, which is a histogram of *image* => the value of *result[i]* should be the ammount of times *i* is in the matrix *image*. 

###12. Raise an integer to a power of another###
```long pow(int a, int b)```

Write a O(log(b)) solution.

###13. Find the only number, that occurs odd times in an array###
```int getOddOccurrence(int... array)```

Every element in array will occur an even ammount of times.  There will be exactly one element
Example: {1,2,2,1,3,4,3,4,4,6,5,6,5} => 4 occurs only an odd number of times.

###14. Maximal scalar product###
```long maximalScalarSum(int[] a, int[] b)```
You are given two vectors, *a* and *b*. Let a be ```{a1,a2,a3}``` and b be ```{b1,b2,b3}```. The scalar product of vectors *a* and *b* is the number ```a1*b1 + a2*b2 + a3*b3``` 

Find a permutation of a, and a permutation of b, for which their scalar product is the largest possible.  

###15. Max span###
```int maxSpan(int[] numbers)```
Consider the leftmost and righmost appearances of some value in an array. We'll say that the "span" is the number of elements between the two inclusive. A single value has a span of 1. Returns the largest span found in the given array. 

maxSpan({1, 2, 1, 1, 3}) → 4
maxSpan({1, 4, 2, 1, 4, 1, 4}) → 6
maxSpan({1, 4, 2, 1, 4, 4, 4}) → 6

###16. Can balance?###
```boolean canBalance(int[] numbers)```

canBalance({1, 1, 1, 2, 1}) → true
canBalance({2, 1, 1, 2, 1}) → false
canBalance({10, 10}) → true

Return true if there is an element in the array, where you can split the array in half and the sum of left side would be equal to the sum of the right part. 

###17. Rescale an image using nearest neighbour interpolation###
```int[][] rescale(int[][] original, int newWidth, int newHeight)```

You are given an image *original*. Rescale it to newWidth, newHeight, using nearest neighbour interpolation. (See http://en.wikipedia.org/wiki/Nearest-neighbor_interpolation)