# python考试



## 基础序列分析

### 1 

**难度3**

逐行读取序列，并将物种名和序列名对应做成字典，然后输出GC含量(按照GC含量从高到底)和反链DNA。

```
# 1
{"human"："ATCG","mouse":"AAAA"}
# 2
[("human", 0.5), ("mouse", 0)]
# 3
{"human"："TAGC","mouse":"TTTT"}
```

### 2

**难度4**

计算每个物种的kmer（k=2），并输出CSV格式矩阵
（文件名为物种名）

要求写成function, 只要提供序列和kmer的数字就计算出结果

```python
# read fasta
...
# function
# 
def kmer_function(kmer, fasta):  
	retutn dict()
  
```

### 3

**难度5**

给取一段fastq文件，随机从中获得5000(可以用别的数)个序列（注意fastq序列格式），要求逐行读取，防止内存溢出，并输出结果

```
number = 10 or 5000

```



### 4

**难度2**

首先获得负链序列，寻找正负链DNA的motif，并输出正负链的motif位置

```python
motif = "ATTAC"
#
def find_motif(fasta, motif):
    
```

### **5**

**难度5**

滑动窗口找一条序列的最长回文序列

```
#
a = "caattacaa"
# 回文序列：atta
```



### 排序（不要使用包）

### **1**

**难度5**

将列表的数字进行归一化（z-score）（归一化可以掉包，也可手写，但要知道怎么算），并**插入排序**（不能使用内置函数排序）



### R作图

PCA，heatmap，气泡图