# Python-Practice
# Python Practice Solved Programs
# Step By Step Solved Activities of different concepts
```python
# Activity 1
No1 = int(input("Enter 1st number:"))
No2 = int(input("Enter 2nd number:"))
sum = No1 + No2
print(sum)
 
# Activity 2
# formula to calculate side is side * side
Side = int(input("Enter squre side:"))
Side **= 2
print(Side)
 
# Activity 3
Num1 = float(input("enter 1st value: "))
Num2 = float(input("Enter 2nd value: "))
Avg = (Num1 + Num2) / 2
print(Avg)
 
# Activity 4
a = int(input("enter 1st value: "))
b = int(input("Enter 2nd value: "))
print(a >= b)
 
# Activity 5
Q1 = input("plz enter your name : ")
print(Q1)
length = print("length is : ", len(Q1))
 
# Activity 6
str = "us currency is $"
print(str.find("$"))
print(str.count("$"))
 
# Activity 7
Marks = int(input("enter your marks : "))
print(Marks)
if (Marks >= 90):
    print("Grade= A")
elif (Marks >= 80 and Marks < 90):
    print("grade = B")
elif (Marks >= 70 and Marks < 80):
    print("grade = C")
else:
    print("do hard work")
 
# Activity 8
Num1 = int(input("enter number : "))
if (Num1 % 2 == 0):
    print("Number is even")
else:
    print("Number is odd")
 
# Activity 9
a = int(input("Enter 1st number : "))
b = int(input("Enter 2nd number : "))
c = int(input("Enter 3rd number : "))
if (a >= b and a >= c):
    print("a is greatest", a)
elif (b >= c):
    print("b is largest", b)
else:
    print("C is largest", c)
 
# Activity 10
x = int(input("Enter number : "))
if (x % 7 == 0):
    print("it is multiple of 7")
else:
    print("it is not multiple")
 
# Activity 11
a = int(input("Enter 1st number : "))
b = int(input("Enter 2nd number : "))
c = int(input("Enter 3rd number : "))
d = int(input("Enter 4th number : "))
if (a >= b and a >= c and a >= d):
    print("a is greatest", a)
elif (b >= c and b >= d):
    print("b is largest", b)
elif (c >= d):
    print("C is largest : ", c)
else:
    print("d is largest : ", d)
 
# Activity 12
a = int(input("Enter first number : "))
b = int(input("Enter second number : "))
print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a ** b)
 
# Activity 13
a = int(input("Enter first number : "))
print(a * a)
print(a * 4)
 
# Activity 14
a = int(input("enter 1st number: "))
b = int(input("enter 2nd number: "))
if (a == b):
    print("Both are equal")
elif (a > b):
    print("A is greater than b")
else:
    print("b is greater")
 
# Activity 15
a = int(input("enter your marks : "))
if (a > 40):
    print("marks are greater than 40")
else:
    print("MArks are less")
 
# Activity 15
a = 20
a += 10
print(a)
a -= 5
print(a)
a *= 2
print(a)
a /= 5
print(a)
a %= 3
print(a)
 
# Activity 16
a = int(input("enter 1st number : "))
b = int(input("enter 2nd number : "))
if (a > 0 or b > 0):
    print(" one of them is positive")
else:
    print("Both are negative")
 
# Activity 17
a = "25"
a = int("25")
print(a * 4)
 
# Activity 18
a = input("plz enter your age : ")
a = int(a)
a += 5
print(a)
 
# Activity 18
Name = input("Enter your name ")
Age = int(input("Enter your age "))
City = input("Enter your City ")
print("My name is ", Name)
print("I am ", Age, " years old")
print("I live in", City)
 
# Activity 19
N1 = input("Enter First name ")
N2 = input("Enter Second name ")
print(N1 + ' ' + N2)
 
# Activity 20
a = input("Enter your Sentence ")
length = len(a)
print(length)
 
# Activity 20
a = "Abdul Wahid"
print("your name contains", len(a), "characters")
 
# Activity 21
a = "Comsats"
print(a[0])
print(a[4])
print(a[6])
 
# Activity 22
a = "Abdul Wahid"
print(a[:3], a[8:])
 
# Activity 23
a = "islamabad is capital of Pakistan"
b = a.capitalize()
print(b)
b = a.find("Pakistan")
print(b)
b = a.count("a")
print(b)
b = a.replace("islamabad", "Karachi")
print(b)
 
# Activity 24
mail = "aw3949@gmail.com"
print(mail.endswith(".com"))
 
# Activity 25
a = input("enter word ")
b = input("enter other word ")
length1 = len(a)
length2 = len(b)
if (length1 > length2):
    print("a is longer ")
else:
    print("b is long")
 
# Activity 26
a = input("enter password ")
b = len(a)
if (b < 8):
    print("weak passowrd")
else:
    print("strong password")
 
# Activity 27
a = input("Enter file name")
b = a.endswith(".pdf")
if (b == True):
    print("File is correct")
else:
    print("file is corrupt")
 
# Activity 28
a = input("enter email addresss : ")
b = len(a)
print(b)
c = a.endswith(".com")
print(c)
if (b >= 10 and c):
    print("Valid Email")
else:
    print("Invalid Email")
 
# Activity 29
Movie1 = input("Enter 1 movie Name : ")
Movie2 = input("Enter 2 movie Name : ")
Movie3 = input("Enter 3 movie Name : ")
lis = [Movie1, Movie2, Movie3]
print(lis)
 
# Activity 30
Pali = [1, 2, 3, 2, 1]
Pai = Pali.copy()
Pai.reverse()
if (Pali == Pai):
    print("It is palindrome")
else:
    print("Not palindrome")
 
# Activity 30
Grade = ["C", "D", "A", "A", "B", "B", "A"]
print(Grade.count("A"))
Grade.sort()
print(Grade)
 
# Activity 31
Fruits = ["Mango", "Apple", "Banana", "Strawberry"]
print(Fruits)
print(Fruits[0:3])
Fruits[1] = ("Melon")
print(Fruits)
 
# Activity 32
Marks = [56, 89, 34, 90]
Marks.append(75)
print(Marks)
 
# Activity 33
Marks = [67, 45, 98, 23, 89]
Marks.sort()
print(Marks)
Marks.sort(reverse=True)
print(Marks)
 
# Activity 34
Numbers = [10, 20, 40, 50]
Numbers.insert(2, 30)
print(Numbers)
 
# Activity 35
Colors = ["Red", "Blue", "Green", "Black"]
Colors.remove("Green")
print(Colors)
 
# Activity 36
Student = ["Abdul", 20, 89.5, "Computer Science"]
Student[3] = "Software Engineering"
print(Student)
 
# Activity 37
tup = (1, 2, 1, 4, 5, 1, 7)
print(tup.count(1))
 
# Activity 38
tup = (10, 20, 30, 40, 50)
print(tup.index(40))
 
# Activity 39
sub = ("Maths", "Urdu", "English", "Islamiat")
print(sub[3])
 
# Activity 40
Grades = ["C", "D", "A", "A", "B", "B", "A"]
count = Grades.count("A")
print(count)
Grades.sort()
print(Grades)

# Activity 41 :
 Movie1=input("Enter 1st Movie : ")
 Movie2=input("Enter 2nd Movie : ")
 Movie3=input("Enter 3rd Movie : ")
 Movies = [Movie1,Movie2,Movie3]
 print(Movies)
 Movies.sort()
 print(Movies)
 Movies.sort(reverse=True)
 print(Movies)
 Movies.remove(Movie2)
 print(Movies)
 Movies.insert(1,"Spiderman")
 print(Movies)

# Activity 41 :
 list1 = [1, 2, 3, 2, 1]
 list2 = list1
 list2.reverse()
 if(list2==list1):
     print("It is palindrome")
 else:
    print("No")

# Activity 42 :
Random ={
     "table" : ["a piece of furniture", "list of facts and figures"],
     "cat" : "a small animal"
 }
 print(Random)

# Activity 43 :
 Class={"python","java","C++","python","Javascript","java","python","java","C++","C"}
print(Class)

# Activity 44 :
 Marks={}
 Chemistry = input("Enter chemistry marks ")
 Physics = input("enter physics marks ")
 DataBase = input("enter DB marks ")
 Marks.update({"Chemistry": Chemistry})
 Marks.update({"Physics" : Physics})
 Marks.update({"DataBase" : DataBase })
 print(Marks)

# Activity 45 :
 num = set()
 num1= int(input("Enter 1st value "))
 num2= input("Enter 2nd value ")
 num.add(num1)
 num.add(num2)
 print(num)

# Activity 46 :
 Num1 = int(input("Enter 1st Number "))
 Num2 = int(input("Enter 2nd Number "))
 print(Num1+Num2)
 print(Num1*Num2)
 print(Num1/Num2)
 if (Num1 > Num2):
     print("Number 1 is greater")
 else:
     print("Number 2 is greater")

# Activity 47 :
 Sentence= input("Enter your sentence")
 print(len(Sentence))
 print(Sentence.endswith("."))
 print(Sentence.count("a"))
 
 # Activity 48 :
 Movie1= input("Enter 1st movie ")
 Movie2= input("Enter 2nd movie ")
 Movie3= input("Enter 3rd movie ")
 Movie=[Movie1,Movie2,Movie3]
 print(Movie)
 Movie.sort()
 print(Movie)
 Movie.sort(reverse=True)
 print(Movie)
 Movie.remove(Movie2)
 print(Movie)
 Movie.insert(1,"SpiderMan")
 print(Movie)

# Activity 49 :
 tup = (1, 2, 3, 4, 1, 5, 1)
 print(tup.count(1))
 print(tup[4])

# Activity 50 :
 Create = {
     "Name" : "Umar",
     "Age" : 20,
     "Semester" : "3rd",
     }
 print(Create)
 Create.update({"City" : "Attock"})
 print(Create)
 Create.update({"Age" : 29})
 print(Create)
 print(Create.keys())
 print(Create.values())
 print(Create.items())
 print(len(Create))

# Activity 51 :
 Student = {
    "Name": "Random",
     "Subjects": {
         "DB": 32,
         "CN": 23,
         "Calculus": 45
    }
 }
 print(Student)
 print(Student["Subjects"] ["Calculus"])

 # Activity 52 :
set1 = {1,2,3,4,5}
set2 = {3,4,5,6,7}
print(set1.union(set2))
print(set2.intersection(set2))
set1.add(8)
print(set1)
set2.remove(7)
print(set2)

# Activity 53 :
Email = input("Enter your Email : ")
end= Email.endswith(".com")
length = len(Email)
if(len(Email) > 10 and end):
     print("Valid Email")
else:
    print("Invalid Email")
dic={}
dic.update({"Email" : Email})
dic.update({"Length" : length })
print(dic)

# Activty 54 :
for x in range(100,0,-1):
     print(x)

# Activity 55 :
n=int(input("Enter a number : "))
 for x in range(1,11):
    print(n*x)

# Activity 56 :
x = int(input("Enter a number: "))
i = 1
total = 0
while i <= x:
     total = total + i
     i += 1
print("Sum =", total)

# Activity 57 :
n=int(input("Enter a number : "))
sum=0
for i in range(0,n+1):
    sum+=i
print("Sum is : ",sum)

# Activity 58 : 
n = int(input("Enter a number : "))
fact = 1
for i in range (1,n+1):
     fact*=i
print("Factotial is ", fact)

# Activity 59 :
 while True:
     x=int(input("Enter number : "))
     if(x==0):
         print("Program Ended")
         break


# Activity 60 :
x = 1
while x <= 20:
     if x % 3 != 0:
         print(x)
     x = x + 1

# Activity 61 :
x=int(input("Enter 1st number : "))
y=int(input("Enter 2nd Number : "))
print(x+y)
print(x-y)
print(x*y)
print(x%y)
if (x>y):
     print("1st is greater ")
else:
     print("2nd is greater")

# Activity 62 :
Name = input("Enter a name : ")
print(len(Name))
print(Name.capitalize())
x=Name.endswith("n")
print(x)
print(Name[2:6])

# Activity 63 :
x=input("Enter 1st number : ")
y=input("Enter 2nd number : ")
x=int(x)
y=int(y)
print(x*y)

# Activity 64 :
x= int(input("Enter marks : "))
if (x>=90 and x<=100):
    print("A grade")
elif(x>=80 and x<=90):
    print("B grade")
elif(x>=70 and x<=80):
    print("C grade ")
elif(x<70):
    print("D grade.")

# Activity 65 :
L=[9,78,94,25,45]
print(L)
L.append(99)
print(L)
L.insert(2,50)
print(L)
L.pop(1)
print(L)
L.sort()
print(L)

# Activity 66:
Dict= {
     "Name" : "Wahid",
     "Age"  : 21,
     "Semester" : 3,
     "City" : "Attock"
 }
Dict.update({"City" : "Lahore"})
print(Dict)
Dict.update({"Grade" : "A"})
print(Dict)
print(Dict.keys())
print(Dict.values())

# Activity 67 :
T=(3, 7, 3, 9, 3, 1, 7)
print(T.count(3))
print(T[5])
set1={1,2,3,4,5}
set2={3,4,5,6,7}
print(set1.union(set2))
print(set1.intersection(set2))

# Activity 68 :
Stud = [45,55,65,75,85]
Sum = 0
for stu in Stud:
     print(stu)
     Sum+=stu
print(Sum)
L = len(Stud)
print("Number of students marks : ",L)
Average = Sum/ L
print(Average)

# Activity 69 :
Sent = input("Enter a Sentence: ")
idx = 0
while idx < len(Sent):
     if Sent[idx] == " ":
         idx += 1
         continue
    if Sent[idx] == "z":
         print("Letter z found")
         break
     print(Sent[idx])
     idx += 1

#Activity 70 :
Dict = [
    {"Name": "Ali", "Marks": 32, "Subject": "Physics"},
    {"Name": "Ibrahim", "Marks": 54, "Subject": "Chemistry"},
    {"Name": "Moosa", "Marks": 80, "Subject": "Biology"},
    {"Name": "Daniyal", "Marks": 60, "Subject": "Maths"},
]
top_performers = []
for student in Dict:
    print(student["Name"], "-", student["Subject"])
    if student["Marks"] >= 80:
        print("Excellent")
        top_performers.append(student["Name"])
    elif student["Marks"] >= 50:
        print("Passed")
    else:
        print("Failed")
print("Top Performers:", top_performers)

# Activity 71 :
def calc_avg (a,b,c):
sum=a+b+c
avg=sum/3
print(avg)
return(avg)
calc_avg(2,3,4)

# Activity 72 :
numbs = [1,2,3,4,5,6,]
def print_len(list):
    print(len(list))
print_len(numbs)

# Activity 73 :
Elements = ["a", "b", "c", "d", "e"]
def print_len(list):
    for item in list:
         print(item,end=" ")
print_len(Elements)

# Activity 74 :
def py():
    print("Hello . Wellcome to pyhton")
py()

# Activity 75 :
 def sq(a):
     print(a*a)
sq(5)

# Activity 76 :
a=int(input("Enter a number : "))
def cat(a):
    if(a%2 ==0):
    print("Even")
    else:
        print("odd")
cat(a)

# Activity 77 :
x = int(input("Enter x : "))
y = int(input("Enter y :"))
def large(x,y):
    if (x > y):
    print("X is greater")
    else:
    print("Y is greater")
large(x,y)


# Activity 78 :
Marks = [45, 55, 65, 75]
def add(numbers):
     total = 0
    for num in numbers:
         total += num
     return total
result = add(Marks)
print("Sum =", result)

# Activity 79 :
Marks = [5,6,7,8,9,10]
def t(numbers):
     total = 0
     for num in numbers:
         total += num
     Average = total / len(numbers)
     return total, Average
print(t(Marks))


# Activity 80 :
Students = []
while True:
    print (""" ---Student Menu---
    1. Add Student
    2. View Students
    3. Search Student
    4. Calculate Average Marks
    5. Show Topper
    6. Exit""")
    x= input("Enter your choice : ")
    if(x == "1"):
     Name =input("Enter Student Name : ")
     Age =int(input("Enter Age : "))
     Marks =int(input("Enter Marks : "))
     Stu= {
     "Name" : Name,
     "Age" : Age,
     "Marks": Marks 
}
     Students.append(Stu)
    elif (x=="2"):
       for s in Students:
        print("Name:", s["Name"])
        print("Age:", s["Age"])
        print("Marks:", s["Marks"])
    elif(x=="3"):
       y=input("Enter Student Name to search : ")
       found = False
       for s in Students:
        if s["Name"] == y:
         print("Student Found")
         print("Name:", s["Name"])
         print("Age:", s["Age"])
         print("Marks:", s["Marks"])
         found = True
       if found == False:
         print("Student not found")
    elif(x=="4"):
        if not Students:
            print("No Students added yet")
        else:
            Total = 0
            for m in Students:
                Total = Total + m["Marks"]
            Average = Total / len(Students)
            print("Average Marks are : ", Average)
    elif(x=="5"):
        if not Students:
            print("No Students added yet")
        else:
            Topper = Students[0]
            for t in Students:
                if t["Marks"] > Topper["Marks"]:
                    Topper = t
            print("Topper is : ", Topper["Name"])
            print("Age:", Topper["Age"])
            print("Marks:", Topper["Marks"])
    elif(x=="6"):
       print("Exiting")
       break

# Activity 81 :
St1 = input("Enter Student Name : ")
Sub1 = int(input("Enter 1st subject marks : "))
if (Sub1 <0 or Sub1>100):
    print("Invalud marks")
Sub2 = int(input("Enter 2nd subject marks : "))
if (Sub2 <0 or Sub2>100):
    print("Invalud marks")
Sub3 = int(input("Enter 3rd subject marks : "))
if (Sub3 <0 or Sub3>100):
    print("Invalud marks")
Sub4 = int(input("Enter 4th subject marks : "))
if (Sub4 <0 or Sub4>100):
    print("Invalud marks")
Sub5 = int(input("Enter 5th subject marks : "))
if (Sub5 <0 or Sub5>100):
    print("Invalud marks")
Subjects = {
    "Name" : St1,
    "Subject 1": Sub1,
    "Subject 2": Sub2,
    "Subject 3": Sub3,
    "Subject 4": Sub4,
    "Subject 5": Sub5
}
print(Subjects)
Total = Sub1 + Sub2+ Sub3+Sub4 +Sub5
print("Total Marks are : ", Total) 
Percentage = Total /500 *100
print("Percentage is ",Percentage )
if (Percentage >= 90):
    print("A grade")
elif(Percentage>=80 and Percentage <90 ):
    print("B Grade")
elif(Percentage>=70 and Percentage<80):
    print("C Grade")
else:
    print("D grade") 

# Activity 82:
Name = input("Enter Username: ")
Pass = input("Enter Password: ")

if len(Name) >= 5 and " " not in Name:
    print("Username Entered")
else:
    print("Enter Again")
    exit()

if len(Pass) >= 8 and ("@" in Pass or "#" in Pass):
    print("Password Entered")
else:
    print("Enter Password Again")
    exit()

Info = {
    "UserName": Name,
    "Password": Pass
}

print(Info)     

# Activity 83 :
Prod1 = input("Enter Product Name: ")
Price1 = int(input("Enter Product Price: "))
Prod2 = input("Enter Product Name: ")
Price2 = int(input("Enter Product Price: "))
Prod3 = input("Enter Product Name: ")
Price3 = int(input("Enter Product Price: "))
info = {
    Prod1: Price1,
    Prod2: Price2,
    Prod3: Price3
}
print("Products:", info)
Waste = input("Enter product to remove: ")
if Waste in info:
    info.pop(Waste)
    print("Product removed.")
else:
    print("Product not found.")
print("After removing:", info)
NewProd = input("Enter new Product name: ")
Price4 = int(input("Enter product price: "))
info[NewProd] = Price4
print("Final Products:", info)

# Activity 84 :
Num = [] 
n1 = int(input("Enter 1st number: ")) 
n2 = int(input("Enter 2nd number: ")) 
n3 = int(input("Enter 3rd number: ")) 
n4 = int(input("Enter 4th number: ")) 
n5 = int(input("Enter 5th number: ")) 
n6 = int(input("Enter 6th number: ")) 
n7 = int(input("Enter 7th number: ")) 
n8 = int(input("Enter 8th number: ")) 
Num = [n1, n2, n3, n4, n5, n6, n7, n8] 
print(Num) 
unique=set(Num) 
print(unique) 
print(max(Num)) 
print(min(Num)) 
print(sum(Num)) 
print(sum(Num)/len(Num))

# Activity 85 :
Stud1 = {"Maths", "Physics" ,"Urdu", "English","Maths"}
Stud1.add("Islamiat")
Stud2={"Bio","Chem","Maths","Urdu","DB"}
print(Stud1.intersection(Stud2))
print(Stud1)
print(Stud1-Stud2)

# Activity 86 :
Line = input("Enter a sentence : ")
print(len(Line))
words=Line.split()
print(len(words))
print(Line.count("a"))
print(Line.upper())
print(Line[0])
print(Line[-1])
print(Line[::-1])# Activity 86 :
Line = input("Enter a sentence : ")
print(len(Line))
words=Line.split()
print(len(words))
print(Line.count("a"))
print(Line.upper())
print(Line[0])
print(Line[-1])
print(Line[::-1])

# Activity 87 :
employees = {
     "Ali": {"age": 22, "salary": 50000},
     "Ahmed": {"age": 25, "salary": 65000},
     "Usman": {"age": 21, "salary": 45000}
}
user = input("Enter Employee name : ")
if user in employees:
    print("Employee info is ",employees[user])
else:
    print("Employee doesnt exist")# Activity 87 :
employees = {
     "Ali": {"age": 22, "salary": 50000},
     "Ahmed": {"age": 25, "salary": 65000},
     "Usman": {"age": 21, "salary": 45000}
}
user = input("Enter Employee name : ")
if user in employees:
    print("Employee info is ",employees[user])
else:
    print("Employee doesnt exist")

# Activity 88 :
Ali = (23,34,78,56,90,56)
Umar =(45,67,87,65,43,24)
Sum1 = sum(Ali)
print(Sum1) 
Sum2=sum(Umar)
print(Sum2)
Avg1 =Sum1/len(Ali)
print(Avg1)
Avg2 = Sum2/len(Umar)
print(Avg2)
if (Sum1 > Sum2):
  print("Ali has highest marks")
else:
    print("Umar has highest marks")
print(Ali.count(90))
print(Umar.count(43))# Activity 88 :
Ali = (23,34,78,56,90,56)
Umar =(45,67,87,65,43,24)
Sum1 = sum(Ali)
print(Sum1) 
Sum2=sum(Umar)
print(Sum2)
Avg1 =Sum1/len(Ali)
print(Avg1)
Avg2 = Sum2/len(Umar)
print(Avg2)
if (Sum1 > Sum2):
  print("Ali has highest marks")
else:
    print("Umar has highest marks")
print(Ali.count(90))
print(Umar.count(43))

# Activity 89 :
def q():
    n=int (input("Enter a number :"))
    if n%2==0:
        print("Number is even")
    else:
        print("num is odd")  
q()

# Activity 90 :
def add(n):
    if n == 0:
       return 0
    else:
        return n + add(n-1)
sum =add(5)
print(sum)# Activity 90 :
def add(n):
    if n == 0:
       return 0
    else:
        return n + add(n-1)
sum =add(5)
print(sum)

# Activity 91 :
L=["Ironman","Superman","Batman","Joker"]
def elements(list, idx=0):
    if (idx == len(list)):
        return
    else:
        print(list[idx])    
        elements(list,idx+1)  
Heroes = elements(L)
print(Heroes)

# Activity 92:
def is_prime(a):
    for i in range(2,a):
        if a%i==0:
            print("Not a prime number")
            return
    print("Prime number")
p=is_prime(5)

# Activity 93 :
f = open("sample.txt","w")
f.write("Hi everyone")
f.write("\nwe are learning file I/O")
f.write("\nusing Java")
f.write("\nI like programming in Java")

# Activity 94 :
f = open("sample.txt","r")
data = f.read()
new_data=data.replace("Java","Python")
print(new_data)
f = open("sample.txt","w")
f.write(new_data)

# Activity 95 :
f = open("sample.txt","r")
data = f.read()
if(data.find("learning") != -1):
    print("Word Exist")
else:
    print("Not exist")



```