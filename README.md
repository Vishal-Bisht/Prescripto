
# Prescripto

Prescripto is a modern web application designed to streamline the process of booking, managing, and tracking medical appointments for patients, doctors, and administrators. Built with a robust backend and a responsive frontend, Prescripto aims to simplify healthcare management for all users.

## Features

### For Patients
- Browse and search for doctors by specialty
- Book, view, and manage appointments
- View doctor profiles and ratings
- Track appointment history
- Secure login and profile management

### For Doctors
- Manage appointments and schedules
- View patient details and appointment history
- Update profile and availability
- Secure login and dashboard

### For Admins
- Manage doctors and patients
- View and manage all appointments
- Analytics and earnings dashboard
- Add or remove doctors

## Tech Stack

- **Frontend:** React, Vite, CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Cloud Storage:** Cloudinary (for file uploads)
- **Authentication:** JWT (JSON Web Tokens)
- **Other:** Multer (file uploads), ESLint (code quality)

## Project Structure

```
Prescripto/
├── backend/
│   ├── config/           # Configuration files (Cloudinary, MongoDB)
│   ├── controllers/      # Route controllers for admin and doctor
│   ├── middlewares/      # Middleware (e.g., Multer for uploads)
│   ├── models/           # Mongoose models (Doctor, User)
│   ├── routes/           # Express routes (admin, doctor)
│   ├── package.json      # Backend dependencies
│   └── server.js         # Entry point for backend server
├── frontend/
│   ├── public/           # Static assets
│   ├── src/              # React source code
│   │   ├── assets/       # Images, SVGs, and other assets
│   │   ├── components/   # Reusable React components
│   │   ├── context/      # React context providers
│   │   ├── pages/        # Page components (Home, Login, etc.)
│   │   ├── App.jsx       # Main app component
│   │   ├── main.jsx      # Entry point for React
│   │   └── index.css     # Global styles
│   ├── package.json      # Frontend dependencies
│   └── vite.config.js    # Vite configuration
└── README.md             # Project documentation
```

## Getting Started

### Prerequisites
- Node.js (v14 or above)
- npm or yarn
- MongoDB instance (local or cloud)
- Cloudinary account (for image uploads)

### Installation

1. **Clone the repository:**
	```sh
	git clone https://github.com/Vishal-Bisht/Prescripto.git
	cd Prescripto
	```

2. **Install backend dependencies:**
	```sh
	cd backend
	npm install
	```

3. **Install frontend dependencies:**
	```sh
	cd ../frontend
	npm install
	```

4. **Set up environment variables:**
	- Create a `.env` file in the `backend` directory with your MongoDB URI, JWT secret, and Cloudinary credentials.

5. **Start the backend server:**
	```sh
	cd backend
	npm start
	```

6. **Start the frontend development server:**
	```sh
	cd frontend
	npm run dev
	```

7. **Open the app:**
	- Visit `http://localhost:5173` in your browser.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

## License

This project is licensed under the MIT License.

---

**Prescripto** — Simplifying healthcare, one appointment at a time.
