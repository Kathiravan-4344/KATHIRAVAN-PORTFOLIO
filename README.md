# KATHIRAVAN V — Personal Developer Portfolio

A modern, high-performance developer portfolio website designed for **KATHIRAVAN V**, an aspiring Frontend Developer seeking junior frontend engineering roles and freelance clients.

Built with semantic **HTML5**, **CSS3**, and **Vanilla JavaScript** (zero heavy frameworks, zero runtime bloat).

---

## 📁 Project Structure

```text
KATHIRAVAN-PORTFILIO/
├── index.html       # Main semantic HTML structure, SEO tags, accessible landmarks
├── style.css        # Pure CSS design system: dark-mode palette, glow effects, responsive breakpoints
├── script.js        # Vanilla JS: mobile navigation, scroll-reveal, back-to-top, toast feedback, modal
├── serve.js         # Zero-dependency local development server (Node.js)
└── README.md        # Documentation, customization guide & deployment instructions
```

---

## 🎨 Design System & Color Palette

- **Main Background**: `#080D18`
- **Secondary Background**: `#0D1423`
- **Cards Background**: `#101A2B` (Hover: `#142238`)
- **Primary Blue**: `#4D8DFF`
- **Bright Blue**: `#6EABFF`
- **Main Text**: `#F2F6FF`
- **Secondary Text**: `#9AA8BD`
- **Borders**: `rgba(77, 141, 255, 0.15)`
- **Typography**: 
  - Headings: **Space Grotesk** (Google Fonts)
  - Body: **DM Sans** (Google Fonts)
  - Code/Monospace: **SFMono / Consolas / Menlo**

---

## 🚀 How to Run Locally

You have several easy options to preview and run your portfolio:

### Option 1: Using the Included Node.js Server (Recommended)
Open your terminal in the portfolio folder and run:
```bash
node serve.js
```
Then visit: `http://localhost:4173/` in your browser.

### Option 2: Using VS Code Live Server
1. Open the project folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and click **"Open with Live Server"**.

### Option 3: Direct Browser File
Simply double-click `index.html` to open it in Google Chrome, Microsoft Edge, Brave, or Firefox.

---

## ✏️ Personal Details to Replace

Search for `USER NOTE:` in `index.html` and `script.js` to easily customize your personal links:

1. **Email Address**:
   - In `index.html` (Lines around Contact Section):
     - Replace `kathiravan.developer@example.com` in the `mailto:` link with your real email address.
     - Replace `kathiravan.developer@example.com` in the `data-email` attribute of `#copyEmailBtn`.
   - In `script.js`:
     - Update fallback email string inside the clipboard copy handler.

2. **LinkedIn URL**:
   - In `index.html`:
     - Replace `https://www.linkedin.com/in/kathiravan-v` with your actual LinkedIn profile URL (in the mobile drawer, hero section, and contact section).

3. **Resume / CV (Optional)**:
   - If you want to add a "Download Resume" button, you can place your `resume.pdf` in the root folder and add an `<a href="resume.pdf" download class="btn btn-secondary">Download Resume</a>` in the hero section.

---

## 🌐 How to Upload to GitHub and Deploy on Vercel

### Step 1: Initialize Git and Push to GitHub
If you haven't initialized Git yet:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: Kathiravan V. portfolio website"

# Link to your GitHub repository (create a new repo named 'portfolio' on GitHub first)
git remote add origin https://github.com/Kathiravan-4344/portfolio.git

# Push your code
git branch -M main
git push -u origin main
```

### Step 2: Deploy to Vercel (100% Free)
1. Go to [vercel.com](https://vercel.com/) and sign in with your GitHub account (`Kathiravan-4344`).
2. Click **"Add New..."** → **"Project"**.
3. Select your `portfolio` repository from the list.
4. Framework Preset: **Other** (Static HTML).
5. Root Directory: `./` (Leave as default).
6. Click **"Deploy"**.
7. In ~15 seconds, Vercel will give you a live production URL (e.g., `https://kathiravan-portfolio.vercel.app`) with free SSL, automatic global CDN, and automatic redeployment every time you `git push`!
