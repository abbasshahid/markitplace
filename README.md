Project Title
A brief description of what this project does and who it's for.

Installation
Follow these steps to set up the project environment.

Prerequisites
Python (preferably Python 3)
pip (Python package manager)
Setup
Install Python:

Download and install Python (ideally Python 3) from python.org.
During installation, ensure that Python is added to your system's PATH.
Install pip:

Python 3 comes with pip pre-installed. If for any reason pip is not installed, follow these instructions to install it manually.
Install Django and Dependencies:

Open your command line interface (CLI) and navigate to your project directory.
Run the following commands to uninstall any existing versions of django-crispy-forms and install the latest version:

pip uninstall django-crispy-forms
pip install django-crispy-forms
Start the Django Server:

Within your project directory, execute the following command:
python3 manage.py runserver
If you encounter any errors, it likely means some dependencies are missing. Install any missing dependencies as prompted and repeat the above steps.

Usage
Creating an Account
Register:
Navigate to the registration page and create an account. You may also create additional accounts to simulate different users (e.g., your friends).
Using the Application
Login:

After registering, use your credentials to log in.

Follow these steps to use the application effectively:

Shopping and Checkout
Add Items to Basket:

Browse the application and add your desired items to the basket.
Review Your Basket:

Navigate to your basket to review the items you've selected.
Here, you can modify your selection by removing items or adjusting quantities.
Checkout:

Proceed to checkout when you're ready.
Enter your address and choose a payment plan.
Complete the checkout process.
Note for Demo Users
Remember, this is a demo version of the application. Explore various features, but be aware that it's a simulated environment.
Managing the Application as an Admin
If you need administrative access to manage the application (such as adding items or modifying categories):

Create a Superuser Account:

Run the following command in your terminal:
python manage.py createsuperuser
Follow the prompts to create an admin account.
Access the Admin Panel:

Log in to the admin panel using the account you created. The admin panel can be accessed at:
http://127.0.0.1:8000/admin/login/?next=/admin/catalog/
Here, you can manage various aspects of the application, including item listings, user accounts, and more.

This guide should help you navigate the basic functionalities of the application and manage its content as an admin. For more detailed instructions, refer to the specific sections of the documentation.

