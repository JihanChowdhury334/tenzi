# 🎲 Tenzi Game (React Learning Project)

A simple implementation of the classic dice game **Tenzies**, built with React as a learning project.  
This repo documents my progress in mastering **React fundamentals**, state management, and accessibility practices.

---

## 🚀 Features & Functionality
- 🎲 **Randomized Dice Rolls**: Generates 10 dice using `Math.random()` and updates values dynamically.
- 📌 **Hold Dice**: Click on a die to "hold" it using `useState`, preserving its value between rolls.
- 🏆 **Win Condition**: Detects when all dice are held and equal in value (`Array.every()`).
- 🎉 **Confetti Celebration**: Uses `react-confetti` to celebrate a win.
- 🔄 **New Game Reset**: Resets the game state when the win condition is met.
- 🖱 **Keyboard Focus Management**: `useRef` automatically focuses the roll button when the game is won.
- ♿ **Accessibility Features**: Screen reader messages via `aria-live` regions and semantic labels on dice.
- 🎨 **Responsive UI**: Styled with CSS Grid for dice layout and modern design practices.

---

## 🧠 What I Practiced & Learned
- **React Hooks**:
  - `useState` for managing dice state (values, held status).
  - `useEffect` for win detection and side effects (auto-focus).
  - `useRef` for DOM element manipulation (button focus).
- **Component Design**:
  - Created a reusable `Die` component with dynamic props.
  - Prop drilling and event handling (`onClick`).
- **Array Methods**:
  - `map` to render dice.
  - `every` to check win conditions.
- **Unique Keys**:
  - `nanoid` for generating unique keys in mapped components.
- **Styling & Layout**:
  - CSS Grid and Flexbox for responsive dice layout.
  - Conditional inline styles for held dice (`backgroundColor`).
- **Accessibility**:
  - `aria-pressed`, `aria-label` for buttons.
  - Hidden live region for screen readers to announce game state.
- **Tooling**:
  - Built with **Vite** and **React 18** for fast development.
  - Practiced project structure with modular components.

---

## 📸 Screenshot
![Screenshot of Tenzies Game](./235734b8-a646-4a48-b186-723326e3c357.png)

---

## 🛠️ Installation & Setup
```bash
# Clone the repository
git clone https://github.com/JihanChowdhury334/tenzi.git
cd tenzi

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## 🎯 Purpose
This project is **not for production**, but a **learning exercise** to reinforce:
- React fundamentals (state, effects, refs).
- Component-based architecture.
- Accessibility-first development.
- Styling with CSS Grid & Flexbox.

---

## 📚 References
- [React Docs](https://react.dev)
- [Vite Docs](https://vitejs.dev)
- [Scrimba React Course](https://scrimba.com/learn-react)
