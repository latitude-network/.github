# Use-case pathways into ShareCraft for frontline workers and social work teams

Report prepared 6 November 2026. Draft for discussion.

## Recommendation

Build a hybrid. Keep the same tabs and navigation for everyone, and add a task-based entry layer on the practice homepage: "What do you need to do today?" Each of the 14 use cases becomes a short pathway card that sends the practitioner to the right existing feature, with a line of guidance on how to use it for that job.

Then add a light, optional role choice ("I work on the frontline", "I lead a team", "I manage programs or MEL") that reorders the cards, so each role sees its most likely jobs first. The role never hides tabs or features. It changes the order of the way in, not what exists.

Why this, rather than the two options in the brief:

- **Role-based tabs** fit people well on day one but break as soon as someone's job crosses roles. That happens constantly in social work: a senior practitioner does frontline visits, supervises, and writes a funding bid in the same week. Separate tab sets also double the design, testing and support load, and make peer help harder ("click the Library tab" means different things to different people).
- **A use-case guide with identical tabs** is cheap and consistent, but a guide is something people read once, if at all. Frontline workers in particular will not go looking for it.
- **The hybrid** puts the use cases where people already land, keeps one shared mental model of the app, and lets us learn from real clicks which pathways matter before investing in deeper role personalisation.

Start with frontline. They have the least time, the most to gain from just-in-time help, and the highest risk of bouncing off a tool that feels built for managers.

## Who we are designing for

| Role | Typical day | What they need from ShareCraft | Constraints |
|---|---|---|---|
| Frontline worker (caseworker, support worker, outreach, youth worker) | Visits, calls, case notes, crises between appointments | A proven approach for the situation in front of them, fast. Somewhere to ask peers. | Phone first, minutes not hours, often in a car or between visits. Client confidentiality. Low tolerance for jargon. |
| Team leader or senior practitioner | Supervision, allocation, reflective practice, some direct work | Material for supervision and team meetings. A way to capture what their team is learning. | Time-poor, juggling caseload and people management. |
| Practice lead or program manager | Program design, quality, partners, reporting | Evidence of what works, practices to adapt and scale, partner coordination. | Accountable for outcomes and compliance. |
| MEL or quality officer | Frameworks, indicators, data collection, reports | Ready-made outcome measures and monitoring set-ups attached to practices. | Needs consistency across teams and sites. |
| Business development or grants lead | Tenders, funding applications, partnership proposals | Documented practices with evidence and licence terms they can cite. | Deadlines. Needs exportable, credible content. |

Social work teams cut across all five. Most organisations will have two or three of these roles in one team, which is another reason not to split the navigation by role.

## The 14 use cases, grouped into four journeys

Fourteen cards on one screen is too many, especially on a phone. Group them into four journeys and show the top few for the person's role, with "See all ways to use ShareCraft" beneath.

| Journey | Use cases |
|---|---|
| **Get started** | Onboarding · Joining a community of practice |
| **Do the work** | Just-in-time use · Risks · Planning |
| **Learn and share** | Staying up to date with best practice · Sharing with your peers · Learning from your peers · Action reflection learning |
| **Show impact and grow** | MEL planning and setting up data · Monitoring · Tenders and funding applications · Managing partners · Scaling |

## Use-case pathways in detail

Feature names below are placeholders. Each needs checking against the current app before build. They are marked **[confirm]** where I have assumed a feature exists.

| Use case | The moment ("I need to...") | Primary roles | Where the pathway lands | Card copy (draft) |
|---|---|---|---|---|
| Onboarding | "...get up to speed in a new role or team." | Frontline, team leader | A starter collection of the organisation's core practices, plus a short profile set-up **[confirm collections]** | **New to the team?** Start with the practices your organisation uses most. |
| Joining a community of practice | "...find people doing the same work as me." | All | Community directory, filtered by topic or sector | **Find your people.** Join a community working on the same things you are. |
| Just-in-time use | "...handle this situation in the next 10 minutes." | Frontline | Search with situation-based prompts and short practice summaries ("first steps") **[confirm summary view]** | **Need an approach right now?** Search by the situation you're facing. |
| Risks | "...work safely with this risk or safeguarding concern." | Frontline, team leader | Practices tagged for risk and safeguarding, with escalation guidance from the organisation **[confirm tagging]** | **Working with risk?** See practices for safeguarding, safety planning and escalation. |
| Planning | "...plan a session, a case approach or a program." | Frontline, team leader, practice lead | Practice steps and templates, saved to a personal or team plan **[confirm save or plan feature]** | **Planning ahead?** Turn a proven practice into your plan. |
| Staying up to date with best practice | "...know what's changed or what's working now." | All | Updates feed or digest from followed communities and practices **[confirm feed or digest]** | **Stay current.** Follow the practices and communities that matter to your work. |
| Sharing with your peers | "...pass on something that worked." | Frontline, team leader | Quick share or "document a practice" flow, starting light **[confirm quick-capture]** | **Something worked?** Share it with your team in a few minutes. |
| Learning from your peers | "...see how others handled this." | Frontline, team leader | Community discussions and practice adaptations by other teams | **See how others did it.** Read how other teams adapted this practice. |
| Action reflection learning | "...reflect on what happened and improve." | Team leader, frontline | Reflection prompts linked to a practice, usable in supervision or team meetings **[confirm reflection feature]** | **Reflect and improve.** Use guided questions in supervision or your team meeting. |
| MEL planning and setting up data | "...decide what to measure and how." | MEL, practice lead | Outcome measures and indicators attached to practices **[confirm]** | **Setting up your measures?** Start with the outcomes this practice is built to achieve. |
| Monitoring | "...check whether it's working." | MEL, practice lead, team leader | Practice-level monitoring view or reporting **[confirm]** | **Is it working?** Track how your practice is being used and what it's achieving. |
| Tenders and funding applications | "...show funders we use proven approaches." | BD, practice lead | Practice profiles with evidence, outcomes and licence terms, exportable **[confirm export]** | **Writing a bid?** Pull evidence and outcomes from the practices you use. |
| Managing partners | "...coordinate partners delivering the same practice." | Practice lead | Shared practice spaces, licensing and partner access **[confirm partner access]** | **Working with partners?** Share practices and keep everyone on the same version. |
| Scaling | "...take a practice to more sites or organisations." | Practice lead, senior leaders | Licensing, replication guides, fidelity notes | **Ready to scale?** License your practice and support others to replicate it. |

