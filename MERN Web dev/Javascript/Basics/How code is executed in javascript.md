### JavaScript details
1. JavaScript is a high level single threaded interpreted language.
2. JavaScript code is compiled using V8 engine developed by google and used in chrome browser. It compiles JavaScript code into machine code which improves its performance.
3. JavaScript is used for client side scripting i.e it runs on user's web browser.
4. It is used to create dynamic and interactive webpages.

### JavaScript Execution Context

JavaScript Execution Context is the environment in which code is executed. It contains information about functions, variables and objects as well as scope chain. 

					   EXECUTION CONTEXT 
							  |
							  |
			--------------------------------------
			|                                    |
	CREATION PHASE                          EXECUTION PHASE

#### Creation Phase 
JavaScript engine sets up the environment. Engine creates the following:


						CREATION PHASE
							  |
							  |
		  ---------------------------------------------------
		  |                      |                          |
	VARIABLE OBJECT        THE SCOPE CHAIN          THE "THIS" KEYWORD


#### The Variable Object (VO)
Contains all variables and functions that are defined in the current scope. i.e. function declaration, function argument and variable declaration. VO is used to resolve identifiers to their values during execution.

#### Scope Chain
It is a list of variable that is definedd under the current scope.



