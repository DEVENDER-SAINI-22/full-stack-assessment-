# Full Stack Foundations Assignment

**Name:** Devender Saini  
**Course:** Full-Stack Foundations

---

# PART A: PYTHON BASICS

## Q1. What is the output of the following Python expression?

print(type(1 / 2))

Answer:
Output:

<class 'float'>
**Correct Option:** B

Explanation: The `/` operator always performs floating-point division in Python.


## Q2. Explain the difference between a tuple and a list in Python. Provide a brief code snippet demonstrating when you would use one over the other.

### Answer:

A List is mutable, meaning its elements can be changed after creation.

A Tuple is immutable, meaning its elements cannot be changed after creation.

# List
fruits = ["Apple", "Banana"]
fruits.append("Mango")

remind:- here append ka matlab h list me kisi ir cheez ko jodna.

Lists are used for dynamic data, while tuples are used for fixed values.


## Q3. What will be the output?

my_dict = {"a":1,"b":2,"c":3}
print(my_dict.get("d",4))

Answer:

Output:
4
**Correct Option:** C

Explanation:
Since key "d" is not present, the default value 4 is returned.

---

## Q4. Write a Python function called is_palindrome(word).

### Answer:

def is_palindrome(word):
    word = word.lower()
    return word == word[::-1]

print(is_palindrome("Madam"))

Output:

True



## Q5. Analyze the following loop.
count = 0
while count < 5:
    print("Hello")
    count += 2


Answer:

Hello will be printed 3 times.

**Correct Option:** B

---

## Q6. Given the list numbers=[1,2,3,4,5,6], write a list comprehension that generates a new list containing only the squares of the even numbers.

### Answer:
```
numbers=[1,2,3,4,5,6]

square_evens =[x**2 for x in numbers if x%2==0]

print(squares_evens)
```

Output:

```
[4,16,36]
```


## Q7. What is the behavior of the with statement when opening files in Python?

### Answer:

The `with` statement automatically closes the file after execution, even if an error occurs. This makes the code safer and easier to manage.

Example:

```python
with open("file.txt","r") as file:
    data=file.read()
```

---

## Q8. Write a Python program to find and print the largest element without using max().

### Answer:

```python
numbers=[5,9,2,15,8]

largest=numbers[0]

for num in numbers:
    if num>largest:
        largest=num

print(largest)
```

Output:

15

---

# PART B: HTML BASICS

## Q9. Which HTML5 tag is used to define semantic navigation links?

### Answer:

**Correct Option: C) <nav>

---

## Q10. Create a valid HTML form.

### Answer:

```html
<form>
<label>Username:</label>
<input type="text">

<label>Password:</label>
<input type="password">

<input type="submit" value="Submit">
</form>
```

---

## Q11. Difference between block-level and inline elements.

### Answer:

Block-level elements start on a new line and take full width.

Examples:
<div>
<p>

Inline elements stay on the same line.

Examples:
<span>
<a>

---

## Q12. Which attribute provides alternative text?

### Answer:

alt

**Correct Option: D) alt**

Example:

html
<img src="image.jpg" alt="Nature">
```


# PART C: CSS BASICS

## Q13. Explain the CSS Box Model.

### Answer:

The four parts of the CSS Box Model are:

1. Content
2. Padding
3. Border
4. Margin

---

## Q14. Which CSS property changes background color?

### Answer:

**Correct Option: B) background-color

---

## Q15. Write the CSS rule.

### Answer:

```css
.container p{
    color:blue;
}


## Q16. Difference between id and class selector.

### Answer:

An ID is unique and used only once.

A Class can be used on multiple elements.

---

# PART D: JAVASCRIPT BASICS

## Q17. Which keyword declares a block-scoped variable?

### Answer:

**Correct Option: B) let

---

## Q18. Write calculateArea(width,height).

### Answer:

```javascript
function calculateArea(width=1,height=1){
    return width*height;
}

console.log(calculateArea(5,4));
```

Output:

```
20
```

---

## Q19. What is the output?

```javascript
console.log(2+"2"-1);
```

### Answer:

Output:

```
21
```

**Correct Option:** B


## Q20. Write a JavaScript snippet.

### Answer:

```javascript
document.getElementById("action-btn").addEventListener("click",function(){
alert("Button Clicked!");
});

---

# Thank You