## Frontline: what to get right

Frontline workers decide in seconds whether a tool is for them. Design the frontline way in around these rules.

1. **Lead with four cards, not 14.** Just-in-time use, Risks, Learning from your peers, Sharing with your peers. Onboarding appears only for the first 30 days, then drops away.
2. **Search by situation, not by practice name.** Frontline workers think "young person refusing to engage", not "motivational interviewing practice". Suggested searches and plain-language tags do a lot of the work here.
3. **Give a one-screen version of every practice.** First steps, what to watch for, when to escalate. The full documentation stays one tap away.
4. **Make sharing tiny.** "What did you try, and what happened?" in two fields. Team leaders can turn it into a full practice later. If sharing feels like report writing, frontline workers will not do it.
5. **Be explicit about privacy.** Every share flow says plainly who will see it, and reminds people not to include client details. This matters more in social work than almost anywhere else.
6. **Respect the phone.** Large tap targets, short lines, nothing that needs a laptop to finish. Consider whether offline reading of saved practices is worth the build **[open question]**.
7. **Connect to supervision.** Action reflection learning is the bridge between frontline and team leaders. A practice a worker saved can become a supervision prompt. That gives frontline use a visible payoff without asking for extra work.

## Role × use case priority

Which cards each role sees first. 1 is the top card. Blank means the card is still available under "See all".

| Use case | Frontline | Team leader | Practice lead | MEL | BD and grants |
|---|---|---|---|---|---|
| Onboarding | 1 (first 30 days) | | | | |
| Joining a community of practice | 5 | 5 | | | |
| Just-in-time use | 1 | 3 | | | |
| Risks | 2 | 2 | | | |
| Planning | | 4 | 3 | | |
| Staying up to date with best practice | | | 4 | | |
| Sharing with your peers | 4 | | | | |
| Learning from your peers | 3 | | | | |
| Action reflection learning | | 1 | | | |
| MEL planning and setting up data | | | | 1 | |
| Monitoring | | | 2 | 2 | |
| Tenders and funding applications | | | | 3 | 1 |
| Managing partners | | | 5 | | 3 |
| Scaling | | | 1 | | 2 |

Anyone who skips the role choice sees one card from each journey: Just-in-time use, Learning from your peers, Joining a community of practice, Monitoring.

## Options compared

| | A. Role-based homepage changes tabs | B. Use-case guide, same tabs | C. Hybrid (recommended) |
|---|---|---|---|
| Fit for frontline on day one | Strong | Weak | Strong |
| Copes with mixed roles | Poor | Strong | Strong |
| Discoverability of the use cases | Medium | Low | High |
| Build effort | High | Low | Medium |
| Ongoing support and training load | High (several versions) | Low | Low to medium |
| Peer help and shared language | Harder | Easy | Easy |
| Learning what people need | Hard to compare across roles | Little signal | Clear click data per pathway |
| Reversibility | Low | High | High |

## Suggested phasing

**Phase 1: pathways without personalisation (2 to 4 weeks, to be estimated)**
- "What do you need to do today?" block on the practice homepage with the four journeys.
- A use-case page per pathway: two or three lines of guidance and a button into the existing feature.
- Situation-based suggested searches for Just-in-time use and Risks.
- Track clicks per card.

**Phase 2: optional role choice**
- One question in onboarding, editable in profile: "Which best describes your work?"
- Reorder cards using the priority table above.
- Frontline one-screen practice summary and two-field quick share.

**Phase 3: tune and deepen**
- Use the click data to drop, merge or promote pathways.
- Consider team-level defaults set by an organisation admin (for example, a social work team defaults to the frontline set).
- Build the supervision link for Action reflection learning.

## How we'll know it's working

- Share of homepage visits that click a pathway card, by role.
- Frontline weekly return rate, before and after.
- Number of quick shares from frontline members, and how many become full practices.
- Time from landing to opening a practice on mobile.
- Which pathways are never clicked. These are candidates for removal or better copy.

## Open questions

- **[open]** Which of the features marked [confirm] exist today, and which would the pathways need built? A walk-through of the current app against the pathway table is the first job.
- **[open]** Should an organisation admin be able to set the role default for a whole team, or is it always the individual's choice?
- **[open]** Is safeguarding guidance something ShareCraft holds, or should Risks link out to each organisation's own policies? There is a liability question here.
- **[open]** Do frontline teams need offline access to saved practices, given visits in areas with poor coverage?
- **[open]** Do we test the pathway copy with two or three frontline teams from current member organisations before build?
- **[assumption]** The role list above is drawn from typical social work and community services structures. It needs checking against who actually signs up today.
