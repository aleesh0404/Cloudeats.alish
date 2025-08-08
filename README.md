# 🍽️ Cloud Eats - Premium Cloud Kitchen

A modern, responsive cloud kitchen website built with React frontend and Node.js backend.

## 🚀 Features

- **Interactive Menu**: Browse delicious food items with prices
- **Shopping Cart**: Add/remove items and view total
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Modern UI**: Beautiful gradient design with smooth animations
- **RESTful API**: Complete backend with order management
- **Real-time Updates**: Dynamic cart and order status

## 📁 Project Structure

```
cloud-eats/
├── frontend/          # React application
│   ├── public/
│   ├── src/
│   │   ├── App.js     # Main component
│   │   ├── App.css    # Styles
│   │   └── index.js   # Entry point
│   └── package.json
├── backend/           # Node.js server
│   ├── server.js      # Express server
│   └── package.json
└── README.md
```

## 🛠️ Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Install Frontend Dependencies:**
   ```bash
   cd frontend
   npm install
   ```

2. **Install Backend Dependencies:**
   ```bash
   cd ../backend
   npm install
   ```

### Running the Application

1. **Start Backend Server:**
   ```bash
   cd backend
   npm start
   ```
   Server will run on: http://localhost:5000

2. **Start Frontend Development Server:**
   ```bash
   cd frontend
   npm start
   ```
   App will open on: http://localhost:3000

## 🍽️ Menu Items

- Grilled Chicken - $12.99
- Beef Burger - $9.99
- Caesar Salad - $8.99
- Pizza Margherita - $14.99
- Pasta Carbonara - $11.99
- Chocolate Cake - $6.99
- Ice Cream - $4.99
- French Fries - $5.99

## 🔧 API Endpoints

- `GET /api/menu` - Get all menu items
- `GET /api/menu/:id` - Get specific menu item
- `POST /api/orders` - Create new order
- `GET /api/orders` - Get all orders
- `GET /api/orders/:id` - Get specific order
- `PUT /api/orders/:id/status` - Update order status
- `GET /api/health` - Health check

## 🎨 Features

- **Responsive Design**: Mobile-first approach
- **Modern UI**: Gradient backgrounds and smooth animations
- **Interactive Cart**: Add/remove items with real-time updates
- **Order Management**: Complete order lifecycle
- **Beautiful Typography**: Poppins font family
- **Hover Effects**: Engaging user interactions

## 📱 Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## 🚀 Deployment

### Frontend (React)
```bash
cd frontend
npm run build
```

### Backend (Node.js)
```bash
cd backend
npm start
```

## 🛠️ Technologies Used

**Frontend:**
- React 18
- CSS3 with Flexbox/Grid
- Responsive Design
- Modern JavaScript (ES6+)

**Backend:**
- Node.js
- Express.js
- CORS
- Body Parser

## 📞 Support

For any questions or issues, please contact the development team.

---

**Cloud Eats** - Premium Cloud Kitchen Experience 🍽️
