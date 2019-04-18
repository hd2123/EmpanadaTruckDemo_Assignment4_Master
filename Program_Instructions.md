# ITP 120 Program 4 (Classes, Objects, and Inheritance)

You are writing a program for the **SamePriceEmpanadaFoodTruck** company that _keeps track of how many empanadas are sold for each truck that the company has._

<br>

## REQUIREMENTS

**Below listed are the _Program Requirements_**:

<br>

### Create a class called EmpanadaTruck that contains the following

<br>

- [ ] a data member that keeps track the quantity of empanadas sold for all trucks

- [ ] a data member that keeps track of the truck ID

- [ ] a data member that keeps track of the quantity of empanadas sold for a single truck

- [ ] a default constructor that sets the quantity of empanadas sold for a single truck to 0 and sets the truck ID to 0. 
**This is a no args constructor.**

- [ ] a constructor that accepts 2 parameters for the quantity of empanadas sold and truck id

- [ ] an accessor method (getter method) that gets the truck ID

- [ ] an accessor method (getter method) that gets the quantity sold for a truck

- [ ] a mutator method (setter method) that sets the truck ID

- [ ] a mutator method (setter method) that sets the quantity sold for a single truck

- [ ] a method that sums the total quantity of empanadas sold for all trucks

- [ ] an accessor method (getter method) that gets the total quantity of empanadas sold for all trucks

<br>

### Create a program called **EmpanadaTruckDemo** that references the **EmpanadaTruck class** that contains the following

- [ ] a loop the runs the program by allowing the user to choose to run the program or not

- [ ] a prompt to enter the truck number and input accordingly

- [ ] a prompt to enter the quantity of empanadas sold for the truck and input accordingly

- [ ] create an object that represents a sale and passes the truck ID and
quantity of empanadas sold as arguments to the constructor in the EmpanadaTruck class

- [ ] create an object that represents a sale and passes the truck ID and quantity of for the object created,
run the method that adds the quantity sold to the total quantity of empanadas sold for all trucks

- [ ] create an object that represents a sale and passes the truck ID and quantity offor the object created, display the truck ID.
You will need to run the getter method for the truck ID.

- [ ] create an object that represents a sale and passes the truck ID and quantity of for the object created,
display the quantity of empanadas sold.
You will need to run the getter methods for the quantity sold for that truck

- [ ] create an object that represents a sale and passes the truck ID and quantity of
for the object created, display the total quantity of empanadas sold for all trucks at that
point.
You will need to run the getter method that sums the total quantity of empanadas sold for all trucks

- [ ] create an object that represents a sale and passes the truck ID and quantity of empanadas sold as an argument
to the constructor in the EmpanadaTruck class

- [ ] Save the total quantity of empanadas sold for all trucks in a variable for displaying after the program ends

- [ ] Prompt the user to run the program again and accept input accordingly

- [ ] When the program has ended, display the total quantity of empanadas sold for all trucks
Extend the EmpanadaTruck class to the Sales class to enable tracking of sales dollars earned in
addition to quantities sold

- [ ] Create a data member for the sale price (remember money is always a double)

- [ ] Create a constructor that accepts 3 parameters for the quantity of empanadas sold and
truck id and the price. Within it, call the superclass constructor passing 2 parameters for
the truck id and the quantity of empanadas sold and set the price.

- [ ] Create an accessor method (a getter method) to get the price of the empanadas sold

- [ ] Create an accessor method (a getter method) to get the sale which uses the price as a
parameter and calculates the sale by multiplying the price by the result returned from
the get number sold method

- [ ] Create an accessor method (a getter method) to get the total price for all empanadas
sold which uses price as a parameter and calculates the total sales for all trucks by
multiplying the price by the result returned from the get total sold method.

<br>

### Create a program called SalesDemo that references the Sales class that contains the following:

- [ ] a loop the runs the program by allowing the user to choose to run the program or not

- [ ] a prompt to enter the truck number and input accordingly

- [ ] a prompt to enter the quantity of empanadas sold for the truck and input accordingly

- [ ] a prompt to enter the price of the empanda sold for the truck and input accordingly

- [ ] create an object that represents a sale and passes the truck ID and quantity of
empanadas sold and price as arguments to the constructor in the Sales class

- [ ] for the object created, run the method that adds the quantity sold to the
total quantity of empanadas sold for all trucks

- [ ] for the object created, run the method that gets the price

- [ ] for the object created, display the truck ID.
You will need to run the getter method for the truck ID.

- [ ] for the object created, display the quantity of empanadas sold.
You will need to run the getter method for the quantity sold for that truck

- [ ] for the object created, display the price of the empanadas sold.
You will need to run the getter method for the price

- [ ] for the object created, display the amount owed.
You will need to run the method for calculating the amount of the sale

- [ ] for the object created, display the total quantity of empanadas sold for all trucks at that point.
You will need to run the getter method that sums the total quantity of empanadas sold for all trucks

- [ ] for the object created, display the total sales for all trucks at that point.
You will need to run the getter method that calculates the total sales for all trucks.

- [ ] Save the total quantity of empanadas sold for all trucks in a variable for displaying after
the program ends

- [ ] Save the total sales for all trucks at that point in a variable for displaying after the
program ends

- [ ] Prompt the user to run the program again and accept input accordingly

- [ ] When the program has ended, display the total quantity of empanadas sold for all trucks and  total sales for all trucks

- [ ] As always, name data members, methods, variables, classes correctly using camelCase.

- [ ] As always, indent correctly.

- [ ] As always, format dollars and cents using the printf command.

- [ ] As always, document your program at the beginning and for each logical requirement throughout.

<br>

### Extra Credit 

Submit UML diagrams for the _**EmpanadaTruck** and **Sales** classes_ indicating:

- [ ] data members
- [ ] constructors
- [ ] methods
- [ ] whether they are public or private and data types
