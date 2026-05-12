# Nixon Abuku — Roadmap Progress

## Current Status
- Week: 1
- Day: 1
- Last session: May 6 2026
- Next session: May 8 2026 (Day 2)

## Sessions Completed
### Day 1 — May 6 2026
- Topics: Git fundamentals
- Built: learning-log repo, 3 commits pushed
- Commands mastered: init, add, commit, push, status, log, remote add
- Weak spots: commit message quality
- Next: JavaScript variables and data types

## Projects Status
- [ ] Portfolio website
- [ ] Job Tracker API
- [ ] Full-stack Job Tracker
- [ ] Docker + CI/CD
- [ ] AWS deployment
- [ ] Terraform

## Project Ideas
- Shift Schedule API (Week 12)
  - Log shifts, calculate hours and pay
  - Node + Express + PostgreSQL
  - Personal use case: I work night shifts

## May 7 2026 — Day 2

### What I learned
- Variables: const vs let — const cannot be reassigned, let can
- Data types: string, number, boolean, null, undefined
- typeof operator — tells you the data type of a variable
- Functions — containers that store instructions
- Parameters — variables that only exist inside a function
- return vs console.log — return sends value back, console.log just displays
- Template literals — backtick syntax with ${variable}
- Reading error messages — file name, line number, error type

### What I built
- day1.js with variables, functions, multiply challenge, template literals

### Commands used
- node filename.js — runs a JavaScript file

### Mistakes made
- Typo: reuslt instead of result — caused ReferenceError
- git add without . — nothing staged

### Next session
- Day 3 Friday — arrays, objects, loops

## May 8 2026 — Day 3

### What I learned
- Arrays — storing multiple values in one container
- Zero-based indexing — first item is position 0
- array.push() — adds item to end
- array.pop() — removes last item
- array.length — counts items
- for...of loop — iterates through every item
- Objects — storing data with labels (keys and values)
- Dot notation — object.key to access values
- Array of objects — the pattern used in real databases

### What I built
- day3.js with arrays, loops, objects, and array of objects

### Key insight
- Array of objects is exactly what a database returns
- Every job application in the Job Tracker will be an object inside an array

### Mistakes made
- Used regular quotes instead of backticks in template literal
- Declared unused variable (countapp)

### Next session
- Day 4 Saturday — rest day
- Day 5 Sunday — conditionals + array methods (.map, .filter)

## May 9 2026 — Day 4 (Saturday)

### What I learned
- How to break down a problem in plain English before coding
- Why you pass the whole array into a function, not a single item
- Variable scope — variables inside a function don't exist outside it
- count = count + shift.hours pattern for running totals
- Calling a function and storing its return value in a variable

### What I built
- night-shift.js — loops through array of shift objects, calculates total hours worked, prints summary

### Mistakes made
- Semicolon inside array literal caused syntax error
- Used count++ instead of adding actual hours
- Tried to use count outside the function — ReferenceError

### Key insight
- Can't return before the loop runs — order of operations matters
- The "why" behind every decision matters more than the syntax

### Next session
- Day 5 Sunday — conditionals + array methods (.map, .filter)

## May 10 2026 — Day 5

### What I learned
- How to use if statements 
- How to use .filter() to filter out what you don't need 
- How to use .map() to display without anything being left out 

### What I built
- Built long-night-shift-log.js 
- Filters out the days that the shift was below 10 hrs using .map() and function
- Displays the days of the longshift using .map() and function
- uses function and for loop to calculate the total hours worked on the days that had long shifts 

### Mistakes made
- Typo in .filter() , used shift.hr instead of shift.hrs 
- Paranthesis placement on .filter(function(shift)){ , instead of .filter(function(shift){})

### Next session
- Day 6 Monday - forEach() + .find() + .reduce() + mini project

## May 11 2026 - Day 6

### What i Learned 
- Using array methods to calculate total using .reduce()
- Using array method .forEach() to loop through every item in an array
- Using array method .find() to find something matching condintion in an array

### What I built 
- Built monthly-paycheck-calculator.js 
- Uses array methods .filter() to find weeks with low and high paychecks
- Uses array methods to find total of weeks with low paycheck and total of weeks with high paycheck

### Mistakes made 
- Used dot notation directly on an array to get a property 

### Next Session 
- Ssync/await + fetch + hitting a public API.

## May 12 2026 - Day 7

### What i learned 
-  Using fetch() to grab data from a public API
- Using async / await to tell the code to wait for the data to arrive before moving on
- Using .json() to transform raw internet text into a usable JavaScript object.
- Using Object.values() to extract data from an object when you don't know the exact
- The power of refactoring: Taking three repetitive functions and condensing them into one clean, reusable function using a parameter (countryName).

### What I built 
- Built country-comparison.js (and a refactored v1).
- Used a public API (restcountries.com) to fetch real-world data.
- Printed out a clean comparison summary of the population, capital city, region, and languages for the USA, United Kingdom, and Germany.

### Mistakes made 
- Accessed nested data in the wrong order (tried captial.data[0] instead of data[0].capital).
- Used single quotes (') instead of backticks (`) for template literals, which stopped the variable from working.
- Hardcoded specific values (like USA or .eng) inside a reusable function, which caused an undefined error when testing other countries like Germany

### Next Session 
- Day 8 — Fetch mini project.

