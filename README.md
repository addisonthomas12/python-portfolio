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
 def fahr_to_kelvin(temp_f):
    temp_c= fahr_to_celsius(temp_f)


(base) student@landingvm:~$ 
(base) student@landingvm:~$ anacoda     jupyter lab .  # Launch in the current directory
anacoda: command not found
(base) student@landingvm:~$     jupyter lab ../notebooks  # Launch with a relative path
[C 14:06:22.636 LabApp] No such file or directory: /home/notebooks
(base) student@landingvm:~$     jupyter lab /Users/username/notebooks/test.ipynb  # Open a specific notebook    jupyter lab .  # Launch in the current directory
[C 14:07:07.062 LabApp] No such file or directory: /Users/username/notebooks/test.ipynb
(base) student@landingvm:~$     jupyter lab ../notebooks  # Launch with a relative path
[C 14:07:07.362 LabApp] No such file or directory: /home/notebooks
(base) student@landingvm:~$     jupyter lab /Users/username/notebooks/test.ipynb  # Open a specific notebook    jupyter lab --dev-mode  # Start in development mode (no extensions)
[C 14:07:17.051 LabApp] No such file or directory: /Users/username/notebooks/test.ipynb
(base) student@landingvm:~$     jupyter lab --core-mode  # Start in core mode (no extensions)    jupyter nbconvert --execute --to html --no-input your-notebook.ipynb  [I 14:08:42.322 LabApp] The port 8888 is already in use, trying another port.
[I 14:08:42.326 LabApp] Running JupyterLab in core mode
[I 14:08:42.327 LabApp] JupyterLab extension loaded from /home/student/anaconda3/lib/python3.7/site-packages/jupyterlab
[I 14:08:42.327 LabApp] JupyterLab application directory is /home/student/anaconda3/lib/python3.7/site-packages/jupyterlab
[I 14:08:42.327 LabApp] Running the core application with no additional extensions or settings
[I 14:08:42.534 LabApp] Loading the assignment_list nbgrader serverextension
[I 14:08:42.535 LabApp] Loading the course_list nbgrader serverextension
[I 14:08:42.537 LabApp] Loading the formgrader nbgrader serverextension
[W 14:08:42.539 LabApp] No nbgrader_config.py file found (rerun with --debug to see where nbgrader is looking)
[I 14:08:42.548 LabApp] Loading the validate_assignment nbgrader serverextension
[I 14:08:42.549 LabApp] Serving notebooks from local directory: /home/student
[I 14:08:42.549 LabApp] The Jupyter Notebook is running at:
[I 14:08:42.549 LabApp] http://localhost:8889/?token=59efae60de455f46ff61ed16b31312fb262521574298bd61
[I 14:08:42.549 LabApp]  or http://127.0.0.1:8889/?token=59efae60de455f46ff61ed16b31312fb262521574298bd61
[I 14:08:42.549 LabApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[W 14:08:42.552 LabApp] No web browser found: could not locate runnable browser.
[C 14:08:42.552 LabApp] 


## Command line programs
5.725
5.925
6.15
6.075
5.75
5.975
6.3
5.9
6.75
6.3
5.9
6.75
5.925
7.225
6.15
5.95
6.275
5.7
6.1
6.825
5.975
6.725
5.7
6.25
6.4
7.05
5.9
(base) student@landingvm:~/Desktop/classroom/myfiles/swc-python/data$ inflammation-01.csv
(base) student@landingvm
18.0
18.0
19.0
18.0
17.0
17.0
17.9
16.0
17.0
18.0
18.0
16.0


```python
# Any python interpreter can be used as a calculator:
3 + 5 * 4
```




    23




## Python Fundamentals


weight_kg = 60
```


```python
print(weight_kg)
```

    60



```python
# Weight0 = valud
# 0weight = invalid
# weight and Weight are different
```


```python
# Types of data
# There are three common types of data
# Integer numbers
# floating point numbers
# Strings
```


```python
# Floating point number
weight_kg = 60.3
```


```python
patient_name = 'Jon Smith'
```


```python
# String comprised of numbers
patient_id = '001'
```


```python
# Use variables in python

weight_lb = 2.2 * weight_kg

print(weight_lb)
```

    132.0



```python
# Lets add a prefix to our patient id

patient_id = 'inflam_' + patient_id

print(patient_id)
```


```python
# we can call a function inside another function

print(type(60.3))

print(type(patient_id))
```

    <class 'float'>





```python

```

    


  

             








