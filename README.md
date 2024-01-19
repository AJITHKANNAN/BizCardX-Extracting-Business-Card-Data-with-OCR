# BizCardX-Extracting-Business-Card-Data-with-OCR

**Problem Statement:**

Develop a Streamlit application enabling users to upload business card images, extract relevant information using easyOCR, and save the extracted details along with the image to a database. The extracted information includes the company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The application should also provide functionality for reading, updating, and deleting data through the Streamlit UI.

**Approach**

**Install Required Packages:**

Install Python, Streamlit, easyOCR, and choose a database management system like SQLite or MySQL.

**Design User Interface:**

Utilize Streamlit to create an interactive and user-friendly interface.
Implement widgets such as file uploader, buttons, and text boxes for a seamless user experience.

**Implement Image Processing and OCR:**

Employ easyOCR to extract information from uploaded business card images.
Apply image processing techniques (resizing, cropping, thresholding) to enhance image quality before OCR.

**Display Extracted Information:**

Present the extracted information in a structured manner using Streamlit widgets like tables and labels.

**Implement Database Integration:**

Set up a database (SQLite or MySQL).
Utilize SQL queries to create tables, insert, retrieve, update, and delete data.
Integrate database functionality into the Streamlit UI for seamless data management.

**Test the Application:**

Thoroughly test the application to ensure all features work as expected.
Run the application locally using the **streamlit run app.py** command.

**Improve the Application:**

Continuously enhance the application by adding new features.
Optimize code, fix bugs, and consider implementing user authentication and authorization for security.
Maintain good documentation and organize the code for scalability and maintainability.

**Results:**

A fully functional Streamlit application enabling users to upload business card images and extract relevant details.
Extracted information is displayed in an organized manner, and users can save it to a database.
The application supports reading, updating, and deleting data through the Streamlit UI.
The user interface is intuitive, guiding users through the extraction and storage process.
