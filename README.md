# iNeuron Course Details Scraper & API

Discover course details from iNeuron's website effortlessly and deploy them using this powerful API. Hosted on AWS Elastic Beanstalk, this tool makes learning convenient and insightful.

## Project Structure:
<pre>
<code>
.
├── .ebextensions
│   └── python.config  #  # Configuration for AWS Elastic Beanstalk deployment
├── .elasticbeanstalk
│   └── config.yml     # Elastic Beanstalk configuration settings
├── courses            # Stores the searched course details in PDF
├── templates          # HTML templates 
├── application.py     # Main script for launching the application and interacting with user inputs
├── courses.py         # Script for handling course-related operations
├── db_op.py           # Script for database operations, including adding data to SQL and MongoDB
├── getpdf.py          # Script for generating PDF files
├── url.py             # Manages URLs 
├── user_input.py      # Contains user-specific input, like MongoDB credentials and file paths
├── utility.py         # Holds utility functions used across the application
└── README.md          # Project documentation

</code>
</pre>

## Features

- Effortlessly scrape course details from iNeuron's website.
- Seamless deployment on AWS Elastic Beanstalk.
- Customizable setup through `user_input.py`.
- Quick installation with `requirements.txt`.
- Explore courses by category, subcategory, and name using `application.py`.
- Access results in a PDF file named after the selected course.
- Add available courses to MongoDB using `db_op.py`.
- SQL database (`courses.db`) generated for your convenience.
- Intelligent logging system keeps you informed.
- Data scraped solely for learning purposes.

## Getting Started

1. Update `user_input.py` with MongoDB credentials and file paths.
2. Install required modules: `pip install -r requirements.txt`.
3. Launch the application: `python application.py`.
4. Select course category, subcategory, and name for details.
5. PDF results available in the specified file path.
6. Use `db_op.py` to add courses to MongoDB.
7. SQL database (`courses.db`) generated automatically.
8. Data is deleted after use.

## Visual Overview

- **AWS Elastic Beanstalk Deployment**:
  ![Screenshot_7](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/c0fff186-c9d6-4920-93da-39181086cbff)

- **Homepage Snapshot**:
![Screenshot_5](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/a5bfcc28-bd4d-4e03-b43d-c8e98f570867)

- **Results Display**:
![Results](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/8e32431b-b39f-4962-b9eb-54f4eef330f2)

- **MongoDB Showcase**: 
![Mongo](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/ad736bce-c3da-422c-bf8c-5e14283ec755)

- **PDF Output**: 
![pdf](https://github.com/MKGourab/ineuron_scrapping/assets/104300031/95f15ba9-7f68-4983-8284-0ce3cacea433)

## Installation

1. Clone this repository: `git clone https://github.com/MKGourab/ineuron_scrapping`.
2. Navigate to the project folder: `cd ineuron_scrapping`.
3. Install required modules: `pip install -r requirements.txt`.

## Usage

1. Update `user_input.py` with your MongoDB credentials and file paths.
2. Launch the application: `python application.py`.
3. Follow the prompts to select course details.
4. View results in generated PDF file.
5. Use `db_op.py` to add courses to MongoDB.

