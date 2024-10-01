# Employability and Consultancy System

The **Employability and Consultancy System** is a web application designed to assist job seekers in finding suitable jobs by integrating AI-powered job matching algorithms. It also provides employers with a platform to connect with candidates and offer consulting services for career development and recruitment.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features
- **AI-powered job matching**: The system automatically matches job seekers with relevant job opportunities based on their skills and experience, reducing job search time.
- **Job seeker portal**: Provides an intuitive and user-friendly interface for job seekers to create profiles, upload resumes, and search for jobs.
- **Employer portal**: Allows employers to post job listings and manage applications.
- **Consultancy services**: Offers comprehensive career consulting services to improve job placements and career development.
- **Interactive platform**: An online hub for job seekers and employers to engage and communicate effectively.
  
## Technologies Used
- **Backend**: Python, Django
- **Frontend**: HTML5, CSS3
- **Database**: MySQL
- **Other**: AI-powered job matching algorithm

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/PavanKalyanChapa/Employability-Consultancy-System.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Employability-Consultancy-System
    ```

3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Set up the database:
    ```bash
    python manage.py migrate
    ```

6. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:
    ```bash
    python manage.py runserver
    ```

8. Access the application at `http://127.0.0.1:8000/`.

## Usage
1. Job seekers can register, create profiles, and apply for jobs.
2. Employers can post jobs and review applications.
3. Use the consultancy services section for personalized career advice.

## Screenshots
![Home Page](screenshots/homepage.png)
![Job Seeker Dashboard](screenshots/job_seeker_dashboard.png)
![Employer Dashboard](screenshots/employer_dashboard.png)

## Contributing
Feel free to fork this repository and contribute by submitting a pull request. Any enhancements, bug fixes, or new features are welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
