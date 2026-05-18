# Nixon Abuku — Roadmap Progress

## Current Status
- Week: 2
- Day: 12 started
- Last session: May 18 2026
- Next session: May 19 2026 (Day 13 — CSS deeper: padding, margin, fonts, flexbox basics)

## Sessions Completed
### Day 1 — May 6 2026
- Topics: Git fundamentals
- Built: learning-log repo, 3 commits pushed
- Commands mastered: init, add, commit, push, status, log, remote add
- Weak spots: commit message quality
- Next: JavaScript variables and data types

## Projects Status
- [ ] Portfolio website — started May 18, structure built
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

## May 13 2026 — Day 8

### What I learned
- How to build a small fetch mini project using async / await
- How to use fetch() to get real data from an API
- How to use .json() to turn the API response into usable JavaScript data
- How to read through nested objects and arrays better
- How to make my code cleaner by using one reusable function instead of repeating myself
- I learned that understanding the data structure first makes coding way easier

### What I built
- Built fetch-mini-project.js
- Used a public API to get real data
- Created a function that fetches the data and prints a clean summary
- Practiced using template literals to display the result clearly
- Practiced reading API data and pulling out only the values I needed

### Mistakes made
- Tried to access data before fully understanding how the API response was structured
- Got confused with nested objects and arrays
- Had to slow down and console.log the data first before trying to use it
- Forgot that async functions need await when waiting for fetch() and .json()

### Key insight
- Before coding with an API, I need to look at the data first and understand what it looks like.
- Fetch is not just about grabbing data. The real skill is knowing how to read the response and pull out what I need.

### Next session
- Day 9 — Python basics: lists, dictionaries, functions

## May 17 2026 — Day 9 + Day 10 Catch-up

### What i learned
- I learned that even when I feel rusty mentally, I can still show up and get work done for consistency
- Python lists are basically like JavaScript arrays
- Python dictionaries are basically like JavaScript objects with key value pairs
- Python does not use const, let, semicolons, curly braces, or .length like JavaScript
- len() is used to count items in a Python list
- for loops in Python read almost like plain English: for shift in shifts
- Indentation matters in Python because it replaces curly braces
- Python functions use def instead of function
- F-strings are used in Python instead of JavaScript template literals
- open() is used to read files in Python
- The with open() pattern is the better way because it closes the file automatically
- 'w' mode lets Python write to a file and create the file if it does not exist
- import brings in Python modules like csv
- csv.reader reads CSV files and gives each row back like a list

### What I built
- Rebuilt monthly-paycheck-calculator from memory as a JavaScript warmup
- Used .filter() to separate high paycheck weeks and low paycheck weeks
- Used .forEach() to display each week and paycheck
- Used .reduce() to calculate high paycheck total, low paycheck total, and full monthly total
- Created python-practice folder and started a new Python repo
- Built day9.py with Python lists, loops, dictionaries, and a function
- Built day10.py to read shifts.txt, write summary.txt, and read shifts.csv
- Created and pushed the python-practice GitHub repo

### Commands used
- git init — started the new Python repo
- git add . — added all files at once
- git commit -m "..." — saved the Python work
- git push — pushed the work to GitHub
- /usr/bin/python3 day9.py — ran Python file
- /usr/bin/python3 day10.py — ran Python file

### Mistakes made
- Put a semicolon in Python because I was still thinking in JavaScript
- Tried to use .length in Python instead of len()
- Forgot dictionary keys need quotes in Python
- Mixed up list access and dictionary access
- Used backticks like JavaScript instead of Python f-strings
- Got confused with quotes inside f-strings
- Passed the whole list into a function when the function needed one single item
- Used open(summary.txt) without quotes and got a NameError
- Used print() when I needed summary.write() to write into the file
- Tried csv.reader() without passing in the CSV file
- Looped through the raw CSV file instead of looping through the reader variable
- Typo: imprt instead of import

### Key insight
- Today did not feel sharp, but it still counted because I showed up and built.
- Python concepts are not brand new — a lot of them match JavaScript, but the syntax is different.
- Files matter in backend because data is not always in a database. Sometimes it is logs, configs, exports, or CSV files.
- I should not rush the CSV reader/writer proof item while tired. It is better to do it fresh and actually understand it.

### Next session
- Day 11 Monday — requests library + build the CSV reader/writer script
- This is the Phase 1 proof item, so I need to do it properly instead of rushing it tired

## May 18 2026 — Day 11 Complete + Day 12 Started

### What i learned
- I learned that just because I forget syntax does not mean I forgot everything
- csv.reader reads the CSV file and gives each row back as a list
- The first row in a CSV is usually the header row and I can skip it using next(reader)
- CSV numbers come in as strings first, so I have to convert them with int() before doing math
- Running totals start at 0 before the loop and then get updated inside the loop
- total_pay = total_pay + pay means keep adding each week's pay instead of replacing the total
- csv.writer writes data into a new CSV file
- writer.writerow() needs parentheses because it is a function call, not square brackets
- HTML is the structure of the page
- CSS is what controls how the page looks
- The head has page setup like title and stylesheet link
- The body has what actually shows on the page
- section tags help organize the portfolio into clean parts
- ul is the whole list and li is each item inside the list

### What I built
- Built day11.py / csv-summary script that reads shift data from a CSV file
- Used csv.reader to read shifts2.csv
- Skipped the header row using next(reader)
- Converted hours and rate from strings into integers
- Calculated total hours worked and total pay earned
- Printed the total pay and total hours in the terminal
- Created summaryshift2.csv using csv.writer
- Wrote total_hours and total_pay into the new CSV file
- Completed the Python CSV reader/writer proof item for Phase 1
- Started the portfolio website
- Built index.html with my name, short bio, GitHub link, projects, skills, education, and work experience
- Connected styles.css to index.html
- Added a dark background and white text
- Got the portfolio page opening in the browser

### Commands used
- /usr/bin/python3 day11.py — ran the Python CSV summary script
- git add . — added all updated files at once
- git commit -m "..." — saved the Python CSV proof item and portfolio work
- git push — pushed the work to GitHub

### Mistakes made
- I could not remember the csv.reader syntax at first
- Tried csvopen even though CSV files are still opened with open()
- Passed 'shifts' as a string into csv.reader instead of passing the shifts variable
- Tried to start the for loop before storing csv.reader in a variable
- Forgot how to skip the CSV header row at first
- Tried to convert two values with int() at the same time
- Tried to use row[3] even though the CSV only had row[0], row[1], and row[2]
- Converted values with int() but did not store them in variables at first
- Updated pay instead of updating total_pay
- Set total_pay = pay + 0 instead of accumulating with total_pay = total_pay + pay
- Used writer.writerow[] instead of writer.writerow()
- In HTML, I used h4 for things that should have been descriptions
- Used ul like each skill item instead of using one ul with li items inside

### Key insight
- Today showed me that forgetting syntax is not the same as starting over.
- I can forget the exact syntax and still rebuild it with hints because the concept is slowly getting in my head.
- Active learning works because I had to struggle, make mistakes, fix them, and explain what I was doing.
- The CSV script matters because backend work is not always databases. Sometimes data comes from CSV files, logs, exports, or configs.
- My portfolio does not have to look perfect on day one. The structure matters first, then I improve the design with CSS.
- I should measure myself against Day 1, not against mastery. I am not a master yet, but I am building proof that I am improving.

### Next session
- Day 13 Tuesday — CSS deeper: padding, margin, fonts, flexbox basics
- Make the portfolio look less like a plain document and more like a real page
- Keep using active recall before starting: rewrite one small piece from memory before moving forward
