

## Sheriff Adeoti
<br>
<span style="color:#536DFE">Summary</span>
<br>
<span style="color:#536DFE">On</span>
<br>
<span style="color:#304FFE">Andela Homestudy Curriculum</span>

---

### Module 1
<br>
<span style="color:#FFFF00">Computer Science</span>
<br>
Computer science is the study of problems, problem-solving, and the solutions that come out of the problem-solving process. 

<br>
A computer scientist’s goal is to develop an algorithm, a stepby-
step list of instructions for solving any instance of the problem that might arise.

---


### Module 2
<br>
<span style="color:#FFFF00">Programming</span>
<br>
Programming is the process of taking an algorithm and encoding it into a notation, a programming language, so that it can be executed by a computer.

<br>
Although many programming languages and many different types of computers exist, the important first step is the need to have the solution. Without an algorithm there can be no program.

---

#### Loops
Repeats a statement or group of statements while a given condition is TRUE.

```python
for i in 2, 4, 6, 8
print (i)
```
---
#### Variable

<br>
variable can be used to manipulate values inside code.

```python
total = 0
for i in 1, 3, 7:
total = total + i
print(total)
```
<br>
---

#### Challenge

<br>
Make a one line Python statement that uses both sum and range to print the sum of the numbers 1
through 10?
<br>

```python
print sum (range (1,10))
```
<br>
---

#### Functions
<br>
```python
def say_hello_to(name):
	print("Hello " + name)
say_hello_to("Tyron")
say_hello_to("Sara")
```
---
#### Conditional
<br>
```python
angle = 5
if angle > 0:
print("Turning clockwise")
elif angle < 0:
print("Turning anticlockwise")
else:
print("Not turning at all")
```
---
#### Module 3
<span style="color:#FFFF00">Object Oriented Programming</span>

<br>
Object-oriented programming (OOP) is a programming language model organized around objects rather than "actions" and data rather than logic. Historically, a program has been viewed as a logical procedure that takes input data, processes it, and produces output data.

---
#class

contains properties and methods
```python
class pet()
	number_of_legs = 0
	
	def sleep(self):
		print "zzzzzzzzzzzzzzzzzzz"
		
	def count_legs(self):
		print "I have %s Legs " % self.number_of_legs
doug = pet()
doug.sleep()
doug.number_of_legs = 4
nemo = pet()
nemo.number_of_legs = 0
nemo.count_legs()
```

