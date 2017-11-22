# Code Complexity

We will be implementing simple algorithms for checking basic properties of code complexity.

1. Do a simple calculations

   Per Function:

   * **ParameterCount**: The number of parameters for function.   
   * **Returns**: The number of return statements in function. 

   For File:
 
   * **AllConditions**: The total number of conditions in file.
   * **String Usage**: How many string literals are used in file.
   * **PackageComplexity**: The number of imports used in file.

2. Using multiple visitors

   * **SimpleCyclomaticComplexity**: The number of if statements/loops + 1.
   * **MaxMessageChains**: The max length of a message chain in a function. A message chain can be formed from a method call (), a data access (.), or array access [n].
     For example, 
     
     ```
     // Message Chain: 4
     mints.name.toString().split(".")[0];
     ``` 
## Code

The code file to perform the above complexity checks can be found at `/Complexity/analysis.js`.

Steps to run the code:  

1. Download the repo.
2. Go to `Complexity` folder.
3. Run `npm install` in terminal.
4. Run the program using `node analysis.js`.
