# Nixon Abuku — Roadmap Progress

## Current Status
- Week: 4
- Day: 18 complete
- Last session: May 27 2026
- Current phase: Phase 2 started early — Node.js + Express basics
- Next session: May 28 2026 (Day 19 — Node/Express routes, JSON responses, and request/response practice)

## Sessions Completed
### Day 1 — May 6 2026
- Topics: Git fundamentals
- Built: learning-log repo, 3 commits pushed
- Commands mastered: init, add, commit, push, status, log, remote add
- Weak spots: commit message quality
- Next: JavaScript variables and data types

## Projects Status
- [x] Portfolio website — live on Vercel May 21
  - Live URL: https://portfolio-omega-plum-89.vercel.app
  - README completed May 22
- [x] Python CSV reader/writer proof item — completed May 18
- [x] SQL Phase 1 proof item — PostgreSQL + DBeaver + queries completed May 26
- [x] Node practice repo — first Express server pushed May 27
- [ ] Job Tracker API — Phase 2 main project coming next
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

## May 20 2026 — Day 13 Complete + Day 14 Started

### What i learned
- I learned that missing one day does not mean the whole roadmap is messed up if I come back and catch up properly
- CSS is not just about colors, it is really about spacing, layout, and making the page feel less like a plain document
- padding is the space inside an element
- margin is the space outside an element
- max-width keeps the page from stretching too wide across the whole screen
- Font choice matters because the Inter font made the portfolio look cleaner right away
- Section spacing matters because it makes the page easier to read
- Border lines under headings can make sections look more intentional
- Flexbox is used for layout and helps control whether things are stacked or side by side
- flex-direction: column means items stack vertically
- flex-direction: row means items go side by side horizontally
- Tailwind CSS is different from regular CSS because I add ready-made classes directly inside my HTML instead of writing every style in styles.css
- Tailwind reset the default browser styles at first, so the page looked worse for a second, but that showed me Tailwind gives me full control

### What I built
- Continued styling my portfolio website
- Added better spacing using padding and margin
- Added max-width so the page does not stretch too wide
- Added the Inter font to make the portfolio look more professional
- Added teal accent lines under the section headings
- Created a hero section for my name, description, and GitHub link
- Practiced flexbox basics on the hero section
- Added Tailwind CSS using the CDN link in the HTML head
- Started rebuilding the portfolio styling with Tailwind classes
- Added Tailwind classes to the body, h1, h2, and links
- Committed and pushed the CSS/Tailwind progress to GitHub

### Commands used
- git add . — added the portfolio updates
- git commit -m "add CSS styling, font, spacing, section headings, flexbox hero" — saved the CSS/flexbox work
- git push — pushed the portfolio updates to GitHub

### Mistakes made
- I mixed up git add and git commit and tried putting the commit message with git add
- At first I expected flexbox row to show a big difference, but the elements were still block elements so it did not look different
- Tailwind reset the default styles and made the page look plain again at first
- I had to slow down and understand that Tailwind does not style things for me automatically, I still have to add the right classes
- I almost wanted to jump straight to a better looking AI-generated design instead of learning the CSS/Tailwind piece myself

### Key insight
- Today showed me that design is not magic. A portfolio starts looking better from small things like spacing, font, max-width, colors, borders, and layout.
- I also learned that I should not compare my beginner portfolio to polished developer portfolios yet. I need to build the real thing first and keep improving it every week.
- Tailwind is powerful, but I still have to understand what the classes are doing instead of just copying them.

### Next session
- Day 14 Thursday — portfolio build day
- Add navbar, project cards, skill tags, and layout improvements
- Keep the goal simple: make it better and get closer to deployment

## May 21 2026 — Day 14 Complete

