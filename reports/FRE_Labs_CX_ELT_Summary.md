# FRE Labs CX — ELT Summary (DRAFT)

**FRE LABS CX: Turning Consumers Into Co-Creators**

## What is FRE Labs CX?

FRE Labs CX is a consumer-facing digital platform that gives FRE's most engaged consumers a direct voice in what we make next. It lives on frepouch.com and turns the traditional CPG product development model on its head: instead of developing products behind closed doors and hoping the market responds, we let consumers vote on packaging, choose flavors, and earn early access to limited releases — then we use that data to make better decisions, faster.

Think of it as the consumer engagement layer for FRE Labs. FRE Labs is our innovation engine (new brand lines, experimental flavors, co-manufacturing partnerships). FRE Labs CX is how consumers interact with that engine — how they see it, shape it, and ultimately buy from it.

## Why does this matter?

Three reasons:

1. **Consumer intelligence at scale.** Every vote, every poll response, every waitlist signup is a real data point. When we walk into a retailer and say "79% of 2,000 consumers chose this packaging," that's not a focus group of 12 people in a rented conference room. That's statistically significant demand signal that de-risks product launches and strengthens sell-in conversations.

2. **Loyalty through ownership.** When a consumer votes for a flavor and it shows up on shelf six months later, they don't just buy it — they tell people about it. "I voted for this." That psychological ownership converts casual buyers into brand advocates. It's the difference between selling *to* someone and building *with* them.

3. **"Different Not Better" brought to life.** FRE Labs products have a distinct look, mouthfeel, and flavor profile from core FRE. The CX platform reinforces that distinction. It's not a coupon page or a loyalty program bolted onto the existing site. It's a participatory experience that signals: this is where FRE experiments, and you're invited.

## What are we building?

The platform has three layers, rolling out in phases:

### Phase 1 — The Vote (Weeks 1-4)
- **Packaging Vote:** Consumers see 2-3 design variants for upcoming Labs products and pick their favorite (head-to-head tournament style). This directly supports the Rohith demo action item to consumer-test 3 design variants per flavor.
- **Flavor Polls:** "Which flavor should we make next?" with visual flavor cards and real-time results.
- **Early Access Waitlist:** Consumers sign up for first access to limited releases. Tiered — invite friends, move up the list. This builds our owned audience for every future drop.

### Phase 2 — The Loop (Weeks 5-8)
- **Limited Release Drop Pages:** When a Labs product launches, waitlist members get 48-hour early access before retail. Real-time stock counters. One-click purchase.
- **AI Decision Digests:** Automated summaries of consumer sentiment — what people are saying, what's trending, what's polarizing. Generated weekly for the team.
- **Social Integration:** Share your vote, challenge a friend to pick a side. Organic reach from consumer participation.

### Phase 3 — The Hub (Weeks 9-12)
- FRE Labs section fully integrated into frepouch.com as a persistent destination.
- Multi-brand support: different Labs brand lines (Lucy, Juice Head collab, Alp Drifters, etc.) each get their own visual world within the platform.
- Consumer profile: see your voting history, your accuracy ("You picked 3 of our last 4 releases"), your early access status.

## How does it work technically?

We build the interactive engagement features (voting, polls, waitlist) as a custom web application and embed it into frepouch.com via Shopify's App Proxy, so the consumer never leaves the frepouch.com domain. Shopify continues to handle everything it's good at — product pages, checkout, subscriptions, the existing rewards program. The Labs platform handles everything interactive. One seamless experience for the consumer, two optimized systems on the backend.

All consumer engagement data flows into our own database — we own it, we analyze it, we use it. This isn't trapped inside a third-party tool.

## The consumer journey

QR code on a FRE Labs can → frepouch.com/labs → age verification → create account → "Vote on what we make next" → see real-time results → join the waitlist → get notified when it drops → buy with early access → come back and vote on the next one.

That's the flywheel. Each step feeds the next.

## Who's doing something similar?

We're not inventing a new category here. The best brands in the world use consumer co-creation, and the results are proven:

