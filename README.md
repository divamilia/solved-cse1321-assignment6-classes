Download Link: https://assignmentchef.com/product/solved-cse1321-assignment6-classes
<br>
<strong><u>Program 1:</u></strong> Design (pseudocode) and implement (source code) a class (name it QuadraticEquation) that represents a quadratic equation of the form of <strong>ax2+ bx + x = 0.</strong>  The class defines the following variables and methods:

<ol>

 <li>Private data field <strong>a</strong>, <strong>b</strong>, and <strong>c</strong> that represent three coefficients.</li>

 <li>A constructor for the arguments for <strong>a</strong>, <strong>b</strong>, and <strong>c</strong>.</li>

 <li>Three get methods for <strong>a</strong>, <strong>b</strong>, and <strong>c</strong>.</li>

 <li>Method getDiscriminant()returns the discriminant value, which is <strong>disc = b<sup>2</sup> – 4ac</strong>.</li>

 <li>Method getRoot1() returns first root if the discriminant is not negative. First root is defined as</li>

</ol>




<strong>R1 = (-b + SquareRoot (disc) ) / 2a</strong>




<ol start="6">

 <li>Method getRoot2() returns second root if the discriminant is not negative. Second root is defined as</li>

</ol>




<strong>R2 = (-b – SquareRoot (disc) ) / 2a</strong>




Note that if the discriminant values is negative, the roots are Undefined.




Write a test program (name it testEquation) to create objects and test the class methods. Organized your output following these sample runs.




<u>Sample run 1 for <strong>3x<sup>2</sup>+ 8x + 4</strong>:</u>




a = 3b = 8

c = 4

Root 1 = -0.6666666666666666

Root 2 = -2.0




<u>Sample run 2 for <strong>3x<sup>2</sup>+ 4x + 8</strong>:</u>




a = 3b = 4

c = 8

Root 1 is Undefined

Root 2 is Undefined




<u>Sample run 3 for <strong>2x<sup>2</sup>+ 8x + 2</strong>:</u>




a = 2b = 8

c = 2

Root 1 = -0.2679491924311228

Root 2 = -3.732050807568877







<strong><u>Program 2:</u></strong> Design (pseudocode) and implement (source code) a class called Counter.  It should have one <strong>private</strong> instance variable representing the value of the counter.  It should have two instance methods: <em>increment()</em> which adds on to the counter value and <em>getValue() </em> which returns the current value.




After creating the Counter class, create a program that simulates tossing a coin 100 times using two Counter objects (Head and Tails) to track the number of heads and tails.




<strong><u>Program 3:</u></strong> Design (pseudocode) and implement (source code) a class (name it BankAccount) that defines the following data fields and methods:




<ol>

 <li>Private int data field named id to store the account ID (default value is 0).</li>

 <li>Private double data field named balance to store the account balance (default value is 0.0).</li>

 <li>Private double data field named annualInterestRate to store the interest rate (default value is 0.0%). Assume all accounts have same interest rate. Annual interest rate is percentage such as 3.2%, thus you need to divide by 100 to get double value 0.032).</li>

 <li>Private Date data field named dateCreated to store the date when the account was created.</li>

 <li>Non-argument constructor method that creates a default account (with default values).</li>

 <li>Constructor method that creates an account with specified ID and initial balance.</li>

 <li>Get and Set methods for variables id, balance, and annualInterestRate.</li>

 <li>Get method for variable dateCreated.</li>

 <li>Method named getMonthlyInterestRate() that returns the monthly interest rate (i.e., annualInterestRate / 12 , formatted as percentage (%)).</li>

 <li>Method named getMonthlyInterest() that returns the earned monthly interest amount (i.e., balance * monthlyInterestRate, formatted as currency ($)).</li>

 <li>Method named withdraw() that withdraws a specific amount from the account.</li>

 <li>Method named deposit() that deposits a specific amount to the account.</li>

 <li>Method toString()to printout a <u>meaningful description</u> of an account object using all of its instance variables in the following format:</li>

</ol>




Account ID:          123456

Account Balance:     $7,000.00

Interest Rate:       2.50%

Date Opened:         Sun Nov 2 14:18:16 EDT 2017




Now design (pseudocode) and implement (source code) a test program (name it TestBankAccount)to create an account object named myObject as follows:




–  Account ID is 123456;

–  The Initial balance is $10,000

–  The annual interest rate is 2.5%.

–  Withdraw $3,500

–  Deposit $500

–  Print out the account balance

–  Print out the earned monthly interest

–  Print out the date the account was created





