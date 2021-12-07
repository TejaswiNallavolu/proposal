# Proposal For the Class Remainder App -Team 1A

## Objective of the Class Reminder App
- Our app is used to display the class schedule along with the time and location. Once the user logs in, He/She will be able to see the list of his/her upcoming classes based on their class schedule. It always shows the reminder of first class in the home page that user has to attend.

## Overview
- This app contains 2 screens to display the upcoming classes of the student.
- The upcoming class details with timings and location will be displayed in a rectangular box on the first screen.
- The first screen has buttons like login, home and upcoming classes which navigates to other screens.
- The user can view his/her upcoming class list when he/she clicks on upcoming classes button.

## Team members 
 - [Tejaswi Reddy Nallavolu](https://github.com/TejaswiNallavolu)
 - [Priyanka Thambabathula](https://github.com/Priyanka1818)

## Functionality of the app
- **Home page**
   - API to get the upcoming class along with room number and time.
   - Button to redirect the list of upcoming classes.
   - Add class button to add new class that shows subject, time, date, room number.

- **Login screen**
   - Text fields to enter username and password.
   - Button for authenticating into the application.
   - Forgot password link for reseting the password.

- **Upcoming classes list**
   - API to display list of all upcoming classes.
   - Edit button for each class to edit class details.
   - Delete button for each class to delete a class.

- **Header**
   - Your profile link to navigate to user details.
   - Logout button to logout from the application.
   
## ER-Diagram
[Click here to view ER-Diagram](https://github.com/TejaswiNallavolu/proposal/blob/main/erdiagram.png)

## Database Tables
User
- id
- name
- role
- is_delete

Class Details
- id
- user_id
- classroom_id
- class start_time
- class end_time
- is_delete

Classroom Details
- id
- room_number
- subject
- is_delete

## [Sample data](https://github.com/TejaswiNallavolu/proposal/blob/main/SampleData.xlsx)

## Schedule & sprints are set for the GDP semesters (about every 2-weeks = a sprint)

## GDP-1 

### Sprint 1  (Start Date: 20 September 2021 - 4th October 2021)
- We work on design plan and all the basic requirements gathering. 

### Sprint 2  (Start Date: 4th October 2021 - 18th October 2021)
- Enhancing and modifing the requirements and break them into functional requirements.

### Sprint 3  (Start Date: 18th October 2021 - 1st november 2021)
- Building mockups and basic UI pages using Angular.

### Sprint 4  (Start Date: 1st November 2021 - 15th November 2021)
- Working with login and Authentication pages.

 End of semester GDP-1

## GDP-2 

 ### Sprint 5  (Start Date: 12th January 2022 - 26th January 2022)
 - Create Database models and schema.

 ### Sprint 6  (Start Date: 26th January 2022 - 9th February 2022)
 - Designing web APIs

 ### Sprint 7  (Start Date: 9th Fabruary 2022 - 23rd February 2022)
 - Create APIs to fetch data from Database.

 ### Sprint 8  (Start Date: 23rd February 2022 - 9th March 2022)
 - Designing all the UI pages based on requirements

 ### Sprint 9  (Start Date: 9th March 2022 - 23rd March 2022)
 - Integration with both UI and backend.

 ### Sprint 10  (Start Date: 16th March 2022 - 30th March 2022)
 - Testing and fixing issues

 ### Sprint 11  (Start Date: 30th March 2022 - 15th April 2022)
 - Deployment of the application, and production fixes.

## BUDGET
* ### GDP1
| Names                   | Roles               | Hours per week | Cost per hour | Total hours | GDP1 Cost |
| ----------------------- | ------------------- | -------------- | ------------- | ----------- | --------- |
| [Tejaswi Reddy Nallavolu](https://github.com/tejaswinallavolu) | Front-end Developer | 20             | 40            | 160 hours    | $6400      |
| [Priyanka Thambabathula](https://github.com/Priyanka1818)  | Back-end Developer  | 15              | 40            | 120 hours    | $4800       |

* ### GDP2
| Names                   | Roles               | Hours per week | Cost per hour | Total hours | GDP2 Cost |
| ----------------------- | ------------------- | -------------- | ------------- | ----------- | --------- |
| [Tejaswi Reddy Nallavolu](https://github.com/tejaswinallavolu) | Front-end Developer | 15              | 40            | 210 hours   | $8400      |
| [Priyanka Thambabathula](https://github.com/Priyanka1818)  | Back-end Developer  | 20             | 40            | 280 hours   | $11200      |

## STACK

**Backend language + framework** 
- C#/.NET

**Backend free app host** 
- Heroku 

**Data host**
- Heroku PostgreSQL

**Front-end page plan** 
- Single Page Application

**Front-end responsive design** 
- Bootstrap

 ### ___Mock-up screens of the [ClassReminder](https://github.com/TejaswiNallavolu/1A-ClassReminder) App using HTML, CSS, Bootstrap for presentation purpose.___

### [Client Approval for the screen sketches](https://github.com/TejaswiNallavolu/proposal/blob/main/Client%20Approval%20for%20Screen%20Sketches.pdf)

**[References](https://angular.io/guide/forms)**
