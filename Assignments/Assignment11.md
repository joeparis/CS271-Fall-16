**Due November 6**

1. Suppose a computer using direct mapped cache has 2^20 bytes of byte-addressable main memory, and a cache of 32 blocks, where each cache block contains 16 bytes.

   a) How many blocks of main memory are there?   
   b) What is the format of a memory address as seen by the cache, i.e., what are the sizes of the tag, block, and offset fields?   
   c) To which cache block will the memory address 0x0DB63 map?   

2. Suppose a computer using direct mapped cache has 2^32 byte of byte-addressable main memory, and a cache of 1024 blocks, where each cache block contains 32 bytes.


   a) How many blocks of main memory are there?   
   b) What is the format of a memory address as seen by the cache, i.e., what are the sizes of the tag, block, and offset fields?   
   c) To which cache block will the memory address 0x000063FA map?   

3. Suppose a computer using fully associative cache has 2^16 bytes of byte-addressable main memory and a cache of 64 blocks, where each cache block contains 32 bytes.

   a) How many blocks of main memory are there?   
   b) What is the format of a memory address as seen by the cache, i.e., what are the sizes of the tag and offset fields?   
   c) To which cache block will the memory address 0xF8C9 map?

4. Suppose a computer using fully associative cache has 2^24 bytes of byte-addressable main memory and a cache of 128 blocks, where each cache block contains 64 bytes.

   a) How many blocks of main memory are there?   
   b) What is the format of a memory address as seen by the cache, i.e., what are the sizes of the tag and offset fields?
   c) To which cache block will the memory address 0x01D872 map?

5. A 2-way set-associative cache consists of four sets. Main memory contains 2K blocks of eight bytes each and byte addressing is used.

   a) Show the main memory address format that allows us to map addresses from main memory to cache. Be sure to include the fields as well as their sizes.   
   b) Compute the hit ratio for a program that loops 3 times from addresses 0x8 to 0x33 in main memory. You may leave the hit ratio in terms of a fraction.

6. Suppose we have a computer that uses a memory address word size of 8 bits. This computer has a 16-byte cache with 4 bytes per block. The computer accesses a number of memory locations throughout the course of running a program. 

   Suppose this computer uses direct-mapped cache. The format of a memory address as seen
by the cache is shown below:

   | tag | block | offset |
   |-----|-------|--------|
   | 4bits | 2 bits | 2 bits |

   The system accesses memory addresses in this exact order: 0x6E, 0xB9, 0x17, 0xE0, 0x4E, 0x4F, 0x50, 0x91, 0xA8, 0xA9, 0xAB, 0xAD, 0x93, and 0x94. The memory addresses of the first four accesses have been loaded into the cache blocks as shown below. (The contents of the tag are shown in binary and the cache “contents” are simply the address stored at that cache location.)

![](http://i.imgur.com/N2K5u6n.png)

   a) What is the hit ratio for the entire memory reference sequence given above, assuming we count the first four accesses as misses?   
   b) What memory blocks will be in the cache after the last address has been accessed?   

7.  Given a virtual memory system with a TLB, a cache, and a page table. Assume the following:

* A TLB hit requires 5ns
* A cache hit requires 12ns
* A memory reference requires 25ns
* A disk reference requires 200ms (this includes updating the page table, cache, and TLB)
* The TLB hit ratio is 90%
* The cache hit rate is 98%
* The page fault rate is .001%
* On a TLB or cache miss, the time required for access includes a TLB and/or cache update, but the access is not restarted
* On a page fault, the page is fetched from disk, all updates are performed but the access is restarted
* All references are sequential (no overlap, nothing done in parallel)
   
   For each of the following, indicate whether or not it is possible. If so, specify the time required for accessing the requested data.   

   a) TLB hit, cache hit   
   b) TLB miss, page table hit, cache hit   
   c) TLB miss, page table hit, cache miss   
   d) TLB miss, page table miss, cache hit   
   e) TLB miss, page table miss   

   Write down the equation to calculate the effective access time.
