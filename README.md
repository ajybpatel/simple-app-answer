# simple-app-answer
Brand Home page, login, registration and users last activity on account with MySql Database.



ANSWERS:
Question 1:
    File Name: login.php and registration.php

Question 2: 
    File Name: index.php

Question 3:
    File Name: register.sql
    Answer Qyery : SELECT u.name AS user_name,a.name AS activity_name,amount,MAX(ua.occurrence) AS First_occurrence,MIN(ua.occurrence) AS Last_occurrence FROM user_activity ua,activity a,user u WHERE ua.user_id=u.id AND ua.activity_id = a.id GROUP BY activity_id,user_id;

Bonus Challenge :
    
    For bonus challenge all the answers combined in one singe app:
        Company home page:
            About
            Services
            Contact
        Login and registration
        Dashboard
            which contains user name, last activity and logout.
