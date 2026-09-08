+++
date = '2026-09-01T10:32:04-07:00'
title = "Schrödinger's Glass"
slug = 'schrodingers-glass'

[params]
  author = 'Brandon Abear'
+++

Generative AI, specifically Large Language Models (LLMs), pops up in conversation quite often these days; there is no escaping it. Perhaps your company is forcing adoption of LLMs for coding, your social media algorithms are pushing stories about the impact of AI, or your friends are complaining about the inability to afford electronics due to out-of-control memory price gouging. Even if you have not personally interacted with LLMs, the terminology is already embedded in the modern zeitgeist.

Tech discourse treats LLMs as binary: they are either the largest paradigm shift in modern tech or the greatest financial scam and intellectual property heist in recorded history. Depending on where the social media algorithms have slotted you, you are undoubtedly inundated by one side of this debate.

I find myself complaining about LLMs quite frequently. In fact, I *never* have anything positive to say about LLMs when discussing the topic with my friends, family, or professional peers. Yet I use the technology almost daily. On the surface, I would appear a hypocrite! How can I simultaneously leverage LLMs to automate certain aspects of my work or life yet constantly complain about the negative aspects of the technology?

## The Glass is Half Empty

While it is often recommended that you start off with compliments before diving into constructive criticism or critique, explaining my distaste for LLMs first may illuminate why and where I still use the technology at all.

I am a generally skeptical person. It's not that I think all people are liars and thieves, con-artists and grifters, or slimy salespeople, but for better or for worse, my default mental state is "prove it." This manifests in how I work and attempt to convince others of my opinion; I will show you the evidence to back up my argument. When driving technical changes, I will be in the trenches with you, consuming my own dog food. I really dislike bullshitters.

And that is a key driver, I think, in my negative opinions on LLMs. The hype is so far beyond the capabilities of the technology that it is making it seem like a scam. And it is in the sense that the outcomes predicted by the CEOs of big tech are not at all coming to fruition, at least not for the reasons they market.

At my previous company, leadership went all-in on AI, effectively demanding that everyone use AI as much as possible. Utilization and lines-of-code were being measured and celebrated. LLMs were heralded as the great equalizer, allowing anybody to contribute to any code base. For me personally, that contributed to my burn out. Reviewing PRs every day with tens or hundreds of files changed is exhausting enough, but the added pressure by certain managers to merge and deploy as fast as possible undermined quality and controls. I was still liable but had lost my ability to control the products I owned. That is not an enviable position to be in if you give a shit about your work.

Senior leadership was regularly telling engineers to adopt and lean on agentic coding tools for years, literally saying "use it or be left behind." There were constant updates from engineers sharing the latest best practices, sometimes contradicting the previous "best practice" entirely. To me, it seemed like staying on the cutting edge might not be the most economical position; perhaps it is better to wait for McDonald's to find the best real estate and simply open up an Arby's across the street.

But even adoption of LLMs, for whatever productivity gains in code generation there may be, came at a cost. After the first full year of very heavy agentic coding, I realized my coding skills were atrophying. That scared me. The tool I was being forced to use to be better at my job was eroding the foundational skill I had been honing over a decade to get to that point. Continuing this way would literally make me less effective and less marketable. Even internally, the goals for promotion were being shifted.

AI was added to organizational goals, engineer leveling expectations, and driven into every single nook and cranny. Part of promotion included being an advocate for AI. Some of my coworkers were literally using LLMs to write their responses to code reviews, architecture feedback, or anywhere they had offloaded their own thinking. The amount of work was only increasing even though teams had been decimated by layoffs over multiple years. I'm not a stranger to long working hours or challenging work environments, but there was little visible strategy beyond using AI with the assumption that it would guarantee material productivity boosts; it was ultimately AI for the sake of AI, and I find that unacceptable. Companies brand themselves as data-driven but always revert back to following trends when it suits them. That logical incoherence honestly pisses me off. But there are many corporations doing worse than just being hypocritical.

Is AI taking jobs? If you only read the headlines and take the corporate rationalizations at face value, then sure. But in practice, those jobs are generally not being directly replaced by agents; their capital is being reallocated. Follow the money. Companies are reinvesting those salaries into AI capital expenditures (capex) and offshoring to cheaper labor markets. If it smells like bullshit...

