# BokkStore-assignment

## Setup

1. Make sure you have Node.js, Express, and MongoDB installed on your system.
2. Clone the repository: `git clone https://github.com/Indrajeet790/BokkStore-assignment
3. Install the dependencies: `npm install`
4. Start the server: `nodemon index.js`
5. The API will be available at `http://localhost:8000`.

## Endpoints

- POST `/api/items/create` - Create a new item in the database.
- GET `/api/items/listAll` - Retrieve all items from the database.
- GET `/api/items/:id` - Retrieve a specific item by its ID.
- PUT `/api/items/update/:id` - Update an existing item by its ID.
- DELETE `/api/items/delete/:id` - Delete an item by its ID.
