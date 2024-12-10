# Functional Requirements
### User Registration and Authentication:

- Users must be able to register by providing their name, email, phone, password, and role (tenant or landlord).
- Users must be able to log in using their email and password.

### User Management:

- Users must be able to update their profile details (e.g., phone, password).
- Admin should have the ability to manage users (block, delete).

### Property Management:

- Lessor must be able to add new properties, including title, description, address, price, and availability dates.
- Lessor must be able to update or delete properties they own.

### Property Browsing:

- Tenants must be able to view available properties based on filters (price range, location, availability).
- A search functionality should be available for properties by title or address.

### Property Images:

- Lessors must be able to upload multiple images for a property.
- Tenants must be able to view all images associated with a property.

### Booking Management:

- Tenants must be able to book available properties by specifying start and end dates.
- Lessors must be able to view booking requests and approve/reject them.

### Booking Status:

- Tenants must be able to see the status of their bookings (pending, confirmed, rejected).
- Notifications should be sent to tenants when booking status changes.
### Availability Checks:

- System should ensure that properties cannot be double-booked for overlapping dates.
### Admin Reporting:

- Admin should have access to reports on total properties, bookings, and user statistics.
- 
### Security:

- Passwords must be stored securely using hashing.
- Authentication should be enforced using tokens (e.g., JWT).
