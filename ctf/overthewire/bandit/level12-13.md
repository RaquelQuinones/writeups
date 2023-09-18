## Level 12 - 13
# Analysis

This password for the level 13 it is stored in the file "data.txt", which is a hexdump of a file that has been repeatedly compressed. 
For this level I created a new directory to worn under which I use dthe command ***mkdir*** and copied the file into that directory ***cp***.
I ***cat*** the file which gave the information that the file type was a .bin 

I reversed hexdump the file given and outputed into another named "data"
```
xxd -r data.txt > data
```
Then, used ***file*** on data, which gave me the type of file that data is. So i renamed the file to the type and used the right commnad to decompresed it.
Example: if its was a .gz i used gzip -d to decompresed it. or if it was tar i used -xf, or if it was a .bz2 file i used bzip2 -d to decompresed.
I repeated all of this, until i finally foun the file with ASCII text, which had the flag.

## Flag
```
wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
```