### What i learned
- I learned that a deployed basic portfolio is better than a perfect portfolio that is not live
- A navbar helps users jump to different sections on the page
- id attributes connect the navbar links to the sections on the same page
- Project cards make my work look more organized instead of just listing projects as plain text
- Skill tags look more professional than a normal bullet list
- A photo in the hero section makes the portfolio feel more real and personal
- The alt attribute on an image is important because it describes the image
- object-cover helps the photo crop properly without stretching it
- Vercel can deploy a static HTML/CSS portfolio from GitHub
- Once the portfolio is connected to Vercel, every future GitHub push can update the live site
- I learned not to gitignore the photo because Vercel needs the image from GitHub to show it on the live website
- I can save the AI-generated design as a future target, but I should not let it stop me from deploying what I actually built

### What I built
- Added a top navbar with jump links
- Added project cards for JavaScript Paycheck Calculator and Python Shift CSV Analyzer
- Added links from the project cards to my GitHub repos
- Added skill tags for JavaScript, Python, SQL, Git, HTML, and CSS
- Added my photo to the hero section as photo.jpeg
- Updated my headline/description to sound stronger
- Added .gitignore for the design reference image only
- Committed and pushed the portfolio updates to GitHub
- Deployed the portfolio to Vercel
- Got my first live portfolio URL: https://portfolio-omega-plum-89.vercel.app

### Commands used
- echo "design.jpeg" > .gitignore — ignored the design reference image
- git add . — added the portfolio updates
- git commit -m "add photo, navbar, project cards, skill tags" — saved the portfolio build work
- git push — pushed the portfolio to GitHub

### Mistakes made
- I almost wanted to gitignore the photo, but that would have stopped the photo from showing on Vercel
- I started comparing my current portfolio to a much more polished portfolio and it made mine feel too basic
- I had to remind myself that my current goal is a real deployed portfolio, not a perfect design yet
- I had a typo in one of the project card descriptions and needed to clean it up
- I wanted to build the AI-generated design right away, but that design is more of a Week 9 / React-level target

### Key insight
- Today was a big milestone because I got a real live URL. This is not just practice sitting on my laptop anymore.
- My portfolio is basic, but it is real, public, and deployable. That matters more than waiting until it looks perfect.
- I can keep improving the design over time as I learn more CSS, Tailwind, and later React.
- This is my first public proof item for Phase 1, and now I have something I can actually put on my resume.

### Next session
- Day 15 Friday — portfolio polish + README
- Clean up any remaining portfolio issues
- Start SQL early if there is time
- Install PostgreSQL on my Mac, connect to it from the terminal, and write my first SELECT query

## May 22 2026 — Day 15 Complete

### What i learned
- I learned that a README is part of making a project look professional, not just something extra
- PostgreSQL is where a backend app can store data permanently
- A database is basically storage for data, and a backend needs one because the app has to save and use data
- A table organizes data inside the database using rows and columns, almost like a spreadsheet
- Each row in the job_tracker table is one job application
- Each column describes one piece of that job application like job_id, company, job_title, date_applied, and status
- SERIAL means the id auto-increments by itself, so I do not have to manually create the id
- VARCHAR(255) is used for text values like company, job title, and status
- DATE is used when the database needs to store an actual date
- CREATE DATABASE creates a new database
- \c learning connects me to the learning database inside psql
- DBeaver is a visual tool I can use to work with PostgreSQL instead of doing everything in the terminal
- CREATE TABLE creates a table and defines the columns plus the data type for each column
- INSERT INTO adds new rows into a table
- I should not include job_id inside the INSERT because SERIAL handles that automatically
- Text values and date values need single quotes in SQL
- PostgreSQL dates should be written in the format 'YYYY-MM-DD'
- SELECT * FROM job_tracker shows all columns from the job_tracker table
- WHERE lets me filter rows based on a condition
- WHERE status = 'APPLIED' is basically like using .filter() in JavaScript, but in SQL syntax

### What I built
- Completed the portfolio README
- Connected to PostgreSQL from the terminal using psql
- Created the learning database
- Connected to the learning database in DBeaver
- Opened a new SQL script inside DBeaver
- Created my first job_tracker table
- Added columns for job_id, company, job_title, date_applied, and status
- Used SERIAL, VARCHAR(255), and DATE as SQL data types
- Inserted a job application row into the job_tracker table
- Inserted more sample job rows with different statuses
- Used SELECT * to view the rows in the table
- Used WHERE to filter the table by status
- Practiced explaining the SQL in plain English before running it
- Used my notebook first before typing some of the SQL in DBeaver

