# Code Block

The code at the bottom of the page is FizzBuzz. FizzBuzz is a common interview question in coding interviews.

Here are the steps:
1. Print integers 1 to N
2. Print "Fizz" is an integer is divisible by 3
3. Print "Buzz" if an integer is divisible by 5
4. Print "FizzBuzz" if an integer is divisible by both 3 and 5

Here is the code:
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = " ";
	for (i = 1; i < 101; i++) {
   		if (i % 15 === 0){
			document.write(" FizzBuzz ")
   		} else if (i % 5 === 0){
			document.write(" Buzz ")
   		} else if (i % 3 === 0){
			document.write(" Fizz ")
   		} else {
			document.write(' '+i+' ')
   }


	displayHTML += " <p> " + i + " </p> ";
}
display.innerHTML = displayHTML
}
</script>

</head>

<body onload="fizzbuzz()">
<div id="display">
</div>
</body>

</html>
```
