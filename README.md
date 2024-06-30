# Smart Learning Management System

## Overview
The Smart Learning Management System (LMS) is a web-based application designed to improve and modernize the traditional chalk and board style of teaching and learning. This LMS allows students and teachers to access and securely share essential study materials and resources, manage assignments, and facilitate collaborative learning.

## Features

- **Home Page**
- **Registration Page: Teacher**
- **Registration Page: Student**
- **Login Page**
- **Teacher Dashboard**
- **Teacher: Create Classroom**
- **Teacher: Add Resources**
- **Teacher: Add Assignments**
- **Teacher: Assignment Submissions**
- **Student Dashboard**
- **Student: Join Classroom**
- **Student: Sections**
- **Student: Resources**
- **Student: Assignments**
- **Students: Submissions**

## Technology Stack
- **Front End**: HTML, CSS, JavaScript, Bootstrap
- **Back End**: Django
- **Programming Language**: Python
- **Database**: MySQL

## Project Structure

- `manage.py`: Django's command-line utility for administrative tasks.
- `requirements.txt`: List of dependencies.
- `__pycache__/`: Directory containing Python bytecode files.
- `accounts/`: Application for managing user accounts.
- `media/`: Directory for uploaded files such as assignment submissions and resources.
- `mylms/`: Main application configuration for the LMS.
- `students/`: Application for student-related functionalities.
- `teachers/`: Application for teacher-related functionalities.
- `db.sqlite3`: SQLite database file.
- `environ.py`: Environment configuration file.

## Software Requirements
- Certified Distribution of Windows or macOS

## Installation and Setup
1. Clone the repository:
```markdown
   git clone https://github.com/yourusername/Smart-Learning-Management-System.git
```

2. Navigate to the project directory:
```markdown
cd Smart-Learning-Management-System
```

3. Create a virtual environment:
```markdown
python -m venv venv
```

4. Activate the virtual environment:
  - On Windows:
```markdown
venv\Scripts\activate
```

- On macOS/Linux:
```markdown
source venv/bin/activate
```

5. Install the required packages:
```markdown
pip install -r requirements.txt
```

6. Set up the database:
```markdown
python manage.py createsuperuser
```

7. Create a superuser
```markdown
python manage.py createsuperuser
```

8. Run the development server:
```markdown
python manage.py runserver
```
## Future Scope

-  Enhance administrative tools.
-  Implement advanced content management and development features.
-  Improve systems integration and standardization.
-  Foster improved communication and collaboration tools.
-  Incorporate more multimedia resources and synchronous communication tools.
-  Expand national and international collaboration features.

## Contributors
- Usmana Zulfiqar 
- Zoha Mahmood 
- Zunaisha Noor
- Manahil Tahseen

## Contact
For any queries, please contact us at [usmanazulfiqar2001@gmail.com](mailto:usmanazulfiqar2001@gmail.com).
