## Algorithm and Pseudocode
[**Algorithm**](https://edu.gcfglobal.org/en/computer-science/algorithms/1/) is a set of rules to follow to solve a mathematical or computing problem.
[**Pseudocode**](https://www.techtarget.com/whatis/definition/pseudocode#:~:text=Pseudocode%20is%20a%20detailed%20yet,involved%20in%20the%20development%20process.), on the other hand, is way of descriping algorithm in a less formal way. **Pseudocode** uses more informal-like english expression to express algorithm so that programmers can implement the algorithm in any programming language.

Unlike programming language, pseudocode does not follow any particular rule. You can come up with any standard for your pseudocode representation.

In this article, we are going to see how we can express algorithm in pseudocode.

### Expresssing Algorithm in Pseudocode
Assumed you are ask to give algorithm to add two numbers (2 + 3) together. You can give the algorithm in either low level or high level. In low level, you can express the algorithm as below;
```
LOAD 2 AS $a
LOAD 3 AS $b
ADD $a AND $b AS $c
RETURN $c
```

while in  high level, you can express the algorithm as below;
```
sum = 2 + 3
```

As you can see from the example, you can be as low level as possible or as high level as possible in your pseudocode. What matters most is that your audience can undestand your algorithm from the pseudocode.

Let's take one more example pseudocode. Imagine you are given three numbers; a, b and c. To write and algorithm in pseudocode to sort those numbers in ascending order, your pseudocode can be as below;
```
Algorithm to sort three numbers (a, b, c) in ascending order

FOR EACH number IN (a, b, c) BEGIN
    FOR EACH number_again IN (a, b, c) BEGIN
      IF number > number_again BEGIN
        SWAP INDEX OF number WITH INDEX OF number_again
      ENDIF
    ENDFOR
ENDFOR
```

Pseudocode helps you to express your algorithm clearly and also spot correct errors in your algorithm before you even start to code. Pseudocode also helps you communicate effectively with other programmers.

In our next article we will look at some important building blocks in pseudocode to prepare us so that we can be able to express our algorithm effectively before we start our coding journey. See you in the next article.
