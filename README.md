# MANIT Mart

**MANIT Mart** is a modern React-based online marketplace designed specifically for college students to buy and sell products within their campus community. The application offers a smooth and secure user experience with features like Firebase authentication, real-time database, dark mode, and product listing filters.

## ⚙️ Tech Stack

| Technology     | Description                                  |
|----------------|----------------------------------------------|
| React.js       | Frontend library for building UI             |
| Firebase       | Backend-as-a-Service (Auth, Firestore, Storage) |
| React Router   | Client-side routing for SPA                  |
| Tailwind CSS   | Utility-first CSS framework                  |
| React Hot Toast| Toast notifications for user feedback       |
| Vite           | Fast build tool and development server       |

---

## ✨ Features

- 🔐 **Firebase Authentication**  
  - Email/password authentication with email verification  
  - Secure session management  

- 👤 **Profile Management**  
  - Users can update personal information (name, hostel)  
  - View and manage their listed products  

- 🛒 **Product Listings**  
  - Post, update, and delete product listings  
  - View listings from other users  
  - **Filter products by category, condition, and price range**  
  - Mark products as "interested"  
  - Multiple image support per product  

- 🌙 **Dark Mode Support**  
  - Toggle between light and dark themes for better accessibility  
  - Persistent theme preference using localStorage  

- 📱 **Responsive Design**  
  - Mobile-first approach with Tailwind CSS  
  - Optimized for all screen sizes  

- 📧 **Contact Form**  
  - Integrated with Web3Forms for user inquiries  

---

## 🗂️ Folder Structure

```
Manit-Mart/
├── frontend/               # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   │   ├── Navbar.jsx
│   │   │   ├── Banner.jsx
│   │   │   ├── Buy.jsx
│   │   │   ├── Sell.jsx
│   │   │   ├── Profile.jsx
│   │   │   ├── BookCard.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Signup.jsx
│   │   │   ├── Contact.jsx
│   │   │   └── Footer.jsx
│   │   ├── Home/           # Home page components
│   │   │   └── Home.jsx
│   │   ├── App.jsx         # Main app component with routing
│   │   ├── main.jsx        # App entry point
│   │   ├── firebase.js     # Firebase configuration
│   │   └── index.css       # Global styles
│   ├── public/             # Static assets
│   │   └── collegelogo.png
│   ├── package.json
│   ├── vite.config.js
│   └── tailwind.config.js
├── seed.html               # Firestore data seeding tool
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- Firebase account and project setup

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/vinaychallapalli/Manit-Mart.git
   cd Manit-Mart
   ```

2. **Set up Firebase:**

   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication (Email/Password method)
   - Create Firestore Database
   - Get your Firebase configuration

3. **Configure the frontend:**

   ```bash
   cd frontend
   npm install
   ```

   Create `.env` file in the frontend directory:

   ```env
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   VITE_FIREBASE_APP_ID=your_app_id
   VITE_ACCESS_KEY=your_web3forms_access_key
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

5. Open the app at:  
   [http://localhost:5173](http://localhost:5173)

---

## 🌐 Firebase Services Used

- **Authentication**: User signup, login, and email verification
- **Firestore**: Real-time database for users and products
- **Storage**: Image storage for product photos (optional)

---

## 🧠 Future Enhancements

- Real-time chat between buyers and sellers
- Payment gateway integration
- Push notifications for new listings
- Admin dashboard for content moderation
- Mobile app development


