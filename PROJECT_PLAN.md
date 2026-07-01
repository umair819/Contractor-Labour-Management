# 🏗️ Contractor & Labour Management System
**Project Status:** 🔴 Not Started  
**Priority:** ⭐⭐⭐⭐ High  
**Target Market:** Construction contractors, building companies, civil engineers, project managers in Pakistan  
**Tech Stack (Planned):** Python (Flask) + SQLite + HTML/CSS/JS + Electron

---

## 📋 Project Overview

Pakistan ki construction industry mein Rs. Trillions ka kaam hota hai har saal, lekin 
yahan koi bhi digital management nahi hai. Contractor daily wages ka hisaab notebooks mein 
rakhta hai, material ka record alag, payment alag. Ek dedicated offline system jo:
- Labour attendance & wages calculate kare
- Material purchase & usage track kare  
- Project budget vs actual compare kare
- Client billing manage kare

Yeh ek **underserved, high-value niche** hai.

---

## ✅ Features To Develop (Kya Banana Hai)

### 1. 🔐 Login & User Roles
- [ ] Contractor / Owner login
- [ ] Site Supervisor login
- [ ] Accountant login
- [ ] View-only (client access)

### 2. 🏗️ Project Management
- [ ] New project creation (Name, Client, Location, Start Date, End Date)
- [ ] Project type (Residential, Commercial, Road, Interior, etc.)
- [ ] Contract value / budget entry
- [ ] Project status: Planning / In Progress / On Hold / Completed
- [ ] Project photos upload (progress photos)
- [ ] Multiple projects simultaneously

### 3. 👷 Labour / Worker Management
- [ ] Worker profile (Name, CNIC, Phone, Trade/Skill)
- [ ] Trade types: Mason, Carpenter, Electrician, Plumber, Helper, Painter, Welder
- [ ] Worker rate types: Daily wage, Weekly, Fixed monthly
- [ ] Worker assignment to project(s)
- [ ] Worker status: Active / Inactive / Blacklisted

### 4. 📅 Daily Attendance & Wages
- [ ] Daily attendance marking per project
- [ ] Attendance types: Present (Full), Half Day, Absent, Leave
- [ ] Overtime hours entry
- [ ] Daily wage auto-calculation based on rate
- [ ] Bulk attendance entry (for large teams)
- [ ] Weekly attendance summary
- [ ] Monthly wage calculation per worker

### 5. 💸 Worker Payments & Advances
- [ ] Advance payment to worker
- [ ] Weekly/monthly wage payment
- [ ] Advance deduction from salary
- [ ] Payment history per worker
- [ ] Outstanding balance per worker
- [ ] Payment receipt print

### 6. 🧱 Material Management
- [ ] Material catalog (Cement, Bricks, Steel, Sand, Paint, etc.)
- [ ] Material purchase entry (Item, Qty, Rate, Vendor, Date)
- [ ] Material received at site entry
- [ ] Material usage per project
- [ ] Material wastage tracking
- [ ] Current stock at site
- [ ] Material cost report per project

### 7. 🚚 Vendor / Supplier Management
- [ ] Vendor list (material suppliers)
- [ ] Vendor payment tracking
- [ ] Vendor outstanding balance
- [ ] Vendor ledger / statement

### 8. 🏢 Equipment & Machinery
- [ ] Equipment list (Mixer, Shuttering, Scaffolding, Generator)
- [ ] Equipment rental tracking (daily/hourly rate)
- [ ] Equipment maintenance log
- [ ] Equipment hire/return dates

### 9. 📋 Project Budget vs Actual
- [ ] Budget planning per project (breakdown by category)
- [ ] Actual expense tracking
- [ ] Budget vs Actual comparison chart
- [ ] Variance analysis (over/under budget)
- [ ] Cost to complete estimate

### 10. 💰 Client Billing & Payments
- [ ] Running bill / progress bill generation
- [ ] Milestone-based billing
- [ ] Client payment recording
- [ ] Retention money tracking
- [ ] Client outstanding balance
- [ ] Bill print & share via WhatsApp

### 11. 📊 Reports
- [ ] Daily work report (attendance + material)
- [ ] Weekly labour cost report
- [ ] Project cost report (labour + material + equipment)
- [ ] Project profitability report
- [ ] Worker payment history
- [ ] Material purchase report
- [ ] Client billing report

### 12. 📱 WhatsApp Integration
- [ ] Daily report to contractor/owner
- [ ] Worker payment confirmation
- [ ] Client bill send via WhatsApp
- [ ] Material stock low alert
- [ ] Project milestone completion notification

### 13. 📷 Site Progress Photos
- [ ] Photo upload per project per date
- [ ] Photo gallery with dates
- [ ] Progress timeline view
- [ ] Share progress photos via WhatsApp to client

