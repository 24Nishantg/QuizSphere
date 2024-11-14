 QuizSphere

A robust QuizSphere application developed using Angular for the frontend and Spring Boot for the backend. This project is designed to facilitate online exams, providing secure login, real-time exam tracking, and class-specific quiz accessibility. 

 Features

- User Authentication: Secure login for students and admins.
- Exam Session Tracking: Monitors exam sessions, detects tab switches, and tracks user activity.
- Class-Specific Quiz Access: Students can view and attempt only the quizzes assigned to their class.
- Score Calculation: Calculates and displays scores at the end of each exam.
- Admin Panel: Allows admins to track users' activities, view exam sessions, and download session data as an Excel sheet.

 Technology Stack

- Frontend: Angular, Angular Material, and Bootstrap
- Backend: Spring Boot, MySQL
- Database: MySQL for user data, quiz questions, and exam sessions

 Installation

1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/exam-portal.git
   ```
   
2. Backend Setup:
   - Import the Spring Boot project into your IDE (e.g., Eclipse, IntelliJ).
   - Update the `application.properties` file with your MySQL configuration.
   - Run the backend server.

3. Frontend Setup:
   - Navigate to the Angular project directory.
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the Angular server:
     ```bash
     ng serve
     ```

 Usage

- Students: Login, view quizzes, take exams, and view scores.
- Admins: Monitor exam sessions, track user activity, and download session data.

 Future Improvements

- Implement additional proctoring features.
- Enhance UI for improved user experience.
- Add more configuration options for quiz settings.

 Contributing

Feel free to fork the repository and submit pull requests for any features or fixes!






 Working of the Project

This section provides a step-by-step walkthrough of the Exam Portal’s main features, complete with screenshots and a demonstration video. 

 1. User Authentication

The Exam Portal includes secure login functionality for both students and admins.

- Login Screen: Users can log in with their credentials to access the portal.
  - Screenshot:![Alt text](https://github.com/user-attachments/assets/3096d86b-52a2-4e2f-a6f2-1321378bc320)
 - Singup Screen: Users can Singup in with their credentials to access the portal.
  - Screenshot:![Alt text](https://github.com/user-attachments/assets/6b4ba570-6db8-4f42-817c-7eb916ac1e1c)


 2. Dashboard Overview

Once logged in, users are redirected to the dashboard.

- Student Dashboard: Displays available quizzes, class-specific information, and recent activities.
  - Screenshot: ![Show a sample student dashboard view](https://github.com/user-attachments/assets/716b9b10-4a10-4112-aa29-27dbdb6034cf)
- Admin Dashboard: Allows admins to manage quizzes, view exam sessions, and monitor user activity.
  - Screenshot: ![Show a sample admin dashboard view](https://github.com/user-attachments/assets/e9cca9c7-3a52-4305-8290-dd99349193fb)
  

 3. Taking an Exam

Students can access quizzes assigned to their class and start taking them.

- Quiz Selection: Students see only the quizzes meant for their class.
  - Screenshot: ![Show the quiz list for a specific class](https://github.com/user-attachments/assets/53528642-0c8e-4be0-bb66-4625ed70ea77)
- Exam Interface: The quiz starts with a timer, questions are displayed one by one, and answers are submitted.
  - Screenshot: ![Show an active quiz interface](https://github.com/user-attachments/assets/5557c6cc-88fa-4e29-b38c-1a616d79a821)
  - Screenshot: ![Show an active quiz interface](https://github.com/user-attachments/assets/f2db55b2-3c9b-4010-889d-1dae0cfdad0e)


 4. Real-Time Exam Monitoring

The application tracks real-time activities such as tab switches to prevent cheating.

- Tab Switch Detection: If a user switches tabs, the system logs the action and displays a warning.
  - Screenshot: ![Show a warning pop-up for tab switching](https://github.com/user-attachments/assets/f586f490-f8b4-4f97-8300-ac65e7f4c3b0)
    
- Instructions: user instructions , the system logs the action and displays a warning.
  - Screenshot: ![Show a warning pop-up for tab switching](https://github.com/user-attachments/assets/5a6193fa-dc2c-4289-9053-0c5eae072ac6)


 5. Admin Panel Features

Admins can monitor ongoing sessions, download session data, and view user activity.

- Exam Session Monitoring: Admins can see a list of active sessions, with data on user actions and scores.
  - Screenshot: ![Display the exam session monitoring page]()
- Download Session Data: Admins can export session data to an Excel sheet for further analysis.
  - Screenshot: ![Show the download button and an example of the exported Excel data]()
 


- Quiz Management: Admins can add, edit, or delete quizzes that students can access and attempt.
  - Add Quiz: Admins can create new quizzes, specifying the title, subject, and time limit.
    - Screenshot: ![Display the “Add Quiz” form showing input fields for quiz details](https://github.com/user-attachments/assets/e4422799-e926-466d-955d-193ebf4f2b67)
  - Edit Quiz: Modify existing quizzes to update information or change available questions.
  - Delete Quiz: Remove quizzes from the system.


- Question Management: Admins can add questions to each quiz, define question types, and specify correct answers.
  - Add Questions: Each quiz can have multiple questions with different types (e.g., multiple-choice, true/false).
    - Screenshot: ![Show the “Add Question” interface, including fields for question text, options, and answer selection](https://github.com/user-attachments/assets/a5b05607-efc4-4d14-9740-2c31eca3653f)
  - Edit Questions: Update question content and answers as needed.
  - Delete Questions: Remove questions from quizzes if they are no longer needed.

- Class Management: Admins can create and manage classes to organize students and assign quizzes accordingly.
  - Add Class: Set up new classes to categorize students by grade or section.
    - Screenshot: ![Show the “Add Class” form with fields for class name and section](https://github.com/user-attachments/assets/1a31664e-0a5b-43f7-b26d-ea4a7b181a48)
  - Assign Quizzes to Classes: Link specific quizzes to each class so that only students in that class can access them.

  

 

 6. Score Display and Feedback

At the end of an exam, students can see their scores and feedback.

- Score Screen: Students are shown a summary of their performance.
  - Screenshot: ![Show a sample score screen](https://github.com/user-attachments/assets/941d53a7-721b-4755-9968-d1d18d62452c)


 Video Demonstration

To see the full workflow of the Exam Portal, watch this [Video Demo](). (Link to video)
