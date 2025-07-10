```python
import numpy
```

## Analyzing patient data
inflammation data for mulitple patients

numpy.loadtxt(fname = 'inflammation-02. csv', delimter = ',')
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
numpy.loadtxt(fname = 'inflammation-02. csv', delimter = ',')
```

    array('i', [1, 2, 3, 4, 5])
    array('d', [1.1, 2.2, 3.3])



```python
print(data[5:10,  0.10])
```


```python
import numpy 
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
print (numpy.mean(data))
```

    [0 1 2 3 4 5]
    [[0 1 2]
     [3 4 5]
     [6 7 8]]
    [[[ 0  1  2  3]
      [ 4  5  6  7]
      [ 8  9 10 11]]
    
     [[12 13 14 15]
      [16 17 18 19]
      [20 21 22 23]]]



```python
print(stdval)
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
maxval = numpy.amax(data)
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
print(small)
```

    array('i', [1, 2, 3, 4, 5])
    array('d', [1.1, 2.2, 3.3])



```python
print(data[5:10, 0:10])
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
small = data[:3, 36:]
```


```python
numpy.loadtxt(fname = 'inflammation-02. csv', delimter = ',')
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
maxval,minval, stdval = numpy.amax(data), numpy.std(data)
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
print(maxval)
```


```python
numpy.loadtxt(fname='inflammation-01.csv', delimiter=',')
```


```python
maxval = numpy.amax(data)
minval = numpy.amin(data)
```

    [1 2 3 4 5]
    [[1 2 3]
     [4 5 6]]
    [[0. 0. 0. 0.]
     [0. 0. 0. 0.]
     [0. 0. 0. 0.]]
    [[1. 1.]
     [1. 1.]]
    [0 1 2 3 4 5 6 7 8 9]



```python
print('maximum inflammation for patiend 2:', numpy.amax(data[2,:11]))
```


```python
print(numpy.mean(data, axis = 1))
```


```python
import numpy
```

    [2. 5. 8.]



```python
import numpy
```




    array([1.5, 3.5])




## Transcribing Dna into Rna



```
```python
from Bio.SeqRecord import SeqRecord
```


```python
from Bio.SeqRecord import Seq
```


```python
simple_seq = Seq("GATC")
```


```python
simple_seq_r = SeqRecord (simple_sec)
```


```python
simple_seq_r
```


```python
simple_seq_r.id = "AC12345"
```


```python
simple_seq_r. discription = "Made up sequence for the VDB Computational Biology Class"
```


```python
print(simple_seq_r. annotations["evidence"])
```


```python
#http://raw.githubusercontent.com/biopython/bipython/master/Tests/GenBank/NC_005816.fna
```


```python
from Bio import SeqI0
```


```python
record.seq
```

    AUGCGUAGCUAGCAUGC



```python
record.id
```


## Using Loops

```python
odds = [1,3,5,7]
```


```python
print(odds[0])
print(odds[1])
print(odds[2])
print(odds[3])
```


```python
 my_list = [1, 2, 3, 4, 5]
```

    2
    4
    6
    8
    10



```python
odds = [1,3,5,7]

for num in odds:
    print(num)
```

    0
    1
    2
    3
    4



```python
odds = [1,3,5,7,9,11,13,15,17,19]
for num in odds :
    print(num)
```

    0
    1
    2
    3
    4
    1
    3
    5
    7
    9



```python
length = 0
names = [Curie', 'Darwin', 'Turing']
for values in names:
         length = length + 1
print ('There are', length, names in the list.'')
```


```python
print(len([0,1,2,3]))
```

    1



## Making Choices
```python
odds = [1,3,5,7]
```


```python
print(odds[0])
print(odds[1])
print(odds[2])
print(odds[3])
```


```python
 my_list = [1, 2, 3, 4, 5]
```

    2
    4
    6
    8
    10



```python
odds = [1,3,5,7]

for num in odds:
    print(num)
```

    0
    1
    2
    3
    4



```python
odds = [1,3,5,7,9,11,13,15,17,19]
for num in odds :
    print(num)
```

    0
    1
    2
    3
    4
    1
    3
    5
    7
    9



```python
length = 0
names = [Curie', 'Darwin', 'Turing']
for values in names:
         length = length + 1
print ('There are', length, names in the list.'')
```


```python
print(len([0,1,2,3]))
```

    1



```python
num = 37
if num > 100:
    print ('greater')
else:
    print('not greater')
print('done')
```


```python
num = 53
print('before conditional...)
if num > 100
      print(num, ' is greater than 100')
print('...after conditional')
```


```python
num = 14

if num > 0
elif num == 0
print(num, 'is zero')
else:
    print(num, 'is negative')
```


```python
if (1 > 0)or (-1 >= 0):
    print ('at least one part is false')
```


```python
if (1 > 0)and (-1 >= 0):
    print ('at least one part is false')
else
  print ('at least one part is true')
```


## Defensive programming
print(odds[0])
print(odds[1])
print(odds[2])
print(odds[3])
```


```python
numbers = [1,5,2,3]0.7, 0.001, 4.4]
```


```python

```


```python
 my_list = [1, 2, 3, 4, 5]
```

    2
    4
    6
    8
    10



```python
odds = [1,3,5,7]

for num in odds:
    print(num)
```

    0
    1
    2
    3
    4



```python
odds = [1,3,5,7,9,11,13,15,17,19]
for num in odds :
    print(num)
```

    0
    1
    2
    3
    4
    1
    3
    5
    7
    9



```python
length = 0
names = [Curie', 'Darwin', 'Turing']
for values in names:
         length = length + 1
print ('There are', length, names in the list.'')
```


```python
print(len([0,1,2,3]))
```

    1



```python
num = 37
if num > 100:
    print ('greater')
else:
    print('not greater')
print('done')
```


```python
num = 53
print('before conditional...)
if num > 100
      print(num, ' is greater than 100')
print('...after conditional')
```


```python
num = 14

if num > 0
elif num == 0
print(num, 'is zero')
else:
    print(num, 'is negative')
```


```python
if (1 > 0)or (-1 >= 0):
    print ('at least one part is false')
```


## Transribing RNA TO PROTEIN
```python
# prompt the user to enter the input file name

input_file_name = ('Enter the name of the input fasta file: '')
```


```python
#open the input fasta file and read the DNA sequence
with open (input_file_name, 'r')
for line input_file:
    if line.start
    continue
    dna_sequence + line.strip
```


```python
#Transcribe the DNA to RNA
rna_sequence 
for nucleotide in dna sequence

```


```python
#Prompt the user to enter the output file name
out_file_name = input (enter the name of the output file: "")
```


```python
Save teh Rna sequene to a texr file
with open (output_file_name, "w")as output_file
print(ThERna sequence has been save to (output_file_name))
```


```python
from Bio.Seq import Seq

##Function 1,2,3,4
```python
farenheit_val =99
celsius_val= ((farenheit_val - 32) 
print(celsius_val)
```


```python
farenheit_val2m+43
celsius_cal2 = ((farenheit_val2)
print (celsius_cal )
```


```python
def explicit_fahr_to_celsius (temp):
    #Assign the converted value to a variable
    converted = ((temp-32))
```


```python
def fahr_to_kelvin(temp_f):
    temp_c= fahr_to_celsius(temp_f)
    return temp_k
print('boiling popint of water in kelvin:', fahr_to_kelvin)
```


```python
print('Again, temperature in kevlvin')
```python
def visualize (file name):
    data = numpy.loadtxt(fname =file name, delimiter ='.'
    fig = matplot.lib.figure (figsize =(10.0,3.0))
    axes1 = fig.add_subplot                     
```







