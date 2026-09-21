# Maya Manzi — AI & Cybersecurity Portfolio

A responsive, high-performance personal portfolio website built with semantic HTML5, modern CSS3 (Custom Design System with Dark/Light Themes), and Vanilla JavaScript.

## Website Specifications

### 1. Website Title
- **Primary Title**: `Maya Manzi | AI & Cybersecurity Portfolio`
- **Tagline**: *Securing Systems. Engineering Intelligence.*

### 2. Website Purpose
To showcase technical depth, verified credentials, hands-on engineering projects, and research at the intersection of **Cybersecurity** and **Artificial Intelligence**. Designed to serve as a verifiable, comprehensive hub for technical recruiters, engineering leaders, academic researchers, and consulting clients.

### 3. Target Audience
1. **Technical Recruiters & Talent Acquisition**: Fast access to verified credentials, education, core skill matrices, and direct contact options.
2. **Security & AI Engineering Managers**: Deep dives into code architectures, threat modeling rigor, CTF triumphs, machine learning pipelines, and model safety.
3. **Academic & Research Collaborators**: Research interests in adversarial machine learning, LLM safety/alignment, and cryptographic protocols.
4. **Industry Clients & Consulting Partners**: Verifiable expertise for security audits, zero-trust implementation, and custom AI agent solutions.

### 4. Planned Website Pages & Sections
| Page / Section | Anchor | Description |
| :--- | :--- | :--- |
| **Home** | `#home` | Hero banner, value proposition, quick metrics, interactive terminal greeting, and calls-to-action. |
| **About Me** | `#about` | Narrative biography, background in systems & ML, engineering philosophy, and personal directives. |
| **Education** | `#education` | B.S. in Computer Science (Summa/Magna Cum Laude), relevant coursework, and industry credentials (CompTIA Security+, CEH, AWS, Deep Learning). |
| **Skills** | `#skills` | Categorized matrix across Cybersecurity, Artificial Intelligence, Software Systems, and DevSecOps tooling. |
| **Projects** | `#projects` | Filterable project cards (All, Security, AI, Hybrid) with architecture notes, tech badges, and demo/repo links. |
| **Security** | `#security` | Dedicated cyber domain section covering red-teaming, threat modeling (STRIDE), CTF triumphs, and an interactive security posture auditor. |
| **AI** | `#ai` | Dedicated intelligence domain section detailing LLMs, autonomous agent orchestration, RAG, and an interactive prompt guardrail sandbox. |
| **Contact** | `#contact` | Validated contact form, direct secure email, LinkedIn, GitHub, and PGP public key fingerprint. |
| **Site Blueprint Modal** | UI Modal | Interactive inspector accessible from the header, hero, or footer detailing the full website specification and visual site map tree. |

### 5. Site Map
```
Home
│
├── About Me
├── Education
├── Skills
├── Projects
├── Security
├── AI
└── Contact
```

---

## File Structure

```
portfolio-website/
├── index.html         # Main semantic HTML5 markup & architecture
├── style.css          # Modern CSS system, dark/light themes, animations, tree map styling
├── script.js          # Theme toggle, scrollspy, filters, interactive widgets, modal controller
├── site-spec.json     # Structured JSON specification of the site
└── README.md          # Project documentation and deployment guide
```

---

## Running Locally

Since this site is built using standard web technologies with zero external build dependencies, you can run and view it instantly:

### Using Python HTTP Server:
```bash
cd /Users/mayamanzi/.gemini/antigravity/scratch/portfolio-website
python3 -m http.server 8080
```
Then open your browser and navigate to:
```
http://localhost:8080
```

### Direct Browser Access:
You can also directly open `index.html` in any browser:
```bash
open /Users/mayamanzi/.gemini/antigravity/scratch/portfolio-website/index.html
```

---

## Free Deployment Options

### 1. GitHub Pages
1. Initialize git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of portfolio website"
   ```
2. Push to your GitHub repository (e.g. `username.github.io`).
3. Enable GitHub Pages in repository settings under **Pages** > **Deploy from a branch** (`main`).

### 2. Vercel or Netlify
- Drag and drop the `portfolio-website` folder directly into the Netlify or Vercel dashboard for instant SSL-enabled hosting.
