# memcachedChallenge
Memcached Challenge.

Hello.

Recently Tsoding uploaded a challenge from 2014, called the memcached challenge. It involves adding support for multiplication operation to the application. 
This implementation of the same stores 64 bit unsigned integers as values, and therefore accepts operands(scaling values) upto 64 bits. It does not yet support multiplying by negatives. 
The multiplication operation is not handled for big integers, so please make sure the inputs multiply to a number less than 2^64, or the result will overflow. Floats/Doubles are not supported yet. 
The statistics for the mult operation are also not supported yet. The updates are threaded and mutex protected though so there's that. 

I will continue working on memcached and eventually will try to add support for storing arrays, objects and eventually matrices. 

Thank you, please take a look at the following resources to help better understand the motive of this activity.

https://quuxplusone.github.io/blog/2022/01/06/memcached-interview/
https://memcached.org/about
https://github.com/memcached/memcached

Thanks to the original creators and maintainers for sustaining such a well documented and versatile project! 
