AI SEEKHO
by AI Club UMT
Assignment 1 — Session 1


Part 1 — Agentic IDE Research
Below are the five leading agentic coding tools researched in detail: what each is, core features, codebase integration, pricing, differentiators, and an honest take on strengths/limitations/best use case.

1. Cursor
What it is: Cursor is an AI-native code editor forked from VS Code, built by Anysphere. It has grown from a smart autocomplete tool into a full agentic development platform.

Core Features
•	Agent mode for autonomous multi-step coding tasks, plus Composer for coordinated multi-file edits
•	Cloud Agents that run in isolated cloud VMs with terminal, browser, and desktop access, working across repos asynchronously
•	Deep codebase indexing using a custom embedding model for accurate context retrieval across large repositories
•	Native terminal access, in-editor PR review, and support for parallel background agents
•	Tab-based predictive autocomplete alongside chat/ask/edit modes

Codebase Integration
Cursor indexes the entire codebase with hashed file structures and embeddings for fast semantic search. It has native Model Context Protocol (MCP) support (a public registry with 200+ community servers), plus VS Code-style extensions and @ mentions to pull in files, docs, or external tools like GitHub, Figma, Linear, and Slack.

Pricing
Free Hobby tier with limited completions. Pro is $20/month (~$16/month annual) including a $20 monthly credit pool for premium models; Business/Teams is $40/user/month with SSO and centralized billing. Manually picking frontier models (Claude, GPT, Opus) draws down the credit pool, while Auto mode is unmetered.
Key Differentiator
Its biggest edge is being a mature, VS Code-familiar editor with the deepest ecosystem of integrations (200+ MCP servers) and genuinely fast, precise in-editor multi-file edits — it feels like an IDE first, agent second, which lowers the learning curve versus fully agent-first tools.
My Take
Strength: best balance of hands-on control and agent autonomy for developers who still want to review code line-by-line. Limitation: credit-based pricing can spike unpredictably once you go beyond Auto mode, and it's not ideal for zero-cloud/air-gapped environments. Best use case: day-to-day professional development on medium-to-large codebases where a developer wants tight, reviewable AI assistance rather than full delegation.
 
2. Claude Code
What it is: Claude Code is Anthropic's agentic coding tool, available as a CLI, IDE extension, and desktop app, built around the Claude model family (Sonnet and Opus).
Core Features
•	Deep agentic loop: reads a whole codebase, plans, edits multiple files, runs tests, and iterates autonomously
•	Long-context handling for large codebases, with automatic context-window compaction in agentic sessions
•	Full terminal access for running builds, tests, and shell commands as part of its workflow
•	CLAUDE.md project-level instructions, slash commands, and hooks for customizing agent behavior
•	Bundled with Claude's broader ecosystem: Skills, Cowork, and chat access
Codebase Integration
Claude Code has native MCP support, letting it connect to GitHub, Jira, databases, browsers, and thousands of other tools; each connected server adds its tool definitions to context, so heavy MCP use requires managing token overhead. It also supports prompt caching to cut repeated-context costs.
Pricing
Included with paid Claude plans: Pro at $20/month (Sonnet default), Max at $100 or $200/month (Opus default, higher usage caps), Team seats around $20-25/seat/month (annual), and pay-as-you-go API billing (roughly $1-$25 per million tokens depending on model). A limited free/evaluation tier also exists.
Key Differentiator
Its differentiator is raw agentic coding performance — it has led SWE-bench Verified benchmarks — combined with tight integration into Anthropic's own frontier models, making it the strongest choice when model reasoning quality matters more than IDE polish.
My Take
Strength: excellent for complex, large-scope refactors and long autonomous coding sessions with strong reasoning. Limitation: cost can escalate quickly in long sessions or with many MCP servers due to token-based billing, and it's more terminal/CLI-centric than a traditional GUI IDE. Best use case: professional engineers doing large or difficult refactors, backend-heavy work, or automation pipelines where accuracy outweighs a polished visual interface.
 
