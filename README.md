# 🌍 Reiseplaner Itinerary Management API

## 📌 Description  
The **Reiseplaner Itinerary Management API** is designed to help users plan and manage travel itineraries efficiently. This API integrates with **external data providers** to fetch real-time details of **flights, hotels, and tourist sites** based on the user's input. Users can create personalized itineraries by selecting suitable flights, accommodations, and attractions.

This project is built using **Node.js, Express.js, Sequelize, and PostgreSQL**, and it follows a RESTful architecture for efficient data retrieval and management.

---

## 🚀 Features  
✅ Fetch **real-time flight, hotel, and tourist site data** from an external API.  
✅ Create and store **custom travel itineraries** in the database.  
✅ Retrieve a saved itinerary by **ID**.  
✅ **Unit testing** implemented using Jest & Supertest to ensure API reliability.  
✅ Uses **Sequelize ORM** to manage database interactions.  

---

## 🛠️ Tech Stack  
- **Backend Framework**: Node.js, Express.js  
- **Database**: PostgreSQL  
- **ORM**: Sequelize  
- **API Requests**: Axios  
- **Testing**: Jest, Supertest  



## 🔥 API Endpoints Overview  
- **POST /itinerary** → Create and save a travel itinerary.  
- **GET /itinerary/:id** → Retrieve a saved itinerary by ID.  
- **GET /data/flights** → Fetch flight data from an external API.  
- **GET /data/hotels** → Fetch hotel data from an external API.  
- **GET /data/sites** → Fetch tourist site data from an external API.  
- **GET /data/getFlightsByOriginAndDestination** → Get flights by origin & destination.  
- **GET /data/getHotelsByLocation** → Get hotels based on location.  
- **GET /data/getSitesByLocation** → Get tourist sites based on location.  

---

## ✅ Unit Testing Details  
Unit testing is implemented using **Jest** and **Supertest** to ensure API reliability. Each endpoint is tested for:  
- **Successful response** with valid inputs.  
- **Error handling** for missing or invalid data.  
- **Database interactions** to verify that data is correctly stored and retrieved.  

### **Run all tests**  
```bash
npm test
```
