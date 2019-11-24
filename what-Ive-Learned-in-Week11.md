# What I've Learned in Week 11

### Objects

Objects are variables that contain value. Objects are used for storing information like a players health and attack.

Example.
```javascript 
const player = {
    health: 100,
    attack: 12,
    defense: 14
}

//adding a new a new property and value to player
player.specialAttack = 20;
player['specialDefense'] = 15;
console.log(player)
// { health: 100,
//   attack: 12,
//   defense: 14,
//   specialAttack: 20,
//   specialDefense: 15 }

```

### Classlist

- You can target multiple classes 
- You manipulate the DOM with classes by replacing it with another class name 

```javascript
// css file
.mystyle {
  width: 300px;
  height: 50px;
  background-color: coral;
  color: white;
  font-size: 25px;
}
document.getElementById("myDIV").classList.add("mystyle");

```

### Function expression

A function that is stored in a variable

```javascript
const getRectArea = function(width, height) {
    return width * height;


}

console.log(getRectArea(3,4));
// expected output: 12

```


