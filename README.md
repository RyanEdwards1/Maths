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
``` #include <iostream>
	

	using namespace std;
	

	int main(){
	  int a, sum, geo = 1;
	  cout << "Number";
	  cin >> a;
	  
	  
	  for (int i=1; i <= 10; i++){
	    sum += a;
	    geo *= a;
	    cout << "Iteration: " << i << endl;
	    cout << "Airthmetic: " << sum  << endl;
	    cout << "Geometric: " << geo << endl;
	    cout << endl;
	  }
	  return 0;
	} 
```

### Conditional Probability 
Conditional probability is the probability that an event will occur in a random experiment. For example, suppose a fair dice has been rolled and you are asked to guess the probability that it was a five. There are six equally likely outcomes because of the six sides on the dice are the same size and weighted evenly. so your answer is 1/6. Suppose that before you give your answer you are given the information that the number rolled was even. This makes your chances 1/3 which is a very good increase in chance of guessing correctly.

![captaaure](https://user-images.githubusercontent.com/31927415/36474138-7c5e555e-16ee-11e8-997e-954836d39d5a.PNG)

### Event Occurring from a Discrete, Random Variable
![capturre](https://user-images.githubusercontent.com/31927415/36476634-5e589bac-16f6-11e8-83ad-c865fdd0e82e.PNG)

Above is the random selection event only possible from a finite set of inputs. The selection is always mad form a finite set which is repeated. Each time a selection is made it is from a bigger set 

### Simple Shapes using Co-ordinate geometry
There are two main formulas that you need to know firstly the Distance Formula which is ![ssss](https://user-images.githubusercontent.com/31927415/36477740-301f8882-16fa-11e8-9dbf-4bdf5f781cdd.PNG)    . The use of the distance formula is the distance between two points so this can be used to see parallel lines or to see certain shapes like a parallelogram which has four parallel sides.

The other important formula is the Slope Formula which is ![dd](https://user-images.githubusercontent.com/31927415/36477952-e5c7f020-16fa-11e8-9a8f-9a6b0b88e563.PNG) . This formula is used to calculate the angles inside of shapes to then acknowledge which shape it could be.   

![as](https://user-images.githubusercontent.com/31927415/36477985-145148e2-16fb-11e8-9998-11cc56075bd0.PNG)

### Determine the rate of change within an algebraic function
Average rate of change is the average rate that one value is changing with respect to another thing changing. We are familiar with some average rate of change calculations such as ‘Miles per gallon’ which is calculated by dividing the number of miles by the number of gallons used. Another is ‘Cost per kilowatt’ calculated by dividing the cost of the electricity by the number of kilowatts used. And ‘Miles per hour’ calculated by dividing the number of miles travelled by the number of hours it takes to travel them.

In general, and average rate a change function is a process that calculates the amount of change in one item divided by the corresponding amount of change in another. Using this function:
![rate of change](https://user-images.githubusercontent.com/31927415/38804849-c05e86aa-416b-11e8-9033-86a8a500f5ba.PNG)

Some examples of Rate of Change are:

	 F(x) = x²
		Rate of change from 1 to 3
		(3² - 1²) / (3-1) = (9-1) / (3-1) = 8/2 = 4. Binary = 0100
		
	    F(x) = 2x+3
	    	Rate of change from 10 to 100
		(2*100+3) - (2*10+3) / (100 - 10) = 180/90 = 2. Hex Decimal = 2 

### Use integral calculus to solve practical problems involving area
Intergral calculas is used to calculate whats inside a curve, if the shape is normal or common then you don't have to use integral calculus. However if the shape is more complex, then you can use the given a and b points on a graph to work out the area of a to b

Here are some examples:

![ssssssss](https://user-images.githubusercontent.com/31927415/38805040-533a1db8-416c-11e8-876d-0848ae3a82ec.PNG)

The Integral symbol ∫, represents integration, The a and b signs are placed on each side of the ∫ symbol since we want to calculate from a to b. The symbol dx represents the differential of the variable x, indicates that the variable of integration is x. Finding the area to the x axis from the curve means we have to find the integral of a function with respect to x.

A 'higher derivative' is a way of essentially making a function simpler. Where a simple function is also called a linear function as it is portrayed as a line on a graph, but when the function is more complex it becomes curved, a higher derivative is a way of converting a curved line into a straight line. X is infinite, meaning that the whole infinite can be divided into segments and by using each part a sum may be reached. By multiplying the function by the derivative of the function, we can calculate the area by creating an infinite area of rectangles to find the area. Because we already know the formula for the area of a rectangle, it makes it simple to calculate.

![wer](https://user-images.githubusercontent.com/31927415/38805373-7f364850-416d-11e8-81a9-2e4bcdc9d390.PNG)

### Determine shape parameters using appropriate vector methods.
vector is a quantity or phenomenon that has two independent properties: magnitude and direction. The term also denotes the mathematical or geometrical representation of such a quantity

To scale shapes and identify shape parameters I have created a formula that you can use to scale a shape using vector methods here is the code below:

```<html>
<body>

<canvas id="myCanvas" width="300" height="150" style="border:1px solid #d3d3d3;"></canvas>

<br>
<button onclick="move(1)">LEFT</button>
<button onclick="move(2)">UP</button>
<button onclick="move(3)">DOWN</button>
<button onclick="move(4)">RIGHT</button>
<br>
<button onclick="move(5)">DIAGONAL RIGHT DOWN</button>
<button onclick="move(6)">DIAGONAL RIGHT UP</button>
<br>
<button onclick="move(7)">DIAGONAL LEFT DOWN</button>
<button onclick="move(8)">DIAGONAL LEFT UP</button>
<br>
<button onclick="shape()">SHAPE?</button>


<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();

var curX=parseInt(prompt("Please enter the initial X"));;
var curY=parseInt(prompt("Please enter the initial Y"));;

function move(dir){
var mag = parseInt(prompt("Please enter the magnitude"));

if(dir==1){
  //left
  ctx.moveTo(curX, curY);
  curX = curX-mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Left / Vector Magnitude: "+mag);
}else if(dir==2){
  //up
  ctx.moveTo(curX, curY);
  curY = curY-mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Up / Vector Magnitude: "+mag);
}else if(dir==3){
  //down
  ctx.moveTo(curX, curY);
  curY = curY+mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Down / Vector Magnitude: "+mag);
}else if(dir==4){
  //right
  ctx.moveTo(curX, curY);
  curX = curX+mag;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Right / Vector Magnitude: "+mag);
}else if(dir==5){
  //diagonal right down
  ctx.moveTo(curX, curY);
  curX = curX+mag/2;
  curY = curY+mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Right Down / Vector Magnitude: "+mag);
}else if(dir==6){
  //diagonal right up
  ctx.moveTo(curX, curY);
  curX = curX+mag/2;
  curY = curY-mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Right Up / Vector Magnitude: "+mag);
}else if(dir==7){
  //diagonal left down
  ctx.moveTo(curX, curY);
  curX = curX-mag/2;
  curY = curY+mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Left Down / Vector Magnitude: "+mag);
}else if(dir==8){
  //diagonal left up
  ctx.moveTo(curX, curY);
  curX = curX-mag/2;
  curY = curY-mag/2;
  ctx.lineTo(curX, curY);  
  alert("Vector Direction: Diagonal Left Up / Vector Magnitude: "+mag);
}

ctx.stroke();

}

function shape(){
  var shape = prompt("Is this a shape Y/N?");

  if(shape=='Y'){
      prompt("What shape?");
  }else {
      alert("Keep drawing!");
  }
}

</script>

</body>
</html>
```
