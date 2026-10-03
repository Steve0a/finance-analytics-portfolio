# Amazon FC Fulfillment Journey

An interactive, single-page web visual that walks through the end-to-end workflow inside an Amazon Fulfillment Center (FC), from inbound truck to outbound delivery. Built as part of Extern Project 308, an analysis of Amazon Fulfillment Center worker feedback.

**Live site:** https://fulfillmentcenterjourney.com

## What it shows
- **Flow View:** each step of the fulfillment process as a card, showing the role, what the role does, the tools it uses, the roles it works with, and a RACI breakdown.
- **Story Mode:** a guided, step-by-step walkthrough with play, pause, previous/next, and speed controls.
- **3D warehouse scene:** an animated view built with Three.js.

## Roles covered
Truck Driver → Receiving Associate → Water Spider → Stower → Picker → Packer → SLAM Associate → Shipping Associate → Delivery Driver, with Problem Solver supporting across the process.

## Why it matters for the project
Mapping how FC roles connect gives context for the worker-feedback analysis (Glassdoor reviews and YouTube worker videos), especially the Schedule & Physical Workload theme. It shows where in the process the pressure points come up.

## Tech
- Single self-contained `index.html` (HTML, CSS, JavaScript, embedded WebP images)
- Three.js r128 (CDN) and Google Fonts (Barlow, Barlow Condensed)
- Hosted on Cloudflare Workers (static assets) with a custom domain

## Run locally
Open `index.html` in any modern browser. No build step is needed.

## Progress log
| Date | Update |
|---|---|
| 2026-10-03 | Deployed to Cloudflare Workers (`amazonfcjourney.steveoamo960.workers.dev`) |
| 2026-10-03 | Registered `fulfillmentcenterjourney.com` and connected it (plus `www.`) to the site |
| 2026-10-03 | Added the project to this portfolio |

## Note
This is an educational portfolio project. It is not affiliated with or endorsed by Amazon. Role descriptions are based on publicly available information.
