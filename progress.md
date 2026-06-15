# Nixon Abuku — Roadmap Progress

## Current Status
- Week: 6
- Day: 29 complete
- Last session: June 11 2026
- Current phase: Phase 2 — Node.js + Express Job Tracker API with PostgreSQL
- Phase 2 progress: Full CRUD complete. Routes refactored into routes/jobs.js. All routes tested in Postman after refactor. Committed to GitHub.
- Current technical status: job-tracker-api has clean separation — index.js sets up the server, routes/jobs.js handles all job routes. Next step is JWT auth.
- Main roadmap: Claude Backend SWE + DevOps roadmap stays the main hands-on path
- Support track: IBM Full Stack Software Developer Certificate on Coursera — enrolled June 6 2026
- Next session: Day 30 — review refactor from memory, then start JWT auth

## Learning System Status
- Main lane: Backend SWE + DevOps roadmap with Claude
- Support lane: IBM Full Stack Software Developer Certificate on Coursera
- Rule for IBM: no passive watching. Every lesson has to turn into notes, active recall, a mini build, or something that supports the roadmap.
- Daily formula: active recall first, build with my hands, explain in plain English, then log progress
- Practice formula: Codewars for JavaScript, HackerRank SQL for SQL reps, and project work for real proof
- Career lane: backend developer, full-stack developer, healthcare IT developer, HL7 integration engineer, and later DevOps/cloud roles
- Private rule: progress.md tracks learning and public progress. Job applications, recruiter messages, and resume details stay in private project files.
- Hour tracking rule: log session hours and week total at the end of every session starting Day 25
- Proof rule: log Codewars problem name and HackerRank problem name in every progress.md entry starting Day 30

## Projects Status
- [x] Portfolio website — live on Vercel May 21
  - Live URL: https://portfolio-omega-plum-89.vercel.app
  - README completed May 22
- [x] Python CSV reader/writer proof item — completed May 18
- [x] SQL Phase 1 proof item — PostgreSQL + DBeaver + queries completed May 26
- [x] Node practice repo — Express CRUD foundation + basic error handling complete by June 4
  - First Express server pushed May 27
  - Added JSON responses, /jobs GET route, nodemon, npm run dev, Postman testing, POST /jobs, PUT /jobs/:id, and DELETE /jobs/:id
  - Full fake-array CRUD complete: GET, POST, PUT, DELETE
  - Added catch-all 404 handler for unknown routes
  - Added global error handling middleware for clean JSON error responses
  - Tested error handling in Postman and committed to GitHub
- [x] Job Tracker API — routes refactored June 11
  - job-tracker-api folder created
  - npm initialized, packages installed: express, pg, dotenv, nodemon
  - Express server running on port 3000
  - db/pool.js created with PostgreSQL connection using pg and dotenv
  - job_tracker database created in PostgreSQL
  - jobs table created with all columns
  - GET /jobs route connected to real PostgreSQL database ✅
  - POST /jobs route saving new jobs to PostgreSQL and returning 201 ✅
  - Input validation on POST /jobs — returns 400 if required fields missing ✅
  - PUT /jobs/:id route updating existing jobs in PostgreSQL and returning 200 ✅
  - DELETE /jobs/:id route removing jobs from PostgreSQL and returning 200 ✅
  - Routes refactored into routes/jobs.js — index.js is clean ✅
  - All routes tested in Postman after refactor — confirmed nothing broke ✅
  - Still to do: JWT auth, Zod validation, Jest tests, deployment
- [ ] Full-stack Job Tracker
- [ ] Docker + CI/CD
- [ ] AWS deployment
- [ ] Terraform

## Career Readiness Status
- [x] LinkedIn headline updated for backend + healthcare IT / HL7 lane — June 3
- [x] LinkedIn About section updated with portfolio and GitHub — June 3
- [x] LinkedIn skills expanded to 50 skills — June 3
- [x] Resume updated to target backend SWE + healthcare IT / HL7 integration roles — June 3
- [x] Started Week 5 light application calibration — June 3
- [x] Job application tracking moved to a private tracker outside progress.md — June 4
- [x] Added career support mode to the Claude project instructions — June 5
- [x] Responded to Jessica at Mitchell Martin — June 5
- [x] Applied to MEDFAR and BBH — June 5
- [x] Tailored resume for BBH — June 5
- [x] Fixed GitHub bio and updated pinned repos — June 5
- [x] Connected with François Biron at MEDFAR — June 5
- [x] Unpinned repos that cannot be explained from memory — June 6
- [x] Repo honesty audit completed June 8 — Healthcare-Integration-Pipeline, hl7-adt-to-dicom-mwl, Hospital-ADT-Engine stay unpinned until explained from memory
- [ ] Continue targeted applications for market research, recruiter practice, and real interview chances

## IBM Full Stack Certificate Status
- [x] Decided to add IBM Full Stack Software Developer Certificate as a support track — June 5
- [x] Confirmed the IBM course should reinforce foundations, certificate progress, LinkedIn/resume credibility, and concepts Claude may skip
- [x] Set the rule that IBM cannot replace the hands-on Backend SWE + DevOps roadmap
- [x] Enrolled in IBM Full Stack Certificate on Coursera — June 6 2026
- [x] Identified Course 1: Introduction to Software Engineering as starting point
- [ ] Start IBM course work with active recall instead of passive video watching
- [ ] Turn IBM lessons into small code reps, notes, quizzes, or roadmap reinforcement

## Claude Project Instruction / Modes Status
- [x] Roadmap Mode — keeps the Backend SWE + DevOps roadmap organized
- [x] Daily Build Session Mode — tells me exactly what to build next and keeps me moving
- [x] Debugger Mode — helps me debug without just giving me answers too fast
- [x] Feynman / Quiz Mode — forces me to explain concepts in plain English
- [x] IBM Course Companion Mode — helps me use Coursera actively instead of passively
- [x] Career Mode — resume, recruiter messages, job fit, outreach, and application strategy
- [x] Accountability Coach Mode — keeps the tone strict, honest, and focused on execution

## Project Ideas
- Shift Schedule API (Week 12)
  - Log shifts, calculate hours and pay
  - Node + Express + PostgreSQL
  - Personal use case: I work night shifts

## Sessions Completed
### Day 1 — May 6 2026
- Topics: Git fundamentals
- Built: learning-log repo, 3 commits pushed
- Commands mastered: init, add, commit, push, status, log, remote add
- Weak spots: commit message quality
- Next: JavaScript variables and data types

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
- Async/await + fetch + hitting a public API.

## May 12 2026 - Day 7

### What i learned
- Using fetch() to grab data from a public API
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

## June 2 2026 — Day 21 PUT Route + Type Conversion

### What i learned
- I learned the difference between HTTP methods and status codes again because I mixed them up at first
- HTTP methods are the actions: GET, POST, PUT, DELETE
- Status codes are the results: 200 OK, 201 Created, 404 Not Found, etc.
- CRUD means Create, Read, Update, Delete
- GET is used when the client wants to read / request data
- POST is used when the client wants to create new data
- PUT is used when the client wants to update existing data
- DELETE is used when the client wants to delete data
- A PUT request needs two things: the id in the URL and the updated data in the request body
- The URL looks like /jobs/1, but in Express the route is written as /jobs/:id
- :id is a URL parameter, not a fixed value
- req.params.id gets the id from the URL
- req.body gets the new data the client sends
- .find() searches an array and returns the actual object that matches the condition
- req.params.id comes from the URL as a string, even if it looks like a number
- job.id in my array is a number, so I had to use Number(req.params.id) before comparing
- === checks both value and type, so "1" === 1 is false
- Number("1") turns the string into the actual number 1
- if (!foundJob) is a clean way to check if .find() did not find anything
- foundJob.company = req.body.company updates an existing object instead of creating a new one
- PUT is not for adding a new job. POST creates. PUT updates

### What I built
- Reviewed the 4 REST / CRUD methods before coding
- Built a PUT /jobs/:id route in node-practice
- Used jobs.find() to search for the job that matches the id from the URL
- Used Number(req.params.id) to fix the string vs number problem
- Added a 404 response if the job does not exist
- Updated foundJob.company, foundJob.role, and foundJob.status using req.body
- Sent back a 200 response after the job was updated
- Tested the PUT route in Postman
- Sent a PUT request to /jobs/1 with new job data
- Confirmed with GET /jobs that job id 1 changed from Google to Apple / Backend Engineer / INTERVIEW

### Commands / tools used
- npm run dev — started the Express server with nodemon
- Postman PUT request — tested updating an existing job
- Postman GET request — confirmed the job actually changed
- git add . — stage updates
- git commit -m "add PUT /jobs/:id route with findJob and type conversion" — commit message for the PUT route work
- git push — push changes to GitHub

### Mistakes made
- I first gave status codes when asked for HTTP methods
- I remembered GET, POST, and DELETE, but forgot PUT at first and guessed UPDATE
- I had to reason through what the server needs to update a job instead of just trying to remember
- I wrote PUT logic outside the route at first, which caused req is not defined because req only exists inside the route function
- I forgot that the URL needed the id and tested /jobs instead of /jobs/1 in Postman
- The first PUT test returned Job not found because req.params.id was a string and job.id was a number
- I had to learn that Number(req.params.id) fixes the type mismatch
- I almost mixed up company, role, and status when assigning values from req.body
- I tried to send a message back but wrote the JSON object syntax wrong before fixing it

### Key insight
- Today helped me see that API logic is not magic. PUT needs to know which job to update and what new data to put inside it.
- The id tells the server which record to touch. The body tells the server what to change.
- The type mismatch bug was important because I will see that again in real APIs. URLs give strings. My data may use numbers. I have to convert before comparing.
- I did not finish DELETE today because I was tired, but GET, POST, and PUT are now working.

### Next session
- Day 22 Wednesday — build DELETE /jobs/:id
- Finish full CRUD
- Then move into error handling middleware and real Job Tracker API planning

## June 3 2026 — Day 22 DELETE Route + Full CRUD + Career Updates

### What i learned
- I watched the Feynman video and used it to think about how I should learn software engineering
- The 7 Feynman-style principles I pulled out were: become a self learner, learn by understanding not memorizing, do not blindly follow experts, speak my mind honestly, think from first principles, ask stupid questions, and keep learning fun
- I realized I am doing some of those, but I still need to improve on understanding, first-principles thinking, and making learning active
- I learned that looking at notes is okay right now if I actually understand what I am reading
- A function is a reusable machine that does a specific job
- In Express, the function inside app.get(), app.post(), app.put(), or app.delete() is a callback function
- The callback function does not run immediately. Express calls it later when the matching request comes in
- req is what the client sends to the server
- res is what the server uses to send something back to the client
- app.listen() also takes a callback function that runs once the server starts
- DELETE only needs the id in the URL. It does not need a request body
- .find() returns the item itself
- .findIndex() returns the position / index of the item
- .findIndex() returns -1 when it cannot find anything
- -1 is JavaScript's way of saying "not found" for indexes
- I learned why I cannot use !jobIndex to check for not found because index 0 is a real position but 0 is falsy
- jobs.splice(jobIndex, 1) means start at that position and remove 1 item
- The 1 in splice means remove one item only, not two or more
- Early return means if something is wrong, return a response and stop the function right there
- If an if block already has return, I usually do not need an else after it
- console.log() is a built-in function / method that needs parentheses
- return is a JavaScript keyword, not a function, so I do not need parentheses with return
- The same name can exist in different scopes, like a bmi function outside and a bmi variable inside the function

### What I built
- Built the DELETE /jobs/:id route
- Used jobs.findIndex() to find the position of the job by id
- Used Number(req.params.id) again because the id from the URL is a string
- Added a 404 response when the job is not found
- Used jobs.splice(jobIndex, 1) to remove the job from the array
- Sent back a 200 response with a deleted message
- Tested DELETE /jobs/2 in Postman
- Confirmed with GET /jobs that Meta was removed from the jobs array
- Completed the full fake-array CRUD API in node-practice
- Full CRUD now works: GET /jobs, POST /jobs, PUT /jobs/:id, DELETE /jobs/:id
- Committed and pushed the DELETE route work to GitHub
- Updated my LinkedIn headline to target backend + healthcare IT / HL7
- Updated my LinkedIn About section with portfolio and GitHub
- Added more LinkedIn skills and reached 50 skills
- Updated my resume to target both backend SWE roles and healthcare IT / HL7 integration roles
- Started light Week 5 application calibration and kept private details outside progress.md
- Completed one Codewars JavaScript kata: BMI calculator
- Started HackerRank SQL practice and completed the first part of the set before getting tired

### Commands / tools used
- npm run dev — ran the Express server
- Postman DELETE request — tested deleting a job
- Postman GET request — verified the job was removed
- git add . — staged the DELETE route changes
- git commit -m "add DELETE /jobs/:id route - complete CRUD" — saved the CRUD completion work
- git push — pushed the code to GitHub
- LinkedIn — updated headline, About, and skills
- Resume document — updated summary, skills, and project positioning
- Codewars — completed BMI kata
- HackerRank SQL — practiced SQL questions

### Mistakes made
- I first wrote the DELETE route path without the forward slash: jobs/:id instead of /jobs/:id
- I thought about using .find() again, but DELETE needed .findIndex() because splice needs the position
- I struggled with why Number(req.params.id) is needed, but then I understood that URL values are strings
- I thought findIndex should return a 404 by itself, but array methods do not know about HTTP responses
- I had to learn that findIndex returns -1 when nothing is found
- I was confused about why we use jobIndex === -1 instead of !jobIndex
- I had to understand that index 0 is a real item, so !0 would be a bug
- I tried to use splice like it takes a callback function, but splice only needs numbers
- I wrote jobs.splice(jobIndex) at first, but I needed jobs.splice(jobIndex, 1)
- I forgot to send a response after deleting the job at first
- In the BMI kata, I returned the BMI number too early, which stopped the if statements from running
- I had to remember: store first, then check. Do not return before the logic runs
- In SQL, I used a long alias and learned Oracle can complain when an identifier is too long
- I almost used GROUP BY when I only needed one total for the whole table

### Key insight
- Today was a big milestone because I finished full CRUD in Express.
- This is the first time my API can create, read, update, and delete data, even though the data is still just a fake array.
- I also saw that my healthcare IT / HL7 background is a real lane for job applications, not just something random from the past.
- My backend lane and healthcare integration lane can work together instead of fighting each other.
- The biggest learning today was not just DELETE. It was learning how to explain code instead of just reading words.
- When I explain in my own words, I understand more than I think I do.

### Next session
- Day 23 Thursday — Feynman review from memory
- Finish remaining HackerRank SQL problems
- Start error handling middleware if there is time
- Start planning the real Job Tracker API structure
- Keep job application details in a private tracker, not in public progress.md

## June 4 2026 — Day 23 Feynman Review + HackerRank SQL + Roadmap Sync

### What i learned
- I started with a Feynman review before touching code or notes
- I reviewed CRUD from memory: Create, Read, Update, Delete
- I reviewed the 4 HTTP methods: GET reads, POST creates, PUT updates, DELETE removes
- I caught myself almost mixing up POST and PUT, but corrected it
- I reviewed DELETE route logic in plain English before code
- DELETE logic is: get the id from the URL, find the index, check if not found, remove with splice, send a response
- I learned more SQL pattern recognition through HackerRank
- COUNT(city) - COUNT(DISTINCT city) gives the difference between total city entries and unique city names
- GROUP BY is for totals per category, but if I need one total for the whole table, I do not need GROUP BY
- LENGTH(city) counts how many characters are in a city name
- LIKE 'a%' checks if something starts with a
- LIKE '%a' checks if something ends with a
- % is a wildcard that means anything can come before or after
- OR means any condition can be true
- AND means both groups of conditions must be true
- Parentheses matter in SQL because they group OR conditions before connecting them with AND
- I learned that commas do not belong in the WHERE clause. WHERE uses AND / OR
- DISTINCT removes duplicates from the result
- I learned that job application details should stay in a private tracker, not in public progress.md
- The Claude project folder is private, so resume.md and job_applications.md can live there for context, but not in a public GitHub repo
- I also learned that my roadmap needed to be updated to match what actually happened this week

### What I built / updated
- Finished the HackerRank SQL set for the day
- Practiced SQL problems using COUNT, DISTINCT, LENGTH, LIKE, OR, AND, and parentheses
- Prepared to migrate to a new chat because the old chat was close to the image limit
- Created / planned a private job_applications.md tracker for the Claude project folder
- Confirmed the two application entries should stay private and not inside public progress.md
- Reviewed what roadmap updates were needed after this week's progress
- Updated the roadmap direction to reflect that Phase 2 Week 5 is in progress and CRUD is already complete in node-practice
- Updated the roadmap context that LinkedIn headline, About, skills, and resume updates already happened in Week 5
- Confirmed Per Scholas is not realistic right now because of my 11pm–9am work schedule
- Added HL7 Integration Engineer and Healthcare IT Developer as real target lanes alongside backend roles
- Documented that HackerRank SQL is now part of the daily formula
- Prepared the handoff prompt for starting a new chat with roadmap.md and progress.md attached

### Commands / tools used
- HackerRank SQL — completed the SQL practice set
- LinkedIn / resume context — reviewed current job-search positioning
- Claude project folder planning — decided what files should be attached privately
- progress.md — updated here to bring the log current through June 4

### Mistakes made
- I almost mixed up POST and PUT during the Feynman review, but corrected it
- I initially tried to think about SQL conditions too narrowly, like only checking a city that starts with a and ends with a
- I forgot that a city can start with one vowel and end with a different vowel
- I needed to use two groups of OR conditions and connect them with AND
- I almost used commas in the WHERE clause, but SQL uses AND / OR for conditions
- I had to be reminded to use DISTINCT when the problem asks for unique city names
- I almost put private job application information in progress.md, but that should stay private

### Key insight
- Today showed me that the review habit is working. I can forget small details, but I can reason back into them when I slow down.
- Full CRUD is already done in node-practice, so now the next real step is not more fake-array practice forever. The next step is error handling and then the real Job Tracker API structure.
- I also realized my progress files have to stay accurate because I am using them to migrate between chats and keep the roadmap alive.
- The progress.md should track learning and public progress. Job applications and resume details should live in private files.

### Next session
- Day 24 Friday — error handling middleware
- Add a catch-all 404 route for unknown endpoints
- Start setting up the real Job Tracker API project folder
- Connect PostgreSQL to Express for the first time
- Run the first real database query from the API
- Keep doing Codewars + HackerRank SQL as daily active recall

## June 4 2026 — Day 24 Roadmap Sync + IBM Full Stack Decision + Error Handling Middleware + Career Updates

### What i learned
- I learned that adding another course can help me, but only if I do not let it become a distraction
- The Claude Backend SWE + DevOps roadmap is still the main path because it makes me build real projects with my hands
- The IBM Full Stack Software Developer Certificate can support the roadmap by reinforcing foundations and giving me certificate progress
- IBM should help with LinkedIn, resume credibility, and concepts Claude may skip, but it cannot replace real project work
- I learned that passive learning is dangerous for me because watching videos can feel like progress even when I am not building anything
- The rule has to be: watch less, build more, explain more, quiz more
- I learned that having different modes inside the Claude project makes sense because not every session is the same
- Roadmap mode is for planning and sequencing
- Daily build mode is for writing code and finishing the next task
- Debugger mode is for fixing errors without skipping the thinking part
- Feynman / quiz mode is for forcing me to explain things in plain English
- IBM course companion mode is for turning Coursera into active learning
- Career mode is useful because resume, recruiter messages, job fit, and outreach are part of getting hired
- Accountability coach mode is needed because I do not want soft advice. I need honest feedback and execution
- I learned what middleware is in Express: code that runs between the request coming in and the response going back out
- Middleware runs in order from top to bottom, so placement matters a lot
- A catch-all 404 handler is for routes that do not match anything else
- The catch-all 404 handler should come after the real routes because it is the fallback, not the first thing the app should check
- A global error handler is centralized middleware that catches errors and sends one clean response format back to the client
- Express error handling middleware takes 4 parameters: err, req, res, next
- The 4 parameters matter because Express recognizes that function as an error handler only when it has err first
- Express sends HTML error pages by default, but that is a problem for an API because API clients like Postman, frontend apps, or mobile apps expect JSON
- Clean JSON errors are better because the client can read status, message, and error details in a predictable format
- I also learned that progress.md has to be corrected when the plan changes during the day. If I actually built something, the log should not still say it is next

### What I built / updated
- Updated the roadmap direction for June 4
- Added IBM Full Stack Software Developer Certificate as a support track
- Confirmed IBM is not the main roadmap and should not slow down the Job Tracker API
- Defined the project instruction modes for Claude
- Included Resume, recruiter messages, job fit, and outreach as a real mode because job search work is part of the mission
- Built a catch-all 404 handler for unknown endpoints in the Express node-practice API
- Built a global error handling middleware function
- Changed API errors from default HTML-style responses into cleaner JSON responses
- Tested the catch-all 404 handler in Postman using a route that does not exist
- Tested the global error handler in Postman
- Confirmed the middleware order matters by keeping real routes first, then the 404 handler, then the global error handler
- Committed the error handling middleware work to GitHub
- Responded to Jessica at Mitchell Martin
- Applied to MEDFAR
- Applied to BBH
- Tailored my resume for BBH
- Fixed my GitHub bio
- Updated my pinned GitHub repos
- Connected with François Biron at MEDFAR
- Updated progress.md so Day 24 reflects the actual coding and career work completed
- Kept private job application tracking outside the public progress log where needed

### Commands / tools used
- npm run dev — ran the Express server with nodemon
- Postman — tested unknown endpoints and error responses
- Git / GitHub — committed and pushed the error handling middleware work
- Claude project instructions — reviewed and updated the mode structure
- IBM Coursera planning — added as a support lane
- Resume / recruiter workflow — handled BBH, MEDFAR, Mitchell Martin, and GitHub updates
- progress.md — updated current status through June 4

