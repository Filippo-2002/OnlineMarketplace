Digital Marketplace

A Modern Fullstack E-Commerce Marketplace for digital products, built with cutting-edge technologies to deliver a seamless and scalable user experience.

🚀 Features

- Next.js 14 App Router for optimized routing and server-side rendering
- tRPC for type-safe API communication
- TypeScript for enhanced code quality and maintainability
- Payload CMS for flexible content management
- Tailwind CSS for rapid and responsive UI development
- Secure Payment Integration with Stripe
- Email Notifications using Resend API

🛠 Technologies Used

Next.js 14
tRPC
TypeScript
Payload CMS
Tailwind CSS
Stripe
Resend

📋 Installation

1. Clone the Repository

git clone https://github.com/Filippo-2002/OnlineMarketplace.git
cd digital-marketplace

2. Install Dependencies

npm install
yarn install

3. Configure Environment Variables

Create a .env file in the root directory and add the following variables:

# Server Configuration

NEXT_PUBLIC_SERVER_URL=http://localhost:3000

# Payload CMS - Any value works here, should be somewhat secure

PAYLOAD_SECRET=your_payload_secret

# Database - choose either MongoDB or PostgreSQL

MONGODB_URL=your_mongodb_connection_string

# OR

POSTGRES_URL=your_postgres_connection_string

# Payments - Stripe Configuration

STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret

# Email - Resend API Key

RESEND_API_KEY=your_resend_api_key

4. Set Up the Database

MongoDB: If using MongoDB, ensure your MONGODB_URL is correctly set in the .env file.
PostgreSQL: If using PostgreSQL, set the POSTGRES_URL accordingly.

5. Run the Development Server

npm run dev
yarn run dev

🧩 Usage

Admin Panel: Access the Payload CMS admin panel to manage digital products and content.
User Registration: Users can sign up, browse digital products, and make purchases securely.
Payment Processing: Integrated with Stripe for handling payments and webhooks for real-time updates.
Email Notifications: Automated emails sent via Resend for order confirmations and other notifications.

Happy Coding! 🎉
