using System;

class Program {

static void Main(string[] args) {

int a = 5;

int b = 7;

// Greater than

bool isAGreater ThanB = a > b;

Console.WriteLine("Is a>b? "+isAGreater ThanB);

// Less than or equal to

bool isALessThanOrEqualToB = a <= b;

Console.WriteLine("Is a <= b?"+isALessThanOrEqualToB);

// Equal to

bool areAAndBEqual = a == b;

Console.WriteLine("Are a and b equal? "+areAAndBEqual);

// Not equal to

bool areAAndBNotEqual = a != b;

}

Console.WriteLine("Are a and b not equal? "+areAAndBNotEqual);

}




using System;

class Program {

static void Main(string[] args) { bool x = true;

bool y = false;

// Logical AND

bool resultAND =

x && y;

Console.WriteLine("x && y = "+resultAND);

// Logical OR

bool resultOR = x || y; Console.WriteLine("x || y = "+resultOR);

// Logical NOT

bool resultNOTX = !x;

Console.WriteLine("NOT x = "+resultNOTX);

bool resultNOTY =

!y;

Console.WriteLine("NOT у = "+resultNOTY);

}

}




using System;

class Program {

static void Main(string[] args) {

int age = 25;

bool isStudent = true;

/ Using logical AND to check both conditions

/ bool canGetDiscount = age < 30 && isStudent; Console.WriteLine("Can get discount? "+canGetDiscount);

// Using logical OR to check at least one condition bool canEnter Club = age >= 18 || isStudent; Console.WriteLine("Can enter club? "+canEnterClub);

// Combining relational and logical operators

bool isTeenager = age >= 13 && age <= 19; Console.WriteLine("Is teenager? "+is Teenager);

}

}
