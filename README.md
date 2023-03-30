# BizCardX-Extracting-Business-Card-Data-with-OCR
The Basic Workflow of the Program: Importing libraries:  
imports several libraries, including Streamlit, EasyOCR, SQLite, OpenCV, NumPy, and Pandas.                                          
Connects to an SQLite database called card_info.db and creates a table  called Business_card to store the extracted information    from the business cards.                                                                   
The program uses EasyOCR to extract information from images of business cards uploaded by the user.

Creates a file uploader using the Streamlit library to allow users to upload images of business cards.

The program creates a sidebar with four options: Insert Data, Display Data, Update Data, and Delete Data.

Inserting data: If the user selects the option to insert data and uploads an image, the program extracts the information from the image using EasyOCR and saves it to the Business_card table in the database.

Displaying data: If the user selects the option to display data, the program retrieves all the data from the Business_card table in the database and displays it in a table using the Pandas library.

Updating data: If the user selects the option to update data, the program retrieves the information for a selected business card from the database, allows the user to edit the information, and updates the information in the database.

Deleting data: If the user selects the option to delete data, the program retrieves the information for a selected business card from the database and deletes the information from the database.

Running the application: Finally, the program uses the Streamlit library to run the web application.





