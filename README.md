## **Conditional Statements in Python: `if`, `elif`, and `else`**

#### Here am doing basic question sloving:

**Basic Conditions:**

1. Write a program to check if someone is eligible for a bus pass. If they are below 5 years, the bus pass is free. If they are 60 years or older, 
they get a senior citizen discount. Otherwise, they pay the full price and for women the bus pass is free.

#### code:
```python
age = int(input("Enter your age: "))
gender = str(input("Enter gender: "))

if age >= 60:
    print("Ticket is discounted for senior citizens.")
elif age < 5:
    print("Ticket is free for kids.")
elif age <= 10:
    print("Ticket is half price.")
elif age > 10 and gender.lower() == "male":
print("Ticket is full price.")
else:
    print("Ticket is free for women.")
```
**output:**
```python
Enter your age:  30
Enter gender:  male
Ticket is full price.
```
**2. Meal Time Checker:**
###### Create a program that checks the time of day (24-hour format) and prints whether it's time for breakfast,lunch, or dinner. 
- Breakfast:8 AM 
- Lunch:1 PM 
- Dinner:8 PM
- If none of these times, print "It's not meal time."

#### code:
```python
time = int(input (" enter the time: "))

if time==8:
    print("it is the breakfast time")
elif time==13:
    print ("it is the lunch time")
elif time ==20:
    print ("it is the dinner time")

else:
    print (" it not time for eating.")
```

**output**
```python
enter the time:  20
it is the dinner time
```

**Simple Eligibility Check**:
   - Write a program that checks whether a person is eligible for a library membership. If they are under 18, they get a student membership. If they are 60 or older, they get a senior citizen membership. Otherwise, they get a regular membership.

```python
age= int(input (" enter the age: "))

if age <=18:
     print (" get the students pass")
elif age >=60:
     print ("get the senior citizen pass")
elif age>18:
     print (" get the regular pass")
    
else:
     "try again"
```
**output**
```python
enter the age:  60
get the senior citizen pass
```




