# CAMPUT404LAB3

Question 1:
https://github.com/2Bronze/CAMPUT404LAB3

Question 2:
The django landing page with a rocketship. 

Question 3:
/ takes you to a page not found page since a view no exists so no default page exists at /, whereas /polls takes you to the view that was created with the plain text "hello, World. You're at the polls index".

Question 4:
When changes are made to models, they need to be updated and moved into the database schema, this is what migrations are required for. 

Question 5:
It takes you to an admin page where you need to login in with your credentials. To get models to show up on the admin page, they need to first be written and registerd into the admin.py file as Choice and Question are. 

Question 6:
For polls/38 we see that text exclaiming that we are looking at question 38. For /results we see plain text saying we now see results of question 38. /vote disaplys that we are voting on question 38. Using strings results in page not found. To account for this we can in urls.py we can speciify instead of <int>, we can use <str>.

Question 7:
If the url is ever altered once, then every instance where it is referenced would need to be changed, therefore it is better to never hardcode, so if it changes, it only needs to be changed in one place. 

Question 8:
Generics are better since they take care of normal patterns so that you do not have to worry about them everytime. 

Heroku Lab:

Question 1:


Question 2:

Question 3: