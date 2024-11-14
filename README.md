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
  - Screenshot:![Alt text](https://drive.google.com/file/d/1H22SnK1FtH0_bY8VL0xK-JG-PzRUc2uy/view?usp=sharing)
 - Singup Screen: Users can Singup in with their credentials to access the portal.
  - Screenshot:![Alt text](https://drive.google.com/file/d/1QrmQL4_W2LR2t6v8pZAaGpiLPOXmIQb7/view?usp=sharing)


 2. Dashboard Overview

Once logged in, users are redirected to the dashboard.

- Student Dashboard: Displays available quizzes, class-specific information, and recent activities.
  - Screenshot: ![Show a sample student dashboard view](https://drive.google.com/file/d/1tduYwcAvD625t_blrBJP73xpKfCQc-P-/view?usp=sharing)
- Admin Dashboard: Allows admins to manage quizzes, view exam sessions, and monitor user activity.
  - Screenshot: ![Show a sample admin dashboard view](https://drive.google.com/file/d/1_C_QUQVcDF6AfTAy0UghhUw6OkZNiVjw/view?usp=sharing)
  

 3. Taking an Exam

Students can access quizzes assigned to their class and start taking them.

- Quiz Selection: Students see only the quizzes meant for their class.
  - Screenshot: ![Show the quiz list for a specific class](https://drive.google.com/file/d/1O9rP2dYy8aeqqYgLgXata-erj1CNJMHU/view?usp=sharing)
- Exam Interface: The quiz starts with a timer, questions are displayed one by one, and answers are submitted.
  - Screenshot: ![Show an active quiz interface](https://drive.google.com/file/d/1yNbasWQjLx0tf0w7GnOI7Muwu5lyQjkE/view?usp=sharing)


 4. Real-Time Exam Monitoring

The application tracks real-time activities such as tab switches to prevent cheating.

- Tab Switch Detection: If a user switches tabs, the system logs the action and displays a warning.
  - Screenshot: ![Show a warning pop-up for tab switching](https://drive.google.com/file/d/1Iu7RjIC32BItbdpVhMyajITVAdDvSCGs/view?usp=sharing)


 5. Admin Panel Features

Admins can monitor ongoing sessions, download session data, and view user activity.

- Exam Session Monitoring: Admins can see a list of active sessions, with data on user actions and scores.
  - Screenshot: ![Display the exam session monitoring page]()
- Download Session Data: Admins can export session data to an Excel sheet for further analysis.
  - Screenshot: ![Show the download button and an example of the exported Excel data]()
 


- Quiz Management: Admins can add, edit, or delete quizzes that students can access and attempt.
  - Add Quiz: Admins can create new quizzes, specifying the title, subject, and time limit.
    - Screenshot: ![Display the “Add Quiz” form showing input fields for quiz details](https://drive.google.com/file/d/1ojPV4wFD93PgKBG0C6Di3mYDH-4g_tjP/view?usp=sharing)
  - Edit Quiz: Modify existing quizzes to update information or change available questions.
  - Delete Quiz: Remove quizzes from the system.


- Question Management: Admins can add questions to each quiz, define question types, and specify correct answers.
  - Add Questions: Each quiz can have multiple questions with different types (e.g., multiple-choice, true/false).
    - Screenshot: ![Show the “Add Question” interface, including fields for question text, options, and answer selection](https://drive.google.com/file/d/1R4G4_N5ZcQNLJp5rEyhlcPh-pGG4aQyH/view?usp=sharing)
  - Edit Questions: Update question content and answers as needed.
  - Delete Questions: Remove questions from quizzes if they are no longer needed.

- Class Management: Admins can create and manage classes to organize students and assign quizzes accordingly.
  - Add Class: Set up new classes to categorize students by grade or section.
    - Screenshot: ![Show the “Add Class” form with fields for class name and section](https://drive.google.com/file/d/1i63l85S2icFinr3ToBnavp3FeBJxzgmK/view?usp=sharing)
  - Assign Quizzes to Classes: Link specific quizzes to each class so that only students in that class can access them.

  

 

 6. Score Display and Feedback

At the end of an exam, students can see their scores and feedback.

- Score Screen: Students are shown a summary of their performance.
  - Screenshot: ![Show a sample score screen](https://drive.google.com/file/d/1OrOvC9Aq3XHLftVOKbmhmyZf6nLSBa0V/view?usp=sharing)


 Video Demonstration

To see the full workflow of the Exam Portal, watch this [Video Demo](). (Link to video)
