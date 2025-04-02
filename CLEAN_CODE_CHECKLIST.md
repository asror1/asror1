Code is read more often than it is written.

# _7_ patterns to improve code readability: 

### 0. Avoid novelty: 
↳ Stick to familiar patterns instead of using new or complex constructs.

💁‍♂️ This makes your code easier to understand because readers don’t have to learn new styles. 


### 1. Simplify conditionals: 
↳ Keep your conditional checks short and straightforward. 

💁‍♂️ Avoid mixing different logical operators like `&&` and `||` in the same condition. 


### 2. Minimize nesting:
↳ Avoid deeply nested logic by breaking it into smaller functions. 

💁‍♂️ Flattening your code makes it easier to follow and debug. 


### 3. Group logic:
 ↳ Break long chains of functions or iterators into smaller steps. 

💁‍♂️ Use helper functions or intermediate variables to make the flow clearer. 


### 4. Use distinct variable names: 
↳ Choose descriptive and unique names for your variables. 

💁‍♂️ Avoid names that look similar, like `i` and `j`, to prevent confusion. 


### 5. Keep variables short-lived:
↳ Declare variables as close to their usage as possible. 

💁‍♂️ This reduces the mental effort needed to track their values. 


### 6. Write smaller functions:
↳ Keep your functions small and focused on a single task.

💁‍♂️ Smaller functions are easier to read, test, and reuse. 