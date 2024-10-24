# Dummy database
*DATA GENERATION MADE SIMPLE*

Dummy Database is my personal pet-project. My initial goal was to make a tool to create datasets for SQL practice.

Started as a pack of Python-based functions for generating different types of data with different options it came to point where I've decided to make it a full-scale web-tool that anyone can use. On top of that I was eager to have my own experience on web-coding, deploying and maintainance, advertisement and web user-statistics areas.

After 2 month of coding it has landed on [https://www.dummydatabase.com/].

Full-stack development was a new area for me so I've put lot of efforts to go through cilent-server communication protocols, web coding on client side, deployment etc.

**Framework used:**
- Python for data generating functions
- Flask + Python for server side
- JavaScript for client side
- HTML, CSS, Bootstrap for pages layout
- PostgreSQL for database operations
- Git for version control
- Docker for deployment

Hosted on Render.com

**Main features and mechanics:**

Basically it's a website where you can design and generate data tables based on your choice of table names, number of records, 35+ data types and options, connections between tables. You can preview generated data, make some modifications and download tables in XLSX or CSV formats. Also you can see ERD diagram for generated tables and SQL code.

User registration and logging with email-password pair is implemented, so registered user have an account with some benefits (dataset save & load, bigger max. number of rows to generate, ERD diagram and SQL code).

Upon registering user gets an email with unique link-token to follow where he sets a password. All events are being logged in Postgres database (datetime of activity, type, user id and details etc.)

After registering and logging in user gets additinal top menu options and Account secsion where he can see details on generation stats, his user preferences and option to delete account completelty. 


