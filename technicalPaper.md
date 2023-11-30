# Basic Datatype And Data Structure Of Javascript

## Basic Datatypes:

1. [Number](#number)
1. [Boolean](#boolean)
1. [String](#string)
1. [Null](#null)
1. [Undefined](#undefined)

### Number:

- Numbers are used to represent numeric values.
- ```js
  let num = 10; //declaration
  let num1 = 123.5;
  ```

### Boolean:

- Booleans are used to represent true or false values.
- ```js
  let bool = true; //declaration
  let bool1 = false;
  ```

### String:

- Strings are used to represent text values.
- We can use single qoute and double qoute in while declaring string.
- ```js
  let str = "mahir"; //declaration
  let str1 = "anand";
  ```

### Null:

- The null value represents the intentional absence of any object value. It is one of JavaScript's primitive values and is treated as falsy for boolean operations.
- ```js
  const obj = null; //declaration
  ```

### Undefined:

- Undefined is that value when we initialize the variable and doesn't assign any value to it;
- ```js
  let t; // declaration
  console.log(t); // print undefined
  ```

> **Note** :
> Null is a primitive value that represents the intentional absence of a value. Undefined is a property that means a variable has been declared but has not yet been assigned a value.

## Data Structures:

1. [Array](#array)
1. [Objects](#objects)
1. [Maps](#maps)
1. [Sets](#sets)
1. [String(as Arrays)](#stringas-arrays)

### Array:

- An array is a special variable, which can hold more than one value.
- Uses square bracket for declaration.
- Takes continous memory block.
- ```js
  const arr = ["mahir", "a", 10]; //declration
  ```

### Objects:

- Key-value pairs used to store various data.
- ```js
  let obj = {
    name: "mahir",
    age: 21,
  };
  ```

### Maps:

- Similar to objects, but keys can be of any data type.
- ```js
  let map = new Map();
  map.set("key1", "value1");
  map.set(2, "value2");
  ```

### Sets:

- Collections of unique values.
- ```js
  let set = new Set();
  set.add(1);
  set.add(2);
  set.add(3);
  ```

### String(as arrays):

- Strings can be treated as arrays of characters.
- ```js
  let str = "Mahir";
  console.log(str[0]); // Output: "M"
  ```

## Reference Links:

- [w3School](https://www.w3schools.com/js/js_object_sets.asp)
- [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
- [Anvil](https://anvilproject.org/guides/content/creating-links)
