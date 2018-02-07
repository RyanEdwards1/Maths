# Maths
### How to calculate the greatest common divisor and least common multiple of a given pair of numbers.
#### **Greatest Common Divisor**
##### Greatest common divisor of two or more integers, which are not all zero, is the largest positive integer that divides each of the integers. For example, the GCD of 8 and 12 is 4. It is also know and highest common factor. 
##### A example of Greatest common divisor is using these numbers: 10 44 33 27 19 55 87
##### I will show you how to work out the GCD:
```10 = 2×5

44 = 22×11

33 = 3×11

27 = 33

19 = 19

55 = 5×11

87 = 3×29

GCD = 1
```
#### **Least Common Multiple**

##### A common multiple is a number that is a multiple of two or more numbers. The common multiples of 3 and 4 are 0, 12, 24. So the Least common multiple is the number that both of the numbers contain which is not zero which in this case would be 12.

##### An example of Least Common Multiple:

```Numbers: 3 and 5 

The multiples of 3 are 3, 6, 9, 12, (15), 18
The multiples of 5 are 5, 10, (15), 20, 25

As you can see the lowest common multiple is 15
```



### Arithmetic and Geometric progressions
##### The code below is a working sum that can do arithmetic and geometric progressions:
```#include <iostream> /*Libary*/
#include <time.h>


using namespace std;

int main () {
  
int input;

cout << "Enter a number" << "\n";

cin >> input;

int geometric = input + input;

int geometric2 = geometric + input;

int geometric3 = geometric2 + input;

cout << "Geometric Number: " "\n";
cout << geometric << "\n";
cout << geometric2 << "\n";
cout << geometric3 << "\n";
}
```

