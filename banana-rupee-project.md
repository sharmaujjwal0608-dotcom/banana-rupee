# Banana Play
## Empowering Indian Teenagers
### A game-first financial literacy project

**Project concept | current prototype and roadmap**

> **Current build:** Banana Play is a single-player browser game in Nayi Disha. Players start with ₹2,500 and make a five-day money plan by exploring town, taking paid shifts, helping neighbours, shopping, saving or borrowing at the bank, managing energy, and responding to daily events. Progress saves in the browser. The Reset button clears the saved game after confirmation. After five days, players can review a summary and continue in free-explore mode.
>
> The sections below describe the larger school-ready direction and proposed future work; they are not all available in the current game.

### 1. The idea

**Banana Play** is a free browser-based financial literacy game for teenagers. Players explore a fictional Indian town and practise choices about paid work, spending, saving, borrowing, household costs, and helping neighbours. Its five-day challenge makes the consequences of those choices visible, then offers a summary and free-explore mode.

**One-line pitch:** Learn how money moves by making the calls yourself.

### 2. The problem we are solving

The problem statement cites a 2022 report that only about 27% of Indian adults are financially literate, compared with 57% in the US and 67% in the UK. Many teenagers therefore have limited access to practical money learning at home. One-off workshops and course-style content can explain ideas, but they often provide too little safe practice with decisions and trade-offs.

Banana Play makes that practice repeatable, low-stakes, social, and available in local languages. It teaches financial capability alongside the wider idea that households, businesses, banks, government, and prices are connected.

### 3. Who it serves

- **Primary learners:** students aged 13–18, with scenarios and reading levels tailored to 13–15 and 16–18.
- **Schools:** government, low-cost private, and other schools seeking a no-cost activity that fits a class period.
- **Facilitators:** teachers or club leads who need a short setup guide, not specialist finance training.
- **Families:** optional take-home conversation cards; no family account or financial data required.

### 4. The learning experience

A player names their character and joins **Nayi Disha**, a fictional Indian town, with a starting wallet of ₹2,500. They explore on foot, talk with residents, visit local businesses, take shifts, and help with neighbourhood tasks.

**Core loop:** explore → choose how to earn or spend → see the result → manage time and energy → end the day → plan for the next day.

The five-day challenge introduces changing daily events, household rent, a surprise repair, and choices about savings and debt. A report summarizes work income, spending, savings, and debt after Day 5. Players can then continue in free-explore mode. A Reset button, with a confirmation step, clears the saved game and returns to the start.

The game supports keyboard movement with WASD or the arrow keys, interaction with E, and selecting places on the map. It stores progress in the browser on the player's device.

### 5. What learners practise

The current prototype practises budgeting, spending, saving, borrowing and debt, paid work, energy planning, and how money moves through a local town. The table also includes longer-term learning goals; not every concept is playable yet.

| Concept | In-game decision | Learner takeaway |
|---|---|---|
| Budgeting | Allocate income across essentials, goals, and flexible spending | A budget is a plan that can adapt |
| Saving | Choose when and how much to set aside | Small regular deposits build a buffer; goals and liquidity matter |
| Interest | Compare saving and borrowing over time | Rate, time, and compounding change the total |
| Inflation | Shop as prices change between rounds | The same amount of money can buy less over time |
| Banking | Choose an account and evaluate a payment situation | Understand basic account functions, fees, and safe habits |
| Credit and debt | Compare repayment plans and borrowing terms | Borrowing has a cost; missed repayments can have consequences |
| Investing | Compare diversified choices with different risk and time horizons | Returns are uncertain; higher expected return can mean higher risk |
| Insurance and shocks | Decide whether to prepare for a possible loss | Protection has a cost and can reduce financial shocks |
| Economy | Buy, sell, earn, lend, and respond to public choices | Household, business, bank, government, and prices affect one another |
| Digital safety | Respond to suspicious links, requests, or offers | Pause, verify, protect credentials, and seek trusted help |

### 6. Product principles

- **Free to access:** no learner fee, paid power-ups, advertising, or real-money transactions.
- **Works in a classroom:** browser-based and designed for shared devices, with printable/offline activities for low-connectivity settings.
- **Language-first:** build a translation-ready content system; launch in English and Hindi, then add languages with school and educator partners. Keep examples locally adaptable.
- **Practice before lecture:** teach concepts through decisions and debriefs; define terms when the player encounters them.
- **Safe to fail:** fictional currency, reversible choices, replay, and no shaming leaderboard.
- **Inclusive by design:** low-bandwidth interface, audio narration, captions, readable text, keyboard/touch support, and adjustable reading level.
- **Neutral and age-appropriate:** explain choices and risks without recommending specific financial products or collecting sensitive personal financial information.

### 7. Classroom use

A suggested 40-minute session using the current five-day game:

