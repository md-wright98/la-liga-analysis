# ⚽ La Liga Player Analysis - 24/25 Season

### 1. Project Definition

**What is the project?**

The aim of this project is to take performance data for every player in the 2024/2025 La Liga season, clean it, analyse it and visualise it in a simple application. The purpose is
to create an application that allows users to compare player performance, see the top performers in key areas and identify players who are performing above expectation.

**Why am I making this project?**

This project is my first attempt to plan, execute and evaluate a data analytics project. I am making this purely for educational purposes, blending my love of sports, my pursuit of a
meaningful career in a data related field and my need for a portfolio to showcase my skills into a single streamlined project.

**What will I gain from this project?**

The benefits of this project are two-fold. Firstly, I want to develop soft skills around planning and executing data projects to a professional standard, as this is something I have
not done in a professional capacity before. The second benefit is to reinforce my knowledge of python, learn some new tricks to solve problems and also have my first attempt at
building a simple application.

**Who is this project for?**

Mainly for me, and also for any future employers as proof of my capabilities.

**What about this project will make it valuable?**

The ability to easily compare players without wading through hundreds of data fields.

**How will I define success for this project?**

A clean, simple app allowing users to see top performers and compare players, with a complete set of documentation.

---

### 2. User Stories

**What should users be able to accomplish?**

1. Users should be able to choose a player and see a profile showing their information and key stats
2. Users should be able to choose two players and see a visual comparison of how their stats differ in key metrics
3. Users should be able to choose a statistic and see a list of the top 3-5 players in that metric
4. Users should be able to choose two related statistics (such as goals and assists) and see a visualisation of how each player compares to league averages 

---

### 3. Data Models

**Identify sources of useful data**

FBref provides free and readily accessible data for every player in the league, divided into key areas like goalkeeping, shooting, defensive actions etc. Some of these datasets
overlap, so collected data will need to be cleaned, aggregated and then have duplicate columns removed.

**Decide on collection methods**

Manual - since this project is a one-off, it will be quicker and more efficient to collect the data manually than to construct an unnecessary data pipeline.

**How does data relate?**

The different datasets relate to the same players, which means they can be aggregated using the player's name/club/nationality/age information. 

**What might table structures to store data look like?**

Although a database is not needed for this project, I would split the data into two tables - outfield players, which would contain all of the relevant information for players wh
are not goalkeepers, and a seperate table for goalkeepers, as not all of the fields relate to goalkeepers and this would result in a lot of empty fields.

---

### 4. Define the Product

What is my MVP?

What are the nice-to-have features?

What might my product look like?

Stretch goals?

---

### 5. Thinking about the future

What does the future look like?

Does this project need to be maintained?

What are the packaging and production requirements?

---

### 6. Creating a workflow

What are the key actions that need to be completed?

Track these items in a kanban (Trello?)

--- 

### 7. Drilling into the components

What are the steps that will make each component possible?

Create checklists for individual items that need to be completed

---

### 8. Defining the tech stack

Decide what technologies are relevant 

Install and note any packages and libraries used

---

### 9. Execution

Start working through project workflow

---

### 10. Document, reflect and iterate

Ensure all project documentation is complete and up to date

Reflect on what went well, what I learned, what could be improved

Think about what could improve this project in future iterations

What would be some fun stretch goals?