3. Antigravity (Google)
What it is: Google Antigravity is Google's agent-first development platform, launched alongside Gemini 3 in November 2025 and expanded into a full platform (desktop app, CLI, SDK) as Antigravity 2.0 at Google I/O 2026.
Core Features
•	Agent Manager: a dedicated surface to spawn, orchestrate, and observe multiple agents working asynchronously across workspaces, not just a sidebar chatbot
•	Browser Subagent: spins up a real Chrome instance to click, fill forms, take screenshots, and verify that built applications actually work
•	Editor View for hands-on tab completions and inline commands alongside the async Manager Surface
•	Agents generate reviewable Artifacts (task lists, plans, screenshots, recordings) so users can verify logic without reading raw tool calls
•	Support for local model execution (e.g., via Ollama) for privacy-conscious or offline workflows
Codebase Integration
Antigravity is a VS Code fork that supports Gemini 3 alongside Claude Sonnet/Opus and GPT models in one environment. It has an Antigravity CLI with Agent Skills, Hooks, Subagents, and plugins (its version of extensions), plus an SDK for building custom agents; native integrations lean heavily toward Google Cloud (Cloud Run, Firebase).
Pricing
Free to start for individuals, with rate-limited usage; broader access ties into Google's AI Pro (~$20/month) and AI Ultra (~$250/month) subscription tiers. Pricing for heavy platform use is still evolving as the product is in public preview.
Key Differentiator
Its standout feature is genuine multi-agent parallelism with real browser-based verification — agents don't just write code, they test it live in a browser and report back with visual proof, which none of the other four tools do natively.
My Take
Strength: uniquely strong at end-to-end autonomous app building with self-verification. Limitation: still public preview with reported lag on large contexts, an unpredictable credit system, and Google Cloud-biased integrations. Best use case: rapid prototyping and 'vibe coding' full-stack apps or frontend work where visual/UI correctness matters and a developer wants to supervise rather than write code directly.
 
4. Codex (OpenAI)
What it is: OpenAI Codex (the 2025-relaunched version, unrelated to the deprecated 2021 model) is a cloud-based autonomous coding agent built on the GPT-5-Codex model family, accessible via ChatGPT, CLI, VS Code extension, and iOS.
Core Features
•	Delegated task execution: given a task in plain English, it works in an isolated sandbox for minutes to hours before reporting back with a diff, logs, and test results
•	Parallel cloud tasks — multiple Codex jobs can run simultaneously in separate containers
•	Automatic code review and PR generation, with Slack integration for team workflows
•	CLI and IDE extension for terminal-first or in-editor workflows alongside the cloud dashboard
•	Scores 70%+ on SWE-bench Verified, competitive with the top agentic coding tools
Codebase Integration
Codex integrates through ChatGPT's ecosystem and a standalone open-source CLI; it works inside VS Code and, as of mid-2026, Amazon Bedrock. It doesn't have Cursor's or Claude Code's breadth of third-party MCP ecosystem yet, but supports tool use within its sandboxed agent runs.
Pricing
Free and Go ($8/month) for light use, Plus at $20/month (first practical tier for regular use), Pro at $100/month (5x capacity) or $200/month (20x capacity), and Business/Enterprise seat-based billing. Usage is metered by token-based credits on a rolling 5-hour window rather than a flat message count.
Key Differentiator
Its differentiator is true 'fire-and-forget' delegation — you hand off a whole unit of work and Codex completes it end-to-end in an isolated sandbox while you do something else, more like assigning a task to a remote engineer than pair-programming.
My Take
Strength: excellent for well-defined, isolated tasks (bug fixes, feature additions, dependency upgrades) that don't need constant supervision. Limitation: the 5-hour rolling usage window can be exhausted quickly on large repositories, and it's less suited to exploratory, back-and-forth coding. Best use case: teams that want to batch out multiple well-scoped tickets in parallel without babysitting each one.
 
