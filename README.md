
# Empowering Abilities: Sport and Health for All

## 🌟 Features
- Responsive Home Page with mission statement
- Interactive Blog with category filtering
- Events calendar with registration
- Services overview with animated cards
- About page with team profiles
- Accessible navigation
- Mobile-first design

## 💻 Tech Stack
- **Frontend**: React 18 + Vite
- **Styling**: styled-components@6
- **Routing**: react-router-dom@6
- **Animations**: framer-motion@10
- **Build Tool**: Vite@5

## 🛠️ Installation

### Prerequisites
- Node.js ≥16.14.0
- npm ≥8.3.0

1. **Clone repository**
```bash
git clone https://github.com/your-username/abnormal-people-frontend.git
cd abnormal-people-frontend
```

## Install Dependencies  
This will install all required packages, including:  

- `styled-components`  
- `react-router-dom`  
- `framer-motion`  

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

## Build for Production

```bash
npm run build
```

## 🔧 Key Dependencies  

```json
{
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "styled-components": "^6.1.8",
    "framer-motion": "^10.16.0",
    "react-router-dom": "^6.22.3"
  }
}
```
## 🎨 Styling with Styled-Components  

This project uses `styled-components` for CSS-in-JS styling. Example component:  

```jsx
import styled from 'styled-components';

const Button = styled.button`
  background: #3498db;
  color: white;
  padding: 1rem 2rem;
  border-radius: 4px;
  border: none;
  cursor: pointer;

  &:hover {
    background: #2980b9;
  }
`;

// Usage
<Button>Click Me</Button>
```
## Project Structure
```
abnormal-people-frontend/ 
├── public/ # Static assets (not committed) 
├── src/ 
│ ├── components/ # Reusable components 
│ │ ├── Navbar.jsx # Navigation component 
│ │ └── ... 
│ ├── pages/ # Page components 
│ │ ├── Home.jsx # Landing page 
│ │ ├── Blog.jsx # Blog page 
│ │ └── ... 
│ ├── App.jsx # Root component 
│ └── main.jsx # Entry point 
├── .gitignore 
├── package.json 
└── vite.config.js
```

## 📁 Public Folder Setup

The `public` folder containing large assets is not included in this repository to keep the repository size manageable. 

### How to Install Public Files:

1. **Download the public folder**  
   Get the public folder here:  
   [Download public.zip](https://www.mediafire.com/file/u0xyerw0hkvoo8i/public.zip/file)

2. **Extract the files**  
   Unzip the downloaded archive:
   ```bash
   unzip public.zip
   ```
  3.  ####  Place in Project Root 
  Move the extracted `public` folder to your project root directory:  
   ```bash
love-abnormal-frontend/ 
├── public/ <-- Place extracted folder here 
├── src/ 
├── package.json 
└── ...
   ```
 
 4.  ####  Verify Structure
Ensure the folder contains these key subdirectories:

   ```bash
public/
├── images/
│   ├── blog/
│   ├── events/
│   └── team/
└── documents
   ```
  
 ## ⚠️ Important Notes  

- The application expects these files at runtime
- Image paths in components already reference these locations.  



## 🖥️ Development Workflow  

### Create a New Styled Component  
```bash
touch src/components/NewComponent.jsx
```
### Add PropTypes (if needed)
```bash
npm install prop-types
```
### Run Linter
```bash
npm run lint
```
## 📜 License  
Proprietary

