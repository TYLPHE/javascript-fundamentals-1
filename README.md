# javascript-fundamentals1
Playing with JavaScript and git

See my progress here: <a href="https://TYLPHE.github.io/javascript-fundamentals-1/" target="_blank">Javascript fundamentals practice</a>.

reference for fundamentals 2:
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Test_your_skills:_Strings
Solutions by me:
Strings 1:
// Add your code here

let quoteStart = `Don't judge each day by the harvest you reap `;
let quoteEnd = `but by the seeds that you plant.`;
let finalQuote = quoteStart + quoteEnd;

// Don't edit the code below here!

section.innerHTML = ' ';
let para1 = document.createElement('p');
para1.textContent = finalQuote;

section.appendChild(para1);

Strings 2:
let quote = 'I do not like green eggs and ham. I do not like them, Sam-I-Am.';
let substring = 'green eggs and ham';

// Add your code here
let quoteLength = quote.length;
let index = quote.indexOf(substring);
let revisedQuote = quote.substr(0,index) + substring;
// Don't edit the code below here!

section.innerHTML = ' ';
let para1 = document.createElement('p');
para1.textContent = `The quote is ${ quoteLength } characters long.`;
let para2 = document.createElement('p');
para2.textContent = revisedQuote;

section.appendChild(para1);
section.appendChild(para2);

Strings 3:
let quote = 'I dO nOT lIke gREen eGgS anD HAM';

// Add your code here
let excludeFirstLetter = quote.slice(1)
let lowerCaseConvert = excludeFirstLetter.toLowerCase();
let firstLetterCapital = quote.charAt(0).toUpperCase();
let convertedSentence = firstLetterCapital+lowerCaseConvert;

let fixedQuote = convertedSentence.replace(`green eggs and ham`, `black chicken and clam`);
let finalQuote = `${fixedQuote}!`;
// Don't edit the code below here!

section.innerHTML = ' ';
let para1 = document.createElement('p');
para1.textContent = fixedQuote;
let para2 = document.createElement('p');
para2.textContent = finalQuote;

section.appendChild(para1);
section.appendChild(para2);
