---
title: "#3 - Product Discovery 1/2 (HelloPM)"
date: 2026-08-17
tags: ["product-management", "helloPM", "product-discovery"]
showToc: true
cover:
  image: "/images/notes_002_gemini_product_sense.png" 
---

> Notes are based on live lectures via HelloPM (https://hellopm.co/). All credits to Ankit and team. This is just a dump of what I noted for revision

## Lovable case study
- One of the fastest growing SAAS
- Anton built GPT engineer → then changed it to Lovable

## The problem ?
- Before Chat GPT → Developers query → Google → Stack Overflow
- Post Chat GPT → In Chat GPT → Developers copy query and implement
- But still room for improvement. No need to copy and paste. Let the software iterate
- He built GPT engineer (Github repository which can be installed using terminal) → Friction point → Technicalities in installation
- This was a solution only for engineers - not for every one

## He talked, researched found that:
- People want to build businesses but don't have technical expertise
- Non-tech founders always were searching for tech co-founders
- Unproven ideas selling ?
- Cost & Time associated with technical development
- Identify users - non-tech founders, developers, designers, hobbyists
- Needs - building software without technical knowledge

## Pain points
- Good developers are rare, costly and take time
- Current AI solution ~ just a code generation machine + Difficult to set up
- People want complete control as well + all functionalities

## The people ?

## User Research ?
- Finding users - via userinterviews.com
- He reached out to targeted segment people using social media etc.
- Asked the right interview questions
- Problem Space = Past and present; Solution space = Future
- Don't ask future/solution oriented questions → People will give their opinion
- Ask about past only - understand the user, their thought process, their journey, challenges, work-arounds, feedback
- At the end only - you can ask for feature-desires (solution oriented) so that good ideas not missed
- As a PM, you need to work as a doctor, detective to understand the true picture. Look for facts, not opinions

## Insights for execution post research ?
- Users <3 ( Speed) but want control as well
- Need high speed of delivery
- Users need social proof (Other people are also using it)
- Need working software not just UI/code
- They want to see proper code as well
- Different users need different values (e.g. developers → security, entrepreneurs → quick deployment etc.)

## Turn Insights to actual product changes:
- Users love details but demand speed: Visual editing
- Product must deliver as soon as possible: To see the value of product - sample prompts, sample projects
- Users need social proof: Mention made by lovable, Put on website, Blogs/Vlogs
- Users need working software not just UI or code: Shows actual code, Partnered with Supabase - for backend, Option to export everything on Github
- PM is an ongoing thing. It's never done.

## 4 characteristics of a successful product:
- Valuable - Should add value to users. Good enough that they are ready to pay (User angle)
- Usable - Users should be able to use (Design angle)
- Feasible - Can be built by existing processes ? (Engineering angle)
- Viable - What's in it for business ? (Business angle)

## How to know if there is a need for something ? How did Sam Altman know that Chat GPT is needed when google already existed ???
- By observing user behaviour and understanding

## Most important skill in AI PM jobs - identifying right AI use cases. Products succeed because they address a desire or solve a problem in the life of user
- Uber - A to B with predictability
- LinkedIn - Connect with people for jobs, opportunities
- Chat GPT - Answer questions quickly and precisely
- Fridge - Keeps food fresh for a longer time. This is the functional aspect. It has emotional (what are you thinking about yourself ?) usage and social usage as well (what do you think others are thinking of you ?)
- Jacket - Keeps body warm

## Why do PM's fail at user research ?
- Act on opinion (self, user, boss's) vs Dig deep, build insights and only then validate them
- No user interaction vs Create constant feedback loops. Create good relationship with the users
- Seek feature approvals (The have a solution in mind and are seeking validation for that - which reflects in their question) vs Really trying to understand the user
- They share raw interview notes vs Sharing actionable insights from the interviews etc.
- You cannot exist as a PM without doing user research no matter whether it is B2B or B2C

## Research is a decision tool NOT A REPORT you produce
- Who exactly is the user ?
- What problems do they actually have ?
- How painful and frequent is it ?
- What do they do about it currently ?
- Who else is solving it ?
- Is the market urgent, large & reachable ?
- Will the users switch, adopt, ready to pay and invest time ?

## Biggest mistakes in user research:
- Not finding the right users
- Not asking the right questions

## How to ask the right questions ?- The MOM's test
- Talk about their life instead of your idea
- Ask about specifics in the past, rather than opinions about future
- Talk less, listen more
- e.g. Do you think this is a good idea VS Walk me through your current workflow for X ? Would this feature be useful VS What's the hardest part about…?

## You are a PM at OpenAI. You need to create Cursor (an AI assistant/agent) for PM's. What questions to ask for discovery for this product ? Follow the principles from MoM's test

## My take
- Do you feel AI assistants are useful ? What was the last time you used them ? How frequently ?
- If yes, can you explain the current setup and avenues in which you use them ?
- Which AI agents have you tried ? What are the challenges you have faced ?
- How do you go about solving the challenges ?

## Claude's review - Please check my questions for the user interview I need to do as an OpenAI PM for an idea on AI agent for Product Managers. Help me understand if they are following the Mom's test or not

---

Good instinct to check this against The Mom's Test — most first-draft interview scripts fail it in the same few ways. Here's a question-by-question breakdown:

**Q1:** "Do you feel AI assistants are useful? What was the last time you used them? How frequently?" This is two different questions bolted together, and they pull in opposite directions.
- "Do you feel...useful?" — Fails. This is an opinion/rhetorical question. People will say "yeah, pretty useful" to be polite, and that answer teaches you nothing actionable.
- "What was the last time you used them? How frequently?" — Passes. Concrete, past-tense, behavioral. Keep this part.
- Fix: Drop the opinion half entirely. Start with "Walk me through the last time you used an AI assistant for work."

**Q2:** "Can you explain the current setup and avenues in which you use them?" Partially passes — it's aimed at real workflow, not hypotheticals. But "avenues" invites a generic, brochure-style answer ("oh, I use it for brainstorming, writing, research...") rather than specifics.
- Fix: Anchor it to a real artifact or task. "Pull up the last thing you used it for — what were you trying to get done, and what did you actually do step by step?"

**Q3:** "Which AI agents have you tried? What are the challenges you have faced?" The first half is fine (factual). The second half — fails, subtly. "What are the challenges" is a leading fishing question — it presumes challenges exist and invites the person to generate complaints on the spot to please you, rather than recalling something real.
- Fix: "Tell me about the last time one of these didn't do what you needed." Specific incident > generic complaint list.

**Q4:** "How do you go about solving the challenges?" Passes, and it's actually your strongest question — it asks about current workaround behavior, which is gold in Mom's Test terms (it reveals whether the pain is real enough that they've already built a janky solution around it).

Overall verdict: 2 of 4 questions have an opinion/hypothetical component that will generate false positives. The pattern to watch for going forward: any question starting with "Do you think," "Do you feel," "Would you," or "What are the challenges" is asking for a prediction or a performance, not a fact.

Here's a tightened version, all past-tense and behavior-anchored:
- Walk me through the last time you used an AI assistant for a work task — what were you doing right before, and what happened?
- What tools have you used for this, and what did the actual step-by-step look like?
- Tell me about the last time one of these fell short of what you needed — what specifically happened?
- What did you do next — did you find a workaround, give up, go back to doing it manually?

One more Mom's Test staple you might add: "Is there anything else you tried before this?" and "What else have you tried to solve this?" — these surface whether they've spent money or serious time on the problem already, which is a much better signal than stated interest.

---

## If you have to design the user interview, what will be the questions ? Also explain the rationale behind them

Here's a full interview script built for a PM-agent concept, structured around the three core Mom's Test rules: talk about their life, not your idea; ask about specifics in the past, not generics or opinions about the future; talk less, listen more.

## Structure & Rationale

I'm organizing this in five phases, each doing a specific job. The idea itself (the AI agent for PMs) doesn't get mentioned until the very end, if at all.

## Phase 1: Anchor in their actual role and workload
- "Walk me through your day yesterday, hour by hour."
  - Rationale: Forces total specificity. No opinions possible. You'll see where PM time actually goes without them curating for you.
- "Of everything you did yesterday, what took longer than you wanted it to?"
  - Rationale: Surfaces pain organically, from their own account, not from you suggesting a pain point ("do you struggle with X?").

## Phase 2: Current tool behavior (not opinions about tools)
- "What tools or AI assistants did you actually open today or this week? Show me if you can."
  - Rationale: "Show me" is a Mom's Test power move — screen-share/behavior beats self-report every time. People misremember or embellish their own usage.
- "Take me through the last time you used one of them for something PM-related, start to finish."
  - Rationale: One concrete past instance beats ten generalizations. Prevents "I use it for brainstorming, docs, research..." brochure-speak.
- "What did you do right before you opened the tool, and what did you do with the output afterward?"
  - Rationale: Captures the tool's real place in a workflow — most value/failure lives at the handoff points, not inside the tool itself.

## Phase 3: Real friction, not invited complaints
- "Tell me about the last time an AI tool gave you something you couldn't use as-is."
  - Rationale: Specific incident, past tense. Avoids "what are your challenges," which invites on-the-spot complaint generation to please the interviewer.
- "What did you do next — fix it, redo it manually, ignore it, ask a colleague?"
  - Rationale: This is the single highest-signal question in the whole script. Actual next action reveals true severity. If they shrugged and moved on, the pain isn't strong enough to build a product around yet.
- "How much time would you guess that whole task cost you, including the fixing?"
  - Rationale: Puts a rough number on the pain so you can later size the opportunity — but note the word "guess"; treat this as directional, not hard data, since it's their estimate.

## Phase 4: Prior spend and workaround investment (commitment signals)
- "Have you tried to solve this some other way — a different tool, a script, a template, hiring help?"
  - Rationale: Classic Mom's Test money/effort question. If someone has already spent time or budget solving their own problem, that's real evidence of pain. If nobody's tried anything, the pain may be tolerable, not urgent.
- "Is there a budget on your team for tools like this? Who decides?"
  - Rationale: Commitment question — reveals whether this is a real buying process or just personal curiosity, and who the actual economic buyer is (important since you're PM, not necessarily the purchaser).

## Phase 5: Close — let them lead, don't pitch
- "If you could wave a magic wand and fix one part of your week, what would it be?"
  - Rationale: This is the closest thing to a hypothetical in the script, and it's placed last deliberately — by now they've grounded themselves in specifics, so their answer is more likely to reflect real recurring pain than a wish-list fantasy. Still treat the answer as a clue, not a commitment.
- "Who else do you know who deals with this same thing?"
  - Rationale: Referral question — a classic Mom's Test close. People are far more willing to introduce you to a peer than to commit themselves, and it multiplies your sample without more cold outreach.

## Two rules I'd flag for you to hold onto during the actual interview, since a good script can still be undermined by live behavior:
- Don't mention your product idea until the interview is essentially over, if at all. The moment you describe it, every subsequent answer becomes contaminated — people start responding to your idea rather than reporting their own life.
- If they ask "so is this idea good?" — deflect back to their world: "Tell me more about how you'd actually use something like that" rather than pitching. Their imagined-future answer is exactly the kind of soft data Mom's Test warns you not to weight heavily.