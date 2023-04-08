---
description: Control Flow
---

## Controlling the flow

### If then statement

The example below sends the ```isAdmin``` message to ```myObject``` to
determine if an admin email should be sent.

  ```
  if (myObject.isAdmin()) then {
    myObject.sendAdminEmail();
  }
  ```

### If then else statement

The example below sends the ```isAdmin``` message to ```myObject``` to 
determine if an admin email or a non-admin email needs to be sent.

  ```
  if (myObject.isAdmin()) then {
    myObject.sendAdminEmail();
  } else {
    myObkect.sendNonAdminEmail();
  }
  ```

### While statement

The example below sends the ```hasMoreItems``` message to ```myObject``` to
determine whether or not it has more items and if it does it goes into the loop
sending the ```removeItem``` message to ```myObject```.

  ```
  while (myObject.hasMoreItems()) {
    myObject.removeItem();
  }
  ```

### Do while statement

The example below sends the ```decrementTime``` message to ```myObject``` and
then determines whether or not to terminate the loop by sending the
```isMoreThanOneYearOld``` message to ```myObject```.

  ```
  do {
    myObject.decrementTime();
  } while (myObject.isMoreThanOneYearOld());
  ```

### For statement

The example below first initializes ```i```. And then for every iteration of
the loop it determines if the loop needs to be entered by sending the 
```isLessThan``` message to ```i``` and if it must be entered it sends the
the ```tick``` message to ```myObject```. And it completes the iteration by
sending the ```incrementOne``` message to ```i```. If the loop must not be
entered it continues with any statement past the for statement. 

  ```
  for(i=0; i.lessThan(10); i.incrementOne()) {
    myObject.tick();
  }
  ```


