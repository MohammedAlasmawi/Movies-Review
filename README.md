# Movie App

A full-stack Movie App built with a **React.js frontend** and a **Spring Boot backend**. The app allows users to view movie details, watch trailers, add reviews, and manage movies in a MongoDB database.

## 🚀 Technologies

- **Frontend**: 
  - React.js
  - React Router
  - Axios
  - React Bootstrap
  - Material-UI Carousel
  - FontAwesome
  - React Player

- **Backend**:
  - Java 21
  - Spring Boot (with MongoDB)
  - Lombok
  - Spring Data MongoDB
  - Spring Boot REST API

- **Database**: MongoDB (via MongoDB Atlas)

---

## 🌟 Features

- **View Movies**: Display a list of movies with title, release date, poster, and backdrop.
- **Watch Trailers**: Watch trailers for each movie embedded from YouTube.
- **Add Reviews**: Users can add reviews to movies.
- **MongoDB Integration**: The backend stores movie details and reviews in MongoDB.

---

## ⚙️ Setup Instructions

### **Frontend Setup (React.js)**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MohammedAlasmawi/movie-review.git
   cd MovieApp
2. **Install dependencies**:
  ```bash
     npm instal
 ```
3. **Start the development server:**:
  ```bash
     npm start
 ```

### **Backend Setup (Spring Boot)**

1. **Clone the repository (if you clone before no need again)**:
   ```bash
   git clone https://github.com/MohammedAlasmawi/movie-review.git
    cd MovieApp/backend

2. **Adjust MongoDB Atlas Configuration:**:
    - Go to MongoDB Atlas and create a free cluster.
    - Get your MongoDB URI from the Atlas dashboard.
    - Update the application.properties file located at backend/src/main/resources/application.properties with your MongoDB URI.
  ```bash
     spring.data.mongodb.uri=mongodb+srv://<your_username>:<your_password>@cluster0.mongodb.net/<your_db>?retryWrites=true&w=majority
 ```   
3. **Adjust .env File**:
   ```bash
   MONGODB_URI=mongodb+srv://<your_username>:<your_password>@cluster0.mongodb.net/<your_db>?retryWrites=true&w=majority
   ```
4. **Run the backend**:
   ```bash
   ./mvnw spring-boot:run
   ```
### **Don't forget to add the data in MongoDB**



