# Typingstuff
This is my first project and it's a small site about horses.
Main goal was to learn how to use framework Django, use model MTV and ORM.
Main features that project has:
  Multiple viewvs and models
  Custom statics
  Connection to database
  Authorisation
  Captcha
  Pagination
  Django debug Toolbar
  Caсhe
I took the core of different project and proceed to rewrite the code and apply some small changes.
At this point you might find the difference mainly in statics and db, some changes in settings.
Next thing that i wanna change is to get rid of all the database queries from views by creating a new file and put them all in it.
Main reason being  there should not be a bussiness logic in views, database queries is part of it
