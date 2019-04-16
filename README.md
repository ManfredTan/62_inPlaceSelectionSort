# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 3! times, because each time you add n elements
to the ArrayList, the algorithm has to count the ArrayList
n times, then n-1 times, then n-2 times, until it equals n!.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by 3 times. You invoke the reigning champ algorithm
once for each extra element. So by tripling the elements, 
you triple the number of invokations.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by 3 times, because the JVM will have to look
at 3 times as many elements. It goes through each element
once to check if it is lower.
[Justify, in about 2 sentences.]
