Jaret Solomon

Place all written answers from assignment-03.md here for easier grading.

1a. Find the largest 2^k so that 2^k <= N. Minus N - 2^k until 2^k until N <= 1.

1b. K is at its largest every iteration. The largest value of one of our coins making it always less than or equal to N. Therefore thereare no smaller coins to replace it without using more coins.

1c. O(log n)

S(n): O(log n)

2a. D = [1, 6, 8], N = 6; The greedy algorithm would choose 8 first, which would leave 2, leaving two ones to be used. The most efficient way to do this would be to use two sixes, using only two coins.

2b. This is an optimal substructure because it solves smaller problems to take on larger ones.

2c. We take into account the substructures, therefore both work and span is O(n).