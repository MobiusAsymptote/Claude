---
name: nj-building-codes
description: |
  This skill provides comprehensive knowledge of New Jersey residential and affordable housing
  regulations and federal accessibility standards. Use when designing, permitting, planning,
  or reviewing NJ residential or affordable housing projects.

  Use when:
  - Designing multifamily or affordable housing projects in New Jersey
  - Determining which accessibility standards apply to a project
  - Navigating UHAC affordability controls, deed restrictions, or phasing rules
  - Reviewing RSIS site improvement requirements
  - Applying for NJHMFA / LIHTC funding
  - Assessing Mount Laurel / COAH fair share obligations
  - Answering questions about Fair Housing Act design requirements, Section 504, or ADA in housing
  - Evaluating compliance for HUD-funded projects (HOME, CDBG, Section 8)

  Keywords: nj building code, uhac, rsis, njucc, coah, mount laurel, njhmfa, lihtc, fair housing
  act, fha accessibility, section 504, ada housing, ansi a117.1, type a unit, type b unit,
  affordable housing nj, deed restriction, inclusionary zoning, nj dca, visitability
license: MIT
---

# NJ Residential & Affordable Housing Codes

**Status**: Production Ready
**Last Updated**: 2026-04-26
**Dependencies**: None

---

## Regulatory Framework at a Glance

| Regulation | Citation | Agency | Applies When |
|---|---|---|---|
| **NJ UCC** | N.J.A.C. 5:23 | NJ DCA / Codes | All NJ construction |
| **RSIS** | N.J.A.C. 5:21 | NJ DCA | All residential site work |
| **UHAC** | N.J.A.C. 5:80-26 | NJHMFA / DCA | All affordable/COAH-credited units |
| **COAH / Fair Share** | N.J.A.C. 5:93, 5:97, 5:99; N.J.S.A. 52:27D-301 | NJ DCA / DLPS | Municipal affordable obligations |
| **NJHMFA Requirements** | LIHTC QAP; Program Guidelines | NJHMFA | LIHTC, HOME, AHPF, AHGS funding |
| **Fair Housing Act (FHA)** | 42 U.S.C. § 3601; 24 CFR 100.205 | HUD / DOJ | 4+ unit buildings (any funding) |
| **Section 504** | 29 U.S.C. § 794; 24 CFR Part 8 | HUD | Any federal HUD funding |
| **ADA** | 42 U.S.C. § 12101; 2010 Standards | DOJ | Common areas; govt housing |
| **ANSI A117.1-2017** | ICC A117.1 | ICC (adopted by NJ UCC) | All NJ UCC-regulated construction |

---

## When to Load References

| Reference File | Load When |
|---|---|
| `references/nj-ucc-rsis.md` | Permitting, construction standards, site design, parking, stormwater |
| `references/uhac-coah.md` | Affordability controls, rent caps, deed restrictions, phasing, income limits, COAH/Mount Laurel |
| `references/accessibility-fha-504.md` | Unit accessibility, FHA 7 requirements, Section 504 unit counts, ADA, ANSI A117.1 type A/B |
| `references/njhmfa-lihtc.md` | LIHTC allocation, QAP scoring, ENERGY STAR, HOME program, developer eligibility |
| `references/compliance-checklist.md` | Pre-submission review, common pitfalls, phased compliance checklist |

---

## Quick Applicability Decision Tree

### Step 1 — Is this NJ construction?
→ Yes: **NJ UCC** (N.J.A.C. 5:23) and **RSIS** (N.J.A.C. 5:21) apply to all projects.

### Step 2 — Does the building have 4+ dwelling units?
→ Yes: **Fair Housing Act** accessibility design requirements apply to:
- All units in elevator buildings
- Ground-floor units only in non-elevator buildings

### Step 3 — Does the project include affordable / income-restricted units?
→ Yes: **UHAC** (N.J.A.C. 5:80-26) governs pricing, marketing, deed restrictions, and phasing.
→ COAH/Fair Share rules may additionally apply based on municipal obligation.

### Step 4 — Does the project use HUD federal funding (HOME, CDBG, Section 8, etc.)?
→ Yes: **Section 504** (24 CFR Part 8) mandates 5% + 2% accessible units and full common-area access.
→ ADA common-area requirements also apply.

### Step 5 — Is the project applying for LIHTC, HOME, AHPF, or NJHMFA gap financing?
→ Yes: **NJHMFA requirements** apply — QAP scoring, ENERGY STAR certification, affirmative marketing plan, 30-year affordability period.

---

## Fair Housing Act — 7 Design & Construction Requirements

For covered multifamily dwellings (4+ units; elevator = all units; no elevator = ground floor only):

1. **Accessible entrance** on an accessible route
2. **Accessible common areas** (parking, lobby, corridors, laundry, recreation, rental office)
3. **Usable doors** — 32″ clear min. width; lever hardware; adequate maneuvering clearance
4. **Accessible route within units** — continuous accessible path throughout
5. **Accessible controls** — switches, outlets, thermostats at 15–48″ AFF
6. **Reinforced bathroom walls** for future grab bar installation
7. **Usable kitchens and bathrooms** — wheelchair maneuverable clear floor space

Safe harbors: FHA Design Manual (1996/1998), ICC/ANSI A117.1-2009/2017, IBC 2000–2018.

---

