# Online Marketplace System

## Project Overview
The Online Marketplace System is a Java-based e-commerce platform that allows sellers to manage product listings and customers to browse, purchase, and checkout items securely. The system is designed with an object-oriented approach and features a command-line interface for efficient transactions.

## Features
### User Authentication
- Users can log in using an email and password.
- Role-based access control (Seller or Customer).

### Product Catalog
- Sellers can add, update, and remove products.
- Customers can browse a dynamic product catalog.

### Shopping Cart
- Customers can add, remove, and update items in the cart.
- Customers can review their cart before checkout.

### Order Processing
- The system processes orders and maintains order integrity.
- Customers can finalize purchases through multiple payment methods.

### Payment Methods
- Supports Cash on Delivery (COD), Debit/Credit Card, and GCash transactions.

## Installation and Setup
1. Clone the repository or download the project files.
2. Ensure Java is installed on your system.
3. Open the project in your preferred Java development environment (e.g., Eclipse, IntelliJ, or command line).
4. Compile and run `Main.java` to start the application.

## How to Use
### Login and Role Selection
- Users must log in using a valid email and password.
- After authentication, users select their role (Seller or Customer).

### Seller Features
- Manage product catalog (Add, Update, Remove, Search).
- View and update account details.

### Customer Features
- Browse available products.
- Add products to the shopping cart.
- Remove or modify items before checkout.
- Complete transactions with a selected payment method.

### Checkout Process
- Order total is computed, including shipping fees.
- Payment is confirmed, and an option to generate a receipt is provided.

## File Structure
- `Main.java` - Entry point of the system.
- `User.java` - Abstract class defining common user attributes.
- `Seller.java` - Manages product catalog and seller functions.
- `Customer.java` - Handles shopping cart and order processing.
- `Catalogue.java` - Stores and manages product listings.
- `Product.java` - Defines product attributes and methods.
- `ShoppingCart.java` - Manages items selected for purchase.
- `Order.java` - Handles order details and tracking.
- `Payment.java` - Processes payment and receipt generation.

## Future Enhancements
- Implement a GUI-based interface for better user experience.
- Expand payment methods to include more online wallets.
- Add database integration for persistent data storage.

## Contributors
- Luis Anton S. Gonzales
- Mikhael Edman P. Gomez
- Clarence Adrian M. Junio
- Johann Patrick S. Taguiam

## License
This project is for academic purposes and not intended for commercial use.

## Contact
For inquiries or suggestions, please contact the project contributors.

## Link & References
- [Documentation](https://docs.google.com/document/d/1YyMaBH3jv1cHICCrNv3u8prOoUobIJWI/edit?usp=sharing&ouid=116709682777897150867&rtpof=true&sd=true)

