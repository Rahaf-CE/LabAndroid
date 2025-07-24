🏠 Real Estate Android App

This Android application serves as a full-featured real estate platform with two main user roles:

Customers: Browse properties, add favorites, and make reservations.

Admins: Manage users, view statistics, handle reservations, and assign special offers.

Developed using Java, XML, and SQLite in Android Studio.

✨ Features

🔑 Authentication
Login & Registration

Role-based access (User vs Admin)

Validation & Session Management using SharedPreferences

👤 Customer Features
🏘 View Properties

Displayed using RecyclerView

Each property has images, price, location, and description

💖 Favorites

Add/remove properties to favorites

Directly reserve from favorites

🗓️ Reservations

Select a date and reserve a property

View all your reservations

🖼️ Profile Management

Upload/update profile picture

Save updates only when fields change

Success dialogs and feedback

🛠️ Admin Features
Accessible only via a static admin login or admin-registered accounts.

🗑️ Delete Customers

📊 Statistics Dashboard

Total users, reservations, gender & country charts

👨‍💼 Add New Admins

Register new admins with the same form

📅 View All Reservations

List of reservations with all details

🌟 Create Special Offers

Highlight properties with offers

🚪 Logout

🗃️ Tech Stack

Layer	Tech
Language	Java
IDE	Android Studio
UI	XML Layouts, RecyclerView
Database	SQLite
State Storage	SharedPreferences
Image	Glide (for profile pics)

🚀 How to Run

Open in Android Studio

Connect emulator or device

Run the app

🔑 Admin Static Login

pgsql
Copy
Edit
Email: admin@admin.com
Password: Admin123!

🔮 Future Work

Firebase integration

Email verification via SMTP or Firebase

Push notifications

Filtering/sorting for properties

Upload properties with admin panel
