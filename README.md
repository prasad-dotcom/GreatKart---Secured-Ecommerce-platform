# GREATKART – A Secured E-commerce Platform  

GREATKART is a **secured and scalable e-commerce platform** built with Django (backend) and React.js (frontend).  
It provides a dynamic shopping experience with strong security measures, seamless payment integration, and user-friendly features.  

---

## 🔹 Features  

### 1. Mastering Product Management and Variations  
- Scalable product management system for admins to create and manage products.  
- Support for **product variations** such as size and colour.  
- Django’s relational models and custom managers enable users to select specific combinations for a dynamic shopping experience.  

### 2. Custom Shopping Cart Functionality  
- Fully customized **shopping cart** built from scratch (no third-party library).  
- Supports **guest and authenticated user sessions**.  
- Add, remove, and update items with **dynamic subtotal calculation**.  
- Smooth integration with checkout and order modules.  

### 3. Context Processors for Global Data Handling  
- Implemented **Django context processors** for commonly needed data like cart item count and category lists.  
- Reduces redundant code and keeps templates clean.  
- Ensures important data is always available across all pages.  

### 4. Order Management and Payment Flow  
- Structured **order management system** with automatic order number generation.  
- Users can review cart, provide delivery details, and confirm orders.  
- Integrated **PayPal payment gateway** for secure and seamless transactions.  
- Admin dashboard to track and manage transactions.  

### 5. Security with Token-Based Verification  
- Implemented **token-based email verification and password reset**.  
- Ensures only verified users can perform sensitive actions.  
- Strengthens application security and user trust.  

### 6. Google Gmail Login with SMTP Verification  
- Integrated **Google Gmail authentication** for login and registration.  
- Uses **SMTP protocol** for sending verification emails.  
- Enhances both **security and user trust** with verified email accounts.  

### 7. Product Reviews for Customer Engagement  
- Verified customers can leave **reviews and ratings** on purchased products.  
- Reviews displayed on product detail pages, boosting transparency.  
- Encourages user interaction and trust in the platform.  

### 8. Securing Admin Access with Django Honeypot  
- Default `/admin` path replaced with **django-admin-honeypot** for enhanced security.  
- Fake admin login page at `/admin` to mislead bots and unauthorized access.  
- Real admin interface moved to a **secret URL** for safety.  
- Logs suspicious attempts, strengthening backend security.  

---

## 🔹 Tech Stack  

- **Frontend:** HTML, CSS, JavaScript, React.js  
- **Backend:** Django  
- **Database:** SQLite  

---

## 🔹 Installation & Setup  

1. Clone the repository:  
   ```bash
   git clone https://github.com/prasad-dotcom/GreatKart---Secured-Ecommerce-platform.git
   cd GreatKart---Secured-Ecommerce-platform
2.Create and activate a virtual environment:

  python -m venv env
  env\Scripts\activate   # On Windows
  source env/bin/activate  # On macOS/Linux


3.Install dependencies:

  pip install -r requirements.txt


4.Apply migrations:

  python manage.py migrate


5.Create a superuser (for admin access):

  python manage.py createsuperuser


6.Run the development server:

  python manage.py runserver


7.Open in browser:

  http://127.0.0.1:8000/




##DEMO VIDEO


[Click here to watch the demo](demo/GReat_cart%20demo%20video.mp4) (view Raw or download Raw video).

