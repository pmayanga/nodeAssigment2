# nodeAssigment2
Edx node Assigment 2
1. Walk us through the design of your project. Why did you design your project the way you did? What difficulties did you overcome?

The project came with instructions about the files structure. And this is how the project is structures. One file for the server wich takes all the http callings, another file to consolidate all the files that manage the logic for each calling. The main difficut was to invoque each of them form the server.js file  

2. How did you test your project to verify that it works? If you used any specific curl requests, let us know.

I used postman to test my project. I made one call for each method on both cases: posts and comments.

3. Let us know if anything doesn't work as intended so your reviewers will know ahead of time

Actually, the I´ve modified the initial in-memory store so now "comments" is an array of jsons objects. I´ve also copied this data in posts.js and comments.js
