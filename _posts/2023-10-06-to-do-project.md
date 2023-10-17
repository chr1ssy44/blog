**Python Experiences**

We started learning *Python* this month. We were firsted introduced to the *basic syntax* 🔡 of Python. We started making a todo application. Our application had to be able to add ➕ and remove 🚮 an item from the todo list. I started by creating a variable *todos* for my list of todos, 
```
todos = ["do homework", "eat", "go to sleep"]. 
```
Then, I printed out the current todos in the list. I saw a problem 😪 at first when the list would print the console with the brackets and the quotations. So, I searched up how to print the list with the brackets and I had to 
```
 print(", ".join(todos))
```
**So that problem was fixed!🤭** I set variable x as the first input for the user to answer.
```
x = input("Would you like to add or remove a todo? ") 
```
Then, I started of with an **if statement**, I made **x equal "add"** as an *'string'* so if the user types the word *add* they will be able to add a todo.
```
if x == "add"
```
I continued my code with an second input for th user to add any todo they would like and they todo will be added to the end of the list. Then I realized the code was all jambbled up in the console 𝍂 to I began to separate my code so the user 👱🏽‍♀️ will have an **better experience**. I did that by printing a long *line of dashes* and also printing an *empty string*.
```
print("-------------------------------------------------")
```
```
print("")
```
Once the todo was added to the end of the list I moved on to letting the user be able to remove a todo.🙃 Once again I used an if statement to **if x equals "remove" as a string**. One problem that occured when doing this is be able to let the index of the items in the list start from *1 instead of 0*. The user wouldn't know🤦🏽 that the index starts at 0 so I had to change that. I searched up a way to do that and came across the use of **range()**. 

range
:The *range()* function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

I realized after a few attempts that **range** wouldn't be a good element for this process. 

So I had asked my elbow partner for some help. They explained how to be ablt to start the index at 1 instead of 0.
```
if x == "remove":
        z = int(input("Which # todo would you like to remove? "))
        z -= 1
        del todos[z]
```
This allowed the user to have a much *easier experience* with the application now that I fixed the problem.


