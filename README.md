## How to Run the Code

- Fork and clone the repository.
- Install the following modules in python
     1. pip install sklearn
     2. pip install flask
     3. pip install goose3
     4. pip install Flask-Mail
     5. pip install pandas
     6. pip install numpy
- Change sender and recipient's email address in app.py file for the feedback part. Configure flask mail by adding the sender's email address and corresponding password in MAIL_USERNAME and MAIL_PASSWORD under configuration part. 
- Ensure the sender mail has ‘access from less secure apps’ enabled. For gmail IDs, this can be done from the accounts page - Account 
- Run app.py
- Open the website from local host: http://3.101.144.172:8080/