5. Windsurf (Codeium) — now Devin Desktop
What it is: Windsurf began as Codeium, an AI autocomplete plugin, then became a standalone AI-native IDE (a VS Code fork) built around its Cascade agent. In late 2025/early 2026 it was acquired by Cognition (makers of Devin) and, on June 2, 2026, was rebranded to Devin Desktop, folding Cascade's local agent together with Devin's cloud agent under one roof.
Core Features
•	Cascade: an agentic assistant with deep contextual/codebase awareness for multi-file edits and proactive debugging
•	Agent Command Center: a Kanban-style view showing every local and cloud agent's status (Running, Waiting for Review, Done)
•	Spaces: groups sessions, PRs, files, and Git worktrees so multiple agents can share context on the same task
•	One-click hand-off from local Cascade planning to a Devin cloud VM for autonomous execution
•	Unlimited Tab autocomplete on every plan, including Free, historically one of the most generous free tiers in the category
Codebase Integration
It runs on Cognition's proprietary SWE-1.6 model and supports the Agent Client Protocol (ACP), reducing lock-in to a single editor. Model access has historically been managed through Codeium's own infrastructure rather than bring-your-own-key, unlike Cursor.
Pricing
Pricing was overhauled in 2026: the old 500-prompt credit pool was replaced by daily/weekly usage quotas, and Pro moved from $15 to $20/month, now matching Cursor. A free tier remains available for testing Cascade and SWE-1.6.
Key Differentiator
Its differentiator is the fusion of a local, flow-aware agent (Cascade) with Devin's autonomous cloud execution in a single 'Agent Command Center' — effectively treating the IDE as a coordination hub for many agents at once, local and remote, rather than a single in-editor assistant.
My Take
Strength: strong multi-agent coordination view and competitive free tier, good for developers juggling several tasks simultaneously. Limitation: still working through post-rebrand rough edges (autocomplete lag on large projects, heavier CPU use) and less mature than Cursor for surgical single-file edits. Best use case: developers or small teams who want one dashboard to track and hand off work between quick local edits and longer autonomous cloud agent runs.
 
Part 2 — Prompt Engineering: Real-Life Scenarios
Each prompt below follows the 4-part structure from Session 1 — Role, Context, Main, Conclusion — with enough real-world detail to produce a genuinely useful AI response.
Scenario 1: The Budget Trip
Role: Act as an experienced budget travel planner who specializes in short domestic trips within Pakistan and is skilled at building realistic, cost-conscious itineraries.
Context: I have a total budget of PKR 15,000 for the entire trip, 3 free days, and will be traveling with 2 friends (3 people total, so the budget may need to be understood as either per-person or total — assume PKR 15,000 is my personal share unless I say otherwise, and each friend has a similar budget). We cannot ask our parents for extra money, so the plan must be fully self-funded and realistic about transport, food, and lodging costs in Pakistan. I'm open to mountains, a city, or the coast — recommend whichever destination type actually fits the budget and timeframe best, including one-way and return travel time within the 3 days.
Main: Build me a realistic day-by-day itinerary (Day 1, Day 2, Day 3) that includes: the specific destination and why it fits the budget, exact transport options (bus/van/train) with approximate fares, where to stay (hostel, guesthouse, or shared room) with approximate nightly cost, and what to eat each day with approximate costs, so the total stays within PKR 15,000 per person including a small buffer for emergencies.
Conclusion: Present the answer as a day-by-day table or clearly labeled sections (Day 1/2/3), with a running cost breakdown and a final total at the end. Keep the tone practical and encouraging, avoid vague suggestions like 'find affordable options' — give specific place names, rough prices in PKR, and backup options in case something is fully booked.
 Response:
