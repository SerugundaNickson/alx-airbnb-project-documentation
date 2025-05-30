# Airbnb Clone Backend - Features and Functionalities

This document outlines the core features and functionalities required for the backend of the Airbnb Clone project. The purpose is to define the system’s technical and functional components in a clear and structured manner.

##  Core Features

### 1. User Management
- User registration for guests and hosts.
- Secure login system using JWT.
- OAuth support (Google, Facebook).
- Profile update with photos, contact info, and preferences.

### 2. Property Listings
- Hosts can add properties with title, location, price, availability, and amenities.
- Ability to edit or delete listings.
- Upload property images.

### 3. Search and Filter
- Search by location, date, price, number of guests, amenities.
- Pagination for large result sets.

### 4. Booking Management
- Guests can book properties.
- Validations to prevent double bookings.
- Booking status: pending, confirmed, cancelled, completed.
- Guests and hosts can cancel bookings.

### 5. Payments
- Integration with Stripe, PayPal.
- Secure guest payments.
- Automatic host payouts after successful booking.
- Support for multiple currencies.

### 6. Reviews and Ratings
- Guests can leave reviews and ratings (1 to 5 stars).
- Hosts can reply to reviews.
- One review per completed booking.

### 7. Notifications
- Email and in-app notifications:
  - Booking confirmation
  - Cancellations
  - Payment status

### 8. Admin Dashboard
- Admin can view and manage users, listings, bookings, and payments.

---

##  Technical Requirements

- Relational database: PostgreSQL or MySQL.
- RESTful API with proper HTTP methods.
- JWT authentication and role-based access control.
- File storage for images (e.g., Cloudinary or S3).
- Integration with email services (e.g., SendGrid).
- Error handling and logging system.

---

##  Non-Functional Requirements

- **Scalability**: Modular architecture and load balancing.
- **Security**: Password encryption, firewall, rate limiting.
- **Performance**: Redis caching, optimized DB queries.
- **Testing**: Unit and API testing (e.g., Pytest).

---

##  Diagram

Refer to the included `features-diagram.png` for a visual breakdown of these features and their relationships.

![Airbnb Clone Backend Diagram](features-diagram.png)



