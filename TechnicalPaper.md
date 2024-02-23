# JavaScript

## Data Types

A Data type is an attribute that tells a computer how to interpret its value.

**1.** **String**

`String` represents textual data.
```js
let myString = "Hello World";
```

**2.** **Number**

`Number` represents numerical data.
```js
let number = 24;
```

**3.** **Boolean**

`Boolean` represents True or False.
```js
let boolean = true;
```

**4.** **Undefined**

`Undefined` represents a variable which has not been assigned any value.
```js
let undefined;
```

**5.** **Null**

`Null` represents absence value of any object value.
```js
let mySymbol = Symbol('unique');
```

**6.** **BigInt**

`Bigint` represents a larger number value.
```js
let myBig = 789452589;
```



## Data Structures

Data structures provide different ways to organize and store data, and each has its own advantages and use cases.

**1.** **Array**

Collection of values.
```js
let arr = [7,8,4,9,4,5,2,5,8,9];
```

**2.** **Object**

An `Object` is collection of Key-Value pairs.
```js
let obj = {
    name:'Jaswanth Chowdary',
    city:'Banglore',
    age:24,
};
```

**3.** **Stack**

A `stack` is a collection of elements, with two main principal operations.
* Push: Adds an element to the collection.
* Pop: Removes the most recently added element that was not yet removed.
```js
let stack = [];
stack.push(1);
stack.push(2);
stack.push(3);
stack.pop();  // output:3

```

**4.** **Promise**

`Promise` represents the eventual completion or failure of any asynchronus operations.
```js
let myPromise = new Promise((resolve,request)=>{

});
``` 

**5.** **Date**

`Date` represents date and time.
```js
let myDate = new Date();
```

**6.** **Map**

`Map` collection of Key-Value pairs where keys can be of any datatype.
```js
let myMap = new Map();
myMap.set('name','jaswanth');
myMap.set('age',24);
```
----

### References

- [MDN Web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
- [Geeks for geeks](https://www.geeksforgeeks.org/javascript-data-types/)
- [Freecodecamp](https://www.freecodecamp.org/news/data-structures-in-javascript-with-examples/)