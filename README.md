# Study-Planner-App

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)


## General Information
- This project is a good start towards the usage of Android Studio for development of Android apps
- Students can use this app to organise and plan their work

## Technologies Used
- Android Studio and JDK 17.0.1
- SQLite Database
- ## Features
### Home
- The homescreen of the app has 4 tabs "Study Plans", "Assignments", "Exams", and "Lectures"
- Student can access the tabs and can use features provided under each tab
#### Study Plans Tab
- The study plan tab displays the study plans user has added
- It uses a recycler view to display each study plan. Each row of the recycler view displays title of the study plan; date and time set by the user for that particular study plan; course title and description
- The user can click on any study plan under this tab to either modify the details or delete it completely
- A floating action button with "+" sign is provided in the bottom right corner of the screen for the user to add new study plans. Clicking that button takes user to a screen where he is prompted to enter details of the study plan, namely, "title", "course title", "description", "date", and "time"
#### Assignments Tab
- The assignments tab displays the assignments user has added
- It uses a recycler view to display each assignment. Each row of the recycler view displays title of the exam; date and time (deadline) set by the user for that particular assignment; course title and description
- The user can click on any assignment under this tab to either modify the details or delete it completely
- A floating action button with "+" sign is provided in the bottom right corner of the screen for the user to add new assignments. Clicking that button takes user to a screen where he is prompted to enter details of the assignment, namely, "title", "course title", "description", "date", and "time"
#### Exams Tab
- The exams tab displays the exams user has added
- - It uses a recycler view to display each exam. Each row of the recycler view displays title of the exam; date and time given by the user for that particular exam; course title and description
- The user can click on any exam under this tab to either modify the details or delete it completely
- A floating action button with "+" sign is provided in the bottom right corner of the screen for the user to add new exam. Clicking that button takes user to a screen where he is prompted to enter details of the exam, namely, "title", "course title", "description", "date", and "time"
#### Lectures Tab
- The study plan tab displays the lectures user has added
- It uses a recycler view to display each lecture. Each row of the recycler view displays title of the lecture; date and time set by the user for that particular lecture; course title and description
- The user can click on any lecture under this tab to either modify the details or delete it completely
- A floating action button with "+" sign is provided in the bottom right corner of the screen for the user to add new lectures. Clicking that button takes user to a screen where he is prompted to enter details of the lecture, namely, "title", "course title", "description", "date", and "time"

### Calendar
- Calendar screen displays a calendar and once a date is selected on the calendar, the user can see below the calendar, the number of study plans, assignments, exams, and lectures scheduled for that date
- We used the calendar view provided by Android Studio for displaying the calendar

### Side Navigation Drawer
- Student can use the side navigation drawer to switch between the aforementioned Home and Calendar screens



![Screenshot 2024-12-05 184927](https://github.com/user-attachments/assets/c85aa808-8cd5-4934-998c-de20e94e7800)

![Screenshot 2024-12-05 184940](https://github.com/user-attachments/assets/7eeb260b-8a40-495d-a58a-323236826fb4)
![Screenshot 2024-12-05 184913](https://github.com/user-attachments/assets/c73b4d52-ca8e-4927-b347-65119c80e8bf)
![Screenshot 2024-12-05 184824](https://github.com/user-attachments/assets/6a1a0c49-4b71-4132-940a-5b8de091b4f0)
