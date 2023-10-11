# ST10084788_APDS7311_POE_PART2
This is the repository for the APDS7311 POE Part 2.

### To start the project, you would first need to:
1. Open the project folder in Visual Studio Code
2. Open a new terminal
3. Run the following command, 'cd server'
4. Run the next command, 'npm i' - this will install the node_modules
5. Run the next command, 'npm start'
6. This will now allow the application to connect to MongoDB
7. Now navigate to the 'test.http' file which is located in the project folder. In this file, you will be able to make requests to MongoDB - sign up/login/view all posts/create a post/delete a post
8. To do these requests in the 'test.http' file, you would need to click on the 'send request' link that is available above each request

### Connection string to MongDB: mongodb+srv://user:password2023@testdb.gdzzqbi.mongodb.net/?retryWrites=true&w=majority

### ****** PLEASE NOTE: when testing the delete function, you need to change the id that is already typed in the 'test.http' file. You can obtain the ID for a character by running the 'get all posts' request, you may then copy the 'id' field of this character and paste in the delete request method. 

The delete method should look like, 

DELETE https://localhost:3000/api/characters/{character id} HTTP/1.1
content-Type: application/json
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6InRlc3Q5IiwidXNlcmlkIjoiNjM0NTFhMDQyMDE4YmIwY2JjOGIwNGNhIiwiaWF0IjoxNjY1NDczMDY2LCJleHAiOjE2NjU0NzY2NjZ9.FpGxz2CC2koE4PopXTG-qk_Kz93EjLBFBJL0qoWtu60


The testing of the project can be done using the 'test.http' file. 

### Contact Information

Student Name: Shivani Naidu

Student Number: ST10084788

E-mail Address: shivanijw05@gmail.com

Contact Number: 074 343 2766
