
Notes:

1. array declaration methods
	1. let array_name = '['array_elements']';
	2. let array_name = new array(array_elements);
2. We can use .push method to insert an element at last position in an array.
3. another way of adding an element in an array is: arrayName[arrayName.push] = elementToPush;
4. pop() method removes last element and also temporarily stores it value. Hence, it can be used to directly assign popped value to a variable.
5. copywithin method can be used to create a copy of an array.
6. Softcopy - directly references the memory and not the object from which it was copied.
7. Hardcopy - any changes in the memory doesn't affect the copy.
	1. Syntax example: 
		1. let topCities = ["Berlin", "Singapore", "New York"];
		2. let hardcopy = [...topCities];
8. .slice method can also be used to create a hard copy.
9. rest and spread operators.
10. concat method can be used to add two array.
11. .include method can be used to find if an element is present inside an array or not.
