# 🚗 Vehicle Service Management System

This is a web-based **Vehicle Service Management System** designed to streamline customer login, registration, and service tracking functionalities. The system helps service centers manage customer data, bookings, and service records efficiently.

## 📌 Key Features

- 🔐 **Customer Login** using Email and Phone Number
- 📝 **Customer Sign-Up** page for new user registration
- 📊 **Customer Dashboard** with personalized data
- 🧾 Service booking and history (optional modules)
- 📱 Responsive UI built with **Bootstrap 5**

---

## 🏗️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Fetch API)
- Bootstrap 5

### Backend (expected/optional)
- Java with Spring Boot
- Hibernate (JPA)
- MySQL Database
- RESTful API architecture

---

## 📁 Project Structure

/vehicle-service-management-system │ ├── index.html # Customer login page ├── CustomerSignUp.html # Customer registration page ├── CustomerDashboard.html # Logged-in dashboard ├── assets/ # Images and icons ├── style.css # Custom styling (optional) ├── README.md # Project documentation └── ...

yaml
Copy
Edit

---

## 🔌 API Integration

Login form sends a POST request to:

POST http://localhost:8080/api/v1/customers/CustomerLogin

css
Copy
Edit

### Example Request Body:

```json
{
  "email": "john@example.com",
  "phone": "0712345678"
}
Expected Response:
200 OK on success

401 Unauthorized or 404 Not Found on failure

🚀 How to Run
Start your backend server (Spring Boot if you're using it).

Open index.html in a browser.

Use existing customer credentials or click Sign Up to register.

On successful login, you'll be redirected to CustomerDashboard.html.

![Screenshot 2025-04-16 204551](https://github.com/user-attachments/assets/5e547110-0279-4cda-92c7-42fcca0c64ae)
![Screenshot 2025-04-16 204640](https://github.com/user-attachments/assets/7599da7f-3665-41be-bdc0-13708c213d28)


📌 Future Enhancements
 Admin dashboard for service staff

 Service scheduling module

 SMS/email notification support

 Payment gateway integration

👨‍💻 Developed By
Kalindu Akalanka
📘 IJSE | Batch 69 | S2
📧 ktdkakalanka@gmail.com
📞 0705713136
