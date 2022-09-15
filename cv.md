## Nikita Borisevich
***
#### Junior Frontend Developer
***
#### Contacts
***
* **Location:** Vitebsk, Belarus
* **Phone:** [+375(33) 359 60 93](href: " +375333596093") 
* **Email:** borisevich9852@gmail.com
* **GitHub:** [nikitaborisevich](https://github.com/nikitaborisevich)

#### About me
***
Currently I work in a family workshop as a stained glass artist, I am responsible for the full cycle of stained glass production, from the development (creation of a graphic base) of a stained glass window to the production of a finished material product. I have skills in stained glass areas such as: 

* Laid on stained glass.
* Brazed stained glass.
* Faceted stained glass.
* Polymer stained glass.

Initially, he received an education in the specialty software information technology. He stopped moving in this area due to the need to participate in family business.

Why did you decide to change your field of activity? During my work in the field of stained glass production, I have reached the ceiling in development and for a long time I feel like I am trampling on the same level. I want to develop as a specialist as a developer, interest and craving for this field of activity have not faded in me since I studied at the university.

Why am I able to advance in development?
* This type of activity I find extremely exciting for myself.
* I have sufficient perseverance.
* Self-discipline at a high level
* I see prospects for development in the field of programming.

#### Skills
***
* HTML, CSS
* JavaScript (Basic)
* Git, GitHub
* VS Code
* Graphics:
    * Adobe Photoshop
    * Adobe Illustrator
    * Corel Draw
    * Procrate
    * Forger Classic
    * Figma

#### Code example:
***
##### [Array Helpers](https://www.codewars.com/kata/525d50d2037b7acd6e000534) KATA from CODEWARS:

**Deskription:**

This kata is designed to test your ability to extend the functionality of built-in classes. In this case, we want you to extend the built-in Array class with the following methods: `square()`, `cube()`, `average()`, `sum()`, `even()` and `odd()`.

**Explanation:**
* `square()` must return a copy of the array,containing all values squared
* `cube()` must return a copy of the array, containing all values cubed
* `average()` must return the average of all array values; on an empty array must return NaN (note: the empty array is not tested in Ruby!)
* `sum()` must return the sum of all array values
* `even()` must return an array of all even numbers
* `odd()` must return an array of all odd numbers

**Note:** the original array must not be changed in any case!

**Example:**

```
var numbers = [1, 2, 3, 4, 5];

numbers.square();  // must return [1, 4, 9, 16, 25]
numbers.cube();    // must return [1, 8, 27, 64, 125]
numbers.average(); // must return 3
numbers.sum();     // must return 15
numbers.even();    // must return [2, 4]
numbers.odd();     // must return [1, 3, 5]
```

**Solution:**

```
Array.prototype.square = function() {
  let arr = [];
  for (let key = 0; key < this.length; key++) {
    arr.push(Math.pow(this[key], 2)) 
  }
  return arr
}
Array.prototype.cube = function() {
  let arr = [];
  for (let key = 0; key < this.length; key++) {
    arr.push(Math.pow(this[key], 3))
  }
  return arr
}
Array.prototype.average = function() {
  let meaning = 0;
  for (let key = 0; key < this.length; key++) {
    meaning += this[key]
  }
  meaning = meaning / this.length
  return meaning
}
Array.prototype.sum = function() {
  let sum = 0;
  for (let key = 0; key < this.length; key++) {
    sum += this[key]
  }
  return sum
}
Array.prototype.even = function() {
  let arr = [];
  for (let key = 0; key < this.length; key++) {
    if (this[key] % 2 == 0) {
      arr.push(this[key])
    }
  }
  return arr
}
Array.prototype.odd = function() {
  let arr = [];
  for (let key = 0; key < this.length; key++) {
    if (this[key] % 2 !== 0) {
      arr.push(this[key])
    }
  }
  return arr
}
```

#### Education
* **University:** Vitebsk State University named after P.M. Masherov, faculty:"Information technology software", speciality: "Engineer programmer"
* **Self-education:**
    * [LearnJS](https://learn.javascript.ru/)
    * [CodeWar](https://www.codewars.com/)
* **Courses:** [RS School Course](https://rs.school/) ["JavaScript/Front-end.](https://rs.school/js/) Stage 1" (in progress)
* **Books:** Steven C.McConnell: "Code Complete Second Edition" (in progress)

