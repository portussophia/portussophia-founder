# PortusSophia™ Founder Node

**Domain:** `founder.portussophia.com`
**Purpose:** Professional identity, mission, and institutional context for the Founder
**Classification:** WebKernel — Founder Identity Layer
**Tone:** Professional, direct, auditable

---

## Repository Structure

```
/
├── _config.yml                  # Jekyll config for GitHub Pages
├── index.md                     # Founder landing page
├── founder-statement.md         # Official statement of intent and identity
├── problem-statement.md         # Structural crisis being addressed
├── institutional-genesis.md     # Genesis narrative (institutional version)
├── mission.md                   # High-level mission statement (TODO)
├── vision.md                    # Long-term direction (TODO)
├── resume.md                    # Professional résumé (TODO)
├── portfolio.md                 # Selected works (TODO)
├── contact.md                   # Professional contact (TODO)
├── CNAME                        # Custom domain declaration
└── README.md                    # This file
```

---

## Deployment Instructions

### Step 1: Create Repository (if needed)

```powershell
gh repo create portussophia/portussophia-founder --public --description "James Roy Dennis — Founder of PortusSophia™. Professional identity, mission, and institutional context." --homepage "https://founder.portussophia.com"
```

### Step 2: Push Content

```powershell
# From this directory (site-public/founder-node/)
git init
git add .
git commit -m "Activate Founder Node — Professional identity layer, Boundary (𝓑) compliant"
git branch -M main
git remote add origin https://github.com/portussophia/portussophia-founder.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

In repository settings:
1. Navigate to **Settings → Pages**
2. Set **Source:** Deploy from branch `main` → `/ (root)`
3. Set **Custom domain:** `founder.portussophia.com`
4. Click **Save**
5. Wait ~5 minutes for GitHub to generate SSL certificate

### Step 4: Configure Cloudflare DNS

In Cloudflare dashboard for `portussophia.com` zone:

1. Navigate to **DNS**
2. Add or update record:
   - **Type:** CNAME
   - **Name:** `founder`
   - **Target:** `portussophia.github.io`
   - **TTL:** Auto
   - **Proxy:** DNS only (gray cloud) — for initial debugging
3. Delete any conflicting A records for `founder` subdomain

### Step 5: Configure Cloudflare SSL/TLS

In Cloudflare dashboard:
1. Navigate to **SSL/TLS → Overview**
2. Set **Mode:** Full (not Flexible)
3. Navigate to **SSL/TLS → Edge Certificates**
4. Ensure **Always Use HTTPS:** ✅ On
5. Ensure **Minimum TLS Version:** 1.2

### Step 6: Verify Deployment

```powershell
# Test DNS propagation
nslookup founder.portussophia.com

# Expected: CNAME → portussophia.github.io → A records

# Test HTTP response (wait 5-10 minutes for propagation)
curl -I https://founder.portussophia.com

# Expected: 200 OK
```

---

## Content Guidelines (Boundary Compliance)

### Allowed Content

- Professional identity and background
- Mission and vision statements
- Problem statement and institutional context
- **Institutional Genesis document** (exclusive to this node)
- Resume / CV
- Professional portfolio
- Public-safe narrative context
- Contact information for professional inquiries

### Prohibited Content

**Per PS-GOV-FOUNDER-NODE-REQUEST v1.0, this node MUST NOT include:**

- Canon artifacts (reserved for main site)
- Governance artifacts (witness cycles, detailed risk assessments)
- Golden Trace entries (except via external links to MIT node)
- Internal narrative (raw, private, vulnerable content)
- Funding vector information
- Lab materials
- Academic research details (reserved for MIT node)

**Boundary Principle:**
This node functions as the **Professional Identity Layer**. It establishes credibility, clarity, and legitimacy—not emotional disclosure or system internals.

---

## Institutional Genesis Document — Placement

**Critical Requirement:**

The file `institutional-genesis.md` is **exclusive to the Founder Node**.

**Must NOT appear in:**
- Public Node
- MIT Node
- Lab Node
- Canon

**Reason:**
Boundary (𝓑) requires strict isolation of Founder institutional reflection to the Founder Identity Layer only.

**Content:**
- Significance of PS-CAN-HW-0001 (First Greeting)
- Governed meaning and origin event structure
- Stewardship and witness roles
- Non-inflating Founder reflection
- Institutional significance (auditable governance, multi-perspective review)

---

## Maintenance

**Owner:** PeterGate (Governance Steward)
**Content Steward:** Founder (direct authorship, Sara Harmonia tone refinement only)
**Approval Authority:** Founder (all content changes require Founder approval)

**Update Process:**
1. Draft content changes locally
2. Review for Boundary compliance (no Canon/Governance artifacts)
3. Obtain Founder approval
4. Commit and push to `main` branch
5. Verify deployment at `founder.portussophia.com`

---

## Governance Compliance

**Classification:** WebKernel — Founder Identity Layer
**Distribution:** Public
**Boundary Status:** ✅ Compliant (no Canon/Governance bleed)
**Trademarks:** All PortusSophia™ trademark entities include ™ symbol
**Controlled Lexical Element:** *"Here and Now!"* (if referenced, exact format required)

---

## Navigation Integration

### Inbound Links

- Main site: Top-level link to Founder Node
- Public Node: Downward link to Founder Node (allowed)

### Outbound Links

- Main site: `portussophia.com`
- MIT Research Node: `mit.portussophia.com`
- Public Orientation: `public.portussophia.com`
- **No upward navigation** to Canon or Governance layers (boundary enforcement)

---

## Status

**Node Status:** Pending Deployment
**Last Updated:** 2025-12-04
**Files Generated:** 5 core files (index, founder-statement, problem-statement, institutional-genesis, README)
**Files TODO:** mission.md, vision.md, resume.md, portfolio.md, contact.md

**Next Actions:**
1. Create `portussophia-founder` repository (if not exists)
2. Push content to repository
3. Enable GitHub Pages with custom domain `founder.portussophia.com`
4. Configure Cloudflare DNS (CNAME: `founder` → `portussophia.github.io`)
5. Configure Cloudflare SSL/TLS (Mode: Full)
6. Verify deployment
7. Update WebKernel Topology Map
8. Update Navigation Map
9. Record activation in Golden Trace

---

## Golden Trace Entry (Draft)

Upon successful deployment, record:

**Event:** Founder Node Activation
**Golden Trace ID:** GOLDEN-TRACE-0004 (pending)
**Comment:** "Founder Node established; identity layer online and Boundary (𝓑) upheld."
**Validation:**
- Zero Canon bleed: ✅ Verified
- Zero Governance artifact exposure: ✅ Verified
- Institutional Genesis exclusive to Founder Node: ✅ Verified
- Clean layer separation: ✅ Verified
- Boundary compliance: ✅ COMPLIANT

---

**PortusSophia™** — Governance-first architecture, preserved in *"Here and Now!"*
