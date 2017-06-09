

## Sheriff Adeoti
<br>
<span style="color:gray">Summary</span>
<br>
<span style="color:gray">on</span>
<br>
<span style="color:gray">Andela Homestudy Curriculum</span>

---

### Module 1
<br>
<span style="color:gray">Computer Science</span>
<br>
Computer science is the study of problems, problem-solving, and the solutions that come out of the problem-solving process. 

<br>
A computer scientist’s goal is to develop an algorithm, a stepby-
step list of instructions for solving any instance of the problem that might arise.

---


### Module 2
<br>
<span style="color:gray; font-size:0.6em;">Programming</span>
<br>
Programming is the process of taking an algorithm and encoding it into a notation, a programming language, so that it can be executed by a computer.

<br>
Although many programming languages and many different types of computers exist, the important first step is the need to have the solution. Without an algorithm there can be no program.

####Loops

```python
for i in 2, 4, 6, 8
print (i)
```
---
####Variable
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

####Challenge
<br>
Make a one line Python statement that uses both sum and range to print the sum of the numbers 1
through 10?
<br>

```python
print sum (range (1,10))
```
<br>
---

####Functions
<br>
```python
def say_hello_to(name):
	print("Hello " + name)
say_hello_to("Miranda")
say_hello_to("Fred")
```
---
####Conditional
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
####Module 3
<span style="color:gray; font-size:0.6em;">Object Oriented Programming</span>
**class**

<br>
Object-oriented programming (OOP) is a programming language model organized around objects rather than "actions" and data rather than logic. Historically, a program has been viewed as a logical procedure that takes input data, processes it, and produces output data.

```python
class pet()
	number_of_legs = 0
	
	def sleep(self):
		print "zzzzzzzzzzzzzzzzzzz"
		
	def count_legs(self):
		print "I have %s Legs " % self.number_of_legs
dog = pet()
dog.sleep()
dog.number_of_legs = 4
fish = pet()
fish.number_of_legs = 0
fish.count_legs()
---

