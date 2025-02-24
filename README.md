This is  User Authentication System aur Product Management ka combination hai.

1. Database Table Creation
Sabse pehle, MySQL database mein do tables banayenge:

users Table (User Authentication ke liye)
id ,name ,email ,password ,created_at

products Table (Product Management ke liye)
id ,name ,description ,price  ,created_at

2. User Authentication System (PHP Script)
Ek PHP-based login system jo user registration, login, aur password reset ko handle karega.

Features:
User Registration – Name, Email, aur Password store hoga database mein.
Password Storage – Secure hashing (password_hash) ka use karenge.
User Login – Email aur password verify hoga, aur session start hoga.
Forgot Password – OTP 1111 set rahega reset ke liye.
Access Control – Sirf logged-in users ko specific pages dikhenge.
User List Page – Show all users with Add, Edit, Delete option.
Product List Page – Show all products with Add, Edit, Delete option.


3. Product Management (PHP Script)
Ek CRUD (Create, Read, Update, Delete) operations handle karegi.


4. User selects product(s) from the list.
Bill generate button click karne par selected product details fetch honge.
TCPDF ka use karke PDF generate hoga with:
Auto-generated serial number
Today's date
Product details (name, price, total)
Thank YOU!!
