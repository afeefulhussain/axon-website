# AXON — Technical Society of IMAC, UET Lahore
### Web Technologies Assignment 01: Multi-Page Website Development Using HTML & Tailwind CSS

**Course:** Web Technologies  
**Institution:** Institute of Machine Learning, Artificial Intelligence & Cyber Security (IMAC), University of Engineering and Technology (UET) Lahore  
**Assignment:** 01 - Multi-Page Website Development Using HTML & Tailwind CSS  
**Total Marks:** 30  
**Stack:** Pure HTML5 & Tailwind CSS (No JavaScript)  
**Society Motto:** *"Learn by Building, Grow by Connecting."*

---

## About AXON

**AXON** is an official student-led technical society founded in **2026** under the **Institute of Machine Learning, Artificial Intelligence & Cyber Security (IMAC)** at the **University of Engineering and Technology (UET) Lahore**.

Established to bridge regular academic study with real-world technical execution, AXON provides a collaborative platform where students transform core computational concepts into working applications, active project repositories, and industry-ready skills.

### Core Focus Areas:
1. Practical Web & Software Engineering: Responsive layout architecture, clean frontend design, and scalable development using modern web technologies.
2. Core Programming & Foundational AI: Python foundation, algorithmic thinking, and core data structures for applied machine learning and data science.
3. Departmental & Industry Engagement: Connecting students with departmental initiatives, faculty-led projects, tech companies, and software houses through workshops and speaker sessions.

---

## Project Folder Structure

```text
d:\axon\axon website\
│
├── index.html                      # 1. Home Page
│
├── pages/
│   ├── about.html                  # 2. About Us Page
│   ├── contact.html                # 3. Contact Us Page (Google Forms Integrated)
│   ├── signin.html                 # 4. Member Portal Sign In Page
│   └── signup.html                 # 5. Join Society / Registration (Google Forms Integrated)
│
├── assets/
│   ├── css/
│   │   └── style.css               # Basic custom styling (smooth scroll, Arial font)
│   ├── logo.png                    # Official AXON mechanical gear & AI neural logo
│   └── favicon.png                 # Browser tab favicon
│
└── README.md                       # Assignment documentation & submission guide
```

---

### 10+ Tailwind CSS UI Components Breakdown (Per Page)

Every single page contains at least **10 distinct Tailwind CSS UI components** clearly labeled in the HTML code:

### 1. Home Page (`index.html`)
- Component 1: **Navbar** (`<nav>` with flex, logo, active indicator, hover links)
- Component 2: **Hero Section** (Centered hero container with title and sub-heading)
- Component 3: **Primary Button** (`bg-blue-600 hover:bg-blue-700 text-white rounded-lg`)
- Component 4: **Secondary Outline Button** (`border border-gray-300 hover:bg-gray-100`)
- Component 5: **Alert / Info Banner** (`bg-amber-50 border-l-4 border-amber-500`)
- Component 6: **Stats Counter Cards** (4 responsive grid cards with bold numbers)
- Component 7: **Feature Cards Grid** (3 focus area cards with border, padding, hover effect)
- Component 8: **Testimonial / Quote Box** (Rounded card with italic quote and author credit)
- Component 9: **Pure HTML/CSS FAQ Accordion** (Using native `<details>` and `<summary>` styled with Tailwind — No JS needed!)
- Component 10: **Footer** (3-column layout with copyright)

### 2. About Us (`pages/about.html`)
- Component 1: **Navbar** (Consistent navigation)
- Component 2: **Breadcrumb Navigation** (`Home / About AXON`)
- Component 3: **Hero Header Banner**
- Component 4: **Mission & Motto Card** (`bg-blue-50 border-blue-200`)
- Component 5: **Core Focus 3-Pillars Cards** (Web, AI, Industry)
- Component 6: **Society Wings Tag Badges** (Web Wing, AI Wing, Cyber Wing, CP Wing)
- Component 7: **Student Executive Council Grid** (Avatar circle, name, designation)
- Component 8: **Milestones Timeline Cards** (Year badges + descriptions)
- Component 9: **Call to Action (CTA) Card**
- Component 10: **CTA Button**
- Component 11: **Footer**

### 3. Contact Us (`pages/contact.html`)
- Component 1: **Navbar**
- Component 2: **Breadcrumb Navigation** (`Home / Contact Us`)
- Component 3: **Contact Hero Banner**
- Component 4: **Contact Channel Cards** (General, Tech Wing, Department)
- Component 5: **Form Container Card**
- Component 6: **Styled Form Inputs** (Name, Roll No, Email, Dropdown, Textarea)
- Component 7: **Checkbox Input** (Student confirmation check)
- Component 8: **External Fullscreen Link** (Direct access to Google Forms)
- Component 9: **Campus Location Card** (Address & Google Maps link)
- Component 10: **FAQ Accordion** (`<details><summary>`)
- Component 11: **Footer**

