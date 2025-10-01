# 🏠 Real Estate Management System  

Link :https://drive.google.com/file/d/17wA0PCkk84g32Q6zWIemZ4FfpFNJPZg0/view?usp=drive_link

A **full-stack PHP & MySQL powered platform** for managing real estate listings, agents, and customer interactions.  
The system provides role-based dashboards for **Admins, Agents, and Customers**, with integrated property management, authentication, and payment support.  

---

## ✨ Features  

- **Authentication & Roles**
  - Secure login/registration for **Admin, Agents, and Customers**  
  - Email verification & password reset flows  

- **Property Management**
  - Agents can add, edit, and delete properties  
  - Customers can browse, filter, and save properties to wishlist  

- **Payments**
  - Integrated **PayPal & Stripe** checkout for property orders  
  - Success & cancellation flows  

- **Customer Dashboard**
  - Manage profile and saved properties  
  - Reset and manage credentials  

- **Agent Dashboard**
  - Property uploads with **photo & video galleries**  
  - Manage orders and customer interactions  

- **Admin Panel**
  - Centralized control over users, agents, and listings  
  - Pricing & location management  

---

## 🛠️ Tech Stack  

- **Backend**: PHP 8+, Composer  
- **Frontend**: HTML5, CSS3, JavaScript  
- **Database**: MySQL / MariaDB  
- **Payment Gateways**: PayPal, Stripe  
- **Server**: Apache / Nginx  

---

## 📂 Project Structure  

```bash
real_estate_project/
│── admin/                  # Admin dashboard
│── agent-*.php             # Agent functionality
│── customer-*.php          # Customer functionality
│── property.php            # Property details
│── config/                 # Configuration files
│── dist/                   # Frontend assets
│── uploads/                # Uploaded property images/videos
│── composer.json           # Composer dependencies
│── vendor/                 # Autoloaded libraries
│── index.php               # Entry point
