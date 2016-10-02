# SortCount
***************TESTING SHELLBUBBLESORT ONLY**********************

Averages for Random Arrays: (15 tests for each length)

 Length   |    Average comps    |  Average moves
------------------------------------------------
  300             70,968              4,459
  600            286,244             11,229
 3000          7,211,795             85,561
 6000	      28,880,855            207,928
12000        115,596,732            506,438

Averages for Almost Sorted Arrays: (15 tests for each length)

 Length   |    Average comps    |  Average moves
------------------------------------------------
  300             70,968              4,455
  600            286,244             11,103
 3000          7,211,795             87,511
 6000         28,880,855            217,917
12000        115,596,732            509,000

Averages for Sorted Arrays: (15 tests for each length)

 Length   |    Average comps    |  Average moves
------------------------------------------------
  300             70,968              4,529
  600            286,244             11,140
 3000          7,211,795             86,454
 6000	      28,880,855            216,602
12000        115,596,732            509,123


Average comparisons - when n is doubled, the comps are
quadrupled: 

286,244 / 70,968 = 4.03

Average moves - when n is doubled, the moves are increased
by n * 2.5:

11,140 / 4,529 = 2.5

So This sorting method is O(n^2). It also does not get any better
with partially sorted or sorted arrays. It still does the same
amount of comparisons and relatively the same amount of moves. 


