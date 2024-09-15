# Documentation
---

## 1. Introduction and Rationale
The goal of this project is to develop a modern restaurant application that provides a seamless experience for users to explore the menu, make reservations, order food online, and provide feedback. The app aims to improve customer satisfaction and simplify restaurant operations. It will be available on both web and mobile platforms, ensuring accessibility for a wide range of users.

---

## 2. Content Evaluation

### a. Navigation
The app will have the following navigation structure:
- **Home:** Introduction, restaurant information, featured dishes.
- **Menu:** Categorized list of available dishes with descriptions and prices.
- **Reservations:** Allows users to book a table with a date and time selector.
- **Order Online:** Choose food items, add them to the cart, and complete the order.
- **Feedback:** Submit customer reviews and feedback.
- **User Account:** View order history, edit profile, and payment options.

### b. Layout (Wireframe at Start)
- **Home Page:** Banner with the restaurant’s logo, sections showcasing featured dishes, "Order Now" button, and a brief intro of the restaurant.
- **Menu Page:** Category filters (Starters, Mains, Desserts, Drinks), grid view of items with a price and "Add to Cart" button.
- **Reservations Page:** A form with fields for date, time, number of guests, and special requests.
- **Order Page:** Food items listed with cart functionality, payment options at the bottom.
- **Account Page:** Profile picture, order history, and editable contact/payment info.

### c. Content Descriptions and Sources
- **Restaurant Info:** Includes description, mission, and story about the restaurant.
- **Menu Items:** Each dish will have a name, description, price, and availability status. Menu data is stored in a MySQL database and retrieved via a REST API.
- **Images:** High-quality images of dishes sourced from free-to-use image libraries or in-house photography.
- **Feedback and Reviews:** User-generated content (UGC) including text reviews and star ratings.

---

## 3. Functionality (User Stories)

### a. Must Have User Stories
1. As a user, I want to browse the menu by categories (starters, mains, desserts) so I can easily find dishes.
2. As a user, I want to view dish descriptions and prices so I can make informed decisions.
3. As a user, I want to add items to my cart so I can place an order.
4. As a user, I want to checkout and pay for my order with a credit card so I can complete my purchase.
5. As a user, I want to create an account so I can save my contact and payment details.
6. As a user, I want to make a reservation by selecting a date, time, and number of guests.
7. As a restaurant admin, I want to manage the menu so I can update item availability.
8. As a restaurant admin, I want to view all incoming orders so I can process them.

### b. Should Have User Stories
9. As a user, I want to receive notifications on order status changes so I can track my delivery.
10. As a user, I want to filter the menu by dietary preferences (vegan, gluten-free) so I can find appropriate dishes.
11. As a user, I want to view my previous orders so I can reorder easily.
12. As a user, I want to leave feedback on the dishes I ordered.
13. As a restaurant admin, I want to manage reservations to confirm or deny bookings.
14. As a user, I want to cancel my reservation if plans change.
15. As a user, I want to pay via different methods (credit card, PayPal, Apple Pay).
16. As a user, I want to log in with my social media accounts (Google, Facebook).

### c. Nice to Have User Stories
17. As a user, I want to browse the menu in multiple languages so I can understand the content in my language.
18. As a user, I want to view a map of the restaurant’s location so I can plan my visit.
19. As a restaurant admin, I want to receive real-time order notifications on a mobile app.
20. As a user, I want to reserve special requests for seating arrangements (e.g., outdoor, booth).
21. As a user, I want to upload images of my experience to accompany reviews.
22. As a user, I want to see real-time table availability for reservations.
23. As a restaurant admin, I want to generate reports on the most popular menu items.
24. As a user, I want to apply discount codes during checkout.
25. As a user, I want to order food for pickup instead of delivery.

---

## 4. Hourly Estimates

| User Story   | Estimate (Hours) |
|--------------|------------------|
| Must Have    | 40 Hours         |
| Should Have  | 30 Hours         |
| Nice to Have | 15 Hours         |
| **Total**    | **85 Hours**      |

---

## 5. Technical Specifications

### a. Technology Stack
- **Frontend:** HTML5, CSS3, JavaScript, WordPress (for web structure), Elementor/WPBakery (optional), WooCommerce (for online ordering), WPForms (for reservations).
- **Backend:** WordPress PHP Core, Custom PHP (if required), REST API integration.
- **Database:** MySQL (managed by WordPress for content, user, and order data).

### b. Security
- SSL encryption for secure transactions.
- Wordfence plugin for security hardening.
- Regular backups via UpdraftPlus.

### c. Mobile Optimization
- Responsive design using CSS media queries.
- WordPress's built-in themes or custom CSS for optimization.

### d. Payment Gateway
- WooCommerce Payment Gateway (supports PayPal, Stripe, etc.).

### e. Analytics
- Google Analytics integrated via a WordPress plugin.

---

## 6. Development Specifications

### a. File-Naming Conventions
- Component files: Lowercase (e.g., `reservationPage.js`)
- Utility and API files: camelCase (e.g., `api.js`)

### b. Accessibility Standards
- Follow WCAG 2.1 guidelines (color contrast, keyboard navigation, screen reader compatibility).
- Use semantic HTML (`<nav>`, `<header>`, `<main>` tags) for screen reader support.

### c. Responsiveness Requirements
- Mobile-first design approach with media queries for various breakpoints: 
  - 320px (phones), 768px (tablets), 1200px (desktops).

