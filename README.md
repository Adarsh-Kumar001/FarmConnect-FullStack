# 🌾 FarmConnect – Smart Agriculture Web Platform

FarmConnect is an intelligent, full-stack agricultural web platform designed to empower farmers and consumers. It enables users to:
- Detect rotten/fresh fruits and vegetables,
- View weather updates,
- List farm produce or items in an integrated marketplace,
- Communicate instantly via a real-time chat system.

---

## 🔍 Project Features

### 🧠 Shelf Life Prediction
- Upload images of fruits or vegetables to detect freshness.
- Uses a trained YOLOv5 model to determine the state of the produce.
- Predicts estimated shelf life to help with timely sale and usage.

### ☁️ Weather Updates
- Integrated with the OpenWeather API.
- Users can search and view weather details by city to plan harvests and deliveries efficiently.

### 🛒 Marketplace 
- Farmers can list surplus or used items for free.
- Buyers can view product listings, images, and details.
- Chat functionality allows direct communication with sellers.

### 💬 Chat Feature
- Real-time Firebase Firestore-based messaging system.
- Enables buyers and sellers to interact instantly.

### 🔐 Secure Authentication
- authentication via Firebase.
- Ensures a seamless and secure login experience for users.

---

## 🛠 Tech Stack

### 🔧 Frontend
- **React.js** with **Tailwind CSS** for modern, responsive UI.

### 🔧 Backend & Services
- **Roboflow pretrained model api** for serving ML predictions.
- **Firebase Authentication** for login.
- **Firebase Firestore** for real-time messaging.
- **Supabase** for image storage.
- **PostgreSQL**, **DrizzleORM** for database.
- **YOLO** trained model for produce freshness detection.
- **OpenWeather API** for weather updates.

---

## 📁 Project Structure
- 

