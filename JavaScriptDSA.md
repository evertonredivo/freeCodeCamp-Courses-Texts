# JavaScript Algorithms and Data Structures

Step 41
JavaScript has a feature called template literals, which allow you to interpolate variables directly within a string. Template literals are denoted with backticks ``, as opposed to single or double quotes.
Variables can be passed in to a template literal by surrounding the variable with ${} – the value of the variable will be inserted into the string.

For example:

const name = "Naomi";
const templateLiteral = `Hello, my name is ${name}~!`;
console.log(templateLiteral);
The console will show the string "Hello, my name is Naomi~!".

Replace your concatenated string in the querySelector with a template literal – be sure to keep the space between your targetId variable and .input-container.
