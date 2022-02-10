# Heap-Implementation
Project Information:
Implement a library that interacts with the operating system to perform heap management on behalf of a user.
Making our own malloc and free. For this we need to override the existing malloc and free by using 
LD_PRELOAD:
$ env LD_PRELOAD=lib/libmalloc-ff.so cat README.md
