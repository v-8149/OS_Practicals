 https://chatgpt.com/share/673c24ea-b190-800f-933f-a04d01e03fde
 
##########SSTF (Shortest Seek Time First):Selects the request closest to the current head position.
SCAN (Elevator Algorithm):Moves the disk head in a specified direction (up or down) until it reaches the end, servicing requests along the way.
Reverses direction when it reaches the disk's end.
C-LOOK will move upwards, then jump to the smallest request and continue servicing in a circular manner.

####Page Fault: Occurs when a page referenced by the process is not present in the frame (memory).
Replacement Algorithms:
FIFO (First In, First Out): Replaces the oldest page in memory.
LRU (Least Recently Used): Replaces the page that hasn’t been used for the longest time.
Optimal: Replaces the page that will not be used for the longest time in the future (requires future knowledge).

## 