Day	Time / Slot	Activity / Location	Transport & Commute	Food & Expenses	Running Total (PKR)
Day 1	07:00 AM – 11:30 AM	Board Economy Train from Lahore to Rawalpindi	Train: PKR 1,200	—	1,200
	12:00 PM – 01:00 PM	Arrive in Rawalpindi & drop bags at Hostel (Coyote Den / Backpackers)	Local Wagon/Rickshaw: PKR 150	—	1,350
	01:00 PM – 02:00 PM	Traditional lunch at Raja Bazaar or Saddar	—	Lunch: PKR 300	1,650
	02:30 PM – 05:30 PM	Explore Raja Bazaar, Haveli Sujan Singh, Metro to Islamabad	Metro Bus: PKR 50	—	1,700
	06:00 PM – 08:30 PM	Evening walk at Saidpur Village	—	—	1,700
	09:00 PM onwards	Dinner & Check-in to Hostel (Night 1)	—	Dinner: PKR 400


Hostel: PKR 1,500	3,600
Day 2	08:30 AM – 09:30 AM	Heavy local breakfast (Halwa Puri)	—	Breakfast: PKR 250	3,850
	09:30 AM – 12:30 PM	Morning hike on Trail 3 or Trail 5	—	—	3,850
	01:00 PM – 02:00 PM	Lunch near Super Market (F-6)	—	Lunch: PKR 450	4,300
	02:00 PM – 05:00 PM	Visit Lok Virsa Museum	—	Entry: PKR 100	4,400
	05:30 PM – 08:00 PM	Pir Sohawa Road viewpoint sunset & tea	Shared Cab: PKR 300	Tea: PKR 100	4,800
	08:45 PM onwards	Dinner & Second night at Hostel (Night 2)	—	Dinner: PKR 600


Hostel: PKR 1,500	6,900
Day 3	08:30 AM – 09:30 AM	Paratha and Omelette breakfast	—	Breakfast: PKR 200	7,100
	09:30 AM – 11:30 AM	Explore Shah Faisal Mosque	Metro/Transit: PKR 100	—	7,200
	12:00 PM – 02:00 PM	Stroll at Rawal Lake / Lake View Park	Transport Share: PKR 50	—	7,250
	02:30 PM – 03:30 PM	Quick wrap/rolls near Faizabad	—	Lunch: PKR 350	7,600
	04:00 PM – 08:30 PM	Return Journey to Lahore	Train/Bus: PKR 1,200	—	8,800
	Night Arrival	Arrival in Lahore & light snack	—	Snack: PKR 300	9,100
Buffer	Emergency	Emergency cash reserve for unexpected fare spikes	—	—	12,100 (or up to 15,000)

 
Scenario 2: The Difficult Message
Role: Act as a calm, assertive communication coach who helps tenants write firm but respectful messages to landlords that get results without damaging the relationship.
Context: My water heater has been broken for 2 weeks and I need it fixed before winter. I've already asked my landlord twice verbally with no action taken. I plan to renew my lease with this landlord, so the message needs to apply real pressure and set a clear deadline while staying polite and professional — I don't want to sound like I'm making an empty threat or burning the relationship.
Main: Write a message I can send over WhatsApp or email that: references the two prior verbal requests and the 2-week timeline, clearly states the urgency (winter coming, no hot water), requests a specific action and deadline (e.g., repair within 3-5 days), and mentions — respectfully, not aggressively — that I may need to explore other options (like a tenant rights inquiry) if it isn't addressed, without sounding confrontational.
Conclusion: Give me two versions: one for WhatsApp (short, direct, 4-6 sentences) and one for email (slightly more formal, with a subject line). Keep the tone firm but respectful throughout, and avoid legal jargon or aggressive language.
 Response: 
		Here is your messaging strategy as a calm, assertive communication coach. The goal here is to shift the landlord from passive avoidance to active resolution by establishing a written paper trail, citing the elapsed time, and introducing consequences without crossing into hostility.
