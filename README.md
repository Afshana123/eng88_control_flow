# Control Flow
### Control flow is very important in any programming language to control the flow of your conditions and decisions 

- if elif and else conditions

Control flow with if, elif and else - loops
We use elif or else if we have multiple conditions

``` python
weather = "rainy"

if weather == "thinking":
   print("Enjoy the weather ") # If true, this line will be executed
else:
   print ("Opps sorry, something went wrong. Please try later") # If false, this line will be executed
```
add a condition to use elif when the condition is False

``` python
if weather == "sunny":
    print("Enjoy the weather!") # If true, this line will be executed
elif weather == 'rainy':
    print("Remember to take an umbrella!")
else:
    print ("Opps sorry, something went wrong. Please try again later") # If false, this line will be executed
```





Loops are used to iterate through data
Lists, Dictonaries, Sets

``` python
list_data = [1, 2, 3, 4, 5]
print(list_data)
for list in list_data:
    print(list)
```
go and look for the list from the list data - iterate thorugh the list until the last number

``` pyhton
list_data = [1, 2, 3, 4, 5]

for list in list_data:
    if list == 3:
        break
    print(list)
``` 

```python

list_data = [1, 2, 3, 4, 5]

for list in list_data:
   if list == 3:
       print("Now I found 3")
   if list == 2:
       print("I found 2")
   if list == 5:
       print("This is the last number and I found it as well - 5")
else:
   print("Better luck next time")
````

after the condition is met, then it stops running the system

Second Interation
```python

student_1 = {
    "Name" : "Afshana",
#   "Key"  : "Value"
    "Stream" : "Cyber Security",
    "Completed_Lessons" : 3,
    "Complete_Lessons" : ["Variables", "Operators", "Data_Collections"] # List
}

for data in student_1.values():
    if data == "Cyber Security":
        break
    print(data)
```
### While Loops
```python
user_prompt = True
while user_prompt:
    age = input("Please enter your age: ")
    if age.isdigit():
        user_prompt = False # gives output 
    else:
        print("Please provide your answer in digits: ")
print(f"Your age is {age}")
```
