# Food Website

Welcome to the **Food Website**! This project is designed to provide users with a seamless way to explore menus, order food, and enjoy a rich, interactive experience. Additionally, administrators can manage the menu dynamically using an admin panel with Cloudinary integration for image uploads. Below, you'll find an overview of how the website works, its features, and how to run it locally.

---

## Features

### User Features
- **Home Page:** A visually appealing landing page showcasing featured dishes and promotional offers.
- **Menu:** A categorized list of dishes with descriptions, images, and prices.
- **Search Functionality:** Search for dishes by name or category.
- **Order System:** Add items to your cart and place an order with ease.
- **User Authentication:** Register, log in, and manage your profile.
- **Responsive Design:** Optimized for both desktop and mobile devices.

### Admin Features
- **Admin Panel:**
  - Add, update, or delete food items dynamically.
  - View and manage all orders.
- **Cloudinary Integration:** Food item images are securely uploaded and stored using [Cloudinary](https://cloudinary.com).

---

## How It Works

### **1. Homepage**

The homepage serves as the gateway to the website:
- Displays a banner with the latest offers.
- Features a "Top Dishes" section with popular items.

### **2. Menu Page**

- The menu is organized into categories (e.g., Starters, Main Course, Desserts, Beverages).
- Each menu item includes an image, name, description, price, and an "Add to Cart" button.

### **3. Search Functionality**

- Users can search for dishes by name or filter by category.
- Results are displayed dynamically without reloading the page.

### **4. Order System**

- Add items to your cart by clicking the "Add to Cart" button.
- View the cart to see selected items, quantities, and the total price.
- Place the order by clicking "Checkout" and providing necessary details (like delivery address).

### **5. Admin Panel**

- Navigate to `/admin` to access the admin panel.
- Use the provided form to upload new food items, including name, description, price, and image.
- Images are uploaded securely to **Cloudinary**.
- Manage existing menu items by updating or deleting them.

### **6. Responsive Design**

The website adapts seamlessly to different screen sizes:
- Desktop: Full menu and navigation.
- Mobile: Collapsible menu and optimized layouts for smaller screens.

---

## Technologies Used

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Image Storage:** Cloudinary
- **Payment Integration:** Stripe (for demo purposes)
- **Deployment:** Vercel (Frontend), Render (Backend)

---

## How to Run Locally

Follow these steps to run the project on your local machine:

### Prerequisites
- Node.js and npm installed.
- MongoDB running locally or a cloud database (e.g., MongoDB Atlas).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/omwagh28/food-website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd food-website
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     MONGO_URI=<your-mongodb-connection-string>
     PORT=5000
     CLOUDINARY_NAME=<your-cloudinary-name>
     CLOUDINARY_API_KEY=<your-cloudinary-api-key>
     CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
     STRIPE_SECRET_KEY=<your-stripe-secret-key>
     ```

5. Start the development server:
   ```bash
   npm start
   ```

6. Open your browser and visit:
   ```
   http://localhost:3000
   ```

---

## Demo

### User Side
[![Watch the demo video](https://img.youtube.com/vi/9qQwv9ZM_2Y/maxresdefault.jpg)](https://youtube.com/shorts/9qQwv9ZM_2Y?si=XSbePE7roXIaWhgG)

---

## Future Improvements

- Implement real-time order tracking.
- Add support for multiple languages.
- Integrate with third-party food delivery services.
- Add user reviews and ratings for dishes.

---

## Contributing

Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

For any inquiries, feel free to reach out:
- Email: omwagh28@example.com
- GitHub: [omwagh28](https://github.com/omwagh28)

