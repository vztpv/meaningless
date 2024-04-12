tag : uint64_t ?

start node + tag -> same node? 
binary tree?
left(0), right(1)

insert, search, remove.

1 
   2  
      3
=>	  
   2
1     3

first 1 bit means is_root?
(start node + tag + tag_size)
1 : 100, 1 -> 000, 2
2 : 010, 2 -> 100, 1
3 : 011, 3 -> 010, 2

i) uint8_t[]
1     ->  one of  ( 1, 00, 01 )  1->1 (x)
01    ->           ...
011   ->           ...

