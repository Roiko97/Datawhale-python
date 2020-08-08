```python
def longest_word(filename):
    f = open(filename)
    line = f.readlines()
    print("原始字符串{0}".format(line))
    line= str(line)
    line = line[2:len(line)-2]
    line = line.split(" ")
    max_count = 0
    put = ""
    for i in line:
        if len(i)>max_count:
            max_count = len(i)
            put = i
    print("最大的字符串长度为{0},对应单词为{1}".format(max_count,put))
longest_word("word.txt")
```

    原始字符串['apple template orginal banana nginx efficient knowledge appear']
    最大的字符串长度为9,对应单词为efficient
    


```python

```
