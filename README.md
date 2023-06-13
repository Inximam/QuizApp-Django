# QuizApp-Django

<img width="1290" alt="HomePage" src="https://github.com/Inximam/Django-quizApp/assets/85678544/1bfc6b93-903f-44ae-895d-e0e935302117">


This quiz application is a web-based platform designed to enhance learning and engagement through interactive quizzes. Built using Django, a powerful Python web framework, the application offers a user-friendly interface that allows users to register, participate in quizzes, submit answers, and view their results.

Key Features:
- User Registration: Users can create an account with their email, username, and password to access the quiz platform.
- Quiz Categories: The application offers a variety of quiz categories, each with its own set of questions and difficulty levels.
- Dynamic Quiz Questions: Users can navigate through quiz questions, select their answers from multiple options, and submit them within a specified time limit.
- Result Display: After completing a quiz, users can view their results, including the number of correct answers, overall percentage, and submitted answers.
- Password Reset: Users can request a password reset if they forget their login credentials, ensuring secure access to their account.

Technologies Used:
- Django: The web framework used for backend development, providing a robust and scalable foundation.
- Python: The programming language used to build the application's logic and functionality.
- HTML/CSS: The markup and styling languages used for designing the application's user interface.
- JavaScript: Used to add interactivity and enhance the user experience.
- PostgreSQL: The database management system utilized to store quiz-related data.

This project aims to create an engaging and educational experience for users by offering a wide range of quiz categories and challenging questions. The application's intuitive interface and seamless navigation make it accessible to users of all levels. Whether used for self-assessment, educational purposes, or recreational learning, this quiz application provides a platform for users to enhance their knowledge and test their understanding in a fun and interactive manner.

Feel free to explore the project's source code and documentation to learn more about its implementation and customization. Join us in the journey of continuous improvement and contribute to the project's development by providing feedback, reporting issues, or submitting pull requests. Let's make learning enjoyable and accessible for everyone through this quiz application!

Setup

Update the System

sudo apt-get update

To get this repository, run the following command inside your git enabled terminal

git clone https://github.com/Inximam/Django-quizApp.git
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Download django usig pip

sudo apt install python3-pip -y
pip install django

Once you have downloaded django, go to the cloned repo directory and run the following command

python3 manage.py makemigrations

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command

python3 manage.py migrate

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user

python3 manage.py createsuperuser
That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

python3 manage.py runserver
Once the server is hosted, head over to http://127.0.0.1:8000/main for the App.

Cheers and Happy Coding :)
