# Movie Catalog RESTful API – ASP.NET Core

## Problem Statement
You are tasked with building and testing a RESTful API for an online **movie catalog** using **ASP.NET Core**.  
The API allows clients to perform **CRUD (Create, Read, Update, Delete)** operations on movies and their associated directors.

---

## Objective
- Implement CRUD operations for movies and directors.  
- Follow RESTful principles (clean URIs, correct HTTP methods).  
- Use **Postman** for testing and **Fiddler** for debugging.  
- Support associations (movies by director).  
- Store data in **in-memory DB** or **SQLite**.  
---

## Project Structure
MovieCatalogAPI/
│── Controllers/
│ ├── MoviesController.cs
│ ├── DirectorsController.cs
│
│── Models/
│ ├── Movie.cs
│ ├── Director.cs
│
│── Data/
│ ├── AppDbContext.cs
│
│── Program.cs
│── appsettings.json
│── README.md

## API Endpoints
## Movies
GET    /api/movies
GET    /api/movies/{id}
POST   /api/movies
PUT    /api/movies/{id}
DELETE /api/movies/{id}

## Directors
GET    /api/directors
GET    /api/directors/{id}
POST   /api/directors
PUT    /api/directors/{id}
DELETE /api/directors/{id}

## How to run
Setup Instructions
## 1. Clone repo:
 git clone https://github.com/your-username/bookstore-api.git
 cd bookstore-api
 
## 2. Run the project:
dotnet run

## 3. API will be available at:
https://localhost:5001/api/books https://localhost:5001/api/author

Catalog SnapShots:
1. Services Available:
<img width="1919" height="947" alt="Screenshot 2025-08-26 215458" src="https://github.com/user-attachments/assets/0a46e42e-21df-4eb5-a5da-62dbce267b5a" />

2. Get Directors:
<img width="1915" height="952" alt="Screenshot 2025-08-26 215536" src="https://github.com/user-attachments/assets/1c248b57-f0c6-45c5-a6d5-14061830e533" />

3. Post Directors:
<img width="1919" height="957" alt="Screenshot 2025-08-26 215607" src="https://github.com/user-attachments/assets/a79ae72e-a66b-4b79-bb31-8917ceb013a6" />

4. Get Movies:
   <img width="1915" height="946" alt="Screenshot 2025-08-26 215723" src="https://github.com/user-attachments/assets/519f9f3f-1e7f-4ebd-99bc-c4239f0a82c3" />

5. Post Movies:
   <img width="1915" height="930" alt="Screenshot 2025-08-26 215656" src="https://github.com/user-attachments/assets/20cf951b-1696-4c03-8365-2f3ad4a3615b" />

