# Node
f
- const userInput = req.body.input;
- eval(userInput);
+ const userInput = req.body.input;
+ const safeInput = sanitize(userInput);
+ executeCode(safeInput);
