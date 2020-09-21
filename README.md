# B+-Tree-File
Implementation of functions, which manage files based on B+ Trees.

# Summary
In this project we use implemented functions of management with Block Files and we implement functions, which manage files with B+ Tree, some of those are AM_CreateIndex,AM_OpenIndexScan,AM_InsertEntry,AM_FindNextEntry etc. Mainly the difficult part in this project was the implementation of insertion of a node in a B+ tree, cause we have to search or sort entries in blocks or maybe break blocks. Important info is that we can differ index blocks from leaf nodes(data blocks) from their first byte which is 'i' or 'l' respectively. Finally our B+ Tree can deal with we have a lot of Entries with same keys, with a function Same_Keys() which calculates in which point will break old block into two new.

# Execution 
You can check it out, only with successively executions:
1) **bash script1.sh**  (Check results of first queries.)

2) **bash script2.sh**  (Check results of next queries.)

3) **bash script3.sh**  (Clean what we have just created.)
