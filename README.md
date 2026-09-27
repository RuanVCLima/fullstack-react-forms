# 📋 Event Form

A responsive event registration form built with React and TypeScript, featuring form management and schema-based validation with React Hook Form and Yup.


## 🚀 About the Project

This project is a simple event registration form developed to practice form handling and validation in React.

The application allows users to enter:

- Event name
- Event date
- Event subject
- Event description

The form provides validation feedback when required fields are not properly filled out.

## ✨ Features

- 📝 Event registration form
- 📅 Date selection
- 📚 Event subject selection
- ✅ Form validation
- ⚠️ Validation error messages
- 🎨 Dark-themed interface
- 📱 Responsive form layout
- ⚛️ React Hook Form integration
- 🔐 Yup schema validation

## 🛠️ Technologies

### Frontend

- React
- TypeScript
- Vite

### Form Management

- React Hook Form
- Yup
- `@hookform/resolvers`

### Code Quality

- ESLint
- Prettier

The project uses React 18.3.1, React Hook Form 7.53.2, Yup 1.5.0 and Vite 6.0.1. :contentReference[oaicite:0]{index=0}

## 📂 Project Structure

```text
forms/
├── public/
├── src/
│   ├── assets/
│   ├── App.css
│   ├── App.tsx
│   ├── main.tsx
│   └── vite-env.d.ts
├── .gitignore
├── .prettierignore
├── .prettierrc
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```
📝 Form Fields

The form contains four main fields:

| Field       | Type     | Validation                      |
| ----------- | -------- | ------------------------------- |
| Event name  | Text     | Required                        |
| Date        | Date     | Required                        |
| Subject     | Select   | Required                        |
| Description | Textarea | Required, minimum 10 characters |


The validation schema is implemented with Yup and connected to React Hook Form through yupResolver.

The subject selector currently provides:

React
Node.js
Javascript
Typescript

⚙️ Getting Started
Prerequisites

Make sure you have installed:

Node.js
npm
Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Navigate to the project:

```bash
cd forms
```

Install the dependencies:

```bash
npm install
```

▶️ Running the Project

Start the development server:

```bash
npm run dev
```

Vite will start the application in development mode. The project also provides build, lint, format, format:check, and preview scripts.

📦 Available Scripts

| Command                | Description                           |
| ---------------------- | ------------------------------------- |
| `npm run dev`          | Starts the development server         |
| `npm run build`        | Builds the application for production |
| `npm run lint`         | Runs ESLint                           |
| `npm run format`       | Formats the project with Prettier     |
| `npm run format:check` | Checks formatting                     |
| `npm run preview`      | Previews the production build         |


🎨 UI

The application uses a dark interface with a centered form layout. Inputs, selects and textareas share a consistent dark styling, rounded borders and white text. The submit button uses a blue accent color with a hover effect.

Custom calendar and dropdown icons are also used for the date and subject fields.

🧠 What I Practiced

This project was developed to practice:

React form handling
Controlled form fields
React Hook Form
Yup schemas
Form validation
TypeScript types
Error handling
CSS styling
Vite development workflow
ESLint and Prettier configuration
🔎 How It Works

The form is managed using useForm from React Hook Form. The Yup schema is passed through yupResolver, allowing the form to validate its data before submission.

Each form field is integrated with React Hook Form using Controller. Validation errors are displayed below their respective fields.

When the form is submitted successfully, the collected form data is currently logged to the browser console.

🚧 Future Improvements

Possible improvements for future versions:

 Connect the form to a backend API
 Persist submitted events
 Add success notifications
 Add loading states
 Improve accessibility
 Add automated tests
 Add event editing and deletion
 Add a list of registered events
 Deploy the application
👨‍💻 Author

Ruan Victor

Frontend / Full Stack Developer

GitHub: @YOUR-USERNAME
LinkedIn: LinkedIn
