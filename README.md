# icebreaker
Icebreaker game for Day 1

## IceBreaker with Data Types
Everyone gets a letter and a number coming into the classroom
That is their letter is their variable

## Variables
https://www.youtube.com/watch?v=HWRnnfkeEW8
Think of your name as a variable  
Your name can change but you don't change
Jen = me
Variables allow you to store, find and change information in a program

+ Strings - A series of characters (letters, numbers, spaces, symbols in quotes )
+ Integers - Numbers
+ Array

Store information
jen.eyes = 'green'
A lot of times in Math you with use a variable to represent a number like:  
X = 5   
Y = 4  
The Value of X is ? 5  
The Value of X is ? 4  
So then X + Y = 9
Today the letter you were given will represent you.  
My Letter is A  
so the variable llama = 'Jen' or "Jen"

### String
A String is 

### Number

### Organize yourselves
The 
### Variables
python
```python
var x = 47
```
javascript
```js
var x = 47
let y = 23
const = 3
```

---

## Indexed Lists
### Array - JavaScript
```js
var instructors = ['Jen', "Greg', 'Lionel', 'Other']
```

### Conditional
Allows is to contol what the program does  
if this  
then that


---

## Boolean

---

## Loop
Repeat a section of code a set number of times until the process is complete


---

## Key Value Pairs
properties values


### Hash - Python
```python
var jen = {id:1, firstName: 'Jen', lastName: 'Diamond', email: 'thejendiamond@gmail.com'}
```

### Object - JavaScript
```js
var jen = {id:1, firstName: 'Jen', lastName: 'Diamond', email: 'thejendiamond@gmail.com'}

$ jen.name >> 'Jen'
```
### Array of Objects
```
var instructors = [ 
                    {id:1, firstName: 'Jen', lastName: 'Diamond', email: 'thejendiamond@gmail.com'},
                    {id:1, firstName: 'Lionel', lastName: 'X', email: 'lionel@gmail.com'},
                    {id:1, firstName: 'Greg', lastName: 'Santos', email: 'gregsantos@gmail.com'},
                    {id:1, firstName: 'Jen', lastName: 'Diamond', email: 'thejendiamond@gmail.com'},
		  ]
```

---

### Classes
Classes hold information about an Object. It is used as a blue print from which you can ceate a new Object

#### Animals

```js
class Animal { 
  constructor(name) {
    this.name = name;
  }
  
  speak() {
    console.log(this.name + ' makes a noise.');
  }
}

class Dog extends Animal {
  constructor(name) {
    super(name); // call the super class constructor and pass in the name parameter
  }

  speak() {
    console.log(this.name + ' barks.');
  }
}

var d = new Dog('Mitzie');
d.speak(); // Mitzie barks.
```

```js
var r = new Rectangle()
undefined
r
Rectangle {height: undefined, width: undefined}
r.height = 10
10
r
Rectangle {height: 10, width: undefined}
r.width = 20
20
r
Rectangle {height: 10, width: 20}

---

var rect = new Rectangle(10, 10);

console.log(square.area); // 100

```
