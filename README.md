FoodMart is a full-featured MERN Stack food ordering web application where users can browse food items, add them to cart, and place orders seamlessly.
It includes secure authentication, cart management, image uploads, responsive UI, and a fully modular backend using Express and MongoDB.
# Tech Stack
->Frontend
React.js
React Router
Tailwind CSS
Axios
Context API / Redux (if you used)
Responsive UI

->Backend
Node.js + Express.js
MongoDB & Mongoose
Multer (Food image uploads)
JWT Authentication
Bcrypt.js for password hashing
dotenv for environment configs

 #Core Features
->User Authentication
Register / Login with JWT
Password hashing via bcrypt
Protected routes for authorized access

->Cart System
Add to Cart
Remove from Cart
Update Quantity
Automatic cart sync with backend
Cart persists per user

->Food Items
Admin can add food items (with images using Multer)
Food list displayed dynamically
Categories / filtering (if added)

->Order Processing
Users can place orders
Order details stored in MongoDB
Order summary page

->Modern UI
Built with Tailwind CSS
Fully responsive: mobile → desktop
Clean, smooth UX

->Database & API
Mongoose models
REST API architecture
Error handling with middleware
