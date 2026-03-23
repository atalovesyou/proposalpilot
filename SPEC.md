# ProposalPilot — AI Proposals for Freelancers

## One-Liner
Describe your project → get a client-ready proposal in 90 seconds. Win more deals with professional proposals that close.

## Problem
Freelancers lose 30-40% of potential deals because of weak proposals:
- Writing proposals from scratch takes 2-4 hours each
- Generic templates don't stand out
- No idea what pricing to suggest (undercharge or scare clients away)
- Can't track if the client even opened it
- Proposals look unprofessional compared to agencies

## Solution
AI-powered proposal generation that wins deals:
1. **Generate** — Describe the project + client → professional proposal with scope, timeline, pricing, and terms
2. **Price** — AI suggests competitive pricing based on project type, scope, and market rates
3. **Customize** — Multiple proposal styles (minimal, detailed, executive) with smart section toggles
4. **Export** — Download as PDF with your branding (logo, colors, fonts)
5. **Track** — Know when they open it (integrates with GhostTracker)

## Competitive Landscape
| Competitor | Price | Gap |
|-----------|-------|-----|
| Proposify | $49/mo | Expensive, template-based, no AI |
| Better Proposals | $19-29/mo | Good but manual writing |
| PandaDoc | $35-65/mo | Overkill for solo freelancers |
| Qwilr | $35-59/mo | Beautiful but expensive, enterprise focus |
| Bonsai Proposals | $24-39/mo | Bundled with suite, basic templates |
| Canva | Free-$15/mo | Design tool, not proposal-specific |
| Google Docs | Free | Zero structure, unprofessional |

**Our gap:** Nobody does AI-generated proposals from a project description for $0-9/mo. Every competitor requires manual writing or template filling.

## Ecosystem Fit
IntakeBot (qualify client) → **ProposalPilot (win the deal)** → ContractPilot (sign contract) → GhostTracker (track docs) → InvoicePilot (get paid) → ReviewAgent (get review)

**ProposalPilot is the missing revenue-critical step.** IntakeBot qualifies leads, but without a professional proposal, deals die. This bridges the gap.

## MVP Features
- Natural language proposal generation ("Web redesign for a bakery, 3 pages, 4-week timeline, they have $5K budget")
- 3 proposal styles: Minimal (1-page), Detailed (multi-section), Executive (data-heavy)
- Smart sections: Project Overview, Scope of Work, Timeline & Milestones, Pricing (itemized), Terms, About You
- AI pricing suggestions based on project type and scope
- Client-specific customization (tone, formality, industry jargon)
- PDF export with basic branding
- Proposal templates library (Web Dev, Design, Marketing, Consulting, Video, Writing)
- Win/loss tracking dashboard

## Pricing
| Tier | Price | Limits |
|------|-------|--------|
| Free | $0/mo | 3 proposals/month, basic templates, watermark |
| Pro | $9/mo | Unlimited proposals, all styles, no watermark, PDF export |
| Agency | $29/mo | Team proposals, custom branding, analytics, GhostTracker integration |

## Revenue Potential
- TAM: 73M freelancers worldwide × 10% need proposals = 7.3M potential users
- SAM: English-speaking freelancers who bid on projects = ~2M
- Conversion funnel: Free → Pro at 5% = 100K × $9/mo = $10.8M ARR potential
- Realistic Y1: 1,000 paid users × $9/mo = $108K ARR

## Tech Stack
- Frontend: Static HTML + Tailwind + vanilla JS (GitHub Pages)
- Backend: Vercel serverless (shared with other products)
- AI: Claude API for proposal generation
- Export: jsPDF for client-side PDF generation
- Storage: Supabase for proposals + client data
