# 🗺️ One District One Product

![One District One Product](A_README_image_for_the_One_District,_One_Product_w.png)

## 📌 Project Description

**One District One Product** (ODOP) is a web application developed using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). The platform aims to promote **district-level specialization** in India by allowing users to explore unique products from each district across all Indian states and union territories.

The app supports **interactive map-based navigation**, where users can select a state and then a district to view locally produced or specialized items, with the vision to support local artisans, businesses, and industries.

---

## 🚀 Features

- 🗺️ **Map-Based Selection:** Choose any state from the map of India and drill down to districts.
- 📍 **District-Level Information:** Display of unique or popular products from each district.
- 🧩 **Product Listings:** Browse products with images and details.
- 🔎 **Search Functionality:** Find districts or products easily.
- 🌐 **Responsive Design:** Works on desktops, tablets, and mobile devices.

---

## 🛠️ Tech Stack

| Technology | Description                  |
|------------|------------------------------|
| **MongoDB**    | NoSQL database for storing product info |
| **Express.js** | Backend framework with Node.js |
| **React.js**   | Frontend library for UI    |
| **Node.js**    | Backend runtime environment |
| **CSS**        | Styling and layout        |
| **JavaScript** | Application logic         |

---

## 🧭 How It Works

1. **Landing Page** shows a map of India.
2. Click on any **state**, and then select a **district**.
3. The system displays the **district's unique product(s)**.
4. Explore details like **product description, image, and cultural relevance**.

---

## 📁 Folder Structure

```bash
One-District-One-Product/
│
├── client/              # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── assets/
│       └── App.js
│
├── server/              # Express backend
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── .gitignore
├── package.json
└── README.md

📸 Screenshots
![odop](https://github.com/user-attachments/assets/16779fba-b5a8-46ce-ace1-520b2c91c578)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
