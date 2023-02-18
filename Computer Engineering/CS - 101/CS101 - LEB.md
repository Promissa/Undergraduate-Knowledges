## File Operation
#### Open / Close
```Python
# Open the file
myFile = open('sample.txt', <operationType>)
# Close the file
myFile.close()
```
#### Read
```Python
# Open File
myFile = open('sample.in', 'r')
# Read the whole file, jump to the last line
tmp = myFile.read()
# Read the whole file, return the lines to a list
tmp = myFile.readlines()
# Close File
myFile.close()
```
#### Write
```Python
# Open File
myFile = open('sample.out', 'w')
# Write
myFile.write('Hello, this is a test')
# Close File
myFile.close()
```
#### File Path
```Python
# Open File
myFile = open('sample.txt', 'r')
```
## String Methods
`.split()`: Accepts a `str` to split y and returns a `list` of string
`.join()`: Accepts a `list` of string and returns a `str`
## Loop Aids
`zip`: iterates two lists at the same time
`enumerate`: put both the value and the index during iteration
```Python
# Use zip inside for loop
for (q, a) in zip(qs, ps):
	print('What is your %s? It is %s.' %(q, a))
# Use enumerate inside a for loop
for (i, item) in enumerate(my_list):
	print('%s is the $s index item.' %(item, i))
# Use zip without a loop
```
