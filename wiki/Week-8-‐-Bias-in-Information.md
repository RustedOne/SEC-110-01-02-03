Week 8 covers bias: what it is, why it matters in cybersecurity, media bias and how to counter it, decision quality, twelve types of bias, and readings on correcting misinformation, disinformation bots, a supermarket hack, and holding to your convictions inside an institution.

*Sources: SEC-110 notes "Mod 8 - Bias in Information"; Swire-Thompson et al., [The backfire effect after correcting misinformation is strongly associated with reliability](https://pmc.ncbi.nlm.nih.gov/articles/PMC9283209/) (2022); The Guardian, [Ukrainian strikes on Russian datacentres and online disinformation bots](https://www.theguardian.com/world/2026/oct/13/ukrainian-strikes-russian-datacentres-online-disinformation-bots) (Oct 2026); Reuters, [Investigators hunt French supermarket fridge hackers](https://www.reuters.com/legal/litigation/investigators-hunt-french-supermarket-fridge-hackers-no-claim-responsibility-2026-10-13/) (Oct 2026); Revisionist History, [Generous Orthodoxy](https://www.pushkin.fm/podcasts/revisionist-history/generous-orthodoxy).*

## Contents

1. [What Is Bias?](#1-what-is-bias)
2. [Bias in Cybersecurity](#2-bias-in-cybersecurity)
3. [Media Bias](#3-media-bias)
4. [Bias & Decision Quality](#4-bias--decision-quality)
5. [Types of Bias](#5-types-of-bias)
6. [Reading: Correcting Misinformation & the Backfire Effect](#6-reading-correcting-misinformation--the-backfire-effect)
7. [News: Disinformation Bots & the Supermarket Fridge Hack](#7-news-disinformation-bots--the-supermarket-fridge-hack)
8. [Podcast: Generous Orthodoxy](#8-podcast-generous-orthodoxy)
9. [My Notes](#9-my-notes)
10. [Sources & Credits](#10-sources--credits)

---

# 1. What Is Bias?

**Bias** is prejudice **in favor of or against** one thing, person or group compared with another, usually in an **unfair** way.

**Examples:**

- Assuming someone who is bad at sports is also bad at academics, with no evidence.
- Focusing only on information that supports what you already believe, and ignoring other perspectives.
- Actively avoiding someone because of one negative trait.

---

# 2. Bias in Cybersecurity

Why consider bias in cybersecurity and information assurance? Bias affects:

| Area | How bias can hurt it |
| --- | --- |
| **Decision making** | Choices based on gut feeling or assumptions instead of evidence |
| **Risk management** | Under- or over-estimating a threat ([Week 2: Risk](Week-2-‐-Security-Concepts-&-Threats-and-Adversaries#8-risk)) |
| **Technical approaches** | Sticking with a favorite tool or method even when it doesn't fit |
| **Resource allocation** | Spending on the threats people *feel* are scary instead of the ones that are likely |
| **Diversity of perspectives** | A team that all thinks alike has the same blind spots, the opposite of [thinking like an adversary](Week-2-‐-Security-Concepts-&-Threats-and-Adversaries#the-six-cybersecurity-concepts) |

> **Note:** Some cybersecurity examples (not in the slides):
> - **"It won't happen to us"** (optimism bias) leads to skipped patches. Every machine WannaCry hit was unpatched ([Week 1](Week-1-‐-What-Is-Cybersecurity-&-Cyber-Threats#wannacry-ransomware)).
> - **Confirmation bias in incident response:** an analyst decides early that "it's just a glitch" and ignores evidence of an intrusion.
> - **Attackers exploit bias on purpose.** Phishing emails pose as a boss or IT (trust in authority), add urgency, or play on what you expect to see. [Social engineering](Week-7-‐-System-Security#2-vulnerabilities--common-threats) is largely the art of exploiting bias.

---

# 3. Media Bias

Bias shows up even in places we think we can trust. News outlets can let their own views and experiences cloud their judgment of what objectively happened. A common example: two outlets report the same story with very different takes on what happened.

**Media bias** happens when news outlets or other media present information in a way that **supports a particular viewpoint**, instead of presenting all sides of an issue fairly.

**How to combat media bias:**

| Step | Ask yourself |
| --- | --- |
| **Process before sharing** | Have I actually read it, beyond the headline? |
| **Check authenticity** | Is the source real? Is the quote or image genuine? |
| **Check expertise** | Is the source an expert in this field? |
| **Evaluate purpose** | Is it meant to **persuade, inform or mislead**? |

> **Note:** A quick, practical habit is **lateral reading**: instead of judging a site by its own "About" page, open new tabs and see what *other* sources say about it. It connects to [OSINT](Week-3-‐-OSINT-&-Data-Security-Principles#2-open-source-intelligence): the same open-source research skills help you verify information.

---

# 4. Bias & Decision Quality

The course will cover **decision quality** in the coming weeks. It's critical for cybersecurity and information assurance. The steps to making a good decision:

1. **Meeting goals:** what are we trying to achieve?
2. **Logical thinking:** does the reasoning hold up?
3. **Forecasting:** thinking ahead about what could happen
4. **Risk assessment:** how likely is each outcome, and how bad would it be?
5. **Evaluation:** looking back on whether it worked

**Can these be influenced by bias?** Yes, every one of them. For example, confirmation bias skews logical thinking, and the flying-vs.-driving fear below skews risk assessment.

---

# 5. Types of Bias

| Bias | Definition | Example |
| --- | --- | --- |
| **Media bias** | Media presents information to support a particular viewpoint instead of all sides ([section 3](#3-media-bias)) | Two outlets spin the same event differently |
| **Motivational bias** | Personal motivations, desires or interests steer your thoughts, decisions or perceptions toward biased conclusions | Interpreting information, or making decisions, only in ways that serve your own goals |
| **Nonverbal bias** | Showing positive or negative **body language or behavior** toward a group, which ends up excluding others | Clapping only for your friend's presentation; eye-rolling while someone speaks |
| **Affinity bias** | Being drawn to people who share a **connection** with you (hometown, hobbies, same school) | Only hanging out with people who have the same interests |
| **Halo / horns effect** | Letting **one action or trait** shape your whole opinion of a person. **Halo** = one good thing makes them seem all good; **horns** = one bad thing makes them seem all bad. | Halo: favoring someone because they bought you lunch. Horns: disliking an athlete because they play for a rival team. |
| **Similarity bias** | Wanting to surround yourself with people **like you** | Excluding someone because of how they act or look |
| **Contrast effect** | Judging something by **comparing** it to what's around it (or to a stereotype) instead of on its own merits | Choosing between two well-reviewed washing machines and picking the one that looks fancier and has more gadgets |
| **Attribution bias** | Errors in explaining **why** something happened, such as blaming **external factors** | Blaming traffic or unexpected events for being late to work |
| **Confirmation bias** | After making a judgment, looking for or interpreting new information so it **supports what you already believe**, causing tunnel vision | A student ignores research that contradicts their thesis |
| **Appearance bias** | Forming an opinion based **only on physical attributes** | Judging someone by their clothes, looks or body language |
| **Conformity bias** | Going along with **group-think**, or not speaking up for fear of going against the group | Changing your clothes to match your friends' style, even though you don't like it |
| **Cognitive bias** | Thinking **irrationally** in a predictable way | Believing flying is more dangerous than driving |

> **Clarification:** **Cognitive bias** is really the **umbrella term**: a predictable, systematic error in thinking. Confirmation bias, the halo effect, conformity and most others on this list are all *kinds* of cognitive bias. The flying example has a specific name, the **availability heuristic**: plane crashes are rare but memorable, so they feel more likely. Per mile traveled, flying is far safer than driving.
>
> **Clarification:** The slides describe **attribution bias** as blaming external factors. That's one side of it. People tend to credit **themselves** for successes and blame **outside factors** for failures (the **self-serving bias**), while blaming *other* people's failures on their character instead of their circumstances. The slide's diagram showed a manager who takes credit when the team succeeds and blames employees when it fails.
>
> **Clarification:** The **contrast effect** is usually defined as judging something relative to what you saw **just before** or **next to** it. A candidate seems great after a weak one, or average after a star. The slide's washing machine example fits: each machine is judged against the other, not on whether it meets your needs.

**Affinity vs. similarity bias:** these are closely related. Affinity bias is about being drawn to people who share a **connection** with you; similarity bias is about **excluding** people who aren't like you.

---

# 6. Reading: Correcting Misinformation & the Backfire Effect

*Swire-Thompson, Miklaucic, Wihbey, Lazer & DeGutis (2022), "The backfire effect after correcting misinformation is strongly associated with reliability," Journal of Experimental Psychology: General.*

**The question:** a **backfire effect** is when correcting a false belief makes people believe it **more**. Does that really happen? And if it seems to, is it because the correction threatens people's worldview, or because of something else?

**What they did:**

| | |
| --- | --- |
| **Design** | Two experiments. People rated how much they believed 21 false claims and 21 true facts (0–10), then rated them again **three weeks later**. |
| **Groups** | One group read short **corrections** of the myths in between; a **control** group got no corrections. |
| **Participants** | About 390 and 530 online participants |
| **Topics** | Things like vaccine myths, the gender pay gap, and a health claim about testosterone |

**What they found:**

| Finding | Meaning |
| --- | --- |
| **Corrections worked** | People who read corrections believed the myths much less than the control group did |
| **No overall backfire** | No correction made belief in a myth go up overall |
| **Apparent backfire was mostly noise** | Some individuals' scores went up, but that happened just as often, or more, in the control group. In Experiment 1, about 13% of corrected participants vs. 24% of controls showed a 2+ point rise. |
| **Reliability explained it** | Items people answered **inconsistently** (low test-retest reliability) showed the most "backfire." Their beliefs were weak and fuzzy, so scores bounced around randomly. |
| **Worldview didn't predict it** | How personally important a topic was didn't predict backfire |

**Takeaways:**

- **Correct misinformation.** Fact-checkers shouldn't hold back for fear of backfire.
- Many earlier "backfire" findings were probably **measurement error**, not people digging in.
- Researchers need **reliable** measurements before claiming an effect.

**Limitations:** only 21 items; online participants who were more educated and liberal than the average American; a lab setting, not real social media. Part of the funding came from a gift from Facebook, which the authors disclosed.

**Connection to this week:** people often *expect* corrections to backfire, which can itself be a kind of bias. The study shows why you should **check the evidence**, and that evidence can correct beliefs.

> **Note:** The study also saw a small **illusory truth effect** in the control group: just **seeing a claim again** made people believe it a bit more. That's why repetition is a core tactic of disinformation campaigns.

---

# 7. News: Disinformation Bots & the Supermarket Fridge Hack

Both articles were assigned this week, but **neither site would load for me** (The Guardian and Reuters block automated access), so I can't summarize them here. All I can tell from the links themselves:

| Article | Topic (from the link) |
| --- | --- |
| [The Guardian, Oct 13, 2026](https://www.theguardian.com/world/2026/oct/13/ukrainian-strikes-russian-datacentres-online-disinformation-bots) | **Ukrainian strikes on Russian datacentres** and their link to **online disinformation bot** activity |
| [Reuters, Oct 13, 2026](https://www.reuters.com/legal/litigation/investigators-hunt-french-supermarket-fridge-hackers-no-claim-responsibility-2026-10-13/) | **Investigators hunting hackers** who targeted **French supermarket fridges**, with **no one claiming responsibility** |

**Questions to think about while reading:**

- **Bots:** disinformation campaigns rely on bot networks, which need servers (datacenters) to run. What does that say about the physical side of "online" influence? How does repetition by bots tie into the illusory truth effect from [section 6](#6-reading-correcting-misinformation--the-backfire-effect)?
- **Fridges:** supermarket fridges are connected **IoT** devices ([Week 7](Week-7-‐-System-Security#6-iot--physical-security)). Which part of the CIA triad does an attack on them threaten? When no one claims responsibility, how do investigators avoid jumping to conclusions about who did it (confirmation bias in attribution)?

If you paste the article text, I can add proper summaries.

---

# 8. Podcast: Generous Orthodoxy

*Revisionist History, hosted by Malcolm Gladwell (Pushkin Industries).*

**The story:** **Chester Wenger**, a Mennonite minister in his 90s from one of the most traditional religious communities, officiated his **gay son's wedding**. That put him in direct conflict with his church. He wrote an **open letter** to the church explaining his decision, and was stripped of his ministerial credentials.

**The big question:** what do you do when the **institution that shaped your whole life** stands between you and your family? The episode presents Wenger as a model of principled dissent: staying loyal to his community while challenging it from within, instead of either obeying or walking away. The title comes from the idea of a "generous orthodoxy," holding firmly to a tradition while making room for people it would otherwise exclude.

**Connection to bias:**

| Idea from this week | In the episode |
| --- | --- |
| **Conformity bias** | The pressure to go along with the group, or stay silent, rather than speak against it |
| **Affinity / similarity bias** | A tight-knit community can make it hard to accept people who are different |
| **Confirmation bias** | Institutions, like people, can hold onto beliefs and filter out challenges |

> **Note:** The episode page also links to material on the debate over Woodrow Wilson's legacy at Princeton, including a published response to Gladwell from a student, Wilglory Tanjong. That shows his framing was publicly disputed, which is worth keeping in mind (the page itself presents only his view).

---

# 9. My Notes

*From my tech journal. Lightly cleaned up for spelling; added context is in the notes below.*

- Getting to know/understand what people want/need will help you know how you can use them.
- Scams are becoming more sophisticated.
- The uncanny valley is now crossed.
- LLMs can now data-mine Flock/security cameras.
- This may destroy the internet as we know it.
- These agents will fucking kill us.
- GET WIRED INTERNET.
- Security is money.
- Tribalism is spreading.
- "Fuck you, got mine" is becoming worrying.
- Memes are a great psychological weapon.

> **Note:** "Knowing what people want so you can use them" is how **social engineers** think: attackers exploit people's needs, trust and biases ([Bias in Cybersecurity](#2-bias-in-cybersecurity)). Knowing it helps you spot it.
>
> **Note:** "The uncanny valley is crossed" connects to **deepfakes**: AI-generated voices and video are now realistic enough to fool people, which makes scams like fake "boss" calls much more convincing. A good defense is **call-back verification** through a number you already know.
>
> **Note:** **Flock** (Flock Safety) makes automated license plate reader cameras used by many US police departments and neighborhoods. Combining camera networks with AI search raises big privacy questions.
>
> **Note:** "Memes are a psychological weapon" connects to the **illusory truth effect** from [section 6](#6-reading-correcting-misinformation--the-backfire-effect): repeated, catchy messages feel more true. "Get wired internet" connects to [Wi-Fi security in Week 10](Week-10-‐-Network-Security#wi-fi-security): wired connections can't be sniffed from the parking lot.

---

# 10. Sources & Credits

**Class materials**

- SEC-110 notes: *Mod 8 - Bias in Information*

**Readings and media**

- Swire-Thompson, B., Miklaucic, N., Wihbey, J. P., Lazer, D., & DeGutis, J. (2022). [The backfire effect after correcting misinformation is strongly associated with reliability](https://pmc.ncbi.nlm.nih.gov/articles/PMC9283209/). *Journal of Experimental Psychology: General*, 151(7), 1655–1665.
- The Guardian (Oct 13, 2026): [Ukrainian strikes on Russian datacentres and online disinformation bots](https://www.theguardian.com/world/2026/oct/13/ukrainian-strikes-russian-datacentres-online-disinformation-bots). Couldn't be retrieved.
- Reuters (Oct 13, 2026): [Investigators hunt French supermarket fridge hackers; no claim of responsibility](https://www.reuters.com/legal/litigation/investigators-hunt-french-supermarket-fridge-hackers-no-claim-responsibility-2026-10-13/). Couldn't be retrieved.
- Revisionist History: [Generous Orthodoxy](https://www.pushkin.fm/podcasts/revisionist-history/generous-orthodoxy)

<details>
<summary><b>Image credits</b></summary>

No images this week: the slides' pictures were clip art, cartoons, or a branded diagram (attribution bias, WallStreetMojo), so their content is described in text instead.

</details>
