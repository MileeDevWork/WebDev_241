
WEBDEV_241/
├── public/
│   ├── index.php            # File khởi động chính của ứng dụng
│   └── assets/              # Thư mục chứa các tài nguyên tĩnh dùng chung
│       ├── css/
│       ├── js/
│       └── images/
├── src/ 
│   ├── controllers/         # Chứa các controller xử lý logic ứng dụng
│   │   ├── Customer/
│   │   └── Admin/
│   ├── models/              # Chứa các model để tương tác với cơ sở dữ liệu
│   │   ├── Customer/
│   │   └── Admin/
│   ├──views/                # Chứa các view cho từng phần của ứng dụng
│   │   ├── Customer/
│   │   ├── Admin/
│   │   └── Layout/
│   └── routes.php           # File quản lý các URL của ứng dụng
├── config/ 
│   └── config.php           # File cấu hình cơ sở dữ liệu và cài đặt chung
├── database/                # Thư mục chứa các file SQL tạo bảng và seed dữ liệu
├── .env                     # File chứa thông tin bảo mật (như mật khẩu cơ sở dữ liệu)
└── vendor
```
# E-commerce Website Development Project

This is a personal web development project created to demonstrate the use of front-end and back-end technologies. The project features a fully functional e-commerce website with the front-end built using plain HTML and styled with Tailwind CSS, and the back-end developed using PHP.

## Project Overview

This project is designed to showcase basic e-commerce functionality, including product listing, user authentication, and shopping cart features. The front-end provides a user-friendly interface while the back-end ensures dynamic content management and server-side processing.

> ⚠️ **Disclaimer**: Product images and branding materials used in this project are taken from the official Ananas Vietnam website and are used solely for educational and non-commercial purposes. This project is not affiliated with or endorsed by Ananas.

## Technologies Used

- **Frontend**:
  - HTML (Plain HTML for structure)
  - Tailwind CSS (Utility-first CSS framework for styling)

- **Backend**:
  - PHP (For dynamic content rendering and server-side processing)

## Features

- **Responsive Design**: Fully responsive layout optimized for mobile and desktop views.
- **User Authentication**: Users can register, log in, and access their profiles.
- **Product Catalog**: Display products with details such as price, description, and images.
- **Shopping Cart**: Users can add products to their shopping cart and proceed to checkout.
- **Backend Integration**: PHP handles form submissions, user authentication, and dynamic page content.

## Installation

### Prerequisites

To run this project locally, you need:

- A PHP server (e.g., XAMPP, WAMP, LAMP, or any server with PHP installed)
- A text editor (e.g., Visual Studio Code, Sublime Text)

### Steps to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MileeDevWork/WebDev_241.git
