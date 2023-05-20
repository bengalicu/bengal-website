---
description: First Steps
---

### Calling a  method

The example below calls the ```tick``` method on the ``timer`` instance.

  ```
  timer.tick();
  ```

### Assigning a result

The example below calls the ```reverse``` method on ```myObject``` instance and it will assign the result to ```myResult```.

  ```
  myResult = myObject.reverse();
  ```

### Constructing a new instance

The example below creates an instance of ```MyObject```. 

  ```
  myObject = new("MyObject");
  ```

### Releasing an existing instance

The example below shows how to release an object.

  ```
  delete(anObject);
  ```

### Defining an object

If you want to reuse your code you might consider wrapping it into an object
which can be constructed using the new keyword. The example below shows how
you would define the object named ```MyObject```.

  ```
  object MyObject {
  }
  ```
### Defining a method

An object in and of itself cannot do anything so you will need to define some 
methods that can be called. The example below defines a method for
pushing an item.

  ```
  method push(item) {
  }
  ```
