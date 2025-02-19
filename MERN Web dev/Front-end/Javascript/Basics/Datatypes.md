
there are 8 datatypes in javascript 

1. String
2. Number
3. Boolean 
4. Object
5. Null
6. Undefined 
7. Symbol
8. Bigint

There are two types of datatypes in javascript 

							Datatypes 
								|
								|
		----------------------------------------------------
		|                                                  |
	Primitive                                          Non-primitive
		|                                                  |
	-------------------------                            objects
	|String, Boolean, Number|                              |
	|null, undefined, symbol|              ----------------------------
	-------------------------             | arrays, function, objects |
	                                    ---------------------------

Note: 
1. typeof() - this method can be used to find out the type of data inside a variable.
2. objects in javascript can be created using new keyword.
3. In javascript everything is an object.
4. Undefined = value exist but is not known.
5. null = value exist and its value is empty (or in many cases 0).
6. We can explicitly state a value to be undefined.
7. " `` " - is called a backtick.
8. String interapolation - we can use the syntax ` hello ${varible_name}` to use variables inside a string definition.
9. symbol() method can be used to define a symbol.
10. Symbols guarantees uniqueness and it can be used to add a unique property key.
11. We can access the properties inside an object by using a '.'.
12. if an object is defined as a constant then also we can change value of properties inside of that object because the memory block is same only the values are changing.
13. [" "] - this notation can also be used to access the members inside an object. It is  specially useful when name contains whitespaces.
14. toFixed() - this method can be used to cap a decimal to the desired number of digits.
15. In javascript Syntax of array is as follows:
				let array_name = ["element_1", "element_2", "element_3"];
16. We can make array inside an array.
17. Javascript automatically performs implicit type conversion. 
	1. Example: console.log("1"+1); - code output - 11
	   in this example javascript assumes that the integer 1 might also be a string so it implicitly type converts and gives the output as 11.
	2. Example: let isValue = true;
			   console.log(isValue+1); code output - 2
		in this example javascript considers true = 1 hence it adds 1+1 = 2; therefore using implicit type conversion is not a good idea.

18. Type of NaN (Not a number) is also a number.
19. We can force a conversion by using Number(), String() etc.
20. Javascript don't have a predefined datatype it dynamically checks types on the go.
21. TypeScript is JavaScript with types.