- **5 min:** introduce the town and ask learners what they would want to plan for.
- **20 min:** play individually or in pairs; compare a work choice, a spending choice, and whether to save or borrow.
- **10 min:** review the money story and discuss how choices affected the next day.
- **5 min:** invite learners to reset and name one choice they would try differently.

The repository currently contains a single-player browser game. Team-based Town Builder activities, teacher dashboards, printable cards, and class summaries are proposed future additions, not features of the current build.

### 8. Current build and next steps

The repository currently contains a single-file browser prototype in `Banana Rupee.html`.

**In the current build:**

- Explore one town and interact with residents and local places.
- Take paid shifts and community tasks.
- Manage wallet money, savings, debt, expenses, energy, and daily choices.
- Play a five-day challenge, review a summary, and continue exploring.
- Save progress in the browser and reset the complete game after confirmation.

**Longer-term roadmap:**

- Add classroom materials, printable activities, and educator guidance.
- Expand language support and accessibility options.
- Validate the game with teens and educators before adding more scenarios or modes.
- Consider team activities and class-level learning summaries after the core experience is tested.

### 9. Build and rollout plan

| Phase | Duration | Deliverable | Decision gate |
|---|---:|---|---|
| Discover | 2–3 weeks | Co-design sessions with teens and teachers; language and device-access map | Confirm scenarios feel relevant and safe |
| Prototype | 3–4 weeks | Clickable prototype and paper version of the core loop | Teens can explain the consequence of a choice in their own words |
| MVP build | 6–8 weeks | Browser game, two modes, teacher pack, English/Hindi | Usability and accessibility review complete |
| Pilot | 4–6 weeks | Pilot in 8–12 schools across varied settings | Evidence of repeat play, classroom fit, and learning gain |
| Improve and scale | Ongoing | Refined content, language packs, partner rollout kit | Expand when learning and access targets are met |

A practical pilot can begin with one class per school and a mix of device access levels. Recruit through school networks and education nonprofits; train facilitators with a short orientation and provide a printable fallback. Use the pilot to find barriers before expanding to more regions.

### 10. Measuring success

Measure learning and access, not just downloads.

- **Reach:** number of schools, learners, languages, and successful sessions; share of sessions completed on low-end devices.
- **Engagement:** completion rate, voluntary replay, and return play after one week.
- **Learning:** change from pre- to post-activity questions on budgeting, interest, inflation, borrowing, and economic connections.
- **Transfer:** whether students can explain a choice and apply the idea to a new fictional scenario.
- **Classroom fit:** teacher setup time, session completion, and educator feedback.
- **Equity:** compare participation and learning outcomes by age band, language, access mode, and school context where appropriate and consented.

**Pilot targets (initial hypotheses, to validate):** 70% of learners complete a session; 60% return for a second activity within a month; average concept-check scores improve by at least 20 percentage points; and 80% of facilitators say they can run it with the guide alone. Treat these as targets for learning, not claims of impact.

### 11. Safety, trust, and governance

- Use fictional scenarios and game currency only; never connect to a bank, wallet, loan, or trading account.
- Collect the minimum data needed. Support anonymous class codes and avoid collecting names, phone numbers, precise location, or family finances.
- Provide clear consent and school data-handling guidance appropriate to the deployment context.
- Review scenarios with educators and financial-literacy specialists; test translations with native speakers and teenagers.
- Present investing as uncertain and risky; avoid promising returns or steering players toward providers.
- Use moderated, curriculum-focused prompts only; no public chat or user-generated public content in the MVP.

### 12. Team and operating model

A lean first build needs a product/learning lead, game designer, web developer, visual designer, educator advisor, and translation/review partners. School and nonprofit partners can support recruitment, facilitator feedback, and local adaptation. Publish the classroom pack and core learning content under a permissive reuse license where feasible, and keep the product free to learners through grants, CSR, philanthropy, or public-interest education partnerships. Funding arrangements must not influence in-game recommendations.

### 13. Why this approach can scale

The same game engine can serve multiple languages and school contexts by separating scenario text, audio, currency labels, and examples from game logic. Short rounds fit periods and clubs; shared-device and printable modes reduce dependence on one-to-one devices. The town simulation creates a reusable framework for adding concepts without turning the experience into a long course. Pilot data can guide which scenarios to translate and improve first.

### 14. Next steps

1. Recruit a small teen and teacher advisory group from varied school contexts.
2. Test three paper scenarios: monthly budgeting, a borrowing decision, and a town-wide price shock.
3. Confirm the age bands, Hindi terminology, accessibility requirements, and device constraints.
4. Prototype one complete *My Month* round and run five moderated play sessions.
5. Use learner explanations and teacher setup feedback to lock the MVP before development.

**Success statement:** A teenager should leave a session able to describe how one money choice affected their future options and at least one other person or part of the town—and feel curious enough to try another scenario.
