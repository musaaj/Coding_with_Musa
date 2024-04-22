**Basic Concepts in Programming**

Before you start to code, you need to have basic ideas about the following concepts:
- value
- variable
- expression
- function

### Value
A **value** is any piece of data meant to be processed. In computer programming, we can basically have the following types of values, depending on the programming language:
- numeric
- string
- array
- object

**Numeric** values are number values such as 1, 0.5, -1, etc. Numeric values can be integers, which are numbers without a decimal point. Numeric values can also be floats, which are numbers with a decimal point. Some programming languages can have more types of numeric values, while others might even have just one.

**String** is a list of characters. Characters here mean any symbol, especially those symbols used in written languages. Strings are usually indicated by double apostrophes or single apostrophes in various programming languages. Examples of strings can be `"Hello Programming Language"`, `'Programming is awesome!"`, etc.

**Array** is a collection of values. An array can be a collection of values of different types or a collection of values of the same type. Different programming languages use different notations to denote arrays. Arrays can be denoted with pairs of [], {}, or (). Examples: `score = [3, 4, 10, 8]`

**Object** is a group of values put together as a unit. An object is also called a structure in other programming languages. An object helps you organize your code by grouping related values and processing them as a unit. We will talk about objects in our article on objects; however, knowing the basic meaning of an object is sufficient for you to start your coding journey.

### Variable
A **variable** is a reference to a value. A variable also called **identifier**, is used to refer to a value from other locations in our program. We can say variables are a way of identifying value. Let us look at some examples:
```
income = 12000
tax = 500
net_income = income - tax
```
You create a **name** or **identifier** by typing the name of the identifier followed by **=**, then followed by a value. **=** is used in most programming languages to **assign** value to an identifier.

In some programming languages, you can even create an **identifier** without actually assigning value to it. Creating an identifier without assigning a value to it is called **variable declaration**.

It is even compulsory to declare an identifier before assigning a value to it in some programming languages. Let's take Javascript for example; to declare an identifier, you need to prefix the identifier with **var**, **let**, or **const**:
```javascript
var net_income
let income = 12000
const tax = 500
net_income = income - tax
```

### Expression
An **expression** is any mathematical or logical manipulation of a value that can produce another value. An expression is when you combine two or more values to produce a new value. For example, if you add 2 to 3 you get 5. Let's look at examples of expressions through pseudocode:
```
length = 120
breadth = 60
area = length * breadth
```
In the above, `length * breadth` is an expression. The other two lines are expressions as well. We will discuss them in our **Expression in Python** article.

### Function
A function is a group of expressions that are related, acting as a unit. A function is used to organize our program into logical blocks. A function is also called a **procedure** or **method** in some programming languages.

If a function produces a new value, we say the function **returns a value**. A function that does not return a value is usually called a procedure.

A function can also be given a value or values to manipulate. In coding terminologies, the values that we give a function to manipulate are called **arguments**.

Usually, a function has a particular number of **arguments** that it needs in order for it to produce a correct value. The number of arguments that a function needs is called **parameters**.

Let's take examples from some popular programming languages:
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
We will discuss functions in detail in our **Function** article. For now, knowledge of these basic concepts is very important in your coding journey. Don't just brush over them but internalize them to make your journey smooth. See you in another article! 
