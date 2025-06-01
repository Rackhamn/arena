# Arena Allocator
This is a simple arena allocator written in C for a linux system.  
It does not use any Posix specific or Linux specific things other than malloc.  
The arena holds it's initial size always and does not reallocate (even though that would be a good addition)  

