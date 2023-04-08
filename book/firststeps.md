---
description: First Steps
---

### Sending a  message

The example below sends the ```tick``` message to the ``timer`` object.

  ```
  timer.tick();
  ```

### Assigning a result

The example below sends the ```reverse``` message to```myObject``` object and it
will assign the result to ```myResult```.

  ```
  myResult = myObject.reverse();
  ```

### Constructing a new object

The example below creates an instance of ```MyObject```. 

  ```
  myObject = system.new("MyObject");
  ```

### Releasing an existing object

The example below shows how to release an object.

  ```
  system.delete(anObject);
  ```

### Defining an object

If you want to reuse your code you might consider wrapping it into an object
which can be constructed using the new message. The example below shows how
you would define the object named ```MyObject```.

  ```
  object MyObject {
  }
  ```
### Defining a method

An object in and of itself cannot do anything so you will need to define some 
methods that can accept messages. The example below defines the method for
pushing an item.

  ```
  method push(item) {
  }
  ```