- **Lay's "Do Us a Flavor"** — Invited consumers to submit and vote on new chip flavors. Generated 14 million submissions in a single campaign cycle, drove a 12% sales increase, and ran successfully for 5+ consecutive years. Won an Effie Award for marketing effectiveness. The insight: even non-winning flavors created buzz and drove brand conversation.

- **LEGO Ideas** — Consumers submit and vote on product concepts. Designs that hit 10,000 votes get produced. MIT Sloan research found this model creates measurably higher customer loyalty and outperforms internally generated ideas. LEGO went from near-bankruptcy to the world's largest toy company partly on the strength of community co-creation.

- **Jones Soda** — Built their brand identity around consumer-submitted label art with community voting. Achieved a 69% engagement rate on their voting platform — a number most brands would kill for. The label art became the brand's most recognizable feature.

- **Nike SNKRS** — The limited-release drop model applied to sneakers. 160 million active members. Digital business grew 34% driven primarily by membership engagement. Limited drops are only 5% of the sneaker industry by volume but drive a disproportionate share of brand heat, conversation, and loyalty. Nike's CEO credited membership as the single biggest driver of digital growth.

- **ZYN Rewards** — Our direct competitor runs a points-for-cans loyalty program with a rewards store (electronics, apparel, gift cards). It's transactional — scan a code, get points, buy stuff. There's no co-creation, no consumer voice, no sense of ownership. It's a retention tool, not an engagement platform. **This is the gap we're exploiting.** ZYN treats consumers as buyers. FRE Labs treats them as collaborators.

## Three patterns from the best co-creation programs

1. **Give consumers real influence, not the illusion of it.** Lay's actually produced the winning flavors. LEGO actually manufactures the voted designs. If consumers vote for a packaging design and we use a different one, the program dies instantly. Authenticity is non-negotiable.

2. **The drop model creates urgency and habit.** Nike proved that limited releases drive disproportionate engagement. People check the app daily. They set alarms. That behavioral pattern is exactly what we want for Labs releases — a reason to come back.

3. **Co-creation converts spectators into advocates.** Jones Soda and LEGO both found that consumers who participate in creation become the brand's loudest evangelists. They don't need to be paid or incentivized to tell people. They do it because they feel ownership.

## Why are we confident this will win?

1. **Nobody in nicotine pouches is doing this.** ZYN has a transactional loyalty program. On! has nothing. Rogue has nothing. VELO has nothing. We'd be the first nicotine pouch brand to give consumers genuine co-creation power. First-mover advantage in a category doing $4B+ annually.

2. **We already have the infrastructure.** The internal Design Review app proves the voting engine works. The Purilum partnership gives us 15 flavors in the consumer testing pipeline. Streamline manufacturing gives us $1.30/can economics with 10K MOQ — we can produce limited runs that a company our size can actually afford.

3. **The data flywheel compounds.** Every campaign makes the next one smarter. Vote data from Q3 informs the Q4 launch slate. Consumer preferences aggregate into a dataset no competitor has. Over time, this becomes a genuine competitive moat — we know what our consumers want before our competitors even ask.

4. **Speed is our advantage.** This entire platform is being built by AI agents — not an agency on a 6-month timeline, not a dev shop billing $250/hr. We prototype in a day, ship in a week, iterate in real-time. By the time a competitor decides to copy this, we'll be three generations ahead.

5. **It maps directly to the strategy.** The Rohith demo produced 12 action items. FRE Labs CX directly executes action items #4 (consumer packaging test) and #10 (early access program), and creates the infrastructure for #9 (limited release drops), #11 (social integration), and #12 (website hub). This isn't a side project — it's the execution layer for the strategy we've already aligned on.

## What we need from the ELT

- Legal review on consumer data collection, age verification requirements, and state-specific restrictions before any consumer-facing deploy
- Alignment that FRE Labs CX is the consumer-facing arm of the FRE Labs innovation strategy
- Green light to proceed with Phase 1 build (Packaging Votes + Flavor Polls + Waitlist)
