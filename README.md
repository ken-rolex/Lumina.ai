# Lumina - AI Chat Interface ✨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Built with Next.js](https://img.shields.io/badge/Built%20with-Next.js-blueviolet)](https://nextjs.org/)
[![Styled with Tailwind CSS](https://img.shields.io/badge/Styled%20with-Tailwind%20CSS-blue)](https://tailwindcss.com/)
[![UI Components by shadcn/ui](https://img.shields.io/badge/UI%20Components-shadcn%2Fui-orange)](https://ui.shadcn.com/)
[![Authentication by Clerk](https://img.shields.io/badge/Authentication-Clerk-lightgreen)](https://clerk.com/)

Lumina is a modern, responsive AI chat interface built with Next.js and TypeScript, designed to provide a seamless and engaging user experience.
 
## Features 🚀

*   **Next.js 13+ (App Router):** Leverages the latest features of Next.js for optimal performance and routing.
*   **TypeScript:** Ensures type safety and maintainability with TypeScript.
*   **Tailwind CSS:** Provides a utility-first CSS framework for rapid and consistent styling.
*   **Clerk Authentication:** Secure and easy-to-integrate authentication with Clerk.
*   **File Attachments:** Supports file uploads for enhanced communication.
*   **Dark/Light Mode:** Offers a customizable user experience with a dark/light mode toggle.
*   **Real-time Chat:** Delivers a fluid and responsive real-time chat experience.
*   **Modern UI Components:** Utilizes `shadcn/ui` for a beautiful and accessible user interface.
*   **Responsive Layout:** Adapts seamlessly to different screen sizes and devices.

## Getting Started 🛠️

Follow these steps to get Lumina up and running on your local machine.

### Prerequisites

*   [Node.js](https://nodejs.org/) 18.0 or later
*   [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/ken-rolex/Lumina.ai.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd lumina
    ```

3.  **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

4.  **Configure Environment Variables:**

    Create a `.env.local` file in the root directory and add your Clerk API keys:

    ```
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
    CLERK_SECRET_KEY=your_secret_key
    ```

    *   **Note:**  Replace `your_publishable_key` and `your_secret_key` with your actual Clerk API keys.  You can obtain these from your [Clerk dashboard](https://clerk.com/).

5.  **Run the development server:**

    ```bash
    npm run dev
    # or
    yarn dev
    ```

6.  **Open in your browser:**

    Open [http://localhost:3000](http://localhost:3000) with your browser to see Lumina in action!

## Project Structure 📂




lumina/
├── app/
│   ├── api/
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── ui/
│   ├── nav-bar.tsx
│   └── thread.tsx
├── public/
└── styles/


## Key Components 🧩

  **`app/`:** Contains the core routing and layout of the application, powered by Next.js's App Router.
*   **`components/ui/`:** Houses the modern UI components from `shadcn/ui`, providing a consistent and visually appealing design.
*   **`components/nav-bar.tsx`:** Implements the navigation bar, allowing users to navigate the application.
*   **`components/thread.tsx`:** Renders the chat thread, displaying messages and handling user input.

## Contributing 🤝

We welcome contributions to Lumina!  Here's how you can contribute:

1.  **Fork the repository:** Click the "Fork" button at the top right of the GitHub page.
2.  **Create your feature branch:**

    ```bash
    git checkout -b feature/amazing-feature
    ```

3.  **Commit your changes:**

    ```bash
    git commit -m 'Add some amazing feature'
    ```

4.  **Push to the branch:**

    ```bash
    git push origin feature/amazing-feature
    ```

5.  **Open a Pull Request:**  Submit a pull request from your feature branch to the `main` branch of the original repository.  Please provide a clear and concise description of your changes.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

*   Built using [Next.js](https://nextjs.org/)
*   Styled with [Tailwind CSS](https://tailwindcss.com/)
*   UI components from [shadcn/ui](https://ui.shadcn.com/)
*   Authentication by [Clerk](https://clerk.com/)

---

Made with ❤️ by Rajan Jha
