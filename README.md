# Jason Erickson

**Data engineer and entrepreneur. I build automation and AI systems that actually work.**

Twin Lakes, CO · Open to roles in applied AI, automation, data & analytics, business/systems analysis, and solutions/sales engineering

I'm a data engineer who ships production systems and an entrepreneur who builds the businesses they run. Eight years at Wells Fargo, where I grew from a business systems role into a senior data engineer, and these days I'm focused on building out my real estate and hospitality portfolio and the AI that operates it. I find the highest-leverage problem, build the system that solves it, and measure whether it actually moved the number.

## What I build (in software)

**An autonomous pricing platform** managing six vacation-rental properties, built solo over roughly two years and running 24/7, directly driving revenue.

- **GPT-4o pricing advisor** that analyzes booking pace, occupancy velocity, seasonality, and lead-time percentiles, and returns structured pricing decisions with natural-language reasoning
- **Deterministic guardrails on the LLM**: floor-price enforcement, lead-time guards, and tier constraints, so the AI suggests but hard rules prevent bad calls
- **Human-in-the-loop approval** over SMS and a React dashboard
- **Around 30 Supabase Edge Functions in production** (Deno/TypeScript): a dependency-ordered daily pricing pipeline, webhook ingestion for bookings and cafe sales, dead-letter retry queues, and the APIs that serve the dashboard, with about 19 running on cron schedules
- **Multi-channel rate sync** to Airbnb, Booking.com, VRBO, and a direct booking site, with Playwright automation where the channel APIs fall short
- Roughly 90K lines of TypeScript and Python; currently in private beta with neighboring property operators before a broader launch

## What I build (in the real world)

I build in atoms as well as bits. I general contracted and built my own home at 9,700 feet, on site every day doing all the finish work myself. I built out a coffee shop by hand, the electrical, the plumbing, and the cabinetry, and took it through every health-department requirement. And I run a real estate and hospitality portfolio: a mountain lodge, short-term rentals, and that coffee shop, all of which the pricing platform above helps keep running.

## Background

- **Wells Fargo (8 years)**: joined as a Business Systems Consultant and grew into a Senior Data Engineer. Built ETL pipelines in SQL and SSIS, regulatory and compliance reporting, data-quality and validation frameworks, and Tableau reporting used by 20+ teams, all under real regulatory constraints (PII, audit). Automated 2,800+ hours of manual work in my first year, with tools the whole team adopted.
- **Founder, Mobile Ad Point**: grew a mobile advertising business to $1.8M in revenue.

## Tooling

Python · TypeScript · OpenAI & Claude APIs · prompt engineering · agentic workflows · RAG · React · Supabase / PostgreSQL · FastAPI · REST APIs · SQL · ETL · Playwright · Twilio · Square
