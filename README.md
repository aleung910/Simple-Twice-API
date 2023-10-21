#SIMPLE TWICE ALBUM SORTER USING CRUD
This project serves as a CRUD (Create, Read, Update, Delete) API for managing albums. It allows users to dynamically add, update, and delete albums, with the data being stored in a MongoDB database. 
I used it specifically for the group TWICE but users are able to use it for whatever albums they choose. 

## Technologies Used
- Express.js
- dotENV
- EJS (Embedded JavaScript)
- MongoDB
- Vercel
- Node.js

API Endpoints
- GET /: Retrieves a list of albums,covers, and their artists, sorted by likes.
- POST /addAlbum: Adds a new album, its cover, and base likes.
- PUT /addOneLike: Increments the like count for a specific album.
- DELETE /deleteRapper: Deletes an album.


