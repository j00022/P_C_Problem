# P_C_Problem
Assignment for cs570 Operating Systems at San Diego State University. 

Solves the producer consumer problem using C++, threads, and semaphores. It simulates a candy factory with a belt with a max size, two types of producers, and two workers (consumers). Upon producing and consuming a set amount of candies, a summary will be printed. 

Flags can be used in the command line to add delays to producing and/or consuming speeds:

-E N Specifies the number of milliseconds N that the Ethel consumer requires to put a candy in the box and should be invoked each time Ethel removes a candy regardless of the candy type.

-L N Similar argument for the Lucy consumer.

-f N Specifies the number of milliseconds between the production of each crunchy frog bite.

-e N Specifies the number of milliseconds between the production of each everlasting escargot sucker.