### 4. Member Sign In (`pages/signin.html`)
- Component 1: **Navbar**
- Component 2: **Breadcrumb Navigation** (`Home / Member Sign In`)
- Component 3: **Left Info / Benefits Card**
- Component 4: **Sign In Card Container**
- Component 5: **Text & Email Input Fields**
- Component 6: **Password Input Field**
- Component 7: **Checkbox Input** ("Remember me")
- Component 8: **Primary Sign In Button**
- Component 9: **Alert / Notice Box**
- Component 10: **Register Callout Card**
- Component 11: **Footer**

### 5. Join Society (`pages/signup.html`)
- Component 1: **Navbar**
- Component 2: **Breadcrumb Navigation** (`Home / Join AXON`)
- Component 3: **Left Benefits Card**
- Component 4: **Bullet Feature List**
- Component 5: **Already Registered Box**
- Component 6: **Custom Form Container**
- Component 7: **Success Notification Banner** (Shown upon submission)
- Component 8: **Form Inputs** (Full Name, Roll No, Email, Password, WhatsApp Phone)
- Component 9: **Select Dropdown** (Current Semester)
- Component 10: **Skill Domains Checkbox Grid** (11 departmental domains)
- Component 11: **Radio Button Group** (Baseline Experience)
- Component 12: **Agreement Checkbox** (Departmental Code of Conduct)
- Component 13: **Primary Submit Button**
- Component 14: **Footer**

---

## Headless Google Form Backend Integration
Both interactive forms on the website use 100% custom Tailwind CSS interfaces connected directly to Google Form backends:

### 1. Student Registration (`pages/signup.html`)
- **Backend Form:** `https://docs.google.com/forms/d/e/1FAIpQLSenPCvSY0g_Gxleh6bG6nlFg_p8VTT6an-kSU5RLAT4O4k9MA/viewform`
- **Fields Mapped:** Full Name (`entry.194799993`), Roll Number (`entry.1509153094`), Email (`entry.1710915499`), Password (`entry.1939020738`), WhatsApp (`entry.1271692415`), Semester (`entry.920465027`), Skill Domains (`entry.1796528477`), Experience (`entry.1945902891`), Agreement (`entry.890987086`).

### 2. Contact & Inquiries (`pages/contact.html`)
- **Backend Form:** `https://docs.google.com/forms/d/e/1FAIpQLSc8TwkvgrFD_iw-TvUmLDPYdQEtlUjs5d790Ztq3obblG2-6w/viewform`
- **Fields Mapped:** Name (`entry.367302119`), Email Address (`entry.1837688206`), Subject (`entry.892232999`), Message Details (`entry.1741666240`).

### Official Society Contact:
- **Email:** `axon.uet@gmail.com`
- **Department:** Institute of Machine Learning, Artificial Intelligence & Cyber Security (IMAC), UET Lahore

---

## How to Host on GitHub Pages (For Live Link)

1. Open your terminal in this directory:
   ```bash
   git init
   git add .
   git commit -m "AXON IMAC UET Lahore Website - Assignment 01"
   ```
2. Create a new repository on GitHub named `axon-website` (Public).
3. Push your code:
   ```bash
   git remote add origin https://github.com/<your-username>/axon-website.git
   git branch -M main
   git push -u origin main
   ```
4. In your GitHub repository:
   - Go to **Settings** > **Pages**
   - Under **Branch**, select `main` and `/ (root)` and click **Save**.
   - Your live link will be ready: `https://<your-username>.github.io/axon-website/`

---

## Submission Links & Checklist
- **Live Website Link (GitHub Pages):** [https://afeefulhussain.github.io/axon-website/](https://afeefulhussain.github.io/axon-website/)
- **GitHub Repository Link:** [https://github.com/afeefulhussain/axon-website](https://github.com/afeefulhussain/axon-website)

### Assignment Requirements Checklist:
- [x] **Live Website Link** enabled via GitHub Pages
- [x] **GitHub Repository** public & structured
- [x] **VS Code Folder Structure** (`index.html`, `pages/`, `assets/`, `README.md`)
- [x] **10+ Tailwind CSS UI Components per page**
- [x] **All 5 Pages Functional**:
  - `Home` (`index.html`)
  - `About` (`pages/about.html`)
  - `Contact` (`pages/contact.html`)
  - `Sign In` (`pages/signin.html`)
  - `Sign Up` (`pages/signup.html`)
