<div align="center">

<svg width="100%" height="400" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #f5f0e8 0%, #e8f4f0 100%);">
  <defs>
    <style>
      @keyframes float { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-20px); } }
      @keyframes glow { 0%, 100% { opacity: 0.3; } 50% { opacity: 1; } }
      @keyframes dash { to { stroke-dashoffset: 0; } }
      .float-text { animation: float 3s ease-in-out infinite; }
      .glow-circle { animation: glow 2s ease-in-out infinite; }
      .dash-line { animation: dash 2s linear infinite; stroke-dasharray: 1000; }
    </style>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#378ADD;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#185FA5;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- Floating circles background -->
  <circle cx="200" cy="100" r="80" fill="url(#grad1)" opacity="0.1" class="glow-circle"/>
  <circle cx="1000" cy="300" r="100" fill="#639922" opacity="0.08" class="glow-circle" style="animation-delay: 0.5s"/>
  
  <!-- Main heading -->
  <text x="600" y="120" font-size="72" font-weight="700" text-anchor="middle" fill="#2C2C2A" class="float-text">
    ZOHA MALIK
  </text>
  
  <!-- Subheading with gradient effect -->
  <text x="600" y="180" font-size="28" text-anchor="middle" fill="#378ADD" font-weight="600">
    FULL-STACK DEVELOPER
  </text>
  
  <!-- Decorative line -->
  <line x1="350" y1="210" x2="850" y2="210" stroke="#378ADD" stroke-width="2" opacity="0.3"/>
  
  <!-- Description -->
  <text x="600" y="280" font-size="16" text-anchor="middle" fill="#6b7f55" font-weight="400">
    Shipping production-grade applications | Real solutions for real problems
  </text>
  
  <!-- Stats with animated boxes -->
  <g>
    <rect x="250" y="320" width="200" height="60" fill="white" stroke="#378ADD" stroke-width="2" rx="4"/>
    <text x="350" y="345" font-size="32" font-weight="700" text-anchor="middle" fill="#378ADD">5+</text>
    <text x="350" y="370" font-size="12" text-anchor="middle" fill="#6b7f55" font-weight="600">PROJECTS SHIPPED</text>
  </g>
  
  <g>
    <rect x="500" y="320" width="200" height="60" fill="white" stroke="#639922" stroke-width="2" rx="4"/>
    <text x="600" y="345" font-size="32" font-weight="700" text-anchor="middle" fill="#639922">3+</text>
    <text x="600" y="370" font-size="12" text-anchor="middle" fill="#6b7f55" font-weight="600">YEARS BUILDING</text>
  </g>
  
  <g>
    <rect x="750" y="320" width="200" height="60" fill="white" stroke="#D85A30" stroke-width="2" rx="4"/>
    <text x="850" y="345" font-size="32" font-weight="700" text-anchor="middle" fill="#D85A30">∞</text>
    <text x="850" y="370" font-size="12" text-anchor="middle" fill="#6b7f55" font-weight="600">LEARNING MODE</text>
  </g>
</svg>

---

## 🚀 What I Build

I don't just write code. I architect scalable solutions, design databases that don't break under pressure, and ship features that actually work. Every project is built with production-ready standards.

**Currently:** CodeKonix Web Development Intern (Aug–Sept 2026)  
**Based:** Multan, Pakistan  
**Philosophy:** Write code today that you won't hate tomorrow

---

## 💻 TECH ARSENAL

<table>
  <tr>
    <td align="center" width="25%">
      <div style="border: 3px solid #378ADD; padding: 20px; border-radius: 8px; background: #f5f0e8;">
        <h4>BACKEND</h4>
        <p><strong>Node.js</strong></p>
        <p><strong>Express</strong></p>
        <p><strong>PHP</strong></p>
        <p style="color: #639922; font-size: 12px;">REST APIs</p>
      </div>
    </td>
    <td align="center" width="25%">
      <div style="border: 3px solid #639922; padding: 20px; border-radius: 8px; background: #f5f0e8;">
        <h4>DATABASES</h4>
        <p><strong>PostgreSQL</strong></p>
        <p><strong>MySQL</strong></p>
        <p><strong>Prisma ORM</strong></p>
        <p style="color: #378ADD; font-size: 12px;">MongoDB</p>
      </div>
    </td>
    <td align="center" width="25%">
      <div style="border: 3px solid #D85A30; padding: 20px; border-radius: 8px; background: #f5f0e8;">
        <h4>FRONTEND</h4>
        <p><strong>Next.js</strong></p>
        <p><strong>React</strong></p>
        <p><strong>TypeScript</strong></p>
        <p style="color: #6b7f55; font-size: 12px;">Tailwind • Animation</p>
      </div>
    </td>
    <td align="center" width="25%">
      <div style="border: 3px solid #993556; padding: 20px; border-radius: 8px; background: #f5f0e8;">
        <h4>TOOLS</h4>
        <p><strong>Git</strong></p>
        <p><strong>Docker</strong></p>
        <p><strong>Figma</strong></p>
        <p style="color: #D85A30; font-size: 12px;">Vercel • AWS</p>
      </div>
    </td>
  </tr>
