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
will grow based on the number of elements in the list,
which means in linear fashion. This is becuase that is
the cost of the add function, and the expansion algorithm,
and we don't care about coefficients.
[Justify, in about 2 sentences.]