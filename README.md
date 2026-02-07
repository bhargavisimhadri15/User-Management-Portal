# User Management Portal (Extensible React CRUD)

A modern, responsive React application built to manage user data with a focus on **Schema-Driven UI** and **Extensibility**.

## 🚀 Live Demo

**Link:** [Insert your Vercel/Netlify URL here]

## ✨ Key Features

* **Full CRUD Functionality:** Create, Read, Update, and Delete user records seamlessly.
* **Schema-Driven Architecture:** The entire UI (forms and tables) is generated from a central configuration file.
* **Global Search:** A high-performance search filter that scans all user fields dynamically.
* **Theme Engine:** Integrated Dark Mode toggle using CSS Variables.
* **Responsive Design:** Optimized for Desktop, Tablet, and Mobile views.

## 🛠️ Built With

* **React 18** (Functional Components & Hooks)
* **Vite** (Build Tool)
* **CSS3** (Flexbox, Grid, & Variables)
* **Lucide-React** (for Icons - optional)

## 🏗️ Technical Architecture & Extensibility

The core requirement of this project was to ensure that adding new fields requires minimal code changes. I achieved this using a **Metadata-Driven Approach**:

### How it works:

1. **Centralized Schema:** All user attributes are defined in `src/userSchema.js`.
2. **Dynamic Form Factory:** Instead of hard-coding inputs, the `UserForm` component maps through the schema and renders the appropriate field type (text, email, select, etc.).
3. **Agnostic Logic:** The Search and Update functions iterate through object keys rather than specific names, meaning they automatically "inherit" any new fields added to the schema.

## ⚙️ Installation & Setup

1. **Clone the repo:**
```bash
git clone https://github.com/your-username/react-crud.git

```


2. **Install dependencies:**
```bash
npm install

```


3. **Run the development server:**
```bash
npm run dev

``
