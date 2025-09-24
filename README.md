# React Card Component Example

This repository is a simple React demo project that showcases how to build reusable components with **React Hooks** (`useState`, `useEffect`) and props.

---

## 🔑 Key Takeaways
- **React Functional Components** – using function components with props.  
- **React Hooks** – demonstrates `useState` and `useEffect` for managing state and side effects.  
- **State Management**
  - `count`: increments every time the card is clicked.  
  - `hasLiked`: toggles between liked ❤️ and unliked 🩶 states.  
- **Side Effects with `useEffect`** – logs to the console whenever the `hasLiked` state changes.  
- **Reusability with Props** – each `<Card />` receives its own `title` (and could accept other props like `rating` or `isCool`).  

---

## 🚀 Features
- Click on a card to increase its count.  
- Toggle a like button (❤️ / 🩶).  
- Multiple `Card` components rendered inside a container.  

---

## 🛠️ Installation & Setup
Clone the repository and run the project locally.

```bash
# Clone the repository
git clone https://github.com/your-username/my-first-react-app.git

# Navigate to the project
cd my-first-react-app

# Install dependencies
npm install

# Run the development server
npm run dev

📸 Preview

When running the project, you’ll see multiple cards (e.g., Star Wars, Avatar, The Lion King) with clickable like buttons and a click counter.

💡 Learning Purpose

This project is ideal for beginners learning:

- How to pass props in React
- How to manage state and side effects
- How to build reusable and interactive components
