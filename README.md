# Full-Stack PG Accommodation Website

This project is a **Full-Stack PG (Paying Guest) Accommodation Website**, designed to help users find, list, and manage PG accommodations efficiently. The platform provides a user-friendly interface with secure authentication and real-time booking capabilities.

## Features
- **User Authentication & Authorization** (Login, Signup, JWT-based security)
- **PG Listings with Search & Filter**
- **Booking & Availability Management**
- **Admin Dashboard for PG Owners**
- **Real-Time Chat Support**
- **Responsive UI** for all devices

## Technologies Used
### Frontend:
- **HTML, CSS, JavaScript** (UI Development)
- **React.js** (Component-based UI)
- **Tailwind CSS** (Modern styling)

### Backend:
- **Node.js + Express.js** (Server-side logic)
- **MongoDB** (Database for storing listings and user data)
- **JWT Authentication** (Secure user sessions)

### Additional Tools:
- **Redux Toolkit** (State management)
- **Socket.io** (Real-time chat & notifications)
- **Cloudinary** (Image upload for PG listings)

## Installation & Setup
### Prerequisites
- **Node.js & npm** installed
- **MongoDB** running locally or via cloud (MongoDB Atlas)

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/PG-Website.git
   cd PG-Website
   ```
2. **Install Dependencies**
   ```sh
   cd backend && npm install
   cd ../frontend && npm install
   ```
3. **Set Up Environment Variables**
   - Create a `.env` file in the backend directory with the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     CLOUDINARY_URL=your_cloudinary_url
     ```
4. **Run the Application**
   ```sh
   cd backend && npm start
   cd ../frontend && npm start
   ```
   - The backend runs on `http://localhost:5000`
   - The frontend runs on `http://localhost:3000`

## File Structure
```
PG-Website/
│── backend/            # Server-side code
│   ├── models/         # Mongoose Schemas
│   ├── routes/         # API Endpoints
│   ├── controllers/    # Business Logic
│   ├── config/         # Database & Cloudinary Config
│   ├── server.js       # Main Backend File
│── frontend/           # React Frontend
│   ├── src/
│   │   ├── components/ # Reusable UI Components
│   │   ├── pages/      # Page-Level Components
│   │   ├── store/      # Redux Store
│   ├── App.js          # Main Frontend File
│── README.md           # Project Documentation
```

## Future Enhancements
- **Payment Gateway Integration**
- **Automated Booking Confirmation**
- **Reviews & Ratings for PGs**
- **Google Maps API for Location-based Search**

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests!

## License
This project is licensed under the MIT License.