### 14. ⚙️ Settings
- [ ] Company/contractor name, logo, CNIC, NTN
- [ ] Default wage rates per trade
- [ ] Overtime calculation rules
- [ ] Tax/WHT settings
- [ ] Backup & restore

### 15. 🔒 Licensing
- [ ] 15-day trial
- [ ] License key per contractor
- [ ] Per-project pricing model (alternative)

---

## 🛠️ Tech Stack Details

| Layer | Technology |
|-------|-----------|
| Backend | Python + Flask |
| Database | SQLite |
| Frontend | HTML + CSS + JS |
| Charts | Chart.js (budget vs actual) |
| WhatsApp | Baileys Node.js |
| Packaging | Electron + PyInstaller |

---

## 📁 Planned Folder Structure

```
CrewLink/
├── app.py                    # Flask backend
├── database.py
├── db_config.json
├── frontend/
│   ├── index.html            # Dashboard
│   ├── projects.html         # Project management
│   ├── workers.html          # Labour management
│   ├── attendance.html       # Daily attendance
│   ├── payments.html         # Worker wages & advances
│   ├── materials.html        # Material tracking
│   ├── vendors.html          # Supplier management
│   ├── equipment.html        # Machinery
│   ├── client_billing.html   # Client invoices
│   ├── budget.html           # Budget vs actual
│   ├── reports.html
│   └── settings.html
├── whatsapp/
│   └── wa-server.js
├── generate_license_key.py
├── 1. Start_App.bat
├── 1. End_App.bat
└── PROJECT_PLAN.md
```

---

## 💰 Monetization Plan

| Plan | Price | Features |
|------|-------|----------|
| Trial | Free (15 days) | 1 active project |
| Basic | Rs. 8,000 - 12,000 | Up to 5 projects |
| Professional | Rs. 18,000 - 25,000 | Unlimited projects |
| Enterprise | Rs. 35,000+ | Multi-user + network |
| Annual Support | Rs. 3,000 - 5,000/year | |

---

## 🎯 Development Phases

| Phase | Tasks | Status |
|-------|-------|--------|
| Phase 1 | Projects + Workers + Attendance | 🔴 Not Started |
| Phase 2 | Wages + Advances + Payment history | 🔴 Not Started |
| Phase 3 | Material management + Vendors | 🔴 Not Started |
| Phase 4 | Equipment + Budget vs Actual | 🔴 Not Started |
| Phase 5 | Client billing + Reports | 🔴 Not Started |
| Phase 6 | Site photos + WhatsApp | 🔴 Not Started |
| Phase 7 | Licensing + Packaging + EXE | 🔴 Not Started |

---

## 📝 Notes & Ideas

- Naam rakhein: **TaameerPro** ya **ContractorPak** ya **SiteManager**
- Urdu interface bohot zaroori hai (site supervisors English nahi jaante)
- Android tablet version socho — site pe phone/tablet zyada use hota hai laptop se
- Acadexa ka HR/Payroll module reuse karo labour wages ke liye
- Civil engineers aur project managers Facebook groups per target karo
- Rs. 10,000-25,000 pricing — contractors yeh easily afford kar sakte hain

---

## 🔐 Final Phase: Security & Licensing System (Launch Se Pehle Lazim)

> **Is phase ko complete kiye baghair software sell nahi karna!**
> **Note:** Acadexa jaisi same Python/Flask architecture — same `license_manager.py` reuse.

### Steps:

#### Step 1 — PC ID Generation (Python)
- [ ] `license_manager.py` → `MachineGuid` → SHA256 (Acadexa se copy karo)
- [ ] Project limit enforce karo trial mein (sirf 1 active project)

#### Step 2 — Trial (Server-Side, 15 days, 1 project)
- [ ] "Trial — X days, 1 project active"
- [ ] Server pe register, file nahi

#### Step 3 — License Activation
- [ ] `XXXX-XXXX-XXXX-XXXX` key (Basic/Professional/Enterprise)
- [ ] `POST /activate` → `{key, pc_id, project_limit}` → encrypted save

#### Step 4 — Startup Validation
- [ ] PC ID + expiry + project limit verify
- [ ] Har 3 din online + 7-din offline grace

#### Step 5 — Deactivation + Lock
#### Step 6 — Code Protection (PyArmor + PyInstaller)
#### Step 7 — Admin License Panel

### Phase Table:
| Phase | Tasks | Status |
|-------|-------|--------|
| Phase 8 | PC ID + Trial (1 project limit) | 🔴 Not Started |
| Phase 8 | License activation | 🔴 Not Started |
| Phase 8 | Startup + project limit validation | 🔴 Not Started |
| Phase 8 | Deactivation + lock | 🔴 Not Started |
| Phase 8 | Admin license panel | 🔴 Not Started |
| Phase 8 | PyArmor + PyInstaller build | 🔴 Not Started |
