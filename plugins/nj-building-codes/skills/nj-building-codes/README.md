# NJ Building Codes Skill

Comprehensive reference for New Jersey residential and affordable housing regulations, covering:

- **NJ Uniform Construction Code** (N.J.A.C. 5:23) — 2021 IBC base with NJ amendments
- **Residential Site Improvement Standards / RSIS** (N.J.A.C. 5:21) — parking, streets, stormwater
- **UHAC** (N.J.A.C. 5:80-26, amended December 2024) — affordability controls, phasing, deed restrictions
- **COAH / Mount Laurel** — fair share obligations, income tiers, Fourth Round (2024)
- **NJHMFA Developer Requirements** — LIHTC QAP, ENERGY STAR, HOME program
- **Fair Housing Act** — 7 design & construction requirements for 4+ unit buildings
- **HUD Section 504** — 5% + 2% accessible unit requirements for federally funded projects
- **ADA** — common area accessibility; Title II (govt housing) / Title III (public areas)
- **ANSI A117.1-2017** — Type A and Type B dwelling unit technical specifications
- **NJ Law Against Discrimination** — broader protected classes including source of income

## Installation

```bash
# Install to local Claude skills
cp -r . ~/.claude/skills/nj-building-codes/
```

## Trigger Keywords

This skill loads automatically when Claude sees:
`nj building code`, `uhac`, `rsis`, `njucc`, `coah`, `mount laurel`, `njhmfa`, `lihtc`,
`fair housing act`, `fha accessibility`, `section 504`, `ada housing`, `ansi a117`,
`type a unit`, `type b unit`, `affordable housing nj`, `deed restriction`,
`inclusionary zoning`, `nj dca`, `visitability`, `grab bar blocking`,
`affordable housing permit`, `site improvement standards`

## Reference Files

| File | Contents |
|---|---|
| `SKILL.md` | Quick reference tables, decision tree, top pitfalls |
| `references/nj-ucc-rsis.md` | Full UCC and RSIS standards detail |
| `references/uhac-coah.md` | UHAC affordability controls, COAH/Mount Laurel |
| `references/accessibility-fha-504.md` | FHA 7 requirements, Section 504, ADA, ANSI A117.1 |
| `references/njhmfa-lihtc.md` | NJHMFA programs, LIHTC QAP, ENERGY STAR, HOME |
| `references/compliance-checklist.md` | Phase-by-phase checklist, 10 common pitfalls |

## Official Sources

- NJ DCA Codes: https://www.nj.gov/dca/codes/
- NJHMFA: https://www.nj.gov/dca/hmfa/
- HUD Fair Housing: https://www.hud.gov/fairhousing
- U.S. Access Board: https://www.access-board.gov/

## License

MIT