### Commands / SQL used
- psql postgres — connected to PostgreSQL from the terminal
- CREATE DATABASE learning; — created the learning database
- \c learning — connected to the learning database
- CREATE TABLE job_tracker (...) — created the job tracker table
- INSERT INTO job_tracker (...) VALUES (...); — added job application rows
- SELECT * FROM job_tracker; — viewed all rows and columns
- SELECT * FROM job_tracker WHERE status = 'APPLIED'; — filtered rows by status
- Ctrl + Enter — ran SQL statements inside DBeaver

### Mistakes made
- I did not remember the command to open PostgreSQL in the terminal at first
- DBeaver gave an error because the connection was using the wrong PostgreSQL role / username
- I had to fix the connection before working inside DBeaver
- I almost included job_id in the INSERT even though SERIAL creates the id automatically
- I forgot that text values need single quotes in SQL
- I forgot that the date also needs single quotes
- I used date as the column name in the INSERT, but the real column name was date_applied
- I had to read the error message carefully instead of guessing
- I had to slow down and match my INSERT columns to the table columns exactly

### Key insight
- Today made SQL feel less scary because it connects to stuff I already learned.
- INSERT is like adding data.
- SELECT is like reading data.
- WHERE is like filtering data.
- The job_tracker table is basically the database version of the Job Tracker API I will build later.
- The same logic keeps showing up in different languages. JavaScript has .filter(), Python has loops and files, and SQL has WHERE.
- Reading errors is becoming part of the work. The error told me exactly what column was wrong, and I fixed it.

### Next session
- Saturday May 23 — rest day
- Sunday May 24 — long SQL session
- Go deeper into SELECT, INSERT, UPDATE, DELETE, JOIN, GROUP BY, schemas, and table relationships
- Keep writing the logic in plain English before running SQL

## May 25 2026 — Day 16 SQL Deep Dive

### What i learned
- I learned that missing the Sunday long session does not mean the roadmap is broken if I come back and do the work
- UPDATE changes existing rows instead of creating new rows
- SET tells SQL what value I want to change
- WHERE is very important with UPDATE and DELETE because it controls which exact row gets changed or removed
- DELETE removes rows from a table
- DELETE needs FROM before the table name
- ORDER BY arranges data in a certain order
- LIMIT controls how many rows come back
- I can insert multiple rows at once using one INSERT statement with multiple VALUES
- PRIMARY KEY identifies each row uniquely
- FOREIGN KEY connects one table to another table
- Table relationships are how real backend databases connect data instead of putting everything in one giant table
- JOIN lets me connect data from two tables together
- GROUP BY lets me group rows together and summarize them
- COUNT, SUM, and AVG are aggregate functions that help summarize data
- SQL is not just storing data. It is also a way to ask questions about the data

### What I built
- Continued working inside the learning PostgreSQL database
- Used DBeaver to run SQL visually
- Added more job application rows to the job_tracker table
- Inserted multiple companies and statuses in one INSERT statement
- Updated Amazon from INTERVIEWING to OFFERED
- Deleted the Meta row from the table
- Used SELECT * to check if the changes worked
- Practiced ORDER BY to sort job applications
- Practiced LIMIT to return only a certain number of rows
- Practiced filtering with WHERE
- Practiced table relationship thinking with primary keys and foreign keys
- Practiced JOINs to connect related tables
- Practiced GROUP BY with COUNT / SUM / AVG style summary thinking
- Kept using my notebook to write the SQL logic before running it