### Mistakes made
- Day 24 work was actually completed on June 4, not June 5. June 5 was a skip day.
- I had to be honest about this in the next session instead of covering it up
- I had to remember that middleware order is not random. Express reads from top to bottom
- I had to understand that the 404 handler should not be placed before real routes or it would catch requests too early
- I had to learn that an error handler is different from normal middleware because it starts with err and has 4 parameters
- I had to understand why default Express HTML errors are not good enough for an API
- I almost treated IBM like it could become the new main path, but the main thing is still building backend projects
- I need to avoid jumping between too many learning tracks without producing code

### Key insight
- Full fake-array CRUD is done, and now basic Express error handling is done too.
- The API is starting to look more like a real backend because it can handle missing routes and errors in a clean way instead of just crashing or sending messy HTML.
- Middleware is not magic. It is just code that sits in the request/response pipeline, and Express runs it in the order I write it.
- The next step is the real Job Tracker API setup and PostgreSQL connection.
- Career work also counts, but it has to support the technical roadmap, not replace the build work.

### Next session
- Day 25 — real Job Tracker API setup
- Create the real Job Tracker API project folder
- Initialize npm and install the needed backend packages
- Create the Express server structure for the real project
- Connect PostgreSQL to Express for the first time
- Run the first real database query from the API
- Start moving from fake-array CRUD toward real database-backed CRUD

## June 6 2026 — Day 25 Job Tracker API Setup + PostgreSQL Connection

### What I learned
- I learned that I have to be honest with my progress because June 5 was actually a skip day
- I learned that if I skip a day, Saturday can become a makeup day instead of a full rest day
- I learned the difference between node-practice and job-tracker-api
- node-practice was just a sandbox to learn API foundations with fake array data
- job-tracker-api is the real project that will use real PostgreSQL data
- I learned again why const express = require('express') and const app = express() are different
- express is the tool I import, and app stores the Express application that gets created
- I learned that app.use(express.json()) is what lets Express read JSON from the request body
- I learned that app.listen() can still run without a callback, but the callback gives me feedback in the terminal
- I learned why node_modules goes in .gitignore because it is huge and can be recreated with npm install
- I learned why .env goes in .gitignore because it can hold passwords and database connection details
- I learned what pool.js does
- pool.js reads the database connection details from .env, creates the database connection, and lets other files use it without repeating the same connection code
- I learned that require('dotenv').config() loads the .env file into process.env
- I learned that new creates a real usable thing from a class blueprint
- I learned that Pool has a capital P because it is a class from the pg package
- I learned that fetch is for external APIs, but pool.query() is for talking directly to PostgreSQL
- I learned that async warns JavaScript that the function will pause, and await is the actual pause while waiting for the database
- I learned that result.rows is the actual data returned from PostgreSQL, not the full PostgreSQL response object

### What I built
- Created the real job-tracker-api project folder
- Ran npm init and created the package.json file
- Fixed the package name after accidentally naming it yes
- Installed express, pg, and dotenv
- Installed nodemon as a dev dependency
- Added the dev script with nodemon index.js
- Created index.js and built the Express server from memory
- Created .gitignore and added node_modules and .env
- Created the .env file with PostgreSQL connection details
- Created a new PostgreSQL database called job_tracker
- Created the db folder and db/pool.js
- Connected the app to PostgreSQL using pg, dotenv, and Pool
- Created the jobs table in DBeaver with columns for company, position, status, location, job URL, notes, interview date, applied date, created date, and updated date
- Added SERIAL PRIMARY KEY for the job id
- Added DEFAULT NOW() for created_at and updated_at
- Built the first real GET /jobs route connected to PostgreSQL
- Tested GET /jobs in Postman and got an empty array first
- Inserted a real job row into the database using DBeaver
- Tested GET /jobs again and saw real database data come back as JSON
- Initialized Git for the project
- Made the first commit with a descriptive commit message
- Pushed the job-tracker-api repo to GitHub
- Unpinned older repos from GitHub that I cannot explain from memory yet
- Scheduled Monday June 9 as the repo honesty audit day

### Commands / tools used
- mkdir job-tracker-api — created the project folder
- npm init — initialized the project
- npm install express pg dotenv — installed main packages
- npm install --save-dev nodemon — installed nodemon as dev dependency
- npm run dev — started the server with nodemon
- psql postgres — opened PostgreSQL in the terminal
- CREATE DATABASE job_tracker; — created the real project database
- DBeaver — created the jobs table and inserted test data
- Postman — tested GET /jobs and confirmed real data response
- git init, git add ., git commit, git push — first commit to GitHub

### Mistakes made
- I forgot some Express basics at first, like app.use(express.json())
- I wrote get('express') instead of require('express')
- I forgot why we store express() inside app
- I forgot what npm init does at first
- I typed yes during npm init and accidentally made the package name yes
- I forgot nodemon, pg, and dotenv at first
- I wrote commas in the npm install command, but packages should be separated by spaces
- I missed the comma in package.json between the test script and the dev script
- I put app.listen() before the route at first, but routes should come before app.listen()
- I almost changed the port to 5000 without a real reason
- I forgot how to export from Node.js and had to relearn module.exports = pool
- I forgot that SERIAL is used for auto-incrementing ids
- I wrote DEFAULT (NOW) instead of DEFAULT NOW()
- I first tried to use fetch for the database route, but PostgreSQL uses pool.query()
- I wrote result.json() at first, but res.json() is what sends data back to the client
- I almost sent back the full result instead of result.rows

