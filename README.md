# CodingNotes

Slicing:

O(1) Look up

```python
array = [1,2,3,4,5]
# array[start:end:step]
```

Reverse List
```
array[::-1]

[5,4,3,2,1]
```

Sliding Window





#System Design

Symbolic link to mount many/infinite files. Helps to keep reference if there are space issues.

Create:
```linux
link -symbolic current_destination_filename filename_link
ln -s /script/file.sh file.sh
```
Delete:
```linux
rm -rf file.sh
```

i.e need space?
```linux
mv /games/gamedirectory 100tb/games/gamedirectory
ln -s /games/gamedirectory gamedirectory
```
