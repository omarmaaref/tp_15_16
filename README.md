# tp_15_16
LAB 15 :

what changes {
declaration :
    HashSet<Good> set=new HashSet();  }

->in 3.2 toaster won't be added twice because hashset does not allow duplications.
-> set.remove(paint); // to remove paint

LAB 16 :
BONUS:
since PAINT is not present in the array list , collections.binarySearch will return 
                        - ( insertion point ) - 1
where : insertion point is the index where paint should be present for the array to be sorted
-4 - 1= -5

step 5:
the documentation says :
It makes no guarantees as to the iteration order of the set; in particular, it does not guarantee that the order will remain constant over time.

so a search that require the data structure to be sorted (like in binarysearch) is not feasible.


