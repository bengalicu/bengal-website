---
description: Control Flow
---

## Controlling the flow

### If then statement

The example below calls the ```isAdmin``` method on ```myObject``` to
determine if an admin email should be sent.

  ```
  if (myObject.isAdmin()) then {
    myObject.sendAdminEmail();
  }
  ```

### If then else statement

The example below calls the ```isAdmin``` method on ```myObject``` to 
determine if an admin email or a non-admin email needs to be sent.

  ```
  if (myObject.isAdmin()) then {
    myObject.sendAdminEmail();
  } else {
    myObkect.sendNonAdminEmail();
  }
  ```

### While statement

The example below calls the ```hasMoreItems``` method on ```myObject``` to
determine whether or not it has more items and if it does it goes into the loop
calling the ```removeItem``` method on ```myObject```.

  ```
  while (myObject.hasMoreItems()) {
    myObject.removeItem();
  }
  ```

### Do while statement

The example below calls the ```decrementTime``` method on ```myObject``` and
then determines whether or not to terminate the loop by calling the
```isMoreThanOneYearOld``` method on ```myObject```.

  ```
  do {
    myObject.decrementTime();
  } while (myObject.isMoreThanOneYearOld());
  ```

### For statement

The example below first initializes ```i```. And then for every iteration of
the loop it determines if the loop needs to be entered by calling the 
```isLessThan``` method on ```i``` and if it must be entered it calls the
the ```tick``` method on ```myObject```. And it completes the iteration by
calling the ```incrementOne``` method on ```i```. If the loop must not be
entered it continues with any statement past the for statement. 

  ```
  for(i=0; i.lessThan(10); i.incrementOne()) {
    myObject.tick();
  }
  ```