### Key insight
- Today was a real milestone because the API is not using fake array data anymore.
- node-practice was just training wheels, but job-tracker-api is the real project.
- I created a real database, connected Express to PostgreSQL, wrote a real query, and got real data back in Postman.
- I also learned that I cannot keep projects pinned on GitHub if I cannot explain them from memory.
- Using AI to help me build something is not the problem. The problem is not understanding what the code does after.
- I need to keep asking simple questions until the concept clicks instead of pretending I understand.
- I also need to start tracking session hours because if I do not track them, I cannot know if I am really hitting the weekly goal.

### Session hours
- Session hours: 4
- Week total: 20

### Next session
- Day 26 — continue the real Job Tracker API
- Add POST /jobs so I can create jobs from Postman and save them into PostgreSQL
- Practice async / await, pool.query(), and SQL inserts
- Start tracking session hours and week total inside progress.md
- Monday June 9 repo audit: review the older healthcare repos and learn how to explain them honestly before pinning them again
- Enroll in IBM Full Stack Certificate on Coursera before Day 26

## June 7 2026 — Day 26 POST /jobs Route + PostgreSQL Insert

### What I learned
- I learned that POST /jobs is for creating new job data and saving it into the database
- I learned that POST is for creating new data
- I learned that PUT is for updating data that already exists
- I learned that req.body is how Express reads JSON data sent from Postman
- I learned that req represents the full request from the client
- I learned that req.body holds the JSON body sent by the client
- I learned that req.body.company pulls out the company value from the request body
- I learned that app.post('/jobs') creates a route that handles POST requests to /jobs
- I learned that the function inside the route contains the instructions that run when the client sends a POST request
- I learned that pool.query() is how Express sends SQL commands to PostgreSQL
- I learned that INSERT INTO is used to save new data into a database table
- I learned that $1, $2, and $3 are placeholders for values
- I learned that [company, position, status] fills in the placeholders
- I learned that if the values array is missing, PostgreSQL cannot fill the placeholders and throws an error
- I learned that placeholders make the query reusable and safer
- I learned that RETURNING * sends back the full row that was just created including the auto-generated id
- I learned that res.status(201).json(...) sends back a Created response with JSON
- I learned that 201 means the resource was successfully created
- I finally understood the difference between req, req.body, and req.body.company using an Amazon box analogy
- req is the whole box from the client
- req.body is the smaller container inside the box holding the JSON data
- req.body.company is one specific item pulled from that container

### What I built
- Continued the real job-tracker-api project
- Built the POST /jobs route
- Pulled company, position, and status from req.body
- Used pool.query() to insert a new job into PostgreSQL using this SQL pattern:
  INSERT INTO jobs (company, position, status) VALUES ($1, $2, $3) RETURNING *
- Passed [company, position, status] as the values array into the query
- Returned the created job back to the client as JSON
- Used res.status(201).json(result.rows) to return a 201 Created response
- Tested POST /jobs in Postman with company Apple, position Junior Backend Engineer, status APPLIED
- Confirmed the API returned a full job object with an auto-generated id of 2
- Confirmed PostgreSQL created the new row successfully
- Checked DBeaver and confirmed the new job was saved into the jobs table
- Confirmed the database had two rows after the POST test
- Committed and pushed to GitHub

### Mistakes made
- I first left the POST route body empty
- I wrote INSERT INTO(company, position, status) and forgot the table name jobs
- I wrote RETURN instead of RETURNING
- I forgot that RETURNING * has to stay inside the SQL string
- I forgot to include the values array at first
- I misspelled company as compamy
- I wrote res.status.json(...) instead of res.status(201).json(...)
- I had to review why routes should go above app.listen()

### Key insight
- GET /jobs reads job data from PostgreSQL
- POST /jobs creates new job data in PostgreSQL
- req.body is the data sent by the client — the Amazon box analogy made this click
- pool.query() is the connection between Express and PostgreSQL
- $1, $2, and $3 are placeholders that get filled by the values array
- RETURNING * gives back the full row that was created
- The Job Tracker API now has the first two CRUD operations working with a real database: read and create
- Frustration is not the same as failure. I wanted to give up today but pushed through and built something real.

### Session hours
- Session hours: 2.25
- Week total: 22.25

### Next session
- Day 27 — add validation for POST /jobs
- Make sure company, position, and status are required before inserting into PostgreSQL
- Return a clean JSON error if required fields are missing
- Practice explaining POST /jobs without notes
- Review req.body, placeholders, RETURNING *, and res.status(201).json()
- Continue IBM Introduction to Software Engineering after the main build work
- Keep tracking session hours and week total

## June 8 2026 — Day 27 Input Validation for POST /jobs + Codewars + HackerRank SQL

### What I learned
- I learned that input validation checks required fields before the API inserts data into PostgreSQL
- I learned that company, position, and status should be required for POST /jobs
- I learned that missing request body values in JavaScript can be checked with !
- I learned that !company means company is missing, empty, or not provided
- I learned that || means OR
- I learned that if (!company || !position || !status) means if any one required field is missing, the validation should run
- I learned that validation should happen before the database insert
- I learned that return stops the route early so the insert query does not run after a bad request
- I learned that 400 means Bad Request
- I learned that a clean JSON error response is better than letting the database throw a confusing error
- I reviewed that result is the full PostgreSQL response object
- I reviewed that result.rows is the actual data returned from PostgreSQL
- I reviewed that RETURNING * returns the row that was just created, not the whole table
- I learned that RETURNING * gives back the new row with database-generated fields like id, created_at, and updated_at
- I reviewed that placeholders like $1, $2, and $3 get filled by the values array
- I learned that if the values array is missing, PostgreSQL cannot fill the placeholders
- I learned Math.abs() in JavaScript — it returns the absolute value of a number
- I learned how to turn the Codewars Twice as old problem into a formula before writing code
- I practiced using LENGTH(city), ORDER BY, and LIMIT 1 for HackerRank SQL
- I reviewed that SQL tiebreakers need a second ORDER BY condition like sorting by city name alphabetically

