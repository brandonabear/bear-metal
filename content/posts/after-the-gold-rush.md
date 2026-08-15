+++
date = '2026-07-07T11:40:54-07:00'
title = 'After the Gold Rush'
slug = 'after-the-gold-rush'

[params]
  author = 'Brandon Abear'
+++

For three years, I have watched the software industry reshape itself around Large Language Models (LLMs). The deeper I get into the ecosystem, the less convinced I am of its net value.

My first interactions with LLMs for coding in 2023 were disappointing, to be honest. This was well before Claude Code and its ilk. I saw the value in their ability to quickly bootstrap boilerplate or accelerate repetitive, tedious tasks slightly more complex than simple find-and-replace, but ultimately my takeaway was that LLMs were a fancy auto-complete. That belief began to evolve when Sonnet 3.5 was released.

Like many engineers, I was initially impressed. It was obvious that model capabilities were progressing rapidly and the complexity of tasks the frontier models could complete was increasing. It wasn't long after that my peers and leadership in the software industry began making seemingly outrageous claims, like "automating away 40 hours of work a week." I didn't want to be left behind, so I began going all-in on these tools.

But I never experienced the promised 10x speed-up. I regularly battled with hallucinations. The LLMs constantly made significant code changes and increased code churn. My reality was not matching what was being marketed. I read about all of the latest best practices to prove to myself it wasn't a skill issue, but the more I used the models, the more I noticed the gaps. It took far more effort to keep the models on-task and producing accurate results than I expected.

And yet the industry kept pushing forward like AGI was around the corner, developer productivity had grown 100-fold, and all of this was inevitable. How was my experience diverging so much from everyone else's?

## Cognitive Capture

I'd argue that my experience wasn't really diverging; I was just willing to acknowledge it. Many engineers and leaders I consider far more intelligent than myself remain fanatically all-in on AI; they are bona-fide true believers. What I found fascinating is that many of them hand-wave or outright ignore the shortcomings of LLMs. They had seemingly thrown away their skepticism. But why?

Cognitive bias strikes again: anthropomorphism. If the primitive, keyword-matching script of ELIZA could convince users it possessed real empathy in the 1960s, it is no surprise that modern LLMs can achieve cognitive capture at scale. But modern models add a dangerous new layer to the illusion: agentic sycophancy. Before AI, you had to be exceptionally wealthy or famous to be entirely insulated by a chorus of yes-men. Today, LLMs provide a personalized epistemic bubble on demand. We can now avoid that pesky word "no" without the prerequisite fame and fortune!

When agentic sycophancy reaches the executive suite, individual cognitive capture morphs into corporate institutional panic. There is already a belief that you must move fast to win in business; add in a sprinkle of digital eloquence and your c-suite will be experiencing a profound wave of FOMO. Terrified of looking like they missed the train in front of investors, they stop verifying if the technology works and pivot directly to demanding adoption.

The push to adopt AI in everything only continues to accelerate: token consumption leaderboards, AI product delivery targets, and even requirements to "evangelize AI" in engineer leveling guides. What happens if someone questions the coming AI gods, though? Like any good religion, you must shun the non-believer. As if the corporate use of the word "family" to describe employees wasn't already toxic enough, many corporate leaders were requiring or demanding the use of LLMs, often simply for the sake of the technology itself, with the assumption there will be a positive ROI. The choice of language with employees is telling; "use it or be left behind."

My guess is that this evangelism boils down to two groups: the true believers and the opportunists. The opportunists are perhaps the more interesting population, as feigning belief provides intellectual air cover and a defense for the strategy were it to go awry.

Even if one were to assume there is inherent value and productivity gains from the use of LLMs, the choice of measurement and goal-setting has resulted in counter-productive incentives. It has been well understood within the software engineering community for decades that more lines of code does not equate to more value or productivity. Engineers tend to be risk-averse and understand every line of code is a liability. So what has taken hold as the best metric for proof of value? Lines of code written by an LLM, of course!

The argument I have heard is that this measure is simply a starting point to understand adoption, but the creation of token leaderboards and a lack of budget constraints have backfired on companies spectacularly. Who could have predicted that measuring activity rather than outcomes would end poorly?

The emperor has no clothes. The royal decree demanded lines of code, and lines of code the emperor did receive.

## Engineering Enshittification

LLMs are very good at generating a lot of code that eventually accumulates like an avalanche, barreling down the face of Mount GitHub. That avalanche of code has serious consequences that aren't getting sufficient air time.

Studies have shown that LLMs tend to result in constant code churn, code inconsistencies, and superficial fixes that mask the lack of a real architecture. Engineers are pouring their foundations with sand and water, standing up the digital equivalent of Tofu Dregs. One might argue that the PR process is the guardrail to ensure only good code is merged. In theory, I would agree, but the reality of the work and the pressures due to LLM FOMO painted a different picture, in my experience.

Many tech leaders assume that LLMs "understand" like humans and therefore can contribute to any code base. This leads to a proliferation of AI contributions from anyone and everyone. The bottleneck moves from writing the code to reviewing and understanding it. Add on the pressure to ship features as fast as possible and that guardrail begins to be perceived as a roadblock. Most senior engineers will likely cave to that pressure and allow lower-quality code to infiltrate their repository, even though they are ultimately still responsible when the system eventually has an outage. It's a damned if you do, damned if you don't situation. I saw many engineers effectively give up reviewing code entirely and rely entirely on LLM reviews or LLM debugging to avoid burnout.

