# Imaginify - AI SaaS Platform

Imaginify is a cutting-edge AI SaaS platform built with Next.js 14 that offers advanced image processing capabilities. Users can restore old images, perform generative fill, remove objects, recolor objects, and remove backgrounds using AI. It features a robust credit system for usage limits, secure authentication, and seamless payments.

## 🚀 Features

- **Authentication & Authorization**: Secure user login and registration powered by Clerk.
- **Image Restoration**: Refine images by removing noise and imperfections.
- **Generative Fill**: Enhance image dimensions using AI outpainting.
- **Object Removal**: Identify and eliminate unwanted objects from images seamlessly.
- **Object Recolor**: Easily identify and recolor specific objects within an image.
- **Background Removal**: Extract subjects from their background with high precision using AI.
- **Credit System**: Users can purchase credits to use AI features via Stripe integration (Free, Pro, and Premium plans available).
- **User Profile**: Track usage, manage credits, and view past transformations.
- **Modern UI/UX**: Built with Tailwind CSS and Shadcn UI for a responsive, accessible, and beautiful interface.

## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Database**: [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)
- **Image Processing & AI**: [Cloudinary](https://cloudinary.com/)
- **Payments**: [Stripe](https://stripe.com/)
- **Forms**: [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)

## ⚙️ Getting Started

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   cd ai_saas_app-main
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the required environment variables as seen in `.env.local` or `.env.example`:
   ```env
   # Clerk
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
   WEBHOOK_SECRET=

   # MongoDB
   MONGODB_URL=

   # Cloudinary
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=

   # Stripe
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
   STRIPE_SECRET_KEY=
   STRIPE_WEBHOOK_SECRET=
   
   NEXT_PUBLIC_SERVER_URL=http://localhost:3000
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open-source and available under the MIT License.
