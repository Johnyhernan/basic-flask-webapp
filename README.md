# basic-flask-webapp
This is a basic web-app created on python using Flask along with css and html. This web-app uses a PostgreSQL db hosted on supabase free tier.
## How It's Made:
**Tech used:** Python(flask),JavasScript,HTML,CSS
This web-app is built using python framework Flask, and socket-io for its chat functionality. It uses a postgreSQL db hosted on supabase. The reason for this is that dockerizing a db would be beyond my skills and expertise.The web-app uses basic HTML,CSS, and JavaScript for its ui. 
## functionalities:
This web-app allows users to create an account, like, post ,comment/reply, follow and create a personal real time chat with other users. 
Other functionalities 
Sort comments by active(comments with most replies), most liked, and new.
Sort post in dash by active(post that receives above the average number likes in the first 4 hours of creation), followed, new, liked, and top.
Search for a specific word in a comment, post, or username.
Change bio, or profile picture of an account. 
Threaded comments with parent-child tree.
# Deployment
The following dockerfile has already been made. All you need to do is build an image and run it. The following web-app should run on localhost. Be sure to have the host port set to '5000'. Once you run it, it should start on  (http://localhost:5000) it it starts on (http://0.0.0.0:5000) change (0.0.0.0) to localhost.
# To-DO's
The obvious– a reporting system, post/comment deletion. Post editing, email verification which could easily be done. 
## Lesson's learned
One of the biggest lessons learned was underestimating the time it took to make a web-app look presentable. Creating the basic functionalities was not as hard as it was to make it look nice for the user. Also finding a way to display threaded comments was a bit of a challenge. I had fun creating this web-app and learned many things like database relationships, how to use docker, and the importance of planning.



