
#Algorithm


###Graph Implementation Tips

<http://www.geeksforgeeks.org/depth-first-traversal-for-a-graph/>

<https://ece.uwaterloo.ca/~cmoreno/ece250/2012-03-26--graphs-implementation.pdf>

<http://www.algolist.net/Data_structures/Graph/Internal_representation>

<https://stackoverflow.com/questions/22120639/making-an-adjacency-list-in-c-for-a-directed-graph/22121060#22121060>


###Priority queue for user-defined types

<http://stackoverflow.com/questions/9178083/priority-queue-for-user-defined-types>




### C++ throw exception

<http://stackoverflow.com/questions/8480640/how-to-throw-a-c-exception>


### Vector VS. List

<http://stackoverflow.com/questions/2209224/vector-vs-list-in-stl>


### Prim VS. Dijkstra
<http://stackoverflow.com/questions/14144279/difference-between-prims-and-dijkstras-algorithm>

### Vector iteration

<http://stackoverflow.com/questions/409348/iteration-over-vector-in-c>

### Array of List

<http://stackoverflow.com/questions/17897943/array-of-stdlist-c>

### C++ sort
<http://stackoverflow.com/questions/5897319/how-to-use-stdsort-to-sort-an-array-in-c>

```
#include <algorithm>

static const size_t v_size = 2000;
int v[v_size];
// Fill the array by values
std::sort(v,v+v_size); 

```

### C++ compile on Mac

<http://stackoverflow.com/questions/24462973/why-won-t-this-simple-c-code-compile-with-clang>

```
$ clang++ -std=c++11 -stdlib=libc++ t.cpp
```

#OS

### BlockingQueue

<http://docs.oracle.com/javase/7/docs/api/java/util/concurrent/locks/Condition.html>

<http://stackoverflow.com/questions/20110013/implement-your-own-blocking-queue-in-java>


###Memory Translation 

<http://programmers.stackexchange.com/questions/178921/how-many-bits-address-is-required-for-a-computer-with-n-bytes-of-memory?>

###Java ProcessBuilder: Input/Output Stream
<http://stackoverflow.com/questions/11573457/java-processbuilder-input-output-stream>


###Implements VS Extends
<http://stackoverflow.com/questions/10839131/implements-vs-extends-when-to-use-whats-the-difference>

###A java file multiple classes
<http://stackoverflow.com/questions/968347/can-a-java-file-have-more-than-one-class>

### Difference between try/catch and throw
<http://stackoverflow.com/questions/3794910/difference-between-try-catch-and-throw-in-java>


### CPU bound VS I/O bound

<http://stackoverflow.com/questions/868568/what-do-the-terms-cpu-bound-and-i-o-bound-mean>


### Run a jar file

<http://stackoverflow.com/questions/5774970/run-jar-file-in-command-prompt>

###Java - Sockets

<https://www.youtube.com/watch?v=6G_W54zuadg>


### Add external jar to Eclipse

<https://www.genuitec.com/forums/topic/the-import-org-apache-log4j-can-not-be-resolved/>


### Use Junit test
<https://courses.cs.washington.edu/courses/cse143/11wi/eclipse-tutorial/junit.shtml>

### Exception handle
<http://blog.csdn.net/hguisu/article/details/6155636>


### Throwable and Exception 
<http://stackoverflow.com/questions/2274102/difference-between-using-throwable-and-exception-in-a-try-catch>



#Discrete Math


###Set and Element Relations
<http://mathforum.org/library/drmath/view/62565.html>

###Zero not a natural number
<http://mathforum.org/library/drmath/view/57186.html>

###MergeSort

<https://en.wikipedia.org/wiki/Merge_sort>

###Divide

**a divides b** b is divided by a → **b = ac // write as a|b** 

<https://en.wikipedia.org/wiki/Division_(mathematics)>

###GCD

```
		 	 b, if a = 0
gcd (a,b)〈  							//a < b 
  			 gcd(b mod a, a)
 

```

<https://en.wikipedia.org/wiki/Greatest_common_divisor>

###Counting Rules

<http://utdallas.edu/~sizheng/2015/5333.d/l-notes.d/l-note5.pdf>

<http://krisyu.github.io/2015/more_counting_problem:principle/>


###Pigeonhole principle

<https://en.wikipedia.org/wiki/Pigeonhole_principle>


### Ramsey's theorem
<https://en.wikipedia.org/wiki/Ramsey%27s_theorem>