### What I built
- Continued the real job-tracker-api project
- Added input validation to the POST /jobs route
- Checked if company, position, or status is missing before inserting into PostgreSQL
- Added validation pattern: if (!company || !position || !status) return 400 with clean JSON error
- Kept the validation before the database insert
- Confirmed the route still returns 201 when a job is created successfully
- Tested the validation in Postman by sending a request with a missing required field
- Confirmed the API returns a clean JSON error instead of saving incomplete data
- Committed and pushed the updated job-tracker-api work to GitHub
- Completed the Codewars kata: Twice as old
- Solved using: Math.abs((2 * sonYearsOld) - dadYearsOld)
- Completed 5 HackerRank SQL problems covering LENGTH, ORDER BY, LIMIT, LIKE, NOT LIKE, DISTINCT, OR vs AND logic
- Completed the repo audit for older healthcare GitHub repos
- Confirmed Healthcare-Integration-Pipeline, hl7-adt-to-dicom-mwl, and Hospital-ADT-Engine stay unpinned until I can explain them from memory

### Mistakes made
- Did not write progress.md entry on the day — had to write it next morning
- Could not explain the older healthcare repos from memory during the audit
- Started writing SQL before explaining the HackerRank problem in plain English
- Sorted by LENGTH(s.city) twice instead of using s.city ASC as the alphabetical tiebreaker
- Had to review that || means OR not AND
- Had to review that missing values in JavaScript are undefined not SQL NULL
- Had to review that validation should happen before the database insert

### Key insight
- POST /jobs now has basic input validation
- Validation protects the database from incomplete required data
- The correct order inside POST /jobs is: get data, validate, return 400 if missing, run INSERT, return 201
- The Job Tracker API now has GET /jobs, POST /jobs, and input validation all working
- Writing progress.md on the same day is non-negotiable — doing it the next morning means details get lost

### Session hours
- Session hours: 3
- Week total: 25.25

### Next session
- Day 28 — PUT /jobs/:id route for updating an existing job
- Practice explaining POST /jobs validation without notes
- Review req.body, !company, ||, return, 400, and res.status(400).json()
- Continue Codewars daily JavaScript rep
- Continue HackerRank SQL daily reps
- Schedule healthcare repo deep-dive for Saturday or Sunday

## June 9 2026 — Day 28 PUT /jobs/:id + DELETE /jobs/:id + Full CRUD Complete

### What I learned
- I learned the difference between POST and PUT more clearly
- POST /jobs is for creating a new job
- PUT /jobs/:id is for updating a job that already exists
- I learned that PUT should return 200 OK because it updates existing data, it does not create new data
- I learned that 201 Created is for POST, not PUT
- I learned that req.params.id comes from the URL
- I learned that req.body.company, req.body.position, and req.body.status come from the JSON body
- I learned that PUT /jobs/3 means the id is inside the URL
- I learned that Number(req.params.id) converts the id from a string into a number
- I learned that UPDATE jobs SET ... WHERE id = ... RETURNING * is used to update a row in PostgreSQL
- I learned that $1, $2, $3, and $4 are placeholders
- $1 is company, $2 is position, $3 is status, $4 is the job id
- I learned that the values array [company, position, status, id] fills in those placeholders
- I learned that result.rows.length === 0 means PostgreSQL did not find a matching row
- I learned that if the job does not exist, the API should return 404 Not Found
- I learned that DELETE FROM jobs WHERE id = $1 RETURNING * deletes a job from PostgreSQL
- I learned that DELETE /jobs/:id also uses req.params.id
- I learned that after deleting, I should verify the row is actually gone in DBeaver

### What I built
- Built the PUT /jobs/:id route
- Used req.params.id to get the job id from the URL
- Used Number(req.params.id) to convert the id into a number
- Pulled company, position, and status from req.body
- Used UPDATE jobs SET company = $1, position = $2, status = $3 WHERE id = $4 RETURNING *
- Passed [company, position, status, id] into pool.query()
- Added a 404 check using result.rows.length === 0
- Returned the updated job with 200 OK
- Tested PUT /jobs/1 in Postman — confirmed 200 OK and updated job returned as JSON
- Tested PUT /jobs/999 in Postman — confirmed 404 Not Found with clean JSON message
- Verified the updated job in DBeaver using SELECT * FROM jobs
- Committed and pushed the PUT route to GitHub
- Built the DELETE /jobs/:id route
- Used DELETE FROM jobs WHERE id = $1 RETURNING *
- Passed [id] into pool.query()
- Added a 404 check for jobs that do not exist
- Returned a success JSON message when a job is deleted
- Tested DELETE /jobs/2 in Postman — confirmed 200 OK
- Tested DELETE /jobs/999 in Postman — confirmed 404 Not Found
- Verified in DBeaver that job id 2 was deleted from the database
- Committed and pushed the DELETE route to GitHub
- Completed full CRUD for the Job Tracker API with PostgreSQL