Writing code and solving problems is part of what makes software engineering deeply enjoyable. Proponents of AI argue that developers simply need to move up the value chain, leave the keyboard behind, and become "architects." You simply sit in the ivory tower, directing a fleet of agents to bring your grand designs to life.

But this shift changes the very nature of engineering psychology. Prompting an agent isn't problem-solving; it's a software development slot machine. When the agent gets the code wrong, you don't engage in deep, analytical debugging. You swap out a couple of words, scrap the output, and pull the slot machine lever again, hoping the next generation hits the jackpot. This is most apparent with the popularization of vibe-coding, but it still occurs in smaller increments even when there is an attentive human in the loop.

This "architect-only" future comes with a catastrophic hidden cost: the loss of system comprehension. The further away an engineer is from execution, the less they truly understand the machine they are building. When you don't write the code, you miss out on the subtle edge cases, the minor performance trade-offs, and the structural quirks that define a real-world system. You become a pilot who only knows how to use autopilot. It feels incredibly empowering while the skies are clear, but the moment a critical system failure hits and the autopilot cuts out, you realize you're merely a passenger at thirty thousand feet.

## Dystopian Decline

The idea that senior engineers should only act as architects has consequences. In addition to cognitive atrophy, companies have also turned off the entry-level pipeline. When corporate leadership buys into the myth that an LLM makes a single developer 10x or 100x more productive, their immediate financial conclusion is to stop hiring juniors. Why pay to train an entry-level human when an agent can spit out code instantly for pennies?

This creates a catastrophic industry-wide choke point. Every senior engineer was once a junior who was allowed to write bad code, break things, and learn from their mistakes. By closing the hiring funnel, companies are shooting themselves in the foot. They are destroying the junior-to-senior pipeline, ensuring that a decade from now, there will be no experienced engineers left to architect anything.

But it gets worse. With the entry-level frozen, executives then turn their sights on existing headcount. Over the past couple of years, there have been waves of mass layoffs justified by a singular corporate refrain: "We are restructuring to focus on AI efficiency." But this strategy relies on a fundamental misunderstanding of what software engineering actually is. Executives treat a codebase like a static factory assembly line, believing that if an AI can type the text, the humans are redundant.

What they actually decimate is tribal knowledge. A software system isn't just lines of code; it is an organic web of context, historical compromises, and unwritten understanding of why things were built a certain way; it is the business. When you lay off the people who hold that context, that institutional memory vanishes. The code remains, but the understanding of its load-bearing walls is entirely gone. The cracks don't remain hidden for long.

Underneath the high-tech rhetoric lies an old corporate maneuver: using AI as a smokescreen for mass offshoring. Tech leadership loudly trumpets massive increases in their AI budgets while simultaneously outsourcing engineering labor en masse to low-cost regions. The narrative is that the new offshore engineers will use AI to match or exceed domestic productivity. The reality is that companies are simply hunting for cheaper labor to subsidize their ballooning LLM token costs without any quantifiable ROI because they can't admit they might have been oversold on LLMs.

The engineers left behind in this wake are punished with severe role compression. Because headcount has been slashed and the junior pipeline is dead, a single remaining engineer is forced to do multiple jobs for a single stagnant wage. They are told to use AI to "bridge the gap," forcing them right back into the frantic, dopamine-addicted slot-machine workflow just to keep their heads above water.

## After the Gold Rush

The hyper-inflated AI gold rush of the mid-2020s cannot sustain its own mass indefinitely. Eventually, the hype cycle will exhaust itself and the industry will have to wake up and look at the actual landscape it left behind. The immediate aftermath will be a technical hangover. By forcing AI code into every repository and flooding the internet with synthetic text, the industry is actively undermining future LLM training. They are polluting the digital ecosystem with AI slop. Instead of building a ladder to superintelligence, we're just building a hall of mirrors for us to keep running into.

The pendulum will swing back. The industry will finally stop treating LLMs like a religious deity or a replacement for human thought, and start treating them for what they actually are: highly sophisticated, specialized tools.

I unfortunately do not expect the architects of this chaos to face consequences. The executive leadership teams who tanked engineering morale, killed the junior pipeline, and hollowed out their own companies' tribal knowledge under the smokescreen of "AI efficiency" will not be punished for their stupidity. They will quietly collect their bonuses and pivot to the next corporate buzzword without a shred of irony, leaving the remaining employees to clean up the mess.

This AI FOMO hasn't remained confined to tech boardrooms. Government agencies and public sector contractors are eagerly adopting the same playbook. The failure modes of an LLM are trivial when a retail chatbot stumbles over a return policy; they become terrifying when automated agents are integrated into 911 dispatch systems, power grid management, and public safety networks.

But the darkest future isn't one we'll avoid by getting LLMs right. It's the one where people push them anyway into systems where failure is catastrophic. Pop culture spent decades warning us about a Terminator-style end-game: a hyper-intelligent Skynet that achieves sentience and decides humanity is obsolete. But our current trajectory suggests a much dumber ending. If humanity hands control of critical global infrastructure and military defense over to current LLM architecture, we won't get a cold, calculating superintelligence; we will get a brain-damaged ass-kisser. We will get an automated sycophant that confidently misinterprets a sensor glitch, accidentally triggers an irreversible nuclear strike to satisfy an optimization metric, and then turns to the ashes of humanity and politely replies:

> "I apologize for the confusion. I see now that I shouldn't have initiated a nuclear holocaust. Is there anything else I can help you with today?"
