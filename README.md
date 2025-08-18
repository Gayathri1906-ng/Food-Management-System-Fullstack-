🍴 Food Management System 
📌 Overview  
This project is a Food Management Dashboard built using React + Vite.  
It enables administrators to manage food items, categories, and customer orders with a responsive and user-friendly interface.  
The dashboard is designed for restaurants, food delivery platforms, and online ordering systems.  

⚙️ Tech Stack  
- ⚛️ Frontend:React (Vite for fast builds)  
- 🎨 Styling: CSS  
- 🛣️ Routing:React Router  
- 🔔 Notifications:React Toastify  
- 🖼️ Assets:Custom icons for food, orders, and profile  

🚀 Features  
✅ Admin Dashboard with Sidebar & Navbar  
✅ Add New Food Items with details & images  
✅ View & Manage Food Items (Edit/Delete options extendable)  
✅ Handle Customer Orders (Approve / Reject)  
✅ Responsive UI (Desktop & Mobile)  
✅ Super-fast builds & hot reload using Vite  

📊 Pages  
- Dashboard→ Overview of activity  
- Add Page → Add new food items  
- List Page → View and manage menu items  
- Orders Page → Handle customer orders  

👨‍🍳 Customer (Frontend)  
✅ Browse food items  
✅ Add to cart & checkout  
✅ Place orders  
✅ User authentication  

🛠️ Admin (Dashboard)  
✅ Manage food items (Add / Edit / Delete)  
✅ View all food items in a list  
✅ Handle customer orders (Approve / Reject)  
✅ Dashboard with responsive sidebar & navbar  

⚡ Backend  
✅ REST API for orders, food items, users  
✅ JWT authentication  
✅ MongoDB database integration  


📂 Project Structure  
food/
├── frontend/ # Customer-facing React app
│ ├── src/ # Components, pages, assets
│ ├── package.json
│ └── ...
├── backend/ # Node.js + Express API
│ ├── models/ # Database models (MongoDB)
│ ├── routes/ # API routes
│ ├── controllers/ # Business logic
│ ├── server.js # Main backend entry
│ └── package.json
├── admin/ # Admin Dashboard
│ ├── src/ # React components, pages
│ ├── vite.config.js
│ ├── package.json
│ └── ...
└── README.md # Project documentation

🔧 Installation & Setup  
1️⃣ Clone the repository  
git clone https://github.com/yourusername/food-management-system.git
cd food
2️⃣ Setup Backend
bash
Copy
Edit
cd backend
npm install
npm start
Runs on: http://localhost:5000

3️⃣ Setup Frontend
bash
Copy
Edit
cd frontend
npm install
npm run dev
Runs on: http://localhost:3000

4️⃣ Setup Admin Dashboard
bash
Copy
Edit
cd admin
npm install
npm run dev
Runs on: http://localhost:5173

📜 License
This project is licensed under the MIT License.

✨ Built with ❤️ using **React + Vite**

