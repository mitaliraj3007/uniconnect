UniConnect
UniConnect is a web-based student marketplace that makes it easy for university students to buy, sell, or trade used textbooks, stationery, and other study materials with peers on campus. It aims to reduce the financial burden of education while promoting a more sustainable, reuse-driven campus community.

#  Features
•	Exclusive Campus Networking: Automatically filters listings based on the authenticated user's college.
•	Live Utilization Dashboard:  Real-time statistics showing the number of items Available, Rented, and Sold.
•	Advanced Search & Filtering:  Keyword search; Category dropdown (Books, Electronics, Furniture, Misc)
•	Listing type toggle (Rent vs. Sell)
•	Interactive price range slider
•	Seamless Listing Creation:   A beautiful, animated modal form for users to post new items instantly.
•	Fluid UI/UX:  Powered by Framer Motion for smooth component mounting, modal transitions, and hover effects.
•	Toast Notifications:   Real-time success and error feedback for network requests.

#Tech Stack
Frontend FrameworkReact.js
Styling: Tailwind CSS
Animations: Framer Motion
Form Handling: React Hook Form
Notifications: React Hot Toast
Routing/Context: React Router DOM & Custom Context API (`AuthContext`)

#Project Structure:
uniconnect/
│── uniconnect-main/
│   ├── uniconnect/              # Frontend
│   ├── uniconnect-backend/      # Backend

# Getting Started:
# Prerequisites
Make sure the following are installed:
•	Node.js
•	MongoDB Atlas account (or local MongoDB)
 # Installation
1. Clone the Repository
https://github.com/mitaliraj3007/uniconnect.git 

2. Install Frontend Dependencies
•	Navigate to frontend:
cd uniconnect-main/uniconnect
npm install
•	Run frontend:
npm run dev
•	Frontend runs on:
http://localhost:5173

3. Install Backend Dependencies
•	Open another terminal:
cd uniconnect-main/uniconnect-backend
npm install
•	Run backend:
npm run dev
•	Backend runs on:
http://localhost:5000

# Environment Variables
Create a .env file inside:
uniconnect-backend/
•	Add:
MONGO_URI=mongodb://127.0.0.1:27017/
uniconnectPORT=5001

#Contributing:
Contributions, issues, and feature requests are welcome!
Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
