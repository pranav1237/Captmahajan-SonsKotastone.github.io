# Capt. Mahajan & Sons KotaStone Website

## Overview

This is a modern, mobile-friendly single-page website developed for **Capt. Mahajan & Sons KotaStone**.

The website showcases products, allows customers to add products to a shopping cart, submit their details, and place an order directly through EmailJS without requiring any backend server.

---

## Features

### Hero Section

* Full-width responsive hero banner
* Business name and tagline
* Smooth scrolling "Shop Now" button

### Product Showcase

* Auto-sliding product carousel
* Product images and titles
* Add-to-cart functionality

### Shopping Cart

* Dynamic cart management
* Real-time product listing
* Customer information form

### Order Placement

* Customer Name field
* Customer Phone Number field
* Sends cart details directly to the shop owner's email
* Powered by EmailJS (Free Plan Compatible)

### WhatsApp Integration

* Floating WhatsApp button
* Direct customer contact via WhatsApp

### Responsive Design

* Mobile-first layout
* Tablet optimized
* Desktop optimized
* Modern UI with smooth interactions

---

## Shop Information

**Shop Name:** Capt. Mahajan & Sons KotaStone

**Tagline:** Complete Stone & Tile Solutions Under One Roof

**Email:** [chander151973@gmail.com](mailto:chander151973@gmail.com)

**Phone:** +91 9785843101

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* EmailJS
* Google Fonts (Poppins)

No backend server is required.

---

## Project Structure

```text
project-folder/
│
├── index.html
├── README.md
│
└── assets/
    └── product-images
```

---

## Setup Instructions

### 1. Download Files

Place the website code inside:

```text
index.html
```

### 2. Create EmailJS Account

Visit:

https://www.emailjs.com

Create a free account.

---

### 3. Create Email Service

Inside EmailJS:

* Add Email Service
* Connect your Gmail account
* Copy the Service ID

Example:

```javascript
service_xxxxxx
```

---

### 4. Create Email Template

Create a template with the following content:

```text
New Order Received

Customer Name:
{{customer_name}}

Phone Number:
{{customer_phone}}

Products Ordered:
{{order_items}}
```

Copy the Template ID.

Example:

```javascript
template_xxxxxx
```

---

### 5. Get Public Key

Go to:

Account → API Keys

Copy your Public Key.

Example:

```javascript
abcdef123456
```

---

### 6. Update Website Code

Replace:

```javascript
emailjs.init("YOUR_PUBLIC_KEY");
```

with

```javascript
emailjs.init("YOUR_ACTUAL_PUBLIC_KEY");
```

Replace:

```javascript
"YOUR_SERVICE_ID"
```

with

```javascript
"YOUR_ACTUAL_SERVICE_ID"
```

Replace:

```javascript
"YOUR_TEMPLATE_ID"
```

with

```javascript
"YOUR_ACTUAL_TEMPLATE_ID"
```

---

## How Order System Works

1. Customer visits website.
2. Customer adds products to cart.
3. Customer enters:

   * Name
   * Phone Number
4. Customer clicks **Send Order**.
5. EmailJS sends order details directly to:

```text
chander151973@gmail.com
```

6. Shop owner receives order instantly by email.

---

## WhatsApp Integration

The floating WhatsApp button is configured for:

```text
+91 9785843101
```

Link:

```text
https://wa.me/919785843101
```

Customers can directly start a WhatsApp conversation with the shop owner.

---

## Product Images Used

### Product 1

```text
https://i.ibb.co/nNJk4Zm8/1000058338-1.jpg
```

### Product 2

```text
https://i.ibb.co/NntVhpbQ/1000058351-1.jpg
```

### Hero Banner

```text
https://i.ibb.co/PZwqGCyq/3d-rendering-modern-luxury-hotel-office-reception-meeting-lounge.jpg
```

---

## Browser Support

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari
* Opera
* Mobile Browsers

---

## Future Enhancements

* Product quantity selector
* Product pricing
* Order total calculation
* Multiple product categories
* Customer order history
* Admin dashboard
* Razorpay payment integration
* Product filtering and search

---

## License

This project is created exclusively for:

**Capt. Mahajan & Sons KotaStone**

Free to modify and customize according to business requirements.