### Commands / SQL used
- INSERT INTO job_tracker (...) VALUES (...), (...), (...); — inserted multiple rows at once
- UPDATE job_tracker SET status = 'OFFERED' WHERE company = 'Amazon'; — changed an existing row
- DELETE FROM job_tracker WHERE company = 'Meta'; — removed one row
- SELECT * FROM job_tracker; — checked the table
- SELECT * FROM job_tracker ORDER BY date_applied; — sorted rows
- SELECT * FROM job_tracker LIMIT 3; — limited the result
- JOIN — connected tables together
- GROUP BY — grouped rows for summaries
- COUNT(), SUM(), AVG() — summarized data

### Mistakes made
- I wrote UPDATE with WHERE before SET at first
- I had to learn that SQL has a specific order: UPDATE table, then SET, then WHERE
- I wrote DELETE job_tracker instead of DELETE FROM job_tracker at first
- I had to slow down and remember that without WHERE, UPDATE or DELETE can affect too many rows
- I had to keep checking exact column names instead of guessing
- I still needed reminders that SQL statements have a pattern and the order matters

### Key insight
- Today made SQL feel more real because I was not just creating a table anymore. I was changing, deleting, sorting, limiting, and connecting data.
- UPDATE and DELETE showed me why databases require careful thinking. One small missing WHERE can change the wrong data.
- JOINs showed me that real databases are built from connected tables, not one giant messy table.
- GROUP BY showed me that SQL can summarize information, not just store it.
- This is all preparing me for the Job Tracker API because the backend will eventually send requests to PostgreSQL and PostgreSQL will return the data.

### Next session
- Day 17 Tuesday — SQL review, rebuild practice, HackerRank SQL problems, and Phase 1 audit
- Make sure I can still write the main SQL commands without just copying them
- Check that Phase 1 proof items are complete before moving into Node.js / Express

## May 26 2026 — Day 17 SQL Review + Phase 1 Audit

### What i learned
- I learned that review is not passive watching. Review means rebuilding from memory and checking what I actually remember
- SQL syntax still needs repetition, but the concepts are starting to connect
- SELECT reads data
- INSERT adds data
- UPDATE changes data
- DELETE removes data
- WHERE filters rows
- ORDER BY sorts rows
- LIMIT controls how many rows come back
- GROUP BY groups data so I can summarize it
- JOIN connects tables together using related columns
- HackerRank SQL problems are useful because they force me to read the question and write the query myself
- The proof items matter because they show actual progress instead of just saying I studied
- Phase 1 was not about being a master. It was about building the foundation and proof that I can keep going

### What I built / reviewed
- Reviewed the SQL commands from the previous session
- Rebuilt the SQL logic from memory instead of just looking at old queries
- Practiced SELECT, WHERE, ORDER BY, LIMIT, UPDATE, DELETE, JOIN, and GROUP BY
- Completed 5 HackerRank SQL practice problems
- Audited Phase 1 proof items
- Confirmed the portfolio is live on Vercel
- Confirmed the Python CSV reader/writer script is complete
- Confirmed the PostgreSQL / SQL proof item is complete
- Confirmed the GitHub repos are showing real work
- Confirmed I am ready to start Phase 2 early with Node.js and Express

### Commands / SQL reviewed
- SELECT * FROM table_name;
- SELECT column_name FROM table_name WHERE condition;
- INSERT INTO table_name (...) VALUES (...);
- UPDATE table_name SET column = value WHERE condition;
- DELETE FROM table_name WHERE condition;
- ORDER BY column_name;
- LIMIT number;
- JOIN related tables
- GROUP BY column_name
- COUNT(), SUM(), AVG()

### Mistakes made
- I still needed repetition with exact SQL order
- I had to slow down and not treat WHERE as a standalone command
- I had to remember that column names must match exactly
- I had to remind myself that HackerRank questions are about understanding the question first, not rushing into typing SQL
- I had to stop measuring myself against mastery and measure myself against where I started on Day 1

### Key insight
- Phase 1 is basically complete now.
- I am not a master yet, but I have real proof items: a live portfolio, JavaScript mini projects, a Python CSV script, and real PostgreSQL/SQL practice.
- The biggest improvement is not just the code. It is that I am learning to think before I code, write the logic in plain English, make mistakes, read errors, and fix them.
- I am ready to move into Phase 2 because Node.js and Express will build directly on the JavaScript and SQL foundation I already started.

