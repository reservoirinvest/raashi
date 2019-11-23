# The scenario
There are m is participants
Are asked to gave rating of 1 - 5 *s for n movies each
2D array of m (participants) x n (movies)

Company decides to give a pair of movie tickets to two participants with most similar taste.

Use Euclidian distance as a measure of similarity
distance = sqrt[(ri1 - rj1)sq + (ri2 - rj2)sq + ... + (rin - rjn)sq]
Participants with the smallest Euclidian distance wins the tickets

# The challenge
Write a function _most similar_ taking 2D array and returns the indices of two participants with most similar movie taste.
At least 2 partipants
Movies (1... 100)
