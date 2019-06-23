TestIterator.java
  TODO also try with a LinkedList - does it make any difference?

    Inserting numbers into a list occurs at faster rate with LinkedList
    over ArrayList. The use of pointers makes it easier to add numbers
    to the list.

  TODO what happens if you use list.remove(77)?

    An error pops up the IndexOutOfBoundsException, trying to remove an
    element that doesn't exist.



TestList.java
  TODO also try with a LinkedList - does it make any difference?

    Inserting numbers into a list occurs at faster rate with LinkedList
    over ArrayList. The use of pointers makes it easier to add numbers
    to the list.

  list.remove(5); //what does this method do?

    The value of 5 is removed from the list

  list.remove(Integer.valueOf(5)); // what does this one do?

    The int value of 5 is removed from the list



TestPerformance.java
    For list = new ArrayList<Integer>();
                      Size=10         Size=100        Size=1000          Size=10000
    TestPerformance   0.106s          0.144s          0.881s             12.332s

    For list = new LinkedList<Integer>();
                      Size=10         Size=100        Size=1000          Size=10000
    TestPerformance   0.099s          0.140s          0.864s             11.245s

  Which of the two lists performs better as the size increases?

    There is no surprise that LinkedList's test performance would be better
    as size increases. When the size is 10,000 the performance between the two
    list can be seen clearly.
