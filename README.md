# EISS-Exploration-Image-Search-Software
The EISS is an Exploration Image Search Software built using the Django web framework allow Image exploration, in-depth browsing, and navigation in a nonlinear way via Interactive Search User Interfaces.

*How to Install and Use "EISS: Exploration Image Search Software" *

The ISRE-Tool is an Image Search Engine built using the Django web framework. Follow these steps carefully to install and set it up for use.
----------------------------------------------------------------------------------------------------------------
1. Install PyCharm Professional 2018 in Django Web Framework
Download PyCharm Professional 2018:

Visit JetBrains PyCharm website to download the Professional version (2018 edition).
Install the software following the provided instructions for your operating system.
Install Django in PyCharm:

Open PyCharm and create a new project or open an existing one.
Navigate to File > Settings > Project: <Project Name> > Python Interpreter.
Click the "+" button to add Django:
Search for "django" in the package list.
Click Install Package.
Verify Django Installation:
Run the following command in the terminal to check if Django is installed:

	django-admin --version

If successful, proceed to the next step.
---------------------------------------------------------------------------------------------------------------
2. Add ISRE-Tool to PyCharm and Open the Image Search Engine Folder
Download ISRE-Tool:

Obtain the EISS source code, either from a provided link or repository (e.g., GitHub).
Unzip the downloaded file if necessary.
Add the Project in PyCharm:

Open PyCharm and select File > Open.
Navigate to the ISRE-Tool folder and open it.
PyCharm will recognize the folder as a Django project.
Set Up the Django Configuration:

Go to Run > Edit Configurations.
Click the "+" button, select "Django Server," and configure the project settings (host, port, etc.).

------------------------------------------------------------------------------------------------------------------
3. Add I-Search Multimodal Database and Provide Dataset Location
Download the I-Search Multimodal Database:

Obtain the database from the specified source or the tool's documentation.
Place the dataset folder in a desired location on your system.
Configure Dataset Location in the Code:

Open the ISRE-Tool project in PyCharm.
Locate the settings or configuration file where the dataset path is defined (e.g., settings.py or config.py).
Update the path with the dataset location:
python

	DATASET_PATH = "/path/to/your/dataset"

Save and Verify:
Ensure that the dataset is accessible and correctly linked by testing small operations in the terminal or within the code.
-----------------------------------------------------------------------------------------------------------------------------
4. Install the Requirements File
Install Requirements.txt:

Open the terminal in PyCharm or navigate to the ISRE-Tool folder in your system terminal.
Run the following command:

	pip install -r requirements.txt

This will install all the dependencies listed in the requirements.txt file.
Verify Installation:
Once completed, confirm that all dependencies have been installed without errors.
-------------------------------------------------------------------------------------------------------------------------
5. Launch the Tool
Run the Django Server:

Navigate to the ISRE-Tool project in PyCharm.
Open the terminal and execute:
	
	python manage.py runserver

The server will start, and the tool will be accessible via a local URL (e.g., http://127.0.0.1:8000).
Start Searching Images:
Open the provided URL in your web browser.
Use the ISRE-Tool interface to upload or search for images using the I-Search multimodal database.

Congratulations!!!!!

The ISRE-Tool is now installed and ready to use. Explore and enjoy searching through the image dataset with advanced search functionalities.
---------------------------------------------------------------------------------------------------------------------------------------------------------
Example Configuration
Here’s an example of how your configuration file might look after completing the steps:

python

	# config.py or settings.py
	DATASET_PATH = "C:/Users/YourName/Datasets/I-Search"
	DEBUG = True
	ALLOWED_HOSTS = ['127.0.0.1', 'localhost']

HAPPY IMAGE EXPLORATION!!!!
