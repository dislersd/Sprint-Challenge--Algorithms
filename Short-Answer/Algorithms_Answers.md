Add your answers to the Algorithms exercises here.

1.
a) O(n) because as n grow by 1 the loop increases by 1

b) O(n^3) because the nested loops add to the complexity. One for loop is O(n) and three more make it O(n^3): O(n) * 3 = O(n^3)

c) O(n) because the input is linear to the amount of times the function runs. Every 1 bunny adds another stack.

2.
Take n floors and divide by two. Go to the highest floor in lower half and drop egg. If it breaks than f is not in this half, forget these floors and continue to higher half. If it does not break than split floors in half again and repeat until you have found f. 

If lower half did not contain f go to first floor of higher half and drop egg to determine if floor = f. If does not break split in half again and continue until you have found f.

O(log n) because you are cutting half the floors while searching. This is binary search.
