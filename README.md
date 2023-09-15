# Real EState Project In Django
This project is designed to manage the properties and realtors for a real estate company. The key features of this project are:

* Property Listing: Users can view all the available properties with their details like price, location, type, and other features.
* Realtor Management: Admin users can add, update, and delete realtors who are responsible for the properties.
* Property Management: Admin users can add, update, and delete properties with all their details.
* Buy and Sell Query: Users can send queries to the admin users for buying or selling properties.

# Installation
To clone this project from GitHub, follow these steps:

* Open your terminal or command prompt.
* Navigate to the directory where you want to clone the project.
* Run the following command: git clone https://github.com/kanchanCS/real-e-state.git
* Once the project is cloned, navigate to the project directory using cd real-e-state.
* Create a virtual environment using python -m venv env.
* Activate the virtual environment using source env/bin/activate on Linux/Mac or .\env\Scripts\activate on Windows.
* Install the project dependencies using pip install -r requirements.txt.

# Usage
To run this project, follow these steps:

* Navigate to the project directory using cd real-e-state.
* Activate the virtual environment using source env/bin/activate on Linux/Mac or .\env\Scripts\activate on Windows.
* Run the following command to migrate the database: python manage.py migrate.
* Create a superuser account using python manage.py createsuperuser.
* Run the development server using python manage.py runserver.
* Open your web browser and navigate to http://localhost:8000/admin to access the admin panel.
* Use your superuser account credentials to log in to the admin panel.
* You can add, update, or delete realtors and properties from the admin panel.
* To view the property listing page, navigate to http://localhost:8000/listings.
* To send a query for buying or selling a property, navigate to http://localhost:8000/contact.


