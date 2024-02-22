# JavaScript

## Data Types

A Data type is an attribute that tells a computer how to interpret its value.

**1.** **String**

Represents textual data.
```js
let myString = "Hello World";
```

**2.** **Number**

Represents numerical data.
```js
let number = 24;
```

**3.** **Boolean**

Represents True or False.
```js
let boolean = true;
```

**4.** **Undefined**

Represents a variable which has not been assigned any value.
```js
let undefined;
```

**5.** **Null**

Represents absence value of any object value.
```js
let mySymbol = Symbol('unique');
```

**6.** **BigInt**

Represents a larger number value.
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

Collection of Key-Value pairs.
```js
let obj = {
    name:'Jaswanth Chowdary',
    city:'Banglore',
    age:24,
};
```

**3.** **Function**

Reusable block of code.
```js
function problem(parm){
    return problem * problem
};
```

**4.** **Promise**

Represents the eventual completion or failure of any asynchronus operations.
```js
let myPromise = new Promise((resolve,request)=>{

});
``` 

**5.** **Date**

Represents date and time.
```js
let myDate = new Date();
```

**6.** **Map**

Collection of Key-Value pairs where keys can be of any datatype.
```js
let myMap = new Map();
myMap.set('name','jaswanth');
myMap.set('age',24);
```
