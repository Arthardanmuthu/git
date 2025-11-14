✨ Features
1. User Authentication

Register and Login (stored in localStorage)

Password validation

Greeting banner

Logout support

2. Product Management

Preloaded sample products (name, price, rating, image)

Featured products on the home page

Full products list

“Buy Now” & “Add to Wishlist” actions

Review posting with name, rating, text, and timestamp

3. Orders

Add orders (requires login)

Orders saved to localStorage

Order history rendering

JSON report download (orders + wishlist + messages + reviews + user info)

4. Wishlist

Add/remove items

Stored locally

Quick “Buy” option from wishlist

5. Contact Form

Customer-care form (name, email, subject, message)

Stores message history in localStorage

Messages shown in reverse chronological order

6. Reviews

Per-product review section

Inline posting

Name, rating, and comment

Recent reviews displayed (up to 5)

7. Navigation (SPA-like)

Single-page layout

Switching between views without reloading

Smooth scroll & active-menu highlighting

8. UI / UX

Modern clean design

Fully responsive

Modal for Register/Login

Reusable UI components

🗂️ Project Structure

All logic and styling exist in one HTML file:

index.html
 ├── <style> ... CSS styles
 ├── <body>
 │    ├── Header + Navigation
 │    ├── Home / Products / Orders / Wishlist / Contact / About sections
 │    ├── Modal container
 └── <script> ... All JavaScript logic

💾 LocalStorage Keys
Key	Purpose
sd_user	Saved user (name, email, password)
sd_cart	Order history

sd_wishlist	Wishlist items
sd_reviews	Product reviews
sd_messages	Contact form messages
