# ⚡ Modern Developer Portfolio

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

A high-performance, responsive, and minimalist developer portfolio template built with **Next.js**, **React**, and **Tailwind CSS**. Designed to showcase advanced backend and AI engineering projects with a professional "Deep Tech" aesthetic.

## 🚀 Features

* **Modern UI/UX:** Dark mode aesthetic with glassmorphism effects and slate color palette.
* **Fully Responsive:** Optimized for mobile, tablet, and desktop screens.
* **Data-Driven:** All content (Profile, Projects, Bio) is managed via a simple configuration object—no need to dig through HTML structure to update text.
* **Performance:** Built on Next.js for fast loading and SEO optimization.
* **Icons:** Integrated with `lucide-react` for lightweight, crisp iconography.

## 🛠️ Tech Stack

* **Framework:** [Next.js](https://nextjs.org/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Deployment:** Vercel (Recommended)

## 📦 Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/portfolio.git](https://github.com/yourusername/portfolio.git)
    cd portfolio
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Run the development server**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

4.  Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## ⚙️ Customization

To personalize this portfolio, open the main page file (usually `app/page.tsx` or `pages/index.js`):

1.  **Update Profile Info:** Locate the `portfolioData` object to change your name, role, bio, and social links.
2.  **Update Projects:** Edit the `projects` array.
    * Replace the `image` paths with your own screenshots (place images in the `public/` folder).
    * Update `tech` tags to match your specific stack (e.g., Python, Docker, AWS).

## 🚢 Deployment

The easiest way to deploy this Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

1.  Push your code to a GitHub repository.
2.  Go to Vercel and sign up/login.
3.  Click **"Add New Project"** and import your repository.
4.  Click **Deploy**.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
