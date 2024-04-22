## Basic Concepts in Programming
Before you start to code, you need to have basic ideas on the following concepts;
+ value
+ variable
+ expression
+ function

### Value
**Value** is any piece of data that is meant to be processed. In computer programming, we can basically have the following types of value, depending on the programming language;
+ numeric
+ string
+ array
+ object

**Numeric** values are number values such as 1, 0.5, -1 etc. numeric values can be integers, which are numbers without decimal point. Numeric values can also be floats, which are numbers with decimal point. Some programming language can have more types of numeric value while others might even have just one.

**String** is a list of characters. Characters here means any symbol, especially those symbols used in written languages. String is usually indicated by double aphostrope or single aphostrope in various programming language. Example of string can be `"Hello Programming Language"`, `'Programming is awesome!"`, etc

**Array** is a collection of values. An array can be a collection of values of different types or a collection of values of same type. Different programming languages use different notations to denot array. Array can be denoted with pair of [], {}, or (). Examples; `score = [3, 4,10, 8]`

**Object** is a group of values put together as a unit. Object is also called structure in other programming languages such. Object helps you organized your code by grouping related values and processing them as a unit. We will talk about object in our article on objects, however, knowing the basic meaning of object is sufficient for you to start you coding journey.

### Variable
**Variable** is a refrence to value. Variable or **identifier** is used to refer to value from other locations in our program. We can say variables are way of identifying value. Let us look at some examples;
```
income = 12000
tax = 500
net_income = income - tax

```
You create a **name** or **identifier** by typing the name of the identifier followed by **=**, then followed by a value. **=** is used in most programming language to **assigned** value to an identifier.

In some programming languages, you can even create an **identifier** without actually assigning value to it. To create identifier without assigning value to it is called **variable declaration**.

It is even compulsory to declare an identifier before assigning value to it, in some programming language. Let's take Javascript for example, to declare an identifier you need to prefix the identifier with **var**, **let** or **const**;
```javascript
var net_income
let income = 12000
const tax = 500
net_income = income - tax
```

### Expression
**Expression** is any mathematical or logical manipulation of value that can produce another value. Expression is when you combine two more values to produce a new value. For example, if you add 2 to 3 you get 5. Let's look at examples of expression through pseudocode;
```
length = 120
breadth = 60
area = length * breadth
```
In the above, `length * breadth` is an expression. The other two lines are expressions as well. We will discuss them in our **Expression in Python** article.

### Function
Function is a group of expressions that are related, acting as a unit. Function is used to organize our program into logical blocks. Function is also called **procedure** or **method** in some programming languages. 

If a function produces new value, we say the function **return value**. A function that does not return value is usually called a procedure.

A function can also be given value or values to to manipulate. In coding terminologies, the values that we give a function to manipulate are called **arguments**.

Usually a function has a particular number of **arguments** that it needs in order for it to produce a correct value. The number of arguments that a function needs are called **parameters**.

Let's take examples from some few popular programming languages;
```javascript
function add(a, b) {
  return a + b
}
```
```python
def add(a, b):
    return a + b
```
```rust
fn add(a:int, b:int)->int {
  a + b
}
```
We will discuss function in detail in our **Function** article. For now, knowledge of these basic concepts is very important in your coding journey. Don't just brush over them but internalize them to make your journey smooth. See you in another article,l!
