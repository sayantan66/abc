# Node
f
- eval(userInput);
+ const safeInput = sanitize(userInput);
+ executeCode(safeInput);
