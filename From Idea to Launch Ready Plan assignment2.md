# 🚀 AI SEEKHO — Assignment 2
## 💡 From Idea to Launch Ready Product Plan

**Student:** Rehan Mehmood 👨‍💻  
**University:** University of Management and Technology (UMT), Lahore 🎓  
**Program:** BS Computer Science — Year 3 💻  
**Submitted:** August 2026 📅  

---

## 📑 Table of Contents

1. [Part 1: Problem Discovery and Validation](#part-1-problem-discovery-and-validation)
2. [Part 2: Product Definition and Tier Classification](#part-2-product-definition-and-tier-classification)
3. [Part 3: Tech Stack Justification](#part-3-tech-stack-justification)
4. [Part 4: Mobile App vs Web App Decision](#part-4-mobile-app-vs-web-app-decision)
5. [Part 5: SDLC Approach](#part-5-sdlc-approach)
6. [Part 6: Distribution and Go-to-Market Plan](#part-6-distribution-and-go-to-market-plan)
7. [Part 7: Success Criteria](#part-7-success-criteria)
8. [Part 8: Timeline](#part-8-timeline)
9. [Risks and Mitigation](#risks-and-mitigation)
10. [Reflection](#reflection)
11. [Sources / Research Links](#sources--research-links)

---

## 🔍 Part 1: Problem Discovery and Validation

### 📝 Product Overview (Brief)

The product is an AI-powered Home Interior & Home Improvement platform. It serves two sides:

- **Homeowners/customers** 🏡 — who struggle to decide on interior style, visualize it in their actual room, and then execute it by finding the right products and local service providers.
- **Home-improvement businesses** 🏢 — furniture stores, curtain shops, wall-panel suppliers, painters, carpenters, etc. — who need a structured way to receive and manage qualified customer leads.

The long-term vision is a full workflow:

> **📸 Room Capture → 🎨 AI Design Generation → 🛋️ Style Selection → 🛍️ Product/Service Recommendations → 🤝 Local Provider Matching → 🎯 Qualified Lead → 👷 Professional Visit → 📏 Verified Measurement → 💰 Quotation → 🛒 Purchase/Installation**

The MVP is intentionally narrow: upload room photos → AI generates redesign concepts → user selects a design → submits a consultation request → local business receives and manages the lead.

---

### 📊 Demand Signal Method 1: Competitor Landing Page Research

The AI interior design space is genuinely crowded. This is not a reason to abandon the idea — it is evidence that the problem is real and people are actively searching for solutions. The question is whether the *gap* this product addresses is real.

#### 🏆 Key Competitors Researched

**1. RoomGPT** — Direct Competitor 🛋️  
**URL:** [roomgpt.io](https://roomgpt.io)

- **Problem it solves:** Lets users upload a room photo and instantly generates AI-redesigned versions in different styles.
- **Positioning:** "Upload a photo of your room to generate your dream room with AI." Loved by over 4 million users per one third-party review aggregator.
- **Pricing:** Credit-based model. Approximately $9 for 30 credits, $19 for 100 credits, $29 for 200 credits. Pay-per-use, no forced subscription. ([Source: XDA Developers](https://www.xda-developers.com/roomgpt-can-help-you-redesign-your-room/))
- **Free tier:** Yes — limited credits on sign-up.
- **Target audience:** Homeowners, renters, real estate agents seeking quick visual inspiration.
- **Business model:** Pay-per-use credits (no subscription to cancel).
- **Real product matching:** No. Generates images only.
- **Local business connection:** None.
- **CRM / lead generation:** None.
- **Gap:** RoomGPT stops at the image. One detailed third-party review from May 2026 explicitly states: *"The room concept and the actual shopping experience still feel disconnected. The pieces often pull from scattered marketplaces, generic catalogs, or hard-to-verify listings."* ([Source: First Chair Blog](https://www.firstchair.app/blog/roomgpt-alternatives)) — **confirmed by research, not fabricated**. Furthermore, the same source documents a recurring structural weakness: RoomGPT *"frequently adds or removes windows, doors, and structural elements, making results unreliable for actual room planning."*

> **📸 Screenshot to add manually:** RoomGPT homepage and pricing page  
> **🔗 Source:** [https://roomgpt.io](https://roomgpt.io)

---

**2. REimagineHome** — Direct Competitor (with partial product-matching) 🏡  
**URL:** [reimaginehome.ai](https://reimaginehome.ai)

- **Problem it solves:** Virtual staging, interior and exterior redesign, landscaping. Aimed primarily at real estate professionals.
- **Pricing:** Starting at $14/month (Essential). Pro plan at $99/month. ([Source: HomeDesigns.AI comparison](https://homedesigns.ai/go/10-best-ai-interior-design-tools-in-2026-honest-comparison/))
- **Real product matching:** Yes — REimagineHome is noted for its *"Real Products"* feature which links furniture in generated designs to actual purchasable items with retailer links. ([Source: HomeDesigns.AI](https://homedesigns.ai/go/10-best-ai-interior-design-tools-in-2026-honest-comparison/))
- **Local business connection:** None. No local provider directory, no lead workflow.
- **CRM / lead generation:** None — built for individual users and real estate teams, not home-improvement businesses.
- **Free tier:** 30 free images/month after a 7-day trial. ([Source: Pineapple Builder listing](https://www.pineapplebuilder.com/ai-tools/reimagine-home))
- **Gap:** Product-matching exists but is limited to western retail links (West Elm, CB2 style). No local vendor workflow, no lead generation, no CRM for local businesses. Entirely B2C with no B2B side.

> **📸 Screenshot to add manually:** REimagineHome pricing and "Real Products" feature  
> **🔗 Source:** [https://reimaginehome.ai](https://reimaginehome.ai)

---

**3. InteriorAI (interiorai.com)** — Direct Competitor 🖼️  
**URL:** [interiorai.com](https://interiorai.com)

- **Pricing:** $29/month. No free trial. No refund. ([Source: Trustpilot reviews](https://ca.trustpilot.com/review/interiorai.com))
- **Real product matching:** None verified.
- **Local business connection:** None.
- **CRM / lead generation:** None.
- **Gap:** Locked behind a hard paywall with no trial. Multiple Trustpilot 1-star reviews cite *"results were poor and generic"* and *"no trial, no refund, no way to contact anyone"*. ([Source: Trustpilot](https://ca.trustpilot.com/review/interiorai.com)) — a validated user frustration pattern, not an isolated complaint.

---

**4. Planner 5D** — Adjacent Competitor (3D Floor Planning) 📐  
**URL:** [planner5d.com](https://planner5d.com)

- **Problem it solves:** 2D/3D room layout planning, floor plans, furniture placement. More like a design tool than an AI inspiration tool.
- **Pricing:** Free tier available. Paid tiers available (up to ~53% off with annual billing per research). ([Source: GenRoom.io comparison](https://genroom.io/blog/best-ai-interior-design-tools))
- **Real product matching:** No direct product links.
- **Local business connection:** None.
- **Gap:** Complex to use for non-designers. Requires building a floor plan before AI can assist. No lead generation workflow.

---

**5. DecorMatters** — Adjacent Competitor (Social/Gamified) 🎮  
**URL:** [decormatters.com](https://decormatters.com)

- **Problem it solves:** Social design app with gamification — users browse community designs, remix them, use AR to preview furniture.
- **Real product matching:** Furniture links included in some designs.
- **Local business connection:** None.
- **Gap:** Community/entertainment-first, not execution-first. No local provider network, no lead workflow, no business CRM.

---

**6. First Chair** — Adjacent Competitor (Real Furniture Matching) 🪑  
**URL:** [firstchair.app](https://firstchair.app)

- **Positioning:** Every piece in the AI-generated design is real and buyable, pulling from retailers like West Elm, CB2, Crate & Barrel.
- **Real product matching:** Yes — strongest product-matching in the US market per reviewed sources.
- **Local business connection:** None — retail-only, no local providers.
- **Gap:** Only covers purchasable online furniture. No labor services, no local vendor matchmaking, no business CRM, no Pakistani/regional market coverage.

---

#### ⚖️ Competitive Gap Analysis Table

| Capability | Generic AI Room Apps (RoomGPT, InteriorAI) | 3D Planning Tools (Planner 5D) | Product-Matching Tools (REimagineHome, First Chair) | Our Long-Term Vision |
|---|---|---|---|---|
| **AI room redesign** | ✓ | ✓ | ✓ | ✓ |
| **Multiple design styles** | ✓ | ✓ | ✓ | ✓ |
| **Room photo capture** | ✓ | ✓ | ✓ | ✓ |
| **Structural fidelity** | ✗ (frequent complaint) | ✓ | Partial | Target |
| **Real product matching** | ✗ | ✗ | ✓ (western markets) | ✓ |
| **Local business discovery** | ✗ | ✗ | ✗ | ✓ |
| **Qualified lead workflow** | ✗ | ✗ | ✗ | ✓ |
| **Business CRM dashboard** | ✗ | ✗ | ✗ | ✓ |
| **Home visit scheduling** | ✗ | ✗ | ✗ | ✓ |
| **Pakistan / regional market** | ✗ | ✗ | ✗ | ✓ (MVP target) |
| **Full home-improvement journey** | ✗ | Partial | Partial | Long-term vision |

**💡 Research conclusion:** The AI room visualization market is genuinely crowded. The *specific gap* — a workflow that bridges AI inspiration to local provider discovery, qualified leads, and a business-side CRM — is not covered by any tool found during research. This is the strategic differentiator.

---

### 📉 Demand Signal Method 2: Negative Review Mining

Reviews of competitors reveal consistent, repeating problems. These are not cherry-picked — they represent patterns observed across multiple sources.

#### 🛑 Pattern 1: AI Changes Room Structure (Doors, Windows, Walls)

- **Evidence:** A detailed May 2026 comparison of RoomGPT alternatives from First Chair's blog explicitly states RoomGPT *"frequently adds or removes windows, doors, and structural elements, making results unreliable for actual room planning."* ([Source](https://www.firstchair.app/blog/roomgpt-alternatives))
- **Corroboration:** The same issue is acknowledged across multiple comparison articles as a known category-wide limitation.
- **Implication for our product:** If we use AI image generation, we must label outputs as *design concepts*, not realistic renders. Users should expect inspiration-level fidelity, not construction-grade accuracy. This is explicitly built into our product strategy.

#### 🚧 Pattern 2: No Path from Inspiration to Execution

- **Evidence:** First Chair's own positioning directly names this gap: *"The AI interior design market is projected to reach $12.35 billion by 2035, yet most tools still leave you stuck between inspiration and execution."* ([Source](https://www.firstchair.app/blog/roomgpt-alternatives))
- **Corroboration:** Foter (now Decoraid by Foter), a well-established home design platform, restructured itself in October 2025 specifically to address *"purchase anxiety"* and *"choice paralysis"* — directly naming these as the biggest problems in the $300 billion online furniture market. Their CEO stated: *"Customers face two core problems: overwhelming 'choice paralysis' from scrolling through tens of thousands of items, and crippling 'purchase anxiety'—the fear that a product won't fit or match their existing decor."* ([Source: CB Insights / Decoraid by Foter](https://www.cbinsights.com/company/foter/))
- **Implication:** The inspiration-to-execution gap is real, confirmed by an industry pivot from an established company — not just user complaints on app stores.

#### 💸 Pattern 3: Subscription Frustration and No Trial

- **Evidence:** Multiple 1-star Trustpilot reviews on InteriorAI (ca.trustpilot.com/review/interiorai.com) follow a pattern: users pay for a subscription, results are generic or the product breaks, and there is no refund or support. Paraphrased patterns from October and April 2025 reviews: *"Expected much more — results were poor and generic"*, *"No trial, no refund, no support — avoid."*
- **Implication:** Free-tier access for homeowners (or at minimum a free design session) is a competitive advantage. Our monetization strategy correctly focuses on business subscriptions rather than forcing homeowners to pay upfront.

#### 🤯 Pattern 4: Decision Overwhelm (Community Signal, Not App Review)

- **Evidence:** A widely cited Adobe survey of over 1,000 US homeowners found that 49% already use AI for interior design projects, and 51% use AI to test furniture placement before buying — with AI users saving an average of $371 per project. ([Source: Adobe AI Interior Design Survey](https://www.adobe.com/acrobat/resources/ai-interior-design-survey.html)) — This confirms active user demand for AI-assisted design decisions.
- **Corroboration:** Multiple published personal accounts describe the same feeling: *"when it comes to putting it all together in my own space—picking the light fixture and window treatments and rug and table and chairs and art that all work together—I get overwhelmed and freeze."* ([Source: Substack / Book Enthusiast](https://beccafreeman.substack.com/p/how-im-thinking-about-decorating)) This is a widely documented consumer experience, not an isolated anecdote.

#### 📋 Evidence Summary Table

| Signal | Evidence | Source | What it proves |
|---|---|---|---|
| **Structural AI failure** | RoomGPT adds/removes windows and doors | [First Chair Blog, May 2026](https://www.firstchair.app/blog/roomgpt-alternatives) | Design fidelity is a real, documented weakness |
| **Inspiration-execution gap** | Foter pivoted entire business model to fix this exact gap | [CB Insights, Oct 2025](https://www.cbinsights.com/company/foter/) | The problem is large enough to justify a full business pivot |
| **Subscription frustration** | 1-star pattern: poor results, no trial, no refund, no support | [Trustpilot — InteriorAI](https://ca.trustpilot.com/review/interiorai.com) | Business-side monetization is safer than forcing homeowners to pay upfront |
| **Decision overwhelm** | 49% of Americans use AI for interior design; 51% use it to test furniture before buying | [Adobe Survey](https://www.adobe.com/acrobat/resources/ai-interior-design-survey.html) | AI-assisted design decision-making has real, broad demand |
| **No local vendor link** | No competitor found connects AI design to local provider discovery | Competitor research across all tools | The local business-to-consumer lead workflow is an unoccupied position |

---

### 🌍 Demand Signal Method 3: Community and Industry Research

#### 🇵🇰 Pakistan Market Signal

- The Pakistan home decor market is projected to grow at a CAGR of 6.4% from 2025–2031. ([Source: 6Wresearch](https://www.6wresearch.com/industry-report/pakistan-home-decor-market-2020-2026))
- The Pakistan interior design market is experiencing growth driven by urbanization, rising disposable income, and a growing young, design-aware population. ([Source: 6Wresearch Pakistan Interior Design Market](https://www.6wresearch.com/industry-report/pakistan-interior-design-market-outlook))
- Lahore is specifically described as a hub for modern and traditional furniture showrooms with variety and customization. ([Source: NM Furnisher](https://nmfurnisher.com/furniture-in-pakistan-2025/))
- Urban Pakistani households in cities like Lahore and Karachi prefer modern, compact, multifunctional furniture — directly aligned with our target design styles (Modern, Minimal, Contemporary). ([Source: NM Furnisher](https://nmfurnisher.com/furniture-in-pakistan-2025/))

**⚠️ Important caveat:** These are market projections, not verified customer interviews. Actual willingness to use the product — and for businesses to pay for a subscription — must be validated through direct contact with real homeowners and local businesses in Lahore.

#### 🛒 Global Furniture Decision Paralysis Signal

A Trustpilot research report on purchase behavior found that 66% of online shoppers have abandoned a purchase at some point, and the biggest paralysis occurs with *large, expensive items* — with furniture specifically called out. ([Source: Trustpilot — Turn Browsers into Buyers](https://pt.business.trustpilot.com/blog/browsers-to-buyers/tales-from-the-infinite-aisles-real-life-stories-of-shopping-experiences))

This is relevant because our product addresses exactly this moment: the user has seen an AI concept they like, but does not know which specific products to buy or which local business to contact.

#### 👥 Community Verification Note

Specific Reddit threads about Pakistani home design or AI room design apps were not located during research. Reddit community signals exist generally (r/interiordesign, r/malelivingspace, r/femalelivingspace) but no Pakistan-specific verified Reddit discussions were found. This is an honest gap. The decision to proceed should be supplemented with direct user interviews in Lahore before building.

> **📸 Screenshot to add manually:** Pakistan home decor/interior design Facebook group (search: "Home Decor Pakistan" or "Interior Design Lahore" on Facebook)

---

### 💊 E. Painkiller vs Vitamin Classification

**Verdict: Context-dependent. Vitamin for casual users; Painkiller for users actively trying to furnish or renovate a room.**

The research supports a nuanced classification:

**The AI visualization component alone is a vitamin.** RoomGPT has millions of users — but it is a credits-based, occasional-use product. Users browse, enjoy the images, and leave. There is no repeat habit. The Adobe survey confirms that 49% of Americans have used AI for interior design, but using it is not the same as depending on it. A user can visualize their room on RoomGPT, not find anything actionable, and then scroll Instagram or hire a local interior designer anyway. The vitamin framing is honest here.

**The full workflow is closer to a painkiller — but only for users at the right moment.** When someone has just moved into a new apartment, or is renovating a room, and does not know what to do — that is a real, active, frustrating problem. The Foter pivot confirms this: a company with a large existing user base restructured its entire product around *"purchase anxiety"* and *"choice paralysis"* because users were stuck between inspiration and actual buying. A platform that takes a user from *"I have no idea what to do with this room"* to *"Here is a local business that can visit and quote me"* solves a genuinely painful problem at a specific moment in life.

**The business side is clearly painkiller territory.** Local furniture stores and home-improvement businesses in Lahore currently have no structured digital lead-management system. They depend on walk-ins, WhatsApp messages, and word of mouth. A tool that delivers structured, pre-qualified leads with a design brief attached — and a dashboard to track them — solves a real operational problem.

**🎯 Final classification: Vitamin → Painkiller transition product.** The MVP must prove it can convert visualization into action (consultation requests). If it does, the business-side subscription justifies itself.

---

## 📦 Part 2: Product Definition and Tier Classification

### 🎯 Product Definition

This platform serves two audiences: homeowners in Pakistan (initially Lahore) who are overwhelmed by interior design decisions and do not know how to translate inspiration into a real, purchased room — and local home-improvement businesses (furniture stores, curtain shops, wall-panel suppliers, painters, carpenters) who currently lack a structured digital channel for receiving and managing qualified customer leads. The platform guides a homeowner through uploading room photos, selecting a design style, reviewing AI-generated redesign concepts, and submitting a consultation request — which is then delivered as a structured lead to a relevant local business via a CRM dashboard. Why now: AI image generation is sufficiently capable and affordable to generate convincing room redesigns from a photo; the AI interior design app category has proven demand (millions of users on RoomGPT, REimagineHome); product-matching tools are beginning to emerge in western markets; and Pakistan's home decor market is growing with an urbanizing, design-aware young population. The gap between existing tools (pure visualization) and the full workflow (local business discovery, lead management, professional visit) is unoccupied.

### 🏷️ Tier Classification: Standard

The MVP is classified as a **Standard** tier product, not Micro or Premium. Here is the reasoning:

| Dimension | Assessment |
|---|---|
| **Build time** ⏳ | 3–4 weeks for a solo developer building a focused MVP. More than a weekend Micro project; less than a 6-month Premium build. |
| **Complexity** 🧩 | Two user types (customer + business), auth, AI integration, lead workflow, basic CRM dashboard, admin panel — meaningful but scoped. |
| **Revenue model** 💵 | Business subscription (Starter + Pro tiers). Not pay-per-click or one-time purchase. Requires ongoing value delivery. |
| **Revenue gate** 🚪 | Even 5–10 businesses paying a modest monthly subscription makes the MVP financially viable as a test. |
| **Solo-founder feasibility** 👤 | Yes — with modern tooling (Next.js, Supabase, Gemini API, Vercel), a developer of Rehan's skill level can ship the MVP V1 solo in the defined timeframe. |
| **Pricing** 💰 | Business subscription pricing is not finalized and must be validated with actual businesses. A test range of PKR 5,000–15,000/month ($18–$55 USD) is a reasonable hypothesis for a Lahore market pilot, but this requires confirmation through direct conversations before any pricing is announced. |

**Why not Micro?** A Micro product is typically a single-feature utility with simple monetization (e.g., a Gumroad download or a simple tool). This product has two distinct user types, an AI integration pipeline, a lead delivery mechanism, and a CRM dashboard. That scope exceeds Micro.

**Why not Premium?** Premium applies to multi-month builds with complex infrastructure, high-ticket sales, enterprise features, or hardware components. The MVP scope is intentionally narrow — no marketplace, no payment processing, no AI measurement, no advanced CRM. This keeps it in Standard.

---

## 🛠️ Part 3: Tech Stack Justification

### 🏗️ Chosen Stack

`Next.js` · `TypeScript` · `Tailwind CSS` · `shadcn/ui` · `Supabase (PostgreSQL + Auth + Storage)` · `Google Gemini API` · `Vercel`

### ⚖️ Justification by Criterion

#### 1. Time to Market ⏱️

**Next.js** provides full-stack capability (API routes + React frontend) in a single repository, eliminating the overhead of maintaining separate frontend and backend services. A solo developer can ship a complete MVP — auth, database, AI calls, dashboard — without configuring cross-origin setups or separate deployments. **Vercel** deploys Next.js with a single `git push`, removing DevOps from the critical path entirely.

**Supabase** provides a managed PostgreSQL database, authentication, and file storage in one service with a generous free tier. Setting up auth from scratch would cost days. Supabase reduces this to hours.

**shadcn/ui** provides a library of accessible, pre-built React components (tables, forms, dialogs, cards) that can be composed into a professional-looking dashboard quickly. Building UI components from scratch is a time sink the MVP cannot afford.

**Verdict:** This stack allows a single developer to ship a production-ready MVP in 3–4 weeks. Realistic and confirmed by the open-source community using this exact combination for indie SaaS products.

#### 2. Team Size / Skill Fit 👥

All chosen technologies have large ecosystems, strong documentation, and active communities. TypeScript catches type errors at development time, reducing debugging time for a solo developer. The stack does not require specialized DevOps, database administration, or infrastructure expertise to get started. It can be maintained by one developer and extended by a small team without architectural refactoring.

#### 3. Cost at 0–1,000 Users 💳

| Service | Free Tier | Cost Trigger |
|---|---|---|
| **Vercel** | Free for hobby/small projects | Bandwidth and build minutes at scale |
| **Supabase** | 500MB database, 1GB storage, 50,000 MAU on free tier | Upgrades at scale; Pro plan ~$25/month |
| **Supabase Auth** | Included in free tier | Bundled with Supabase |
| **Google Gemini API** | Free tier available; usage-based pricing above threshold | Per-image generation costs money — this is not free at scale |
| **Domain + SSL** | ~$10–15/year | One-time |

**⚠️ Important:** AI image generation is **not free at scale**. Gemini API costs will scale with usage. For MVP validation, usage limits per user (e.g., 3 free design generations per consultation request) are necessary to control costs. This is a real constraint that must be designed into the product from day one — not assumed away.

At 0–1,000 users with reasonable usage limits, the total infrastructure cost is manageable under $50–100/month, possibly less during early validation.

#### 4. Ecosystem Maturity 🌳

- **Auth:** Supabase Auth supports email/password, magic links, and social OAuth. No custom session handling required.
- **Database:** PostgreSQL is the industry standard for relational data. Supabase adds a real-time layer and a REST/GraphQL API.
- **Storage:** Supabase Storage handles image uploads (room photos, AI outputs) with access control built in.
- **AI:** Google Gemini API is accessible with an API key and has well-documented SDKs. For image generation specifically, the team should evaluate whether Gemini's image generation capabilities meet quality requirements, or whether an alternative (Stability AI, Replicate-hosted models) better fits the use case. This requires a technical spike in Phase 1.
- **Deployment:** Vercel has native Next.js support, automatic HTTPS, edge functions, and preview deployments.

#### 5. Scalability Ceiling 📈

The stack will handle early traction well. If the product gains significant scale (tens of thousands of users, hundreds of businesses, high AI generation volume), these components will eventually need revisiting:

- **Supabase** may need to be migrated to a dedicated PostgreSQL instance or a managed provider like Neon or Railway.
- **Vercel** can become expensive at high traffic. A migration to a self-hosted solution or a different CDN is a future option.
- **AI inference** will likely require optimizing prompts, batching, caching previously generated designs, or moving to a more cost-efficient inference provider.
- **The Next.js API routes** can be migrated to a dedicated backend (Express, Hono, or Fastify) if complex background jobs or WebSocket requirements emerge.

None of these migrations are urgent for MVP validation. The rule is: **optimize for learning, not for scale, until scale is proven.**

### 🚫 What We Are NOT Using (And Why)

| Technology | Why Not |
|---|---|
| **MongoDB** | No strong reason to use a document database when our data (leads, users, businesses, designs) is clearly relational. PostgreSQL via Supabase handles it better with full SQL support. |
| **Separate Express backend** | Adds a separate service to deploy, maintain, and debug. Next.js API routes handle all backend logic needed for MVP. Introduce a separate backend only if a specific scaling or processing need justifies it. |
| **Kubernetes / Docker Compose** | Premature. Vercel handles deployment entirely. Kubernetes is for teams managing many microservices at scale — the MVP has one service. |
| **Microservices** | The product does not have the scale or team to justify splitting services. A monorepo monolith is the right starting point. |
| **Redis** | No session management or heavy caching requirements at MVP scale. Add if specific performance bottlenecks appear. |
| **Custom authentication** | Never build auth from scratch when Supabase Auth exists. Custom auth introduces security risks and development time that the MVP cannot absorb. |
| **Custom billing / payment infrastructure** | No customer-facing payments in MVP V1. When business subscriptions are introduced, use Stripe. Never build a custom billing system. |
| **Native mobile app** | Camera access is available via browser on modern smartphones. A native app requires App Store review cycles (1–3 days per update), a separate codebase, and Apple/Google developer fees. Wrong for early validation. |

**💡 Core principle:** The competitive moat should come from distribution, product learning, and the local business network — not from infrastructure complexity. Every hour spent on DevOps is an hour not spent on talking to users.

---

## 📱 Part 4: Mobile App vs Web App Decision

### ⚖️ Decision: Responsive Web App for MVP V1

| Framework Criterion | Assessment for This Product |
|---|---|
| **Distribution** 🔗 | A direct link shared on WhatsApp, Instagram, or Facebook is the primary distribution channel in Pakistan. App Store submission takes days and requires review. A web app link can be shared in seconds. Businesses accessing their lead dashboard are also better served on web (desktop browser). |
| **Hardware / OS access** 📸 | Camera access via `<input type="file" accept="image/*" capture="environment">` works on modern iOS and Android browsers without a native app. Users can photograph their room walls using their phone browser. GPS is not required in MVP V1. |
| **Usage pattern** 🔄 | This is an occasional-use product, not a daily habit app. A user redesigns a room perhaps once every few months. Occasional-use products do not justify the overhead of a native app install. The business dashboard may have more regular use — but it is clearly desktop/web territory. |
| **Iteration speed** ⚡ | MVP V1 will need rapid iteration based on user feedback. A web deployment via Vercel takes seconds. An App Store update takes 1–3 days of review. When you are validating assumptions, iteration speed is survival. |
| **Monetization** 💳 | Business subscriptions will be handled via Stripe on web. No App Store cut (15–30%) applies. Direct checkout is simpler and cheaper. |

### 🔄 When to Reconsider

The decision to build a native or PWA mobile experience becomes worth evaluating when:

- Guided camera capture (scanning all 4 walls in a sequence) is developed in V3+. This benefits significantly from a native camera SDK.
- Repeat usage patterns emerge (businesses using a mobile app for on-site lead management).
- The product has validated traction and can justify a dedicated mobile build.

Until then: **responsive web app, shipped fast, updated continuously.**

---

## ⚙️ Part 5: SDLC Approach

### 🔄 Recommended Model: Agile / Iterative

This product has too many unknowns to follow a Waterfall approach. We do not know:

- Whether homeowners in Lahore will actually submit consultation requests after seeing an AI design.
- Whether local businesses will find the leads valuable enough to pay a subscription.
- Which design styles resonate with the Pakistani market.
- Whether the AI image quality will meet user expectations.

Waterfall assumes requirements are fully known upfront, then develops them sequentially with no room for feedback. For this product, that approach would result in months of development before the first real user ever touches the product — at which point assumptions may have been wrong from day one.

**Agile / iterative SDLC** maps directly to the three-phase blueprint:

---

### 🔎 Phase 1 — Discover & Validate (Days 1–5)

**Goal:** Confirm assumptions before writing a single line of product code.

- Complete competitor research (done above).
- Conduct 3–5 direct interviews with homeowners in Lahore who have recently moved or renovated. Ask: What was frustrating? Did you visit multiple shops? Did you use any app? What would have helped?
- Visit 3–5 local home-improvement businesses in Lahore (furniture shops, curtain stores). Ask: How do you currently get customers? Do you use WhatsApp? Would a structured lead with a design brief be useful? What would you pay for it?
- Write a one-page discovery memo summarizing findings and assumptions to test.
- Define MVP scope precisely (what is in, what is out — already documented above).
- Technical spike: test Gemini API image generation quality for interior room redesign. If quality is insufficient, evaluate Stability AI or Replicate alternatives.

**✅ Deliverable:** Discovery memo + confirmed tech spike result + finalized MVP feature list.

---

### 🏗️ Phase 2 — Build & Ship (Days 6–18)

**Goal:** Ship a working MVP to real users.

- **Days 6–7:** UX wireframes for customer flow (landing → room upload → style select → AI results → consultation form) and business dashboard (login → leads → lead detail → status update).
- **Days 8–9:** Set up Supabase schema, auth, storage. Deploy skeleton to Vercel.
- **Days 10–12:** Build customer-facing flow: room photo upload, style selection UI, AI generation call, swipeable result cards, like/save/select actions.
- **Days 13–14:** Build consultation request form. Connect to Supabase. Build lead delivery to business dashboard.
- **Days 15–16:** Build business dashboard: lead inbox, lead detail view, status update (Contacted / Visit Scheduled / Quotation / Won / Lost).
- **Day 17:** Build admin panel: user list, business list, lead list, basic management.
- **Day 18:** Security review (Supabase RLS policies, auth guards, input validation), cross-device testing, bug fixes.

**🤖 AI as co-builder:** Use Claude/GPT for writing boilerplate code, generating Supabase schema, debugging, and writing test cases — not as a replacement for architectural thinking, but as a productivity multiplier.

---

### 🚀 Phase 3 — Launch & Report (Days 19–25)

**Goal:** Get real behavior data and make evidence-based V2 decisions.

- **Day 19:** Internal bug bash — test every flow end-to-end. Fix critical bugs only.
- **Day 20:** Soft launch — share with 10–20 real homeowners in Lahore via WhatsApp/direct link. Share with 5 local businesses and give them free access.
- **Days 21–23:** Observe usage. Watch: Do users complete the full flow? Where do they drop off? Do businesses log in and check leads? What questions do they ask?
- **Day 24:** Conduct 3–5 short user interviews with homeowners. Conduct 2–3 interviews with businesses.
- **Day 25:** Retrospective — what was validated, what was wrong, what was surprising. Write V2 backlog based on evidence.

**✅ Deliverable:** Retrospective document + V2 feature list ranked by evidence.

---

## 📢 Part 6: Distribution and Go-to-Market Plan

### 🗺️ Framework: Curation → Alignment → Narrative

#### 📍 Where the Target Audience Already Consumes Information

Pakistan homeowners and home-improvement enthusiasts primarily consume content on:

- **Instagram** 📸 — home decor, interior design inspiration, furniture showcases
- **TikTok / YouTube Shorts** 🎥 — before/after room transformations, renovation updates
- **Facebook Groups** 👥 — local community groups for home improvement, buying/selling furniture
- **Pinterest** 📌 — mood board building and style inspiration
- **WhatsApp** 💬 — primary B2B communication channel for local businesses

---

### 👥 Real Communities and Micro-Influencers Identified

The following accounts and communities are real and publicly verifiable. This list does not include fabricated influencers.

| # | Name / Community | Platform | Link | Audience | Why They Fit | Outreach Angle |
|---|---|---|---|---|---|---|
| 1 | **Interior Design Pakistan** | Instagram | [@interiordesignpakistan](https://www.instagram.com/interiordesignpakistan/) | ~5,600 followers — Pakistani home design enthusiasts | Design-focused audience; Lahore and Pakistan coverage | Offer free design consultation credits for followers; propose affiliate arrangement where they earn per lead submitted via their link |
| 2 | **Wallpaper Interior Designs Lahore** | Instagram | [@wallpaper_interior_designs](https://www.instagram.com/wallpaper_interior_designs/) | ~3,600 followers — Lahore-based home interior audience | A Lahore-based business; could be a first beta business partner AND a distribution channel | Propose free business dashboard access; ask them to share the platform with customers |
| 3 | **r/interiordesign** | Reddit | [reddit.com/r/interiordesign](https://www.reddit.com/r/interiordesign/) | 4M+ members globally | Large community for design help and inspiration | Share genuine product story during soft launch; participate in discussions authentically |
| 4 | **r/malelivingspace** | Reddit | [reddit.com/r/malelivingspace](https://www.reddit.com/r/malelivingspace/) | Large community focused on room design for men | Strong overlap with users frustrated by design decisions | Post about the product in show-and-tell or feedback threads |
| 5 | **r/femalelivingspace** | Reddit | [reddit.com/r/femalelivingspace](https://www.reddit.com/r/femalelivingspace/) | Large community focused on room aesthetics | High engagement with design inspiration and product recommendations | Same as above — genuine participation |
| 6 | **Local Facebook Groups (Pakistan)** | Facebook | Search: "Home Decor Pakistan", "Interior Design Lahore", "Furniture Lahore" | Local homeowners, new homebuyers, renovators | Direct local audience in target market | Offer free design sessions; share before/after results |
| 7 | **AI design communities** | Reddit / Twitter/X | r/midjourney, r/StableDiffusion design subs, AI tools Twitter | AI-curious homeowners and tech enthusiasts | Early adopters likely to try new AI tools | Share as a product hunt-style post; explain the local angle |

**📝 Note:** No fabricated influencers are included. Specific large Pakistani home decor influencers were not individually verified during research — direct outreach to find verified micro-influencers in the Lahore home decor space should be conducted during Phase 1 discovery. The Scrumball platform ([scrumball.com](https://www.scrumball.com/ranking/top-home-decor-influencers-on-instagram-in-pakistan)) lists top Pakistani home decor Instagram influencers and can be used to identify suitable candidates.

---

### 🇵🇰 Pakistan-First GTM Strategy

**Why local-first?**

1. **Cold start problem:** The two-sided marketplace requires businesses to be on the platform before customers find it valuable. Starting in one city (Lahore) allows manual onboarding of 5–10 businesses before any marketing spend.
2. **Trust and relationship:** Pakistani B2B sales run on personal relationships. A cold SaaS email will not convert a furniture shop owner. A personal visit, free access, and a demonstration of a real lead will.
3. **Feedback quality:** Proximity allows direct observation of user behavior, which is orders of magnitude more valuable than analytics data alone.
4. **Operational focus:** A single market forces prioritization. You cannot chase Karachi, Islamabad, and Dubai simultaneously while also building the product.

**🏃 Execution steps:**

1. Identify 5–10 Lahore home-improvement businesses through Google Maps, Instagram, and direct visits.
2. Offer free dashboard access for 60 days. No obligation, no credit card.
3. Send test homeowners through the platform (friends, family, social network) to generate initial leads.
4. Interview businesses after 2–3 weeks: Are the leads useful? Would you pay for this? What's missing?
5. If validated: propose Starter subscription pricing.
6. If not validated: iterate on lead quality before scaling.

---

### 🌐 International Expansion Evaluation

The product concept is not Pakistan-specific at the AI or CRM layer. The home improvement problem is universal — people in Dubai, Riyadh, London, and Toronto also struggle with design decisions and local vendor discovery.

**What must be validated before entering any new market:**

| Market | Validation Required |
|---|---|
| **UAE / Saudi Arabia** 🇦🇪🇸🇦 | Local business appetite for SaaS tools; pricing in AED/SAR; WhatsApp as primary B2B channel (already common in Gulf); Arabic language support |
| **UK / USA** 🇬🇧🇺🇸 | Much higher competition from First Chair, REimagineHome, Havenly. Must differentiate on local provider workflow, not just AI visualization. |
| **Canada / Australia** 🇨🇦🇦🇺 | Similar to UK/USA. Local vendor onboarding is the moat, not the AI. |

**🏗️ Architecture for international expansion:**

| Layer | Component |
|---|---|
| **Global** | AI design engine, core UX, CRM framework, lead management logic, SaaS infrastructure |
| **Local** | Vendors, product catalogs, pricing currency, local service provider types, local communication channels (WhatsApp in Pakistan/Gulf; SMS/email in West) |

Each market entry requires: local business partnerships first, then customer marketing. The AI visualization layer can be reused; the local network cannot be copy-pasted.

---

## 🎯 Part 7: Success Criteria

These are targets and criteria for evaluating success — not claims of achievements already made.

| Category | Criterion | Target / Measure | Weight |
|---|---|---|---|
| **Product** 🚀 | Working live MVP | Accessible via public URL, full user flow functional end-to-end | 20% |
| **Product** 🛤️ | Core user flow completed | Homeowner can: upload photos → see AI designs → select → submit consultation form | Required |
| **Validation** 👤 | Real homeowners complete the flow | At least 10 real (non-test, non-team) homeowners complete the full flow | 15% |
| **Validation** 🏢 | Real businesses access the dashboard | At least 3 Lahore-based businesses log in, view leads, and update status | 15% |
| **Validation** 🎤 | User interviews conducted | At least 5 interviews with homeowners; at least 3 with businesses | 10% |
| **Distribution** 📣 | Public launch executed | Shared on at least 3 channels (WhatsApp, Instagram, Facebook group) | 5% |
| **Business** 💰 | Subscription interest signal | At least 1 business verbally expresses willingness to pay for a subscription after trial | 10% |
| **Discipline** 🎯 | Stayed within MVP scope | No marketplace, no payment processing, no advanced CRM shipped in V1 | 10% |
| **Research** 🔬 | Competitor + review mining documented | All 3 demand signal methods completed with real sources | 5% |
| **Reflection** 📝 | Retrospective written | Honest retrospective documents what was validated, what failed, and V2 decisions | 10% |

**⚠️ Important:** A business expressing verbal willingness to pay is a signal, not a commitment. The actual conversion to paid subscriptions happens in V2, after the lead volume and quality are proven. Do not count a business saying "yes sounds good" as revenue — it is only a hypothesis confirmation.

---

## ⏱️ Part 8: Timeline

### 📅 25-Day Plan (Solo Developer)

| Day | Phase | Task |
|---|---|---|
| **1** | Discover | Competitor research finalized; discovery document started |
| **2** | Discover | 3–5 homeowner interviews in Lahore (WhatsApp calls or in-person) |
| **3** | Discover | 3–5 business visits (furniture shops, curtain stores) in Lahore |
| **4** | Discover | Discovery memo written; MVP scope confirmed; Gemini API technical spike |
| **5** | Discover | Tech spike evaluated; AI model and prompt strategy confirmed |
| **6** | Build | UX wireframes: customer flow (5 screens) + business dashboard (4 screens) |
| **7** | Build | Supabase schema setup: users, businesses, rooms, designs, leads, statuses |
| **8** | Build | Supabase Auth integration; Vercel deployment skeleton; environment config |
| **9** | Build | Customer landing page + room type selector + photo upload (4 walls) |
| **10** | Build | Style selection UI (grid/card layout with 10–12 style options) |
| **11** | Build | Gemini API integration: generate AI redesign from photos + style prompt |
| **12** | Build | AI result display: swipeable cards, like/save/select actions, Supabase persistence |
| **13** | Build | Consultation request form: name, phone, location, preferred time, requirements |
| **14** | Build | Lead delivery: form submission → Supabase lead record → business dashboard inbox |
| **15** | Build | Business auth (separate business login flow) + dashboard layout |
| **16** | Build | Business lead inbox: list view, lead detail, selected design preview |
| **17** | Build | Lead status management: Contacted / Visit Scheduled / Visit Done / Quote Sent / Won / Lost |
| **18** | Build | Admin panel: user list, business list, lead list, basic management actions |
| **19** | Build | Supabase RLS policies, auth guards, input validation, security review |
| **20** | Launch | Internal bug bash: test all flows on iOS Safari, Android Chrome, desktop. Fix critical bugs. |
| **21** | Launch | Soft launch: share with 10–20 homeowners (personal network + local WhatsApp groups) |
| **22** | Launch | Give 5 Lahore businesses access; walk through dashboard with them in person or on video call |
| **23** | Launch | Observe usage; note drop-off points, bugs, questions from businesses |
| **24** | Launch | 5 homeowner interviews + 3 business interviews; collect structured feedback |
| **25** | Report | Write retrospective; define V2 backlog ranked by evidence; submit assignment |

---

## ⚠️ Risks and Mitigation

| Risk | Severity | Likelihood | Mitigation |
|---|---|---|---|
| **AI output quality** — AI changes room structure, adds/removes windows, produces unrealistic results | High | High (confirmed by research) | Label all outputs explicitly as *design concepts, not accurate renders*. Use structured prompts to preserve layout. Collect user feedback on each generated design. Evaluate multiple models in technical spike. |
| **No local business adoption** — Businesses don't log in or find leads useless | High | Medium | Manual onboarding with in-person demos. Give free access for 60 days. Start with businesses known through personal network. Quality over quantity: 3 real engaged businesses beats 30 who ignore the product. |
| **Business willingness to pay** — Businesses use the free tier indefinitely but resist subscription | High | Medium–High | Free pilot must have a defined end date. Track lead volume and quality data during pilot. Present ROI evidence before asking for payment. If businesses see one won customer from a lead, the value is demonstrated. |
| **Customer acquisition** — Homeowners don't complete the full flow | High | Medium | Start with personal network for first 20 users. The funnel (upload → designs → form submission) will show exactly where drop-off happens. Iterate on the weakest point. |
| **AI API cost** | Medium | High at scale | Design usage limits from day one (e.g., max 4 designs per consultation request). Cache generated designs instead of regenerating. Monitor API spend daily during early launch. |
| **Marketplace cold start** | Medium | Low (MVP V1 has no marketplace) | Not applicable in MVP V1 — marketplace is explicitly out of scope. |
| **Competition from well-funded tools** | Medium | High | Our moat is not the AI visualization (which is commoditizing). It is the local business network, the lead-to-CRM workflow, and the Pakistan-first distribution. Global tools do not compete in this layer. |
| **Measurement accuracy** (V3+) | Medium | High (confirmed by research) | Explicitly out of scope for MVP V1. When introduced, always label as *estimated dimensions* requiring professional verification before any purchase or construction. |

---

### 💼 Business Model Discussion

The subscription model (rather than commission) is correct for this stage for the reasons stated:

- **Commission requires tracking** whether a sale actually happened, which value the platform created, and managing disputes when a business says the customer bought but the platform didn't refer them. This operational complexity is unsolvable at MVP stage.
- **Subscription is predictable** for both the business and the founder. A business that finds value in the lead flow will renew. One that doesn't will churn — which is the right signal.
- **The value proposition for businesses is clear:** structured leads with a design brief attached, organized in a CRM, with status tracking. This replaces a WhatsApp inbox and a mental tracking system that most small businesses currently use.

**💡 Pricing hypothesis (not validated):** A test range of PKR 5,000–15,000/month ($18–$55 USD) for a Starter plan is a reasonable starting hypothesis for Lahore. This must be validated through direct conversations during Phase 1. Do not announce a price before talking to at least 5 potential business customers.

**📉 Churn risk is real.** If lead volume is low in early months, businesses will not see enough ROI to continue paying. This is why the MVP must generate real leads quickly — the business subscription only works if the homeowner-side of the product works first.

---

## 🧠 Reflection

What surprised me most during validation was how clearly the inspiration-to-execution gap is acknowledged by the industry itself — not just by user complaints, but by a major platform (Foter) pivoting its entire business model around it in late 2025. I expected to find scattered user frustrations; instead I found a named, documented problem that an established company bet its restructuring on. The second surprise was how no tool in the current market — including the ones with real product matching — has built a local business workflow. REimagineHome links to western retailers. First Chair links to Crate & Barrel. Nobody is solving the problem for a furniture shop in Lahore. The third observation: the AI visualization quality problem (doors disappearing, wrong windows) is a confirmed, repeating failure across competitors, not a minor edge case. This means the MVP should deliberately label designs as *concepts* and position the human business visit as the necessary complement — not a bug, but a feature.

---

## 🔗 Sources / Research Links

| Source | URL |
|---|---|
| RoomGPT pricing (XDA Developers) | https://www.xda-developers.com/roomgpt-can-help-you-redesign-your-room/ |
| RoomGPT alternatives + structural failure documentation | https://www.firstchair.app/blog/roomgpt-alternatives |
| REimagineHome pricing + product features | https://homedesigns.ai/go/10-best-ai-interior-design-tools-in-2026-honest-comparison/ |
| REimagineHome overview | https://www.pineapplebuilder.com/ai-tools/reimagine-home |
| InteriorAI Trustpilot reviews (1-star pattern) | https://ca.trustpilot.com/review/interiorai.com |
| Foter → Decoraid pivot (inspiration-execution gap) | https://www.cbinsights.com/company/foter/ |
| Adobe AI interior design survey (49% adoption) | https://www.adobe.com/acrobat/resources/ai-interior-design-survey.html |
| Pakistan Home Decor Market (6.4% CAGR) | https://www.6wresearch.com/industry-report/pakistan-home-decor-market-2020-2026 |
| Pakistan Interior Design Market | https://www.6wresearch.com/industry-report/pakistan-interior-design-market-outlook |
| Pakistan furniture market — Lahore | https://nmfurnisher.com/furniture-in-pakistan-2025/ |
| Purchase paralysis / furniture buying | https://pt.business.trustpilot.com/blog/browsers-to-buyers/tales-from-the-infinite-aisles-real-life-stories-of-shopping-experiences |
| Decision overwhelm (personal account) | https://beccafreeman.substack.com/p/how-im-thinking-about-decorating |
| Best AI interior design tools 2026 | https://genroom.io/blog/best-ai-interior-design-tools |
| Pakistan Instagram influencer rankings (home decor) | https://www.scrumball.com/ranking/top-home-decor-influencers-on-instagram-in-pakistan |
| Interior Design Pakistan (Instagram) | https://www.instagram.com/interiordesignpakistan/ |
| Wallpaper Interior Designs Lahore (Instagram) | https://www.instagram.com/wallpaper_interior_designs/ |
| r/interiordesign | https://www.reddit.com/r/interiordesign/ |
| Global interior design service market | https://www.marketresearchfuture.com/reports/interior-design-service-market-23968 |
| Global home decor market | https://www.marketdataforecast.com/market-reports/home-decor-market |

---

*Document prepared for AI SEEKHO Assignment 2 — August 2026. All competitor data, pricing, and market information sourced from publicly verifiable links as of August 2026. Assumptions are labelled. Unverified claims are noted as requiring validation.*
