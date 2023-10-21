# ALBUM-COLLECTOR-FOR-TWICE-WITH-CRUD
This project serves as a CRUD (Create, Read, Update, Delete) API for managing albums. It allows users to dynamically add, update, and delete albums, with the data being stored in a MongoDB database. I used it specifically for the group TWICE but users are able to use it for whatever albums they choose. 
## DEMO
![Screen recorder_10-21-2023_16-41-49-268 (online-video-cutter com)](https://github.com/aleung910/Simple-Twice-API/assets/138654250/5c753eb0-d3a9-4860-9424-ccbdf8938907)
## Tech Stack
**Server:**
- Node.js
- Express.js
- dotENV
- EJS (Embedded JavaScript)
- MongoDB

**Deployments:**
- Vercel

**Styling**
- CSS

## API Endpoints
- GET /: Retrieves a list of albums, covers, and their artists, sorted by likes.
- POST /addAlbum: Adds a new album, its cover, and base likes.
- PUT /addOneLike: Increments the like count for a specific album.
- DELETE /deleteRapper: Deletes an album.

## Lessons Learned
- MongoDB Proficiency: This project provided me with a deep dive into MongoDB. I learned how to set up and interact with a NoSQL database, including creating collections, performing CRUD operations, and utilizing advanced querying techniques.

-Node.js and Express Integration: This was my first experience using Node.js and Express to build a full-fledged web application. I learned how to leverage these technologies to create a robust backend, handle routes, and middleware, and integrate with MongoDB.

- Dynamic Server Updates: Implementing dynamic updates on the server side was a significant milestone for me. I learned how to efficiently handle user input, initiate API requests, and dynamically update the page content, enhancing the user experience.

- Deployment and EJS Templating: Deploying the application for the first time was a valuable learning experience. I became proficient in setting up deployment pipelines and hosting applications. Additionally, using EJS for templating allowed for dynamic HTML generation on the server side.

Overall, this project has been a tremendous learning opportunity, allowing me to grow my skills in MongoDB, Node.js, Express, and deployment practices.

## Continued Development and Areas of Improvement
While developing this project, I encountered some challenges and areas for improvement:

- Deployment Issues: Unfortunately, I faced difficulties deploying the application on Vercel. I received a 404 error and encountered an issue with the build command (npm run build) resulting in an exit code 11 error. I also attempted to deploy on Heroku but the same issues occurred. I plan to revisit this in the future to troubleshoot and resolve the deployment issues.

- Limited Time for Refinement: Due to time constraints, I wasn't able to invest as much time as I would have liked in refining certain aspects of the application. In the future, I plan to allocate more time for extensive testing, debugging, and optimization.

- CSS Styling for Album List: In subsequent iterations, I aim to enhance the visual presentation by displaying the list of albums horizontally using CSS. I encountered some challenges when dynamically updating the list from updating the CSS and with limited time, I decided to come back in the future to approach it with more efficient practices.

I welcome any feedback or suggestions for improvement, and I'm open to collaboration or discussions on this project. If you have insights or solutions to the challenges I faced, please don't hesitate to reach out. Your input is highly valued :). 
