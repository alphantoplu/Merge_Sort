# Merge_Sort
Our series is [16 21 11 8 12 22]
Let seperate our series two part
then we have [16 21 11]---[8 12 22]
let seperate again
[16 21],[1] and [8,12],[22]
let seperate again
[16],[21] and [11]--- [8],[12] and [22]
Let's sort each group among themselves
[16 21] and [11]---[8 12] and [22]
let sort again
[11 16 21]----[8 12 22]
let sort again
[8 11 12 16 21 22]

Merge-Sorting Big-O?
We have n step sorting and logn step height
big-O = o(n).log(n)=o(nlogn)
