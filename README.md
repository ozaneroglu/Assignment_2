## Assignment-2

Reimplement the code in the `bouncingballs.py` file from the lecture repository into a new file named `HW2.py` by following the requirements below. Ensure that the game **runs properly** and that **all conditions are met simultaneously**.

1. The code must make use of **object-oriented programming (OOP)** principles:
   1. All data should be encapsulated within objects;
   2. Data encapsulation must not be violated;
   3. The public interface of each class should remain minimal.  
      _Hint: Implement a `Game` class to manage game-related functionality. You may introduce additional classes if needed._

2. The program should include **five balls**, each with:
   - A unique size,
   - A unique speed (inter-move time),
   - A unique initial position.  
   Note: Ball-to-ball interaction is not required.

3. A ball must **stop moving** if its speed becomes too slow (i.e., if the inter-move delay is too large).

The balls should bounce off the window borders, as in the original `bouncingballs.py` implementation. Additionally, pressing the **Up Arrow** key should increase the speed of all balls, while pressing the **Down Arrow** key should decrease their speed.

##  Due Date: 24 April, 10AM


### Additional Notes

- Make sure Python and Pygame are installed. If Pygame is not installed, it can be installed using the following command:

  ```bash
  pip install pygame

  