### Mistakes made
- I confused POST and PUT at the start of the session
- I first described PUT using POST logic
- I thought PUT would use INSERT INTO, but PUT uses UPDATE
- I forgot that PUT should return 200 OK, not 201 Created
- I first thought the id came from req.body, but the id comes from req.params
- I wrote app.put('/jobs:id') instead of app.put('/jobs/:id')
- I wrote await.pool.query instead of await pool.query
- I tried to update the id in the SQL instead of using the id in the WHERE clause
- I forgot the values array for the placeholders at first
- I used a string/template literal inside res.json() instead of returning a real JSON object
- I tried to check result.rows before declaring result
- I added an extra parenthesis in the if statement

### Key insight
- POST creates, GET reads, PUT updates, DELETE removes
- req.params is for data in the URL
- req.body is for data sent inside the JSON body
- result.rows.length === 0 is how I check if PostgreSQL found nothing
- The Job Tracker API now has full CRUD working with PostgreSQL

### Session hours
- Session hours: 1.5
- Week total: 26.75

### Next session
- Day 29 — refactor routes into routes/jobs.js
- Review full CRUD flow without notes
- Continue Codewars and HackerRank SQL

## June 11 2026 — Day 29 Route Refactor + Separation of Concerns

### What I learned
- I reviewed the full CRUD routes from memory
- I reviewed that the Job Tracker API has GET /jobs, POST /jobs, PUT /jobs/:id, and DELETE /jobs/:id
- I learned that GET /jobs returns all jobs
- I learned that POST /jobs creates a new job, so it does not need an id in the URL
- I learned that PUT /jobs/:id updates a job that already exists
- I learned that DELETE /jobs/:id deletes a job that already exists
- I reviewed that req.params.id gets the id from the URL
- I reviewed that req.body gets the data sent inside the JSON body
- I reviewed that when PostgreSQL finds no matching row, result.rows comes back as an empty array
- I reviewed that result.rows.length === 0 is used to check if the job does not exist
- I learned why routes should be moved out of index.js
- I learned that index.js should mainly set up the server
- I learned that routes/jobs.js should handle all job routes
- I learned that this is called separation of concerns
- I learned that express.Router() creates a mini router for a group of routes
- I learned that when I use app.use('/jobs', jobRoutes), the routes inside routes/jobs.js should not repeat /jobs
- I learned that inside routes/jobs.js, GET /jobs becomes router.get('/')
- I learned that inside routes/jobs.js, POST /jobs becomes router.post('/')
- I learned that inside routes/jobs.js, PUT /jobs/:id becomes router.put('/:id')
- I learned that inside routes/jobs.js, DELETE /jobs/:id becomes router.delete('/:id')
- I learned that ./ means current folder
- I learned that ../ means go one folder up
- I learned that from inside the routes folder, the pool import should be require('../db/pool.js')

### What I built
- Started Day 29 with a short review session
- Reviewed all 4 CRUD routes before building
- Created a routes folder inside job-tracker-api
- Created a routes/jobs.js file
- Moved all job routes out of index.js into routes/jobs.js
- Changed app.get, app.post, app.put, and app.delete into router.get, router.post, router.put, and router.delete
- Added const express = require('express') inside routes/jobs.js
- Added const router = express.Router() inside routes/jobs.js
- Added const pool = require('../db/pool.js') inside routes/jobs.js
- Added module.exports = router at the bottom of routes/jobs.js
- Cleaned up index.js — removed job routes and pool import
- Imported jobRoutes into index.js using require('./routes/jobs.js')
- Registered job routes with app.use('/jobs', jobRoutes)
- Tested all 4 routes in Postman after the refactor
- Confirmed GET /jobs still returned jobs from PostgreSQL
- Confirmed POST /jobs still created a new job
- Confirmed PUT /jobs/5 updated the job status
- Confirmed DELETE /jobs/5 deleted the job successfully
- Confirmed the refactor did not break any of the 4 CRUD routes
- Committed the route refactor to GitHub

### Mistakes made
- I skipped Wednesday June 10 due to no sleep and a headache
- I first wanted to only review today, but the session still needed a real build deliverable
- I forgot that result.rows comes back as an empty array when PostgreSQL finds nothing
- I first thought routes/jobs.js needed the full Express app, but it needed express.Router()
- I wrote the wrong pool path at first with ./db/pool.js
- I had to fix the pool path to ../db/pool.js because routes/jobs.js is inside the routes folder
- I first used app.use(app, jobRoutes) which was wrong
- I also tried app.use(jobs, jobRoutes) without quotes
- I had to learn that the first argument in app.use('/jobs', jobRoutes) is the base URL path as a string
- I almost kept /jobs inside the route file which would have made the full path /jobs/jobs
- I had to fix the route paths inside routes/jobs.js to / and /:id

### Key insight
- The API still works the same after the refactor, but the structure is cleaner now
- index.js is now responsible for setting up the server
- routes/jobs.js is now responsible for handling job routes
- app.use('/jobs', jobRoutes) connects the server to the job routes
- Since /jobs is already registered in index.js, the routes file only needs / and /:id
- This refactor did not add a new feature but made the project more professional and easier to maintain
- The Job Tracker API now has full CRUD working with PostgreSQL and cleaner route structure

### Next session
- Day 30 — review the refactor from memory
- Explain how index.js connects to routes/jobs.js without notes
- Review express.Router(), module.exports, require, app.use, ./, and ../
- Start JWT auth planning
- Continue Codewars JavaScript rep — log problem name in progress.md
- Continue HackerRank SQL reps — log problem name in progress.md
- Continue IBM Introduction to Software Engineering with active recall format

### Session hours
- Session hours: 1
- Week total: 27.75