### Next session
- Day 18 Wednesday — start Node.js and Express
- Build the first basic server
- Understand runtime vs framework
- Learn request and response using the waiter / restaurant analogy

## May 27 2026 — Day 18 Node.js + Express Started

### What i learned
- I learned that Node.js is not a framework. Node.js is a runtime environment
- A runtime environment means it lets JavaScript run outside the browser
- I realized I had already been using Node.js when I ran files like node day1.js or node country-comparison.js in the terminal
- Express is the framework built on top of Node.js that makes it easier to build servers
- React is a library for the frontend, not technically a framework
- npm means Node Package Manager
- npm init means initialize the folder as a Node project for the first time
- package.json is like the project's ID card because it tracks project information and dependencies
- npm install express downloads Express into the project
- node_modules is where installed packages live, but I should not push node_modules to GitHub
- .gitignore tells Git what files or folders to ignore
- A server is like a waiter: it receives a request and sends back a response
- The client is like the customer
- The server is like the waiter
- The database is like the kitchen
- A route is an instruction that tells the server what to do when someone visits a specific path
- GET means the client is asking the server to give something back
- '/' is the home route / main entrance of the server
- req means request, which is what the client sends
- res means response, which is what the server sends back
- res.send() sends text or data back to the client
- app.listen() tells the server what port to listen on
- localhost:3000 is my own computer serving the app locally on port 3000

### What I built
- Created a new folder called node-practice
- Initialized a Node project using npm init -y
- Installed Express using npm install express
- Created package.json and package-lock.json
- Created .gitignore and ignored node_modules
- Created index.js
- Imported Express with require('express')
- Created an Express app with express()
- Built my first route with app.get('/')
- Sent back "Hello World" using res.send()
- Started the server on port 3000 using app.listen()
- Ran the server with node index.js
- Opened localhost:3000 in the browser and saw Hello World
- Created a GitHub repo for node-practice
- Committed and pushed the first Express server to GitHub

### Commands used
- npm init -y — created package.json with default settings
- npm install express — installed Express
- echo "node_modules" > .gitignore — stopped Git from tracking node_modules
- node index.js — ran the Express server
- Ctrl + C — stopped the server
- git init — started the repo
- git add . — staged all files
- git commit -m "first express server - hello world on port 3000" — saved the first server
- git push — pushed node-practice to GitHub

### Mistakes made
- I thought Node.js was a framework at first, but learned it is a runtime
- I thought React was a framework, but learned it is a frontend library
- I thought runtime meant how long the code runs, but learned it means the environment where code runs
- At first I thought the input was console.log("Hello World"), but then learned the input is the client request
- I started thinking about fetch / async / await, but that is for making requests, and today I was building the server that receives requests
- I tried const app = require('express') first, but then learned the better convention is const express = require('express') and const app = express()
- I forgot express needs quotes inside require('express')
- I used a backslash instead of a forward slash for the route path at first
- I tried to put a string directly in app.get() instead of giving it a function
- I wrote res("Hello World") instead of res.send("Hello World")
- I accidentally put a quote after res in function(req, res)
- I misspelled app.listen as app.listien
- I used port 300 instead of 3000 at first
- I got a git pathspec error while committing, but I fixed it and still pushed the repo

### Key insight
- Today felt like a major shift because I built my first real server.
- Before today, JavaScript was mostly scripts and mini projects. Now I used JavaScript to make something that listens for a browser request and sends a response back.
- The waiter analogy helped everything click: browser asks, server responds, database will later provide the stored data.
- This is the beginning of the backend part of the roadmap.
- The Job Tracker API does not feel as abstract anymore because I can see the first piece: a server listening on a port and responding to requests.

### Next session
- Day 19 Thursday — continue Node.js and Express
- Add more routes
- Practice JSON responses
- Understand request and response more deeply
- Start thinking about how routes like /jobs will eventually connect to PostgreSQL
