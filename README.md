Download Link: https://assignmentchef.com/product/solved-comp2120-assignment-2
<br>



Write a Java program, including any number of required classes, that graphically draws a traffic light in three different situations, Red, Yellow, and Green. For instance, in Red situation, the top circle has Red color, and the other circles are just Black. Draw the traffic light in Red state at the middle left corner of the frame, Yellow state at the middle of the frame and Green state at the middle right corner of the frame. Note that you should compute the locations using the width and height of the objects. Note that you should create a class for traffic light for this problem.




Problem 2.

A microwave control panel has four buttons: one for increasing the time by 30 seconds, one for switching between power levels 1 and 2, a reset button, and a start button. Implement a class that simulates the microwave, with a method for each button. The method for start button should print a message “Cooking for … seconds at level …”. Write a tester program to test your microwave class with different values.




Problem 3.

Enhance the BankAccount class and see how abstraction and encapsulation enable evolutionary changes to software:

<ul>

 <li>Begin with a simple enhancement: charging a fee for every deposit and withdrawal. Supply a mechanism for setting the fee and modify the deposit and withdraw methods so that the fee is levied. Test your class and check that the fee is computed correctly.</li>

 <li>Now make a more complex change. The bank will allow a fixed number of free transactions (deposits and withdrawals) every month, and charge for transactions exceeding the free allotment. The charge is not levied immediately but at the end of the month.</li>

</ul>

Supply a new method deductMonthlyCharge to the BankAccount class that deducts the monthly charge and resets the transaction count. (Hint: Use Math.max(actual transaction count , free transaction count) in your computation.)

<ul>

 <li>Produce a test program that verifies that the fees are calculated correctly over several months.</li>

</ul>




Problem 4.

Implement a Java program that directs a cashier how to give change. The program has two inputs: the amount due and the amount received from the customer. Display the dollars, quarters, dimes, nickels, and pennies that the customer should receive in return. In order to avoid roundoff errors, the program user should supply both input amounts in pennies, for example 274 instead of 2.74. Test your program with at least three different cases using a tester program.




1