# <span style="color:#007BFF;"> E-Commerce-System </span>
## <span style="color:#28a745;">1. Functional Requirements</span>
### 1.1 User Management
- Registration/Login System: Users can register and create an account using email and password, or through social media login (e.g., Google, Facebook).
- User Profiles: Users can edit their profile information (name, email, shipping addresses).
- Roles: Separate user roles for Admin, Customer, and Guest.
### 1.2 Product Management
- Product Listing: Ability to display products with images, descriptions, prices, and sizes (S, M, L, XL).
- Product Categories: Categories for filtering products, such as sweatshirts, t-shirts, new arrivals, and sales.
- Product Details: Individual product pages showing larger images, detailed description, and available sizes.
- Inventory Management: Admin can track inventory and mark products as out-of-stock.
### 1.3 Shopping Cart & Checkout
- Cart Management: Customers can add/remove items from the cart, view cart summary, and proceed to checkout.
- Checkout Process: A secure checkout process where customers provide shipping and billing information.
- Payment Gateway Integration: Support for multiple payment methods (Credit Cards, PayPal, Stripe, etc.).
- Order Confirmation: Email and on-screen order confirmation with order summary.
### 1.4 Order Management
- Order History: Customers can view past orders and order statuses (e.g., Processing, Shipped, Delivered).
- Admin Dashboard: Admin can view and manage orders, update order statuses, and print invoices.
### 1.5 Shipping
- Shipping Calculation: Calculate shipping fees based on location and order size.
- Multiple Shipping Options: Support for different shipping methods (standard, express).
### 1.6 Promotions & Discounts
- Discount Codes: Ability to apply discount codes during checkout.
- Sales and Promotions: Admin can set up and manage promotions (e.g., percentage off, buy-one-get-one-free).
### 1.7 Reviews & Ratings
- Product Reviews: Customers can leave reviews and ratings for purchased products.
### 1.8 Wishlist
- Wishlist Functionality: Registered users can add products to a wishlist for future purchase.
### 1.9 Search & Filtering
- Search: A product search feature with autocomplete.
- Filtering: Filters for size, color, price range, and categories.
### 1.10 Reporting & Analytics
- Sales Reports: Admin can view daily, weekly, monthly sales reports.
- Customer Analytics: Insights into user behavior (e.g., most viewed products, cart abandonment).
  
# 2. E-Commerce System Functional Requirements Use cases

## 2.0 User Management

### 2.1 Registration and Login
- As a Guest, I can create an account using an email and password or by using social media logins (e.g., Google, Facebook).
- As a Registered User, I can log in using my email and password or a connected social media account.
- As an Admin, I can view, manage, and deactivate user accounts.

### 2.2 User Profiles
- As a Registered User, I can edit my profile (name, email, shipping addresses).
- As a Registered User, I can add multiple shipping addresses to my profile for future orders.
- As an Admin, I can update user information when necessary (e.g., for support).

### 2.3 Roles and Permissions
- As a Guest, I can browse products but cannot make purchases or leave reviews.
- As a Customer, I can access all customer features such as purchasing products, adding reviews, and managing my orders.
- As an Admin, I have full access to the system, including user management, product management, order management, and analytics.

## 2.1 Product Management

### 2.1 Product Listing
- As a Customer or Guest, I can view a list of products with images, names, prices, descriptions, and sizes (S, M, L, XL).
- As a Customer or Guest, I can filter products by category, subcategory/brand, size, color, and price range.
- As an Admin, I can add, edit, or remove products, including updating images, prices, descriptions, and inventory.

### 2.2 Product Categories
- As a Customer or Guest, I can browse products by categories (e.g., sweatshirts, t-shirts, new arrivals, sales).
- As an Admin, I can create and manage categories and subcategories/brands for better organization of products.

### 2.3 Product Details
- As a Customer or Guest, I can click on a product to view its details on a product page, including a larger image, detailed description, price, available sizes, and colors.
- As an Admin, I can update product details (e.g., price, stock status, product information).

### 2.4 Inventory Management
- As an Admin, I can track inventory levels for each product.
- As an Admin, I can mark products as "out-of-stock" when inventory runs out and notify customers if stock is replenished.

## 2.2 Shopping Cart & Checkout

### 2.1 Cart Management
- As a Customer, I can add products to the cart from the product listing or product detail page.
- As a Customer, I can remove items or update quantities in my cart.
- As a Customer, I can view a cart summary with total price, item count, and an option to proceed to checkout.

### 2.2 Checkout Process
- As a Customer, I can proceed to checkout, where I provide shipping and billing information.
- As a Customer, I can review my order details before completing the purchase.
- As an Admin, I can view and manage all customer carts, including abandoned carts.

### 2.3 Payment Gateway Integration
- As a Customer, I can pay using various payment methods (e.g., credit cards, PayPal, Stripe).
- As a Customer, I receive an order confirmation once the payment is processed.
- As an Admin, I can manage payment methods and view completed transactions.

### 2.4 Order Confirmation
- As a Customer, I receive an email confirmation after completing an order.
- As a Customer, I can see my order summary on the screen after checkout.

## 2.3 Order Management

### 2.1 Order History
- As a Customer, I can view a history of my orders, including order date, items purchased, total amount, and status (Processing, Shipped, Delivered).
- As an Admin, I can view all customer orders and update the status as orders are processed.

### 2.2 Admin Order Dashboard
- As an Admin, I can view and manage all orders, including updating statuses (Processing, Shipped, Delivered).
- As an Admin, I can print invoices for completed orders.

## 2.4 Shipping

### 2.1 Shipping Calculation
- As a Customer, I can see shipping costs calculated based on my location and the size of the order during checkout.
- As an Admin, I can set shipping rates based on location, weight, and order size.

### 2.2 Multiple Shipping Options
- As a Customer, I can select from different shipping options (e.g., standard, express shipping) during checkout.
- As an Admin, I can manage available shipping methods and update shipping policies.

## 2.5 Promotions & Discounts

### 2.1 Discount Codes
- As a Customer, I can apply a discount code during checkout and see the discount reflected in the order total.
- As an Admin, I can create, manage, and disable discount codes, setting specific rules (e.g., percentage off, minimum order value).

### 2.2 Sales and Promotions
- As a Customer or Guest, I can view ongoing sales and promotions on the website, such as buy-one-get-one-free offers or percentage discounts.
- As an Admin, I can manage promotions and set start/end dates for sales.

## 2.6 Reviews & Ratings

### 2.1 Product Reviews
- As a Customer, I can leave a review and rating for products I have purchased.
- As a Customer or Guest, I can view reviews and ratings left by other users on product pages.
- As an Admin, I can moderate reviews, approving or deleting inappropriate content.

## 2.7 Wishlist

### 2.1 Wishlist Management
- As a Registered Customer, I can add products to a wishlist for future reference.
- As a Registered Customer, I can view and remove items from my wishlist.
- As a Guest, I cannot use the wishlist functionality unless I register.

## 2.8 Search & Filtering

### 2.1 Product Search
- As a Customer or Guest, I can use the search bar to find products by name, brand, category, or keyword, with autocomplete suggestions.
- As an Admin, I can manage search terms and product tagging to ensure products are discoverable.

### 2.2 Filtering
- As a Customer or Guest, I can filter products by various attributes (category, subcategory/brand, size, color, price range) to find exactly what I’m looking for.
- As an Admin, I can set up and manage filters.

## 2.9 Reporting & Analytics

### 2.1 Sales Reports
- As an Admin, I can view daily, weekly, and monthly sales reports, with insights into revenue trends, best-selling products, and order volume.

### 2.2 Customer Analytics
- As an Admin, I can access analytics about customer behavior, such as most viewed products, average cart value, and cart abandonment rates.


## UML Diagrams for Pixels-Store
- [View PDF](pixels-store.drawio (5).pdf)


