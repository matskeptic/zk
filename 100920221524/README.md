# Inodes and how they work

I learned about how inodes is a file structure, so each file has a specific inode in the system, there's 15 direct pointers( addresses) in the inode structure, so
we the first welve blocks of data for small sized files, we can get 13 addresses for one layer of indirection, 2x for two and 3x(15) for three layers.