Communication Overview & Strategy
Feature	WhatsApp Version	Email Version
Length & Tone	Short, direct, 4–6 sentences; casual medium, professional text.	Slightly more formal; includes a structured subject line and polite sign-off.
Key Objectives Met	Establishes 2-week timeline, references prior verbal talks, sets a 4-day deadline, mentions upcoming winter urgency.	Adds a formal paper trail, explicitly outlines next steps (tenant resource check), and keeps lease renewal prospects intact.
Best Used For	Quick notifications and keeping the pressure immediate on mobile.	Creating an official, documented record of maintenance requests.
Version 1: WhatsApp Message (Short & Direct)
Hi [Landlord's Name], I’m following up on our two previous conversations regarding the broken water heater at the property. It’s now been two weeks without hot water, and with winter approaching, getting this resolved urgently is critical for my household. Could you please arrange for a repair technician to fix or replace the unit within the next 4 days (by [Day of week, e.g., Friday])? I really enjoy living here and plan to renew my lease, but I do need to ensure basic habitability standards are met so I don't have to look into local tenant advisory resources for guidance. Thanks for your prompt action on this.
Version 2: Email Message (Formal & Documented)
Subject: Urgent Maintenance Follow-up: Water Heater Repair – [Your Apartment/House Number]
Dear [Landlord's Name],
I hope you are doing well.
I am writing to formally follow up on my two previous verbal requests regarding the broken water heater at the property. As it has now been two weeks without hot water, the situation is becoming increasingly difficult to manage as colder weather approaches.
Could you please confirm when a technician will be sent to repair or replace the unit? I would appreciate it if this could be scheduled and completed within the next 4 to 5 days (by [Date]).
I truly value living here, take great care of the property, and look forward to renewing my lease soon. However, I want to ensure that basic living requirements are addressed so that I don't feel the need to consult local tenant advocacy channels for formal guidance on habitability rights.
Thank you for your prompt attention and cooperation in getting this resolved this week.
Best regards,
[Your Name]
[Your Contact Information]


Scenario 3: The Impossible Schedule
Role: Act as a productivity coach and time-management expert who specializes in realistic scheduling for busy university students, factoring in energy levels rather than just free hours.
Context: I'm a 6th-semester student handling 5 courses, a part-time job (15 hrs/week), a side project with a deadline in 3 weeks, and I want to start going to the gym 4x/week. I've tried making schedules before and consistently fail to stick to them — likely because past schedules only looked at free time slots and ignored when I'm actually mentally or physically able to focus, study, or work out.
Main: Design a realistic weekly timetable (Monday-Sunday) that allocates time for classes, part-time work, side-project deadline work, gym sessions, study/assignments, and rest — while explicitly accounting for typical energy dips (e.g., avoid scheduling deep-focus work right after a long shift or late at night) and building in buffer time for the schedule to actually be sustainable, not just theoretically complete.
Conclusion: Present it as a day-by-day weekly table with time blocks and a short note on the reasoning behind placing high-focus tasks (side project, hard coursework) at higher-energy times and lower-focus tasks (chores, light review, gym) at lower-energy times. Keep it realistic — don't overfill every hour — and add 2-3 tips for sticking to it when the week gets chaotic.
 
Response : 
		As your productivity coach, let's address why your past schedules failed: you were treating your time like a rigid machine instead of managing your energy like a finite human resource. Trying to force deep-focus coding or complex university studies when your brain is already drained from a work shift or late-night classes is a recipe for burnout and immediate schedule abandonment.
As a 6th-semester student balancing 5 courses, a 15-hour/week job, a 3-week side project deadline (Mind Mate AI), and a 4x/week fitness goal, success relies entirely on matching your tasks to your biological peak and trough energy states.
Energy-Aligned Weekly Master Table
Day	Morning Peak Energy (08:00 AM – 12:00 PM)	Afternoon Mid Energy (12:00 PM – 05:00 PM)	Evening Low-to-Moderate Energy (05:00 PM – 10:00 PM)
Monday	University Classes & Light Campus Study	Part-Time Work (15 hrs total structure spread out)	Gym Session (45 min) + Chill / Rest
Tuesday	High-Focus Side Project (Mind Mate AI)	University Classes	Light Review / Reading + Buffer Time
Wednesday	University Classes	Part-Time Work	Gym Session + Early Sleep
Thursday	High-Focus Side Project (Mind Mate AI)	University Classes	Low-Energy Admin Tasks / Chores
Friday	University Classes	Light Assignment Prep	Gym Session + Social / Rest
Saturday	Deep Study Block (Assignments / Exams)	Free / Buffer Afternoon	Gym Session (Weekend Slot) + Relax
Sunday	Meal Prep & Life Admin / Total Rest	Side Project Sprint (2 hrs)	Social / Unwind & Weekly Reset
Detailed Day-by-Day Time Blocks & Reasoning
•	Monday
o	08:00 AM – 12:00 PM: University Classes (High cognitive alertness for lectures).
o	01:00 PM – 04:00 PM: Part-Time Work block.
o	05:30 PM – 06:30 PM: Gym session (great physical outlet to burn off post-work lethargy).
o	Reasoning: Work comes after morning classes when your brain is shifting gears, and the gym acts as a hard boundary before a restful evening.
•	Tuesday
o	08:30 AM – 11:30 AM: Side Project (Mind Mate AI) — Placed during your freshest morning window so creative coding and problem-solving get your absolute best energy.
o	12:30 PM – 04:30 PM: University Classes.
o	07:00 PM – 08:30 PM: Light course reading or flashcard review.
o	Reasoning: Tackling high-priority creative work before classes ensure it actually gets done rather than being pushed off when tired.
•	Wednesday
o	08:00 AM – 12:00 PM: University Classes.
o	01:00 PM – 04:00 PM: Part-Time Work block.
o	06:00 PM – 07:00 PM: Gym session.
o	Reasoning: Structuring a mirror day to Monday keeps your weekly routine predictable and builds reliable habits.
•	Thursday
o	08:30 AM – 11:30 AM: Side Project (Mind Mate AI) core development sprint.
o	12:30 PM – 04:30 PM: University Classes / Group assignments.
o	Evening: Completely free of heavy tasks to prevent midweek burnout.
o	Reasoning: Spacing out two focused side project blocks per week ensures steady progress toward your 3-week deadline without cramming.
•	Friday
o	08:00 AM – 12:00 PM: University Classes.
o	01:00 PM – 03:00 PM: Lightweight coursework / clearing pending emails.
o	05:30 PM – 06:30 PM: Gym session (closing out the 4-day weekly fitness target).
o	Reasoning: Keeping Friday afternoons light ensures you aren't resentful heading into the weekend.
•	Saturday
o	09:30 AM – 12:30 PM: Deep Study Block for your hardest course or major upcoming assignment.
o	Afternoon: Open buffer time for social life, errands, or catching up.
o	05:00 PM – 06:00 PM: Make-up gym session if any weekday was missed.
•	Sunday
o	Morning: Rest, sleep in, and meal prep.
o	03:00 PM – 05:00 PM: Final side project check-in and task mapping for the upcoming week.
o	Evening: Total wind-down.
The Energy Blueprint: Why This Layout Works
•	Peak Energy (Mornings): Reserved for high-cognition tasks like coding for your side project, difficult coding logic, or preparing for tough university exams. When your executive function is sharpest, these tasks take half the time.
•	Mid-to-Low Energy (Afternoons/Evenings): Channelled into structured routines like attending classes, going to work (where external momentum keeps you moving), or physical movement like the gym (which spikes dopamine when mental energy is low).
3 Golden Rules to Stick to the Schedule When Chaos Hits
•	Rule 1: Build a "Shame-Free" Buffer Block If an unexpected assignment or work emergency wrecks a Tuesday or Wednesday slot, do not scrap the whole schedule. Use Saturday afternoon as an automatic overflow valve to absorb spilled-over tasks.
•	Rule 2: Protect the Transition Windows Never transition directly from a 3-hour work shift into deep coding without a 20-minute physical reset (a walk, a shower, or a snack). Cognitive friction happens when you switch contexts with zero downtime.
•	Rule 3: Lower the Bar to Raise Consistency On days when you feel completely burnt out, invoke the 10-Minute Rule: tell yourself you only have to work on your side project or study for 10 minutes. Over 80% of the time, inertia takes over and you will finish the block; if not, you gave yourself permission to rest without guilt.


Scenario 4: The Broke Student Meal Plan
Role: Act as a nutrition-conscious meal planner who specializes in low-budget, dorm/hostel-friendly cooking with minimal equipment.
Context: I have PKR 8,000/month for food, I cook for myself in a hostel/shared kitchen with only a stove and a small fridge (no oven, no full-size kitchen), and I want to stop relying on instant noodles and fast food because my energy and focus have been dropping. I need meals that are quick to cook, don't need special equipment, and use ingredients that are easy to find and store in a small fridge.
Main: Build me a 7-day meal plan (breakfast, lunch, dinner) using simple stove-top cooking, along with a complete grocery list with approximate PKR prices for each item, structured so the total cost stays within PKR 8,000 for the month (assume the 7-day plan repeats roughly 4 times, and note where I can buy in bulk to save money). Prioritize meals with better nutritional balance than instant noodles - more protein, some vegetables - while keeping prep simple.
Conclusion: Present the answer as a 7-day table (Day, Breakfast, Lunch, Dinner) followed by a grocery list grouped by category (grains, protein, vegetables, spices/pantry) with estimated PKR prices and a total. Keep instructions simple enough for a beginner cook, and flag any items that need refrigeration versus pantry storage.
Response: 
		As your nutrition-conscious meal planner, let’s upgrade your fuel. Living on instant noodles drains your energy because they are pure, empty refined carbs with zero protein or micronutrients.
With an 8,000 PKR monthly food budget (~2,000 PKR per week) and just a single stove burner and a small hostel fridge, you can easily cook high-protein, brain-boosting meals. The strategy relies on rotating affordable, nutrient-dense staples like eggs, lentils (daal), chickpeas (chana), seasonal vegetables, and whole wheat rotis or rice.
7-Day Broke Student Meal Plan
Day	Breakfast	Lunch	Dinner
Day 1	2 Scrambled Eggs + 2 Wheat Bread Slices + Tea/Coffee	Boiled Chickpea Salad (Chana Chaat with onions, tomatoes, lemon)	Moong Daal + Boiled Rice + Sliced Cucumber
Day 2	Omelette (1 egg, onions, green chili) + 1 Paratha or Roti	Leftover Moong Daal + Boiled Rice	Potato & Peas Bhujia (Aloo Matar sabzi) + 2 Rotis
Day 3	2 Boiled Eggs + 2 Wheat Bread Slices	Leftover Aloo Matar + Roti	Masoor Daal (Red lentils) + Boiled Rice
Day 4	Omelette (1 egg) + 1 Roti	Leftover Masoor Daal + Boiled Rice	Egg Fried Rice (Made with 2 eggs, leftover rice, frozen/fresh peas)
Day 5	2 Scrambled Eggs + 2 Wheat Bread Slices + Tea/Coffee	Potato & Chickpea Salan + Roti	Chana Daal (Split bengal gram) + Boiled Rice
Day 6	French Toast (1 egg, milk splash, 2 bread slices)	Leftover Chana Daal + Roti	Simple Chicken & Potato Salan (using a small portion of budget chicken) + Roti
Day 7	2 Boiled Eggs + 1 Roti	Leftover Chicken Salan + Roti	Mixed Vegetable Stir-Fry (Cabbage, carrots, potato) + 2 Rotis
Complete Monthly Grocery List & Estimated Pricing
Buying your grains, lentils, and dry pantry items in bulk from a local wholesale market (mandi or large grocery store) stretches your 8,000 PKR budget to comfortably cover the full month.
1. Grains & Carbs (Pantry Storage)
•	Rice (Super Basmati or Karnal broken): 3 kg — PKR 900
•	Wheat Flour (Atta): 5 kg bag (or store-bought ready parathas/rotis if preferred, but flour is cheaper) — PKR 750
•	Bread (Wheat loaves): 4 packs over the month — PKR 520
2. Proteins (Refrigeration Needed for Eggs & Meat)
•	Eggs: 3 dozen (36 eggs total for breakfasts and cooking) — PKR 1,100
•	Moong Daal (Yellow lentils): 1 kg — PKR 350
•	Masoor Daal (Red lentils): 1 kg — PKR 320
•	Chana Daal (Split chickpeas): 1 kg — PKR 300
•	White Chickpeas (Safed Chana): 1 kg — PKR 350
•	Chicken (Curry cut, small portions): 1 kg (used across 2 weeks for protein boosts) — PKR 850
3. Vegetables & Fresh Produce (Store in Small Fridge / Cool Corner)
•	Onions: 3 kg — PKR 300
•	Tomatoes: 2 kg — PKR 250
•	Potatoes: 4 kg (great cheap energy source) — PKR 350
•	Green Chillies & Fresh Coriander: Weekly bundle — PKR 150
•	Seasonal Veggies (Cabbage/Peas/Carrots): 2 kg total — PKR 300
•	Lemons: 1/2 kg — PKR 100
4. Pantry, Oils & Spices (Pantry Storage)
•	Cooking Oil / Ghee: 1 Liter pouch — PKR 550
•	Basic Spices (Salt, Red Chili Powder, Turmeric/Haldi, Cumin/Zeera): Small starter packets — PKR 350
•	Tea Leaves & Sugar: Small pack for morning energy — PKR 300
•	Total Estimated Monthly Spend: ~PKR 8,000
Student Cooking & Storage Quick Tips
•	Fridge vs. Pantry: Keep eggs, leftover cooked daals, and cut vegetables inside your small hostel fridge. Grains (rice, flour, lentils), oil, onions, potatoes, and spices can safely live in a dry corner or shelf outside the fridge.
•	Batch Cooking Hack: When you boil a batch of daal or chana, make enough for two meals. It saves stove gas/electricity and cuts your daily cooking time in half.
 

Scenario 5: The Scholarship Interview
Role: Act as a professional interview coach who has helped many students prepare for competitive scholarship interviews, especially with panels that ask about weaknesses, future plans, and why the candidate deserves the award.
Context: I've been shortlisted for a scholarship interview in 5 days. I know the panel is likely to ask about my weaknesses, my 5-year plan, and why I deserve the scholarship over other applicants. I tend to freeze up under pressure and ramble instead of giving clear, confident answers, so I need practice handling these specific question types under simulated pressure, not just generic interview tips.
Main: Run a mock interview with me: ask me the likely questions one at a time (including follow-up/pressure questions the way a real panel would), wait for my answer each time, then give me specific feedback on clarity, structure, and confidence after each answer - point out where I rambled or was vague, and suggest a tighter way to phrase the answer. Cover at minimum: a weakness question, the 5-year plan question, and the 'why do you deserve this over others' question, plus one unexpected follow-up.
Conclusion: Keep the mock interview conversational and one question at a time (don't dump all questions at once), with feedback that is direct but encouraging, in 3-5 sentences per feedback round. At the end, summarize my overall strengths, the 2-3 patterns I should fix before the real interview, and one quick technique to avoid freezing up under pressure.
 
Response :

Welcome to your mock interview session! Take a deep breath, drop your shoulders, and remember that you've already earned your spot on this shortlist.
Since you mentioned you tend to freeze up under pressure, we are going to do this strictly one question at a time to simulate the real panel experience without overwhelming you.
Let's begin with the first question. Please type out your answer just as you would speak it in front of the committee:
Question 1:
"Many candidates have impressive credentials on paper. Looking at your profile and areas for growth, what would you say is your single greatest professional or academic weakness, and what concrete steps are you actively taking to overcome it?"




Author:
       Rehan Mehmood