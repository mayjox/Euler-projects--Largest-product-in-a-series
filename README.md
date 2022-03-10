# Euler-projects--Largest-product-in-a-series
Find the thirteen adjacent digits in the 1000-digit number that have the greatest product.

# About The Project

Project Euler is a series of challenging mathematical/computer programming problems that will require more than just mathematical insights to solve. https://projecteuler.net/

This is the eighth problem in the series. 

The four adjacent digits in the 1000-digit number that have the greatest product are 9 × 9 × 8 × 9 = 5832.

73167176531330624919225119674426574742355349194934
96983520312774506326239578318016984801869478851843
85861560789112949495459501737958331952853208805511
12540698747158523863050715693290963295227443043557
66896648950445244523161731856403098711121722383113
62229893423380308135336276614282806444486645238749
30358907296290491560440772390713810515859307960866
70172427121883998797908792274921901699720888093776
65727333001053367881220235421809751254540594752243
52584907711670556013604839586446706324415722155397
53697817977846174064955149290862569321978468622482
83972241375657056057490261407972968652414535100474
82166370484403199890008895243450658541227588666881
16427171479924442928230863465674813919123162824586
17866458359124566529476545682848912883142607690042
24219022671055626321111109370544217506941658960408
07198403850962455444362981230987879927244284909188
84580156166097919133875499200524063689912560717606
05886116467109405077541002256983155200055935729725
71636269561882670428252483600823257530420752963450

The challenge was to Find the thirteen adjacent digits in the 1000-digit number that have the greatest product. What is the value of this product?

# Built with:

The solution was built with Javascript ES6. Javascript concepts used:

for loop, short circuiting, sliding window pattern.

# What I learned:

Two approches to solve the problem in the first file. The firt with the linear and second with the quadratic notation. Noticed the second ran faster than the first which is 
not usuall for these, maybe because the second loop had considerably less loops to go through or maybe because the algorithm had to find only one y[i] index and continued from
there while the first had to find all the y[i + number] from the start. Explore linked list later

Working on third approach....

I am learning better how some of these string and array methods work.

Explored the use of console.time()/console.timeEnd() to measure how fast a program runs.

Exploring time complexities with the O(N) and O(N2)

Applied the sliding window problem solving pattern to solve the problem


