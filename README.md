[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# THE PROBLEM

Saraswati John is looking for a health insurance quote using this application.

## INPUT

- Name: Saraswati John
- Gender: Female
- Age: 33 years
- Current health:
  - Hypertension: No
  - Blood pressure: No
  - Blood sugar: No
  - Overweight: No
- Habits:
  - Smoking: No
  - Alcohol: Yes
  - Daily exercise: Yes
  - Drugs: No       


## OUTPUT

- Health Insurance Premium for Ms. John: Rs. 6,856


## BUSINESS RULES

- Base premium for anyone below the age of 18 years = Rs. 5,000
- % increase based on age: 18-25 -> + 10% | 25-30 -> +10% | 30-35 -> +10% | 35-40 -> +10% | 40+ -> 20% increase every 5 years
- Gender rule: Male vs female vs Other % -> Increase 2% over standard slab for Males
- Pre-existing conditions (Hypertension | Blook pressure | Blood sugar | Overweight) -> Increase of 1% per condition
- Habits
  - Good habits (Daily exercise) -> Reduce 3% for every good habit
  - Bad habits (Smoking | Consumption of alcohol | Drugs) -> Increase 3% for every bad habit



# SOLVING THE PROBLEM

- You could use the following tools to solve this problem
    - IDE: Any IDE 
    - Java 8
    - Tomcat
    - JBoss
    - Git
    - My SQL
    - Postgre SQL
    - Sublime Text
- Fork this repo
- Follow TDD. Raise the first PR with failing tests
- Keep adding code that you write in git
- Setup and run the application
- Raise PR with implementation after the test PR has been approved
- [Raising PR from a fork](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)


**HAPPY TEST DRIVING :)**