But the smell of manure isn't emanating only from big corporations forced to bend to the will of their shareholders; it's also coming from many of the consumers of AI themselves. Just open Twitter and you'll be overloaded with truly outrageous claims of productivity and output. Engineers will claim 100x gains. There will be a new best practice every other week. Each new model release comes with a cacophony of "hot takes" from across social media.

Unlike corporations, which are fundamentally motivated by profit, individuals on social media may not be. There are absolutely a number of true believers that have not only bought into the hype, but are driving themselves towards psychosis by their use of LLMs itself. I honestly feel sorry for them; it isn't that different from being in an abusive relationship, and you often don't realize it until you have escaped.

So my dislike of LLMs ultimately comes from an impedance mismatch between what has been promised and what is being delivered, and the manipulation in between. Yet I continue to leverage the technology...

## The Glass is Half Full

My use of AI in my personal life is quite different from what it was professionally. I am quite selective about where and how much I rely on LLM output. A few example use cases will showcase this better than a generalized summary.

I still code at home. I'm not building large, complex applications nor am I creating cookie-cutter front-end experiences. Most of my personal projects are simple utilities, intended as learning exercises, or toy projects to proof-of-concept an idea I have. Even though these may be simple, I limit how much the LLM gets to do on its own. I think through the problem space, narrow down specifically what I will work on and how it should function, and then work towards an implementation. I may ask the LLM to pull documentation or share a general example of a coding pattern if I am rusty, but I stay engaged in the learning and understanding of what I write. I may ask the LLM for refactoring ideas, usually guided by some intuition I have about areas of improvement, but I will force these to be partitioned and selectively allow the LLM to implement one at a time. If it is more boilerplate work, then the LLM can take the reins. But this requires more upfront work, does not allow for a fleet of unsupervised agents, and likely yields at best a 25% productivity increase in very limited scenarios.

This blog is another use case. I don't consider myself a strong writer, so having an LLM do my proofreading and possibly suggest targeted improvements helps me with the polishing step. The result is a slightly more refined version of my work, but it is fundamentally still my voice. I don't have the LLM write, organize, or materially edit my work.

Another use case is for targeted online searches or research. Perhaps it is product research, looking for how-to guides for home improvement projects, or helping plan and organize a vacation. In all of these scenarios, I almost always require sources be included and I go and check those myself.

I try to stay away from prompting LLMs in matters of taste or more abstract questions. For example, when I was updating my resume and prompted an LLM to guess my level in an unbiased fashion, it provided two options with the same leveling. At first glance, that seems like the LLM is accurate given the consistent output. But looking at the details and prompting the LLM to explain its rationale, the reality is that it was cheating and remembered or knew about my public work history and slotted in explanations for its choices in what appeared to be at random. The LLM already had the answer and made up arguments to defend it. If a human did this, it would be considered lying.

I also use LLMs for certain debugging tasks. My wife's Windows machine was behaving oddly and having intermittent random hanging. I haven't used Windows in many years, so most of the default explanations I had did not resolve the issue. In this case, the LLM was useful in narrowing down the issues and pointed to a solution on an obscure forum for a problem that was basically an uncommon conflict between two pieces of software and specific version ranges that apparently only a couple people had run into before.

A common thread in all of these use cases is that I retain understanding and control over the output of the LLM and validate what it produces. I refrain from outsourcing critical thinking or allowing my skills to atrophy any further.

## Schrödinger's Glass

Is the glass half full or is it half empty? I'd argue it's a mistake to assume the state is inherently fixed. AI exists in a superposition: simultaneously an incredible technological achievement and a fast track to deskilling, burnout, and unvetted slop. What collapses that state is simply how you interact with it. If you hand over the reins, letting unsupervised agents generate thousands of lines of unvetted code, offloading your critical thinking, and accepting corporate hype at face value, you open the box to find an empty vessel and atrophy. But if you observe the technology through a lens of conscientious skepticism—forcing it to show its work, scoping it to narrow friction points, and keeping the cognitive burden on yourself—the glass actually holds something of genuine value.
