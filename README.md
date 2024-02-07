# Dissertation_2024
*Instructions for Running the Final Project*

Thank you for your interest in running our final project! Follow the steps below to set up and run the software successfully:

*Prerequisites:*
- Ensure you have Visual Studio Code installed on your system. Alternatively, you can use the terminal command line.
- Download the project code from our GitHub repository.

*Step 1: Extract the Project Code*
1. After downloading the project, locate the downloaded file, which is in a WinRAR format.
2. Right-click on the file and select "Extract Here" to extract the contents of the project.


*Step 2: Navigate to the Project Directory*
1. Open Visual Studio Code or your preferred terminal/command line interface.
2. Navigate to the project folder using the cd command. For example:
   
   cd path/to/project/folder
   

*Step 3: Set Up the Virtual Environment*
1. Once inside the project folder, create a virtual environment named "myenv" by executing the following command:

       python -m venv myenv

*Step 4: Install Required Packages*
1. Activate the virtual environment by running the following command:
   - For Windows:
     
     myenv\Scripts\activate
     
   - For macOS/Linux:
     
     source myenv/bin/activate
     
2. With the virtual environment activated, install the required packages listed in the requirements.txt file by executing:
   
   pip install -r requirements.txt
   


*Step 5: Run the Project*
1. you are ready to run the project.
2. Execute the following command to start the project:
   
   python manage.py runserver

*Step 6: Account Credentials*

   - *Admin Account:*
     - Username: admin
     - Password: admin
       
   - *Dispatcher Account:*
     - Username: dispatcher
     - Password: dispatcher@ecommerce
       
   - *Customer Account:*
     - Username: Paul
     - Password: paul
    


Congratulations! You have successfully set up and run our final project. If you encounter any issues during the process, please refer to our GitHub repository for troubleshooting guidance or reach out to us for assistance.

Thank you for your support and interest in our project!