</table>

---

## ⚡ FEATURED PROJECTS

### 🛍️ BAZAR — E-COMMERCE PLATFORM
**Production-grade. Battle-tested. Shipping real revenue.**

Built a complete e-commerce stack from scratch:
- **15+ REST API endpoints** with JWT authentication
- **3-tier architecture** (routes → controllers → services)
- **Admin dashboard** with full CRUD operations
- **Shopping cart & checkout system** with order tracking
- **PostgreSQL** with optimized queries
- **Node.js + Express** backend

> This isn't a tutorial project. This is code running in production right now.

**Tech:** Node.js · Express · PostgreSQL · JWT · Admin Panel  
**Status:** Live and handling real transactions

---

### 🎨 ARTWALA — EVENT MANAGEMENT PLATFORM
**Currently LIVE at https://artwala.page.gd**

From zero to production in full-stack:
- **Advanced search & filtering** powered by SQL queries
- **Image upload system** with storage optimization
- **Complete admin panel** with event management
- **Relational database design** (users, events, categories)
- **Responsive UI** that works on every device
- **MySQL database** with 50+ events live

> This platform is actively used by event organizers in Pakistan. Real users. Real events. Real impact.

**Tech:** PHP · MySQL · Admin CRUD · Image Upload  
**Live:** https://artwala.page.gd  
**Status:** Production • Active Users

---

### 💼 PORTFOLIO — WINDOWS XP NOSTALGIA MEETS MODERN WEB
**Live at https://zohamalik.dev**

What if your portfolio was... an operating system?

- **Draggable windows** that actually feel native
- **Retro UI elements** with modern performance
- **Typewriter animations** on first load
- **Custom sound design** for interactions
- **Animated cursor companion** that follows you
- **Fully responsive** desktop to mobile

> Built with Next.js & Framer Motion. Proves you can do creative + performance at the same time.

**Tech:** Next.js · Framer Motion · React · Creative Coding  
**Live:** https://zohamalik.dev  
**Status:** Shipped • Design Award Material

---

## 📊 BY THE NUMBERS

```
┌─────────────────────────────────────────────┐
│  5+ PROJECTS SHIPPED TO PRODUCTION          │
│  15+ REST API ENDPOINTS BUILT               │
│  3+ YEARS OF HANDS-ON DEVELOPMENT           │
│  100% CODE QUALITY OBSESSED                 │
│  ∞ LEARNING & IMPROVING DAILY               │
└─────────────────────────────────────────────┘
```

---

## 🎯 WHAT MAKES ME DIFFERENT

✅ **Not just code.** Architecture that scales.  
✅ **Not just features.** Solutions that solve problems.  
✅ **Not just projects.** Production-ready applications.  
✅ **Not just shipping.** Shipping with quality.  
✅ **Not copying tutorials.** Building real things.

---

## 📲 LET'S CONNECT

I'm always interested in:
- Building something amazing together
- Discussing web architecture & best practices
- Contributing to open-source projects
- Exploring opportunities that challenge me

<div style="margin: 40px 0; padding: 30px; border: 3px solid #378ADD; border-radius: 8px; background: linear-gradient(135deg, #f5f0e8 0%, #e8f4f0 100%);">

**Email:** zohamalik.dev@gmail.com  
**Portfolio:** https://zohamalik.dev  
**LinkedIn:** https://linkedin.com/in/zohamalik-  
**GitHub:** https://github.com/zoha-malik01  

</div>

---

<div align="center">

```
╔═══════════════════════════════════════════╗
║  WRITE CODE TODAY THAT YOU'LL LOVE TOMORROW║
╚═══════════════════════════════════════════╝
```

**Every commit is a step toward mastery.**

</div>
