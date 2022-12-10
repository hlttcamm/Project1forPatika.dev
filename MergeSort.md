```
[16,21,11,8,12,22] -> Merge Sort (PROJECT 2)
a-Write steps of the array above according to Merge Sort
b- What is the Big-O notation of that sorting ?
``` 
**a-**    
|STEPS|PART 1|PART 2|
|:---|:---:|---:|
| step 1| [16,21,11]|           [8,12,22]|
|step 2| [16,21] [11]|        [8,12] [22]|
| step 3| [16] [21] [11]|        [8] [12] [22]|
|step 4 |[16,21] [11]    |    [8,12] [22]|
|step 5 |[11,16,21]  |        [8,12,22] |
|step 6 |[8,11,12,16,21,22]| |  

**b-**
The Big-O represantation is O(nlogn) 