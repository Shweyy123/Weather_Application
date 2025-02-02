# Weather Application
 
This is a weather application built with Django. It fetches weather data from a third-party weather API and displays it to the user.

## **Prerequisites**

Before running the project, ensure you have the following installed on your machine:

1) Python (version 3.x or higher)

2) Django (version 4.x or higher)

3) pip (Python's package installer)

How to run this project?

1. Clone the repository
   
       git clone https://github.com/Shweyy123/Weather_Application.git
       cd Weather_Application-Django
   
2. Create and activate a virtual environment (optional but recommended)
   Creating a virtual environment will help you manage dependencies specific to this project.

       python -m venv venv
   
    Activate the virtual environment:
   
    On Windows:

       .\venv\Scripts\activate
   
3. Install dependencies
   
   Make sure you're in the project directory (Weather_Application-Django) and then install the required dependencies:

       pip install -r requirements.txt
   
   If requirements.txt doesn't exist yet, you can install Django manually and any other necessary packages like:

       pip install django requests
   
4. Configure API Key
   
   If your weather application uses a weather API, you'll need to sign up for an API key from a service like OpenWeatherMap or Weatherstack. After obtaining the API key, add it to the project. You can store it in 
   a .env file or directly within your settings, depending on your setup.

5. Start the Django development server
   Now you're ready to run the project! Start the development server:

       python manage.py runserver

   Visit http://127.0.0.1:8000/ in your browser to view the Weather Application.
