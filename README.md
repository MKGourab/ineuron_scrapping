1. This API helps to scrape course details from iNeuron website.
2. First user needs to update the user_input.py file with their MongoDB username, password, file path to save the course details pdf.
3. pip install requirements.txt to install the required modules to run the api.
4. Run application.py to select course category, course subcategory, course name to get course details of the selected course name.
5. Once the result page is displayed user can find a file with "selected course name.pdf" in the file path provided above.
6. User needs to run db_op.py to add all the available courses to MongoDB & a SQL database with filename courses.db is generated in the file path mentioned above.
7. The application uses logging to log all the information.
8. Data is scraped only for learning purpose and is deleted and app removed from deployed server.
  
  
  
  # Output as shown below:
  
  
  ## Homepage:
  
![Homepage](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/1348d2c4-b3eb-40f8-a2cf-ae4b0b723b92)
    
  ## Results Page:
  
![Results](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/8e32431b-b39f-4962-b9eb-54f4eef330f2)
  
  ## Mongodb:
  
![Mongo](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/ad736bce-c3da-422c-bf8c-5e14283ec755)
  
  ## PDF: 
  ![pdf](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/95f15ba9-7f68-4983-8284-0ce3cacea433)
  
  
  
  
  

