P_0.0.2
# NTAN E-Commerce Platform 🛍️

A modern, feature-rich e-commerce platform built with React, Node.js, and MongoDB. NTAN stands out from traditional e-commerce platforms with its unique multi-vendor architecture, advanced product variant management, and innovative company owner system.

## 🚀 Unique Features That Set NTAN Apart

### 1. **Advanced Multi-Vendor Architecture**
- **Dual Admin System**: Regular sellers (`isCompany: true`) and Company Owners (`isAdmin: true, isCompany: true`)
- **Hardcoded Company Owner Access**: Special bypass authentication for company-level operations
- **Seller Transaction Management**: Automatic revenue splitting with configurable platform charges
- **Independent Seller Dashboards**: Each seller manages their own products, orders, and analytics

### 2. **Intelligent Product Variant Management**
- **Dynamic Variant Types**: Support for size, weight, screen size, and custom variants
- **Smart Image Synchronization**: Images automatically sync with color/variant selections
- **Matrix-Based Image Organization**: Systematic image arrangement for variant combinations
- **Variant-Specific Inventory**: Independent stock management for each variant

### 3. **Amazon/Flipkart-Style Product Display**
- **Sticky Product Images**: Fixed image gallery while product details scroll
- **Smart Image Preview**: Always-visible thumbnails even for single images
- **Intelligent Image Detection**: Click on any image to auto-select corresponding variant
- **Visual Section Separation**: Clear dividers between image and product info sections

### 4. **Advanced Authentication & Authorization**
- **Multi-Layer Auth System**: JWT tokens with refresh token support
- **Company Owner Bypass**: Special authentication bypass for administrative operations
- **Phone Number Verification**: SMS OTP integration for user registration
- **Session Management**: Persistent sessions with automatic cleanup

### 5. **Sophisticated Payment Integration**
- **PhonePe Integration**: Support for India's leading payment gateway
- **Demo Payment Mode**: Development-friendly payment simulation
- **Transaction Tracking**: Comprehensive payment history and status tracking
- **Revenue Analytics**: Detailed financial reporting for sellers

### 6. **Enhanced User Experience**
- **Real-time Cart Management**: Persistent cart across sessions
- **Wishlist Functionality**: Save products for later with heart icon
- **Advanced Search**: Multi-field search with category filtering
- **Product Reviews & Ratings**: 5-star rating system with detailed reviews
- **Order Tracking**: Real-time order status updates

## 🏗️ Architecture Overview

```
NTAN E-Commerce Platform
├── Frontend (React + Vite)
│   ├── User Interface
│   ├── Admin Dashboards
│   ├── Company Management
│   └── Authentication
├── Backend (Node.js + Express)
│   ├── Authentication System
│   ├── Product Management
│   ├── Order Processing
│   ├── Payment Integration
│   └── User Management
├── Database (MongoDB)
│   ├── Users & Authentication
│   ├── Products & Variants
│   ├── Orders & Transactions
│   └── Reviews & Analytics
└── External Services
    ├── PhonePe Payment Gateway
    ├── SMS OTP Service
    └── Email Notifications
```

## 🛠️ Technology Stack

### Frontend
- **React 18** - Modern UI library with hooks
- **Vite** - Lightning-fast build tool
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing
- **Lucide React** - Beautiful icon library
- **Sonner** - Toast notifications

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - JSON Web Tokens for authentication
- **bcryptjs** - Password hashing
- **Multer** - File upload handling

### Payment & Communication
- **PhonePe SDK** - Payment processing
- **SMS Gateway** - OTP verification
- **Email Service** - Order confirmations

## 🎯 Core Functionalities

### User Management
- **Registration**: Phone number verification with OTP
- **Authentication**: JWT-based secure login
- **Profile Management**: Complete user profile with preferences
- **Role-Based Access**: Customer, Seller, Admin, Company Owner roles

### Product Management
- **Multi-Variant Products**: Colors, sizes, weights, custom variants
- **Bulk Image Upload**: Support for multiple product images
- **Inventory Tracking**: Real-time stock management
- **Category Organization**: Hierarchical product categorization
- **SEO Optimization**: Product URLs and meta descriptions

### Order Processing
- **Shopping Cart**: Persistent cart with variant selection
- **Checkout Process**: Multi-step checkout with address management
- **Payment Options**: PhonePe integration with fallback options
- **Order Tracking**: Real-time status updates from order to delivery
- **Invoice Generation**: Automatic invoice creation and email delivery

### Seller Dashboard
- **Product Management**: Add, edit, delete products
- **Order Management**: View and process orders
- **Analytics**: Sales reports and revenue tracking
- **Transaction History**: Detailed financial records
- **Performance Metrics**: Sales analytics and insights

### Company Management
- **Multi-Seller Platform**: Onboard and manage multiple sellers
- **Revenue Sharing**: Configurable platform commission rates
- **Admin Requests**: Approve/reject seller applications
- **Platform Analytics**: Overall platform performance metrics
- **Financial Oversight**: Transaction monitoring and reporting

## 🎨 Frontend Components

### Page Components
- **Home**: Hero section, featured products, categories
- **ProductDetail**: Amazon-style product view with variants
- **Cart**: Shopping cart with quantity management
- **Checkout**: Multi-step checkout process
- **Login/Register**: Authentication with OTP verification
- **Dashboard**: User profile and order history
- **Admin**: Product and order management
- **Company**: Platform-level management interface

### Reusable Components
- **Navbar**: Navigation with cart counter
- **ProductCard**: Product display with wishlist
- **CategorySlider**: Horizontal category navigation
- **OrderTracker**: Visual order progress indicator
- **ReviewSystem**: Star ratings and comments
- **PaymentModal**: Payment method selection

## 🔒 Security Features

- **JWT Authentication**: Secure token-based authentication
- **Password Hashing**: bcrypt password encryption
- **Input Validation**: Server-side request validation
- **SQL Injection Protection**: MongoDB query sanitization
- **Rate Limiting**: API request throttling
- **CORS Configuration**: Cross-origin request handling
- **Environment Variables**: Sensitive data protection

## 📊 Performance Optimizations

- **Code Splitting**: Lazy loading of routes and components
- **Image Optimization**: WebP format with fallbacks
- **Database Indexing**: Optimized MongoDB queries
- **Caching**: Redis integration for session management
- **CDN Integration**: Static asset delivery optimization
- **Bundle Analysis**: Webpack bundle size optimization

## 📈 Monitoring & Analytics

- **Error Tracking**: Sentry integration for error monitoring
- **Performance Monitoring**: Real user monitoring (RUM)
- **Analytics**: Google Analytics integration
- **User Behavior**: Heatmap and session recording
- **API Monitoring**: Endpoint performance tracking

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- 📧 Email: himanshu151281@gmail.com
- 📱 Phone: +91-90395-75665

## Acknowledgments

- React team for the amazing framework
- MongoDB team for the flexible database
- PhonePe for payment gateway integration
- Open source community for various packages used

---

**Built with ❤️ by the Himanshu Kumar**

*Revolutionizing e-commerce with innovative multi-vendor solutions*
