 # Movie Management System

This is a simple RESTful API for managing movies. It allows you to perform CRUD operations (Create, Read, Update, Delete) on movie data.

 ## Technologies Used

- Go programming language
- Gorilla Mux router for HTTP routing
- JSON for data exchange

 ### Gorilla Mux
Gorilla Mux is a powerful HTTP router for the Go programming language. It is widely used in building web applications and RESTful APIs due to its flexibility and ease of use.

 Usage
-----

 **Clone this repo**

``` bash
    git clone https://github.com/Shreyank031/Go_Movie_CRUD.git
```
 **Navigate to the repo**

``` bash
    cd Go_Movie_CRUD
```

 **Run the application**

``` bash
    go run main.go
```

Once the application is running, you can interact with it using HTTP requests. Here are the available endpoints:

- `GET /movies`: Retrieve all movies.
- `POST /moives`: Add a new movie to the collection.
- `GET /movies/:id`: Retrieve details of a specific movie by its ID.
- `DELETE /movies/:id` Delete a specific movie by it's ID.
- `PUT /movies/:id` Updates a specific movie by it's ID.

 ### Postman 

!["Result"](https://github.com/Shreyank031/Go_Movie_CRUD/blob/master/output.png)