## Section 504 Unit Requirements (Federally Funded Projects)

| Unit Type | Minimum Percentage | Notes |
|---|---|---|
| Mobility-accessible (Type A) | **5% of total units** (min. 1) | Full wheelchair maneuverability |
| Sensory-accessible (hearing/vision) | **2% of total units** (min. 1) | Visual alarms, TTY, tactile |

Technical standard: UFAS or 2010 ADA Standards (developer chooses); ANSI A117.1 compliant.

---

## UHAC Key Numbers (N.J.A.C. 5:80-26, amended December 19, 2024)

| Parameter | Rule |
|---|---|
| Affordability period | **30 years** (rental and for-sale; deed restricted) |
| Annual rent increase cap | **2%** (or as adjusted by regulation) |
| Income tiers | Very low (≤30% AMI), Low (≤50% AMI), Moderate (≤80% AMI) |
| Phasing — market-rate before affordable | Max **10%** market-rate complete before 1st affordable unit |
| Phasing — mid-construction | Max **25% + 1** market-rate before 25% of affordable units |
| Unit mix | Prescribed bedroom distribution; see UHAC and municipal FAIR SHARE PLAN |
| Marketing | Affirmative marketing plan; lottery if oversubscribed |

---

## RSIS Parking Minimums (N.J.A.C. 5:21)

| Unit Type | Spaces per Unit |
|---|---|
| 1-bedroom | 1.5 |
| 2-bedroom | 1.5 |
| 3-bedroom | 2.0 |
| 4-bedroom | 2.0 |
| Affordable (≤80% AMI) | May qualify for local reduction |

Accessible parking: 1 van-accessible space per 25 total parking spaces (ADA/FHA).

---

## Mount Laurel / COAH Fair Share Income Distribution

| Income Tier | AMI Threshold | Required Share of Affordable Units |
|---|---|---|
| Very low income | ≤30% AMI | **13% minimum** of all affordable units |
| Low income | ≤50% AMI | Combined with very low = **50% minimum** |
| Moderate income | ≤80% AMI | Remaining 50% |

Fourth Round legislation (March 2024): 84,000 additional affordable units mandated statewide.

---

## ANSI A117.1-2017 Unit Types (NJ UCC Reference Standard)

| Unit Type | Applicability | Key Features |
|---|---|---|
| **Type A** | HUD/Section 504 funded; state-mandated % | Full wheelchair maneuverability; removable base cabinets; enhanced clearances |
| **Type B** | FHA-covered buildings (4+ units) | Basic accessibility; aligns with FHA 7 requirements; aging-in-place design |
| **Accessible Unit** | Public accommodations | Highest standard; full ADA/ANSI compliance |

COAH-credited multistory townhouses require Type A features: adaptable entrance + first-floor adaptable bath + bedroom.

---

## NJ UCC Current Edition

- **Base code**: 2021 IBC (International Building Code) with NJ amendments — N.J.A.C. 5:23
- **Accessibility chapter**: Chapter 11, referencing **ANSI A117.1-2017**
- **Energy code**: IECC (International Energy Conservation Code), current NJ adoption
- **Proposed update**: 2024–2025 edition under development incorporating 2024 IBC, 2023 NEC
- Code text available online only (no print after June 6, 2023): https://www.nj.gov/dca/codes/codreg/ucc.shtml

---

## Official Sources

| Agency | URL |
|---|---|
| NJ DCA — Codes & Standards | https://www.nj.gov/dca/codes/ |
| NJ DCA — RSIS | https://www.nj.gov/dca/codes/offices/rsis.shtml |
| NJHMFA | https://www.nj.gov/dca/hmfa/ |
| NJHMFA — UHAC | https://www.nj.gov/dca/hmfa/about/uhac/ |
| NJHMFA — Developer Resources | https://www.nj.gov/dca/hmfa/developers/multifamily/generalinfo/ |
| NJHMFA — LIHTC / QAP | https://www.nj.gov/dca/hmfa/developers/lihtc/qap/ |
| NJ DCA — DLPS (COAH/Fair Share) | https://www.nj.gov/dca/dlps/ |
| NJ Division on Civil Rights (LAD) | https://www.njoag.gov/dcr/ |
| HUD Fair Housing | https://www.hud.gov/program_offices/fair_housing_equal_opp |
| HUD Section 504 | https://www.hud.gov/504 |
| HUD Exchange (HOME, CDBG) | https://www.hudexchange.info/ |
| U.S. Access Board (ADA) | https://www.access-board.gov/ada/ |
| NJ Green Building Manual | https://greenmanual.rutgers.edu/ |
| Fair Share Housing Center | https://www.fairsharehousing.org/ |

---

## Top 5 Compliance Pitfalls

1. **FHA door clearance**: 32″ clear width is minimum; maneuvering clearance on latch side is commonly missed in unit layouts.
2. **UHAC phasing**: 2024 amendment added 10%/25% thresholds — construction sequencing contracts must be updated to reflect this.
3. **Section 504 unit count rounding**: 5% of units rounds *up* to the nearest whole unit; minimum is always 1.
4. **COAH Type A townhouse requirement**: First-floor adaptable bath + bedroom required *and* 10% conversion fund deposit required.
5. **ENERGY STAR certification for LIHTC**: Must be obtained before certificate of occupancy; retroactive certification is not accepted by NJHMFA.
