# BugZilla_ror

Project requirements. 
•	Sign up, login and logout of users(name, email, password, user_type[developer, manager, qa])(use Devise for that)
 only manager can create the projects
 manager can have many projects 
•	manager can assign developers to projects
 qa user can enter many bugs
 a bug belongs to a creator(user)
 a bug belongs to a developer who'll solve the bug reported 
•	 a bug belongs to a project 
•	a project can have many users
 a project can have many bugs too. 
•	bug has a description, title, deadline, an image, type(feature, bug) and status(new, started, resolved, completed)
 image can be of type .png or .gif no other type of image is allowed and file size cannot be larger than 5mb, we can use any file uploader.
 in bug description and image are not compulsory but title and status and type are compulsory fields.
 title of a bug should be unique throughout the project
 bug status is a drop down having values (new, started, completed) if it's a feature or (new, started and resolved) if it's a bug 

•	user email cannot be blank
•	user name cannot be blank 
•	user role cannot be blank 
•	qa cannot create project
 developer cannot create project 
•	only manager can create project 
•	a bug should belong to a user(creator who can only be qa) 
•	a bug should belong to a developer who'll solve it
 a bug should belong to a project
 bug type cannot be blank 
•	bug type can only include (feature, bug)
 bug status can only include (new, started, resolved, completed) 
•	a bug should belong to a project
 a bug should belong to a project 
•	project may have many users
 project can have many bugs too 

![image](https://user-images.githubusercontent.com/48153435/197338992-f8b9a5e1-2daf-4931-8307-986a47eed56a.png)
