---
layout: default
title: My thoughts on nanotechnology strategy research as an EA cause area
---

My thoughts on nanotechnology strategy research as an EA cause area
=================================================================================


**Two-sentence summary:** Advanced nanotechnology might arrive in the next couple of decades (my wild guess: there’s a 1-2% chance in the absence of transformative AI) and could have very positive or very negative implications for existential risk. There has been relatively little high-quality thinking on how to make the arrival of advanced nanotechnology go well, and I think there should be more work in this area (very tentatively, I suggest we want 2-3 people spending at least 50% of their time on this by 3 years from now).

_Context: This post reflects my current views as someone with a relevant PhD who has thought about this topic on and off for roughly the past 20 months (something like 9 months FTE). Note that some of the framings and definitions provided in this post are quite tentative, in the sense that I’m not at all sure that they will continue to seem like the most useful framings and definitions in the future. Some other parts of this post are also very tentative, and are hopefully appropriately flagged as such._

See this report on the Effective Altruism Forum [here](https://forum.effectivealtruism.org/posts/oqBJk2Ae3RBegtFfn/my-thoughts-on-nanotechnology-strategy-research-as-an-ea).

# Key points

* I define **advanced nanotechnology** as any highly advanced future technology, including atomically precise manufacturing (APM), that uses nanoscale machinery to finely image and control processes at the nanoscale, and is capable of mechanically assembling small molecules into a wide range of cheap, high-performance products at a very high rate (note that my definition of advanced nanotechnology is only loosely related to what people tend to mean by the term “nanotechnology”). (<a href="#broadening">more</a>)

* If developed, advanced nanotechnology could **increase existential risk**, for example by making destructive capabilities widely accessible, by allowing the development of weapons that pose a higher existential risk, or by accelerating AI development; or it could **decrease existential risk**, for example by causing the world’s most destructive weapons to be replaced by weapons that pose a lower existential risk. (<a href="#effects">more</a>)

* Timelines for advanced nanotechnology are extremely uncertain and poorly characterised, but **the chance it arrives by 2040 seems non-negligible** (I’d guess 1-2%), even in the absence of transformative AI. (<a href="#probability">more</a>)

* It seems **likely** that there’d be a **long period of development with clear warning signs** before advanced nanotechnology is developed, pushing against prioritising work in this area and pushing towards a focus on monitoring and foundational work. (<a href="#wait">more</a>)

* There has been **relatively little high-quality nanotechnology strategy work**, and by default this seems unlikely to change much in the near future. (<a href="#current_landscape">more</a>)

* **It seems possible to make progress in this area**, for example by clarifying timelines, tracking potential warning signs of accelerating progress, and doing strategic planning. (<a href="#prospects">more</a>)

* Overall, I think that **nanotechnology strategy research could be very valuable** from a longtermist EA perspective. Currently, my extremely rough, unstable guess is that we should have 2-3 people spending at least 50% of their time on this by 3 years from now (against a background of perhaps 0-0.5 FTE over the past 5 years or so). (<a href="#my_view">more</a>)

* Note that it seems that **we don’t want to accelerate progress towards advanced nanotechnology** because of (i) the dramatic but highly uncertain net effects of the technology, including the possibility of very bad outcomes, (ii) the plausible difficulty of reversing an increase in the rate of progress, and (iii) the option of waiting to gain more information. (Though note that I still feel a bit confused about how harmful various forms of accelerating progress might be, and I’d like to think more carefully about this topic.) (<a href="#potential_harms">more</a>)


# Introduction

This post has two main goals:

  1. To provide a resource that EA community members can use to improve their understanding of advanced nanotechnology and nanotechnology strategy.

  2. To make a case for nanotechnology strategy research being valuable from a longtermist EA perspective in order to get more people to consider working on it.

If you’re mostly interested in the second point, feel free to quickly skim through the first parts of the post, or maybe to skip directly to <a href="#prioritise">How to prioritise nanotechnology strategy research</a> below.


# Definitions and intuitions

In this section, I introduce some concepts that seem useful for thinking about nanotechnology strategy. I’ll refer to these in various places throughout the rest of the post.

Note that, although the focus of nanotechnology strategy research is ultimately advanced nanotechnology, I start by describing atomically precise manufacturing (APM), which I consider to be a particular version of advanced nanotechnology. I do this because APM is a far more concrete and well-explored technology than advanced nanotechnology, and because I like to refer to APM to help describe what I mean by advanced nanotechnology.

## Defining atomically precise manufacturing (APM)

I think the term APM is often used in a fairly vague way, and doesn’t have a widely accepted precise definition, so for the purposes of this post I’ll introduce some more precisely defined concepts that pick out important aspects of what people refer to as APM.

These are:

* **Core APM:** A system of nanoscale atomically precise machinery that can mechanically assemble small molecules into useful atomically precise products.

* **Complex APM:** Core APM that is highly complex, made up of very stiff components, operates in a vacuum, and performs many operations per second; that is joined to progressively larger high-performance assembly systems in order to allow a range of product sizes; where the assembly machines and products are perhaps only _mostly_ atomically precise; and where the assembly method is perhaps only _mostly_ mechanical assembly.

* **Consequential APM:** Complex APM that can create a wide range of complex, very high performance products at very low cost ($1000/kg or less) and with very high throughput (1kg of product per 1kg of assembly machinery in 3 days or less).

For more detailed definitions of these terms, see the Appendix section <a href="#apm_definitions">APM definitions in more detail</a>.

The APM concept originated with Eric Drexler.[^1] Complex APM roughly corresponds to the technical side of Drexler’s vision for APM, while consequential APM describes a watered-down version of the capabilities Drexler describes for APM.[^2],[^3] In what follows, I’ll use these terms when I want to be specific, and I’ll use the term “APM” when I want to point to the wider concept.

<a id="intuitions">
## Intuitions for why APM might be possible and impactful

This section provides some quick intuitions for why you might think that consequential APM is possible and for why atomic precision might be desirable when building very high performance assembly machines and products.

We know that core APM is feasible, i.e. that atomically precise nanoscale machines can be used to do mechanical assembly of small molecules into useful atomically precise products, because examples of core APM exist in nature. For example, ribosomes are atomically precise nanoscale machines[^4] that join amino acids to create proteins, which are themselves atomically precise.[^5] (Note that we don’t have similar “existence proofs” for complex or consequential APM.)

Atomic precision might be desirable for nanoscale assembly systems and products because, on the nanoscale, the atomic building blocks might be 1/100th or 1/1000th the width of the structure, so that you need atomic precision unless you design for very wide tolerances in structural parts. Atomic precision also gives you perfectly faithful realisations of your design (provided there are no manufacturing errors).

A manufacturing capability that can exactly reproduce a target structure down to the last atom might intuitively seem able to produce products with performance dramatically exceeding current capabilities. Naturally evolved systems often outperform present-day artificial ones on important dimensions,[^6] showing that we have some way to go before we reach performance ceilings. In addition, these evolved systems are composed of nanoscale machines and structures (albeit not always atomically precise ones), which are themselves a product of nanoscale manufacturing, suggesting that this is a powerful scheme for producing high performance products.

Nanoscale machines might be able to achieve high throughput because stiff nanoscale machines moving small distances can operate with very high frequency, and because 1cm³ of nanoscale assembly systems can together perform vastly more operations per second than a single machine of size 1cm³.[^7],[^8]

This high throughput in turn suggests cheap products, for the following reasons:

* A complex APM system might be able to do efficient processing of input materials into whatever high-quality building blocks are required just as easily as it can do highly efficient assembly of those building blocks, and so be able to accept cheap and abundant input materials (only requiring the presence of the necessary chemical elements).

* Similarly, we might expect efficient processing to allow for harmless, easily manageable waste.

* A complex APM system might itself be cheap if it can manufacture copies of itself.

We can also appeal to naturally evolved systems, which seem to often be significantly cheaper to manufacture (at least based on a rough comparison of energy cost) than artificial ones, showing that nanoscale manufacturing systems can do cheap manufacturing.[^9]

For a more detailed discussion, see Appendix section <a href="#intuitions">More intuitions for why APM might be possible and impactful</a> below.

<a id="broadening">
## Broadening the scope from APM to advanced nanotechnology

As far as I know, EA efforts in this area have been focused on APM. I consider APM to be a remarkably concrete vision for future nanotechnology, and an extremely useful thing to analyse, but I tentatively propose that we slightly broaden the scope of work in this area to consider what I call **advanced nanotechnology**.

I define advanced nanotechnology as any highly advanced technology involving nanoscale machinery that allows us to finely image and control processes at the nanoscale, with manufacturing capabilities roughly matching, or exceeding, those of consequential APM.

Advanced nanotechnology covers a wider range of possible future technologies than APM. For example, a future nanotechnology might rely less on mechanical positioning or very stiff machines than APM does.[^10],[^11] But these technologies would look similar to APM in many ways, and might have the same strategic implications. My current feeling is that it’s better for strategy work to cover this wider area than to focus purely on APM.[^12]

## Advanced nanotechnology vs nanotechnology today

Note that advanced nanotechnology is fairly loosely connected to the concept that’s usually pointed to by the term “nanotechnology”.

The term “nanotechnology field” seems to commonly refer to a loose connection of research areas that are united by the fact that they concern physical systems on a length scale of between roughly 1-100nm (although there are lots of fields that aren’t usually considered nanotechnology that also concern physical systems on that length scale). The term “nanotechnology” is sometimes used to refer to useful (potential) products or technologies that come from this field.

See the later section called <a href="#current_landscape">Current R&D landscape</a> for my take on the present-day fields of research that are most relevant for advanced nanotechnology.

## Defining transformative AI (TAI)

At a few points in this post I’ll refer to “transformative AI”, usually through the abbreviation “TAI”. By this I mean “AI that precipitates a transition comparable to (or more significant than) the agricultural or industrial revolution”, which is the definition for TAI sometimes used by Open Philanthropy (for more detail on this definition, see [What Open Philanthropy means by "transformative AI"](https://perma.cc/B57J-WGXB)).

<a id="effects">
# Potential effects of advanced nanotechnology

Advanced nanotechnology’s extremely powerful capabilities suggest that its development could have very dramatic effects.

The potential effects listed below seem among the most important from a longtermist EA perspective. I’d guess that if advanced nanotechnology is developed within the next 20 years and we haven’t (yet) developed TAI, there’d be something like a 70% chance that it would have very dramatic effects, i.e. effects of at least similar importance to the ones described below.[^13] Note that the first two bullet points use the typology from Nick Bostrom’s paper [The Vulnerable World Hypothesis](https://perma.cc/86WF-PLY8).

* **Vulnerable world type-1 vulnerabilities.** Advanced nanotechnology might lead to widespread access to manufacturing devices able to make things like nuclear weapons, dangerous pathogens, or worse. This seems like a plausible outcome to me, assuming society were to fail to properly regulate and control the use of the technology.

* **Vulnerable world type-2a vulnerabilities.** Even if manufacture of highly destructive weapons doesn’t become widely available to ordinary citizens, advanced nanotechnology might allow states to manufacture weapons that pose an (even) greater probability of existential catastrophe than the highly risky weapons that are currently accessible (such as currently accessible nuclear and biological weapons). I’d place a [“grey goo”](https://perma.cc/9CTX-H6P2) scenario, where self-replicating nanoscale machines turn the entire world into copies of themselves, into this category. It seems very plausible to me that advanced nanotechnology would enable the development of weapons that pose a significantly larger existential risk than do our most dangerous present-day weapons. And while weapons that have a moderate-to-high chance of causing existential catastrophe might not seem very appealing on the face of it, it seems very plausible to me that at least some states would perceive a sufficiently high strategic benefit from developing them.[^14]

* **Reduced existential risk from state weapons.** On the other hand, in a reversal of the above scenario, advanced nanotechnology might lower existential risk from nuclear and biological weapons (or from other future weapons that pose an existential risk) by allowing states to develop weapons that are more strategically useful and pose a lower existential risk. This also seems very plausible to me.

* **More powerful computers, leading to earlier TAI.** Advanced nanotechnology could allow us to build more powerful computers more cheaply. If advanced nanotechnology is developed before TAI, having cheaper and better computers could lead to earlier TAI.[^15] This seems very plausible to me, and I’d also (very tentatively) guess that this would come earlier than the effects mentioned in the previous three bullet points.

Each of the above effects could constitute an existential risk or [existential risk factor](https://perma.cc/N8SF-BVJH), or could correspond to a reduction in existential risk. Overall, currently I’m very unsure about whether advanced nanotechnology would be good or bad for the world on net, and I’m very unsure whether I’d rather learn that advanced nanotechnology was coming sooner or later than expected (but I still currently think that acting to speed up the arrival of advanced nanotechnology is probably bad. See the later section <a href="#potential_harms">Potential harms from nanotechnology strategy research</a>).

Note that the potential effects described above all follow from having an extremely powerful and flexible manufacturing capability, and novel nanoscale devices as products are necessary only in the grey goo scenario.[^16]

For other potential effects of advanced nanotechnology, see the Appendix section <a href="#potential_effects">Other potential effects of advanced nanotechnology</a>.

# When and how advanced nanotechnology might be developed

This section is quite long and complex, so here is a quick summary:

* My rough guess is that there’s something like a 20-70% chance that advanced nanotechnology is feasible (where by “feasible” I mean: it’s possible in principle for a sufficiently advanced civilisation to build the technology, ignoring issues of economic feasibility). (<a href="#in_principle_feasibility">more</a>)

* I’d guess there’s currently something like $10-100 million per year of funding that is fairly well directed towards developing advanced nanotechnology. These efforts are mostly focused on using scanning probe microscopy, which doesn’t seem like the most effective approach for developing advanced nanotechnology. (<a href="#current_landscape">more</a>)

* My current very rough, unstable guesses regarding advanced nanotechnology timelines are:

  * Assuming feasibility, a median estimate of 2110 for the arrival of advanced nanotechnology. (<a href="#median_timelines">more</a>)

  * _Not_ assuming feasibility, a 4-5% probability that advanced nanotechnology arrives by 2040.  (<a href="#probability">more</a>)

  * Not assuming feasibility, _and_ assuming that advanced nanotechnology comes before TAI, a 1-2% probability that advanced nanotechnology arrives by 2040. (<a href="#probability">more</a>)

* It seems likely to me that there’d be a long period of development with clear warning signs before the arrival of advanced nanotechnology. (<a href="#progress">more</a>)

<a id="in_principle_feasibility">
## In-principle feasibility

In this section, I briefly give my views on whether APM technologies, and advanced nanotechnology more broadly, are feasible in principle. By “feasible in principle”, I mean that it’s possible in principle for a sufficiently advanced civilisation to build the technology, ignoring issues of economic viability.

The probabilities given in this section are based on only relatively shallow thinking and are very unstable, and shouldn’t be taken as more than a rough indication of my personal guesses at the time I wrote this. [^17]

As noted in the earlier section <a href="#intuitions">Intuitions for why APM might be possible and impactful</a>, we know that core APM is feasible because examples of it exist in nature.

Maybe I’d give a 50% probability that complex APM is feasible. While I think there’s a significant chance that complex APM is feasible, and I’m not aware of convincing arguments that it couldn’t possibly be built, I wouldn’t find it that surprising if it turns out to be impossible. For example, it might turn out that it’s not possible to find suitable arrangements of atomic building blocks, given the finite selection of atoms and atomic sizes.

Assuming that complex APM is feasible, it seems pretty plausible to me that consequential APM is also feasible. Maybe I’d give this a 10-50% probability (implying that I guess a 5-25% unconditional probability that consequential APM is feasible). The earlier section <a href="#intuitions">Intuitions for why APM might be possible and impactful</a> and the Appendix section <a href="#more_intuitions">More intuitions for why APM might be possible and impactful</a> cover some reasons for thinking that complex APM might be feasible. In addition to those points, I’d note that Drexler has published technical arguments for the in-principle feasibility of APM (including a book, _[Nanosystems](https://www.amazon.com/Nanosystems-P-K-Eric-Drexler/dp/0471575186/)_, which explores designs and capabilities), and in my view no-one has shown that the technology is not feasible despite some attention on the question.[^18]

I don’t assign a higher probability to the feasibility of consequential APM because I feel like there could be practical barriers that block the development of consequential APM even if complex APM is feasible. For example, maybe the system can’t be made reliable enough or is very expensive to maintain (so that the “very cheap products” condition can’t be met), or maybe there just aren’t any designs that allow you to take advantage of the favourable theoretical properties of nanoscale assembly systems.

Advanced nanotechnology is, by definition, at least as likely to be feasible as consequential APM, and we might consider it to be substantially more likely to be feasible because it covers a much wider array of potential technologies. Overall, I’d guess something like a 20-70% chance that advanced nanotechnology is feasible. This is around 3 times as large as my guess for the probability that consequential APM is feasible, which feels reasonable to me.

<a id="current_landscape">
## Current R&D Landscape

Anecdotally, my impression is that the majority of researchers in fields relevant for advanced nanotechnology haven’t heard of APM, and don’t think about visions for transformative nanotechnology more generally.[^19]

Correspondingly, there is not much R&D explicitly targeting APM or broader advanced nanotechnology, as far as I’m aware.

I’d guess there’s something like $10-100 million per year of funding that is fairly well directed towards developing advanced nanotechnology. This is mostly being spent (according to my guess) at [Zyvex](https://perma.cc/765Z-XAHC) and on [a project at Canadian Bank Note](https://perma.cc/G6D6-4MW9). These projects use an approach involving scanning probe microscopy[^20] to make progress towards APM (sometimes called the “hard path” to APM), which doesn’t seem like the most promising approach,[^21] although of course surprises are always possible.

Particular examples of less well-targeted, but still relevant, work include:

* Impressive work on protein engineering from [David Baker’s lab](https://perma.cc/3R8B-ZBQ9).

* Work on spiroligomers from [Christian Schafmeister’s group](https://perma.cc/ADN9-FUHJ).

* Some DNA nanotechnology projects from the [Shih group](https://perma.cc/T74Y-WPQZ) and the [Turberfield group](https://perma.cc/M7Y4-K4LU).

More broadly, my impression is that the most relevant work for progress towards advanced nanotechnology is:

* Work in the protein engineering and DNA nanotechnology fields.

* Work on spiroligomers and foldamers, as well as supporting technologies such as computational approaches ([AlphaFold](https://perma.cc/9JE7-KZLR) is a notable example relevant for protein engineering) and nanoscale imaging.

* Work on advancing scanning probe microscopy.

* Perhaps to a lesser extent, a broad class of work on non-biological dynamic nanoscale systems.[^22]

## Timelines

### Considerations relevant for thinking about APM timelines

In this section, I’ll discuss considerations relevant for thinking about when APM might be developed. I focus on APM here rather than broader advanced nanotechnology because I find it easiest to first think about APM and then consider how much earlier things might happen if we consider timelines to advanced nanotechnology of any form, rather than just timelines to APM.

The most obvious consideration pushing against short timelines for APM is the very slow rate of progress towards APM in the last 35 years. For example, atomic manipulation with scanning probe microscopes doesn’t seem to have improved very much since the original demonstration of the technique by IBM in 1989. In addition, despite significant progress in protein engineering, positional assembly with protein suprastructures (which is perhaps the first step on a hypothesised pathway to APM called the “soft path”, as discussed in footnote 5) has still not been demonstrated.[^23] Overall, my very rough (and unstable) guess would be that we’ve come perhaps 10% of the way to APM in the past 35 years.

Aside from the empirical observation of slow progress, my inside-view impression is that it would be an enormous engineering challenge to make progress along the technical pathways sketched for APM. Further down the line, it also seems hugely challenging to engineer complex APM systems; although perhaps this is mitigated by the consideration that very stiff, later-stage systems might be much more predictable (and so easier to model and engineer) than early-stage ones.

An additional consideration pushing against short timelines is that it doesn’t seem like there would be many commercial applications from making the first few steps towards APM (even though later stages might have lots of commercial applications). This reduces the incentive for private research efforts and reduces researcher interest within academia.

Some considerations push in favour of shorter timelines for APM, however.

Firstly, in outlining the “soft path” to APM (see footnote 5), Drexler has sketched a technical pathway to APM that I find plausible.

In addition, it seems plausible that an APM field could emerge over the next decade, or perhaps that some highly targeted and well-resourced private effort will emerge. Because there has been relatively little highly targeted effort towards the development of APM so far, we have relatively little empirical evidence regarding what rate of progress would be possible under such an effort; perhaps progress would be much faster than expected.[^24]

Further, advances in AI are leading to advances in our ability to model molecular systems, most notably in the field of protein folding, which is particularly relevant for near-term progress along the soft path to APM. It seems plausible to me that increasingly powerful AI, even if it falls short of TAI, will lead to surprisingly fast progress towards APM.

Finally, it seems very possible that the arrival of TAI would lead to the rapid development of APM. This might significantly shorten your timelines for APM, depending on your timelines for TAI.

<a id="median_timelines">
### Median timelines

As mentioned above, my guess for the probability that advanced nanotechnology is feasible in principle fluctuates between roughly 20% and 70%. If my probability for feasibility is less than 50%, it doesn’t really make sense to talk about a median timeline: if I think the chance that it’s possible to develop advanced nanotechnology is less than 50%, it wouldn’t make sense to think that at some point in the future there’s a 50% chance that we’ve developed advanced nanotechnology.

Assuming advanced nanotechnology is feasible in principle, my median timeline is perhaps something like 2110. But this number is very made up and not stable. It also interacts pretty strongly with my timelines for TAI, since TAI could massively accelerate technological progress.

Another data point comes from Robin Hanson in 2013, when he [reported a guess](https://perma.cc/WN43-NE2D) of roughly 100-300 years until something seemingly roughly equivalent to advanced nanotechnology is developed.

<a id="probability">
### Probability of advanced nanotechnology by 2040

We might be particularly interested in the probability that advanced nanotechnology arrives in the next couple of decades, since events further in the future seem generally harder to influence.

We might also be particularly interested in worlds where advanced nanotechnology is not preceded by TAI, because, for example, we might think that after TAI “everything goes crazy” and it’s hard to make useful plans for things that happen after that point. Personally, I think it’s reasonable to imagine that work on nanotechnology strategy will be much less useful if advanced nanotechnology is preceded by TAI, although I’m not at all confident about this and my view feels quite unstable.

I’d guess there’s something like a 1-2% chance that advanced nanotechnology arrives by 2040 and isn’t preceded by TAI.[^25] As with my median timeline, this number is very made up and not stable.[^26]

For the probability that advanced nanotechnology arrives by 2040 and is preceded by TAI, my current speculative guess is something like

<blockquote> “16% chance of TAI by 2040” <br>
× “50% chance that advanced nanotechnology is feasible in principle” <br>
× “40% chance that advanced nanotechnology is developed between TAI and 2040, given that TAI arrives before 2040 and that advanced nanotechnology is feasible in principle” <br>
= 3% chance that advanced nanotechnology arrives by 2040 and is preceded by TAI. </blockquote>

You might want to substitute your own probabilities for the arrival of TAI and/or the chance that TAI leads to the development of advanced nanotechnology.

Overall, then, adding the above probabilities implies that my guess is that there’s a 4-5% chance that advanced nanotechnology arrives by 2040. Again, this number is very made up and not stable.

<a id="progress">
## Rate of progress and warning signs

I imagine that developing advanced nanotechnology would be a huge engineering challenge, and there would be a lengthy road to get there from where we are today. In the median case, I imagine that it would be extremely obvious for many years that this kind of work is being done: the field might look a bit like the present AI field, for example, with notable private-sector efforts alongside lots of work in academia. It seems very unlikely, though possible, that progress would be driven by some huge, secretive, Manhattan Project–style effort instead; but even in that case, it seems like informed people would probably know that something was up, for example by noticing that relevant academics had suddenly stopped publishing.

The main ways I can see the above picture being wrong are:

* Technical progress just turns out to be way easier than it seems now. Maybe surprisingly quick progress along the “hard path” to APM (i.e. making progress using scanning probe microscopy) is the most likely way this could happen.

* Pre-transformative AI dramatically speeds up the rate of progress in relevant fields.

* Transformative AI dramatically speeds up technological progress (but then maybe “all bets are off” anyway).

It’s worth noting that if we’re focused on worlds where advanced nanotechnology arrives in the next 20 years, we should presumably focus more than we would otherwise on worlds where progress happens surprisingly quickly. This is because worlds where advanced nanotechnology arrives in the next 20 years will tend to be worlds where progress happens surprisingly quickly (for example, if there is a gradual ramp up in progress over the next 30 years, we obviously won’t have the technology in 20 years’ time).

# Current landscape for nanotechnology strategy

I’m aware of little thoughtful nanotechnology strategy work currently being undertaken, and I don’t think there’s a very large amount of high-quality existing work.

The most notable public EA work in this area that I’m aware of is a 2015 Open Philanthropy report called [Risks from Atomically Precise Manufacturing](https://perma.cc/V7HG-P72D).

As far as I know, no-one in the EA community, other than me, is currently spending a significant fraction of their time thinking about this or is planning to do so. Due to other (potential) projects competing for my time, I’d guess I’ll spend something like 25% of my time on nanotechnology strategy-related things on average in the next 12 months, with a good chance (maybe 50%) that I don’t spend much time at all on nanotechnology strategy things in the next 12 months. Maybe I’d guess I’ll spend 40% of my time on average on nanotechnology strategy things over the next 5 years.

Outside of EA, the [Foresight Institute](https://perma.cc/T9TG-ZAGR) has historically thought about nanotechnology strategy questions, and they have perhaps 0.2-0.6 FTE working in this broad area currently. Other organisations have been active in this area, such as the [Center for Responsible Nanotechnology](https://perma.cc/N9WP-9LXZ) and the [Institute for Molecular Manufacturing](https://perma.cc/HN7Z-XQKA),[^27] but I’m not aware of relevant recent work. I think that a lot of the public work in this area has been of low quality, and overall I think the existing work falls a long way short of providing complete and high-quality coverage of the important questions within this area.

<a id="prospects">
# Prospects for making progress

The high-level goals of EA work in this area could be to reduce the chance of an existential catastrophe due to advanced nanotechnology, to use its development to reduce existential risk from other sources, or more broadly to achieve any attainable value related to its development.

Potentially valuable interventions might include:

* Seeking to speed up particular technical research areas where that seems to promote safety.

* Making policy recommendations related to regulating, monitoring, and understanding emerging advanced nanotechnology.

* Positively steering the development of advanced nanotechnology by being a major early investor or founder.

We have some reasons to expect progress to be hard in this area: the technology appears likely to be many decades away, and the terrain for strategy work is poorly mapped out at present.

On the other hand, the fact that the world is not paying much attention to advanced nanotechnology gives altruistic actors a chance to make preparations now in order to, for example, be in a position to make impactful policy recommendations at critical moments later. In addition, the relative lack of exploration makes it hard to rule out the existence of valuable low-hanging fruit. And, regarding our understanding of the technology itself, advanced nanotechnology is more opaque than risky biotechnology, but perhaps compares favourably with artificial general intelligence (AGI), since APM is arguably a more plausible blueprint for advanced nanotechnology than present-day machine learning methods are for AGI.

<a id="concrete">
## Examples of concrete projects

One concrete project could be to **consider what you would do if you knew that advanced nanotechnology was coming in 2032, seeking areas of consensus among EA-aligned individuals who are well informed about nanotechnology strategy**. The results could inform what we should do now (given our actual timelines), perhaps pointing to a particular high-value intervention. The results could also help generate a plan to hold in reserve in case our advanced nanotechnology timelines were to dramatically shorten, increasing the chance that EAs successfully execute high-value interventions in the case of shortened timelines. In addition, the exercise would be practice for future strategic thinking, potentially increasing the chance that EAs successfully execute high-value interventions at some future time after a change of circumstances or further deliberation.

Another project could be to **clarify what the key effects of complex APM that we want to forecast are; work out the technical requirements of these effects; and create forecasts using trend extrapolation, other outside-view considerations and methods, and inside-view judgements**. These forecasts could help prioritise nanotechnology strategy research against work in other cause areas. That way, if advanced nanotechnology timelines turn out to be shorter than initially believed, more effort can be exerted in this area, increasing the chance that EAs and others successfully identify and execute high-value interventions. Forecasts of various key effects could also be helpful for directing work within nanotechnology strategy towards the most high-value sub-areas, perhaps increasing the chance that high-value interventions are found and successfully executed.

A third potential project could be to **identify and monitor potential warning signs of surprising progress towards advanced nanotechnology**, for example by identifying the most relevant areas of current research, the most important research groups, and key bottlenecks and potential breakthroughs. Similarly to the previous project, this monitoring could help prioritise nanotechnology strategy research against work in other cause areas, so that more resources are expended in this area if progress appears to be accelerating, increasing the chance that EAs and others successfully identify and execute high-value interventions.

<a id="prioritise">
# How to prioritise nanotechnology strategy research

This section gives some arguments and considerations relevant for prioritising nanotechnology strategy research against other cause areas from a longtermist EA perspective. To skip to my personal bottom line view on this, see the final subsection of this section, <a href="#my_view">My view on how longtermist EAs should be prioritising this work against other areas right now</a>.

## A case for nanotechnology strategy research

Pulling together the information presented in the previous sections, a rough, high-level argument for nanotechnology strategy research being highly valuable from a longtermist EA perspective could be the following:

1. **Advanced nanotechnology could have dramatic effects**, with both positive and negative potential implications for existential risk.

2. There seems to be a **non-negligible (although low) probability that it will arrive within the next 20 years**, even if it’s not preceded by TAI (my wild guess is that there’s a 1-2% probability of this).

3. There’s been **very little high-quality work in this area**.

4. It **seems possible to make progress** in this area.[^28],[^29] I’d also note that I think there’s a synergy between nanotechnology strategy and other areas like AI governance and biosecurity, which makes work in nanotechnology strategy more tractable and more valuable than it would be otherwise. Specifically, because these areas all concern trying to make the development of very powerful emerging technologies go well for the world, methodologies and findings seem likely to be transferable between these areas to some extent.

<a id="wait">
## Could we wait until advanced nanotechnology is about to be developed?

As discussed in the earlier section <a href="#progress">Rate of progress and warning signs</a>, my current guess is that there’s very likely to be a long, obvious-to-the-outside-world R&D process before advanced nanotechnology is developed. This pushes in favour of deprioritising this area until there are signs that progress towards advanced nanotechnology is speeding up.

However, this depends on to what extent nanotechnology strategy work needs to be done sequentially versus in parallel. The more the work needs to happen sequentially, the more it’s worth doing work now. I feel very uncertain about this, although it seems like the work is probably at least a bit sequential. For example, maybe it takes time to lay the conceptual foundations for a new topic, and also presumably it takes time for people to get up to speed and start making contributions.

In addition, we might think that being one of the first to act in this space when progress starts to pick up is valuable. I’d guess there could be a fair amount of value here.

Overall, I think the likely slow and easy-to-detect ramp up towards advanced nanotechnology pushes in favour of spending relatively few resources now to do foundational work, while carefully monitoring progress and being ready to pivot to spending lots of EA effort in the area if that seems important.

<a id="potential_harms">
## Potential harms from nanotechnology strategy research

Nanotechnology strategy is a very complex area, and there are many potential harms from well-intentioned nanotechnology strategy work.

It currently seems to me that we don’t want to speed up progress towards advanced nanotechnology. Roughly speaking, I think this because i) the potential effects of the technology seem dramatic, but very uncertain (they could be very good or very bad), ii) it seems plausible that accelerating progress will be hard to reverse, and iii) we have the option of waiting and potentially gaining more information about the effects of the technology. It seems plausible that accelerating progress will be hard to reverse because, for example, visibly faster progress could generate more interest and a stronger research effort, which in turn sustains the rate of progress. (Though note that I still feel a bit confused about how harmful various forms of accelerating progress might be, including whether some forms would be harmful at all, and I’d like to think more carefully about this topic.)

Because accelerating progress seems bad, public talk about advanced nanotechnology in a way that hypes the technology or otherwise generates interest in developing it could cause harm by speeding up progress towards the technology. And it seems relatively easy to notably increase attention on the technology given that there’s currently relatively little attention on it.[^30] Emphasising military applications seems particularly undesirable, since it might tend to push the direction of the technology’s development towards dangerous applications.

In addition, findings from nanotechnology strategy research could, in some cases, represent information hazards that would inform efforts to speed up advanced nanotechnology development. Examples include findings from efforts to better understand advanced nanotechnology timelines by mapping out technical pathways, or from mapping out scenarios for the development of an advanced nanotechnology field. While it’s possible in principle to keep these findings private, there are advantages to public communication, and exchanging ideas with people interested in speeding up the development of advanced nanotechnology is often very helpful for doing nanotechnology strategy work. So the right policy here isn’t always obvious.

Because this is a relatively unexplored area, maybe there’s also a risk that poor initial attempts at nanotechnology strategy research will 'poison the well', doing long-term damage to the ability for progress to be made in this area. This could happen because researchers develop a poor set of concepts, or because EA-aligned people communicate with policymakers in a poorly thought-out way that discourages them from engaging with EA-aligned people in the future.

There may also be a risk that nanotechnology strategy research leads to making policy recommendations that turn out to be harmful and hard to reverse. For example, this could occur if a policy recommendation seems beneficial after a shallow investigation, but enough thought would show it to be harmful.

Relatedly, some individual or group of nanotechnology strategy researchers might mistakenly come to believe that accelerating progress towards advanced nanotechnology is a worthwhile goal, and then act to accelerate progress, causing irreversible damage. (To be clear, I also think it’s possible that at some point we’ll correctly determine that accelerating advanced nanotechnology progress is a worthwhile goal.)

<a id="mitigating">
## Mitigating the risks of harm

To reduce the risk from these potential harms, prospective nanotechnology strategy researchers require good judgement and a strong support network they can turn to for high-quality advice and feedback. Keeping the [unilaterist’s curse](https://perma.cc/Y3AJ-JUA8) in mind also seems important.

Prospective funders in this area should keep these traits in mind when considering who to fund. In addition, funders could, for example, look for an assurance that nanotechnology strategy researchers won’t share their work outside a trusted circle without particular trusted individuals giving approval.

## Why you might not think work in this area is high priority

Here are a couple of reasons you might not consider work in this area to be high priority from a longtermist EA perspective.

Firstly, you might think that it’s just too difficult to make progress towards concrete impact, because advanced nanotechnology is likely to be far off in time, and hard to analyse because its precise nature is very uncertain. Tangible interventions are notably absent right now.

I think this is a reasonable position, although I disagree with it. I think there are concrete projects that seem useful (see the earlier section <a href="#concrete">Examples of concrete projects</a>), I think that this area is too unexplored to be very sure that there isn’t valuable work here, and I think that in scenarios where advanced nanotechnology arrives in the next couple of decades we’ll be glad that work was done in the early 2020s.

Secondly, you might just be convinced that some other area is much more important from a longtermist EA perspective, so that you don’t think longtermist EA resources should be spent on nanotechnology strategy research. For example, maybe you have short AI timelines and think AI safety work is at least moderately tractable.

Again, I think this position is reasonable (either regarding the great importance of AI safety work, or some other area), although it’s not a position I hold — cause prioritisation is hard, and there’s lots of scope for reasonable people to disagree.

<a id="my_view">
## My view on how longtermist EAs should be prioritising this work against other areas right now

In this section I’ll briefly give some more concrete views on how people from the longtermist EA community should prioritise working on this compared to working in other areas. I haven’t thought about this a huge amount (and this kind of prioritisation is extremely difficult and also strongly depends on details that I’m brushing over), so these are extremely rough views and are liable to change in the near future. But reviewers of earlier drafts of this post were keen to see something like this, so I’m providing it here.

I’d guess that some small, non-zero fraction of EA resources should be going into nanotechnology strategy research right now. In particular, a rough guess might be that we want to move to having 2-3 people each spending at least 50% of their time on this in the next 3 years, and maybe get to 4 FTE in 5 years.

So I don’t think we should be piling a huge amount of resources into this, but the resource allocation I’m suggesting comes against a background of (it seems to me) something like 0-0.5 FTE of longtermist EAs thinking about this at any given time over the past 5 years. So this would represent a significant change from the status quo.

Another angle on this is my view on the following highly abstract case: if I had an aspiring researcher in front of me who seemed about an equally good fit for nanotechnology strategy research, biorisk research, AI safety research, and AI governance research, I’d rank nanotechnology strategy research a bit below the others. I’d rank the options in this way because I think we should be able to recruit enough people from the pool of people who are a better fit for nanotechnology strategy research than for research in other areas (but again, I feel very uncertain about all of this).

# Some guesses at who might be a good fit for nanotechnology strategy research

Being broadly longtermist EA-aligned seems important for doing work in this area.

In addition, I’d guess that, very roughly speaking, the following sorts of people would be a particularly good fit for nanotechnology strategy research:

* People with chemistry/physics/biology/materials science backgrounds (among others), and especially people with PhDs in those areas.

* People who have done this kind of “strategy” thinking in other contexts, including in other EA areas like AI risk or ending factory farming.

* People who are thoughtful, have good judgement, and are not likely to act unilaterally.
* People who are willing to build the support network mentioned in <a href="#mitigating">Mitigating the risks of harm</a>.

* People willing to tackle something hard and relatively unexplored, and willing to go for higher-risk things on the basis of high expected impact.

* People who are okay with doing work that might be less legible to the outside world because of infohazard concerns and the unpredictable nature of exploratory research.

# Conclusion

Advanced nanotechnology could significantly increase or decrease existential risk, and might arrive in the next couple of decades, even without transformative AI. So far there’s been relatively little high-quality work aimed at making its development go well for the world. Doing nanotechnology strategy research now can help lay the foundations to increase the chance that the development of the technology goes well.

I would love to see more people considering working in this area. If you’re interested in learning more, and especially if you’re interested in trying out work in this area now or later in your career, please get in touch by sending me an email at hello[at]bensnodin dot com.

# Acknowledgements

_This post was written by me, Ben Snodin, in my capacity as a researcher at [Rethink Priorities](http://rethinkpriorities.org/). I finished writing this post while at Rethink Priorities, and I did a lot of the work for it prior to joining Rethink Priorities, while employed as a Senior Research Scholar at the Future of Humanity Institute. Many thanks to James Wagstaff, Jennifer Lin, Ondrej Bajgar, Max Daniel, Daniel Eth, Ashwin Acharya, Lukas Finnveden, Aleš Flídr, Carl Shulman, Linch Zhang, Michael Aird, Jason Schukraft, and others for their helpful feedback, and to Katy Moore for copy editing. If you like Rethink Priorities’ work, you could consider [subscribing to our newsletter](https://www.rethinkpriorities.org/newsletter). You can see more of our work [here](https://www.rethinkpriorities.org/research)._

# Appendix

## Further reading

**Update 2022-10-24:** See [here](http://www.bensnodin.com/research_articles/nanotech_resources_database/) for a more comprehensive and up-to-date database of resources.

Some resources that are especially relevant for nanotechnology strategy research are:

* [Risks from Atomically Precise Manufacturing](https://perma.cc/S6JF-ZWSE) (2015) by Open Philanthropy.

* [Evaluating Future Nanotechnology: The Net Societal Impacts of Atomically Precise Manufacturing](https://perma.cc/E56C-RHPX) (2018), a paper from Steven Umbrello and Seth Baum.

These resources are also useful for context and technical understanding:

* [Bottleneck analysis: positional chemistry](https://perma.cc/WN7P-DV34), a report from Adam Marblestone that includes a detailed introduction to “positional chemistry” (a concept that is closely related to advanced nanotechnology), a history of nanotechnology, and details of relevant past and present areas of R&D.

* Richard Jones’s blog [Soft Machines](https://perma.cc/3V57-QDJL) contains writing on advanced nanotechnology, including a [2007 explainer of debates around nanotechnology](https://perma.cc/4EZX-XFVL).

* Eric Drexler’s books: _[Engines of Creation](https://www.amazon.com/Engines-Creation-Nanotechnology-Library-Science/dp/0385199732)_ (1986), _[Unbounding the Future](https://www.amazon.com/Unbounding-Future-Nanotechnology-Eric-Drexler/dp/0688125735/ref=sr_1_1?keywords=Unbounding+the+Future&qid=1663337414&sr=8-1)_ (1991), _[Nanosystems](https://www.amazon.com/Nanosystems-P-K-Eric-Drexler/dp/0471575186/)_ (1992), and _[Radical Abundance](https://www.amazon.com/Radical-Abundance-Revolution-Nanotechnology-Civilization/dp/B08ZBRRZML)_ (2013).

* [Nano-solutions for the 21st century](https://perma.cc/HM8S-BQA4) (2013), a report by Eric Drexler and Dennis Pamlin.

* [Kinematic Self-Replicating Machines](https://perma.cc/5T8V-U7S4) (2004), a book by Robert Freitas and Ralph Merkle (note that I have only skimmed small parts of it).

* The [Foresight Institute website](https://perma.cc/ZV52-BNW9) has relevant articles and talks, some of which are useful for gaining technical knowledge.

<a id="apm_definitions">
## APM definitions in more detail

This section provides more detailed definitions for the core APM, complex APM, and consequential APM concepts introduced in the main text in Definitions and intuitions.

I define **core APM** as:

<blockquote> A system of nanoscale, atomically precise machines that can mechanically assemble small molecules into useful atomically precise products. </blockquote>

Where:

* By _nanoscale_ I mean “extremely small”, roughly of length 1-100nm in each dimension. For comparison, atoms often have a diameter of around 0.1-0.2nm. Note that a core APM system, while composed of nanoscale machines, might itself be larger than 100nm.

* _Atomically precise machines_ means machinery that has exactly the desired atomic structure. Similarly, _atomically precise products_ means products that have exactly the desired atomic structure.

* _Mechanically assemble small molecules_ means (in this context): use nanoscale machines to control the motion of small molecules, using short-range intermolecular forces, such that the molecules form stable bonds with some partially constructed product.

We can describe a particular form of core APM that uses complex, very stiff components and performs many operations per second. In addition, we can imagine that the products from the nanoscale assembly system are used as inputs to slightly bigger (but otherwise very similar) assembly systems, which in turn assemble them into bigger products; and so on until you get to whatever size product you want (including everyday-scale things like laptops). Finally, we can slightly relax the definition to include systems where the assembly machines and products are only mostly atomically precise, and where the assembly method is only mostly mechanical assembly.

I label such a technology **complex APM** (the modifications to the core APM concept are in bold):

<blockquote> An <strong>extremely complex, intricate</strong> system of <strong>very stiff</strong> nanoscale, <strong>(mostly)</strong> atomically precise machines <strong>joined to progressively bigger assembly systems</strong> that <strong>operate in a vacuum and perform many operations per second</strong> to <strong>(mostly)</strong> mechanically assemble small molecules into <strong>(mostly)</strong> atomically precise products <strong>with high throughput, and with product sizes ranging from from nanoscale to metre-scale and beyond</strong>.</blockquote>

Finally, Drexler claims that these APM systems could create a wide range of complex, very high performance products very cheaply and with very high throughput. In this spirit, I define **consequential APM** to refer to:

<blockquote> A complex APM technology that can <strong>create a range of complex, very high performance products for $1000/kg or less and with a throughput of 1kg every 3 days or less per kg of machinery</strong>.</blockquote>

<a id="more_intuitions">
## More intuitions for why APM might be possible and impactful

This section expands on the <a href="#intuitions">Intuitions for why APM might be possible and impactful</a> described in the main text. As in the main text, these arguments are designed to give the reader some feeling for why you might believe these things rather than constituting cast-iron proofs.

See Drexler’s 1992 book, _[Nanosystems](https://www.amazon.com/Nanosystems-P-K-Eric-Drexler/dp/0471575186/)_, for a treatment of the physics underlying nanoscale manufacturing systems. Chapter 2 covers the scaling of important physical properties with system size and is particularly relevant for intuitions about nanoscale manufacturing technology.

### Intuitions for why atomic precision might be a natural goal

If you want to build high-performance systems and products on the nanoscale, it’s perhaps natural to build systems and products with atomic precision.

As mentioned in the main text, if you have small molecules as building blocks and you’re making products on the order of 1-100nm, you’re building things out of discrete building blocks with a width roughly 1/10th to 1/1000th of the width of the product you’re building. You may well then need atomic precision in order to build the product to the correct specification.

In addition, molecular building blocks are perfect copies (e.g. all oxygen molecules are the same[^31]), which bond together in discrete ways to form a finite set of possible structures. So by insisting on atomic precision, you get perfectly faithful physical realisations of your design.[^32]

Finally, given high-performance systems that are able to manufacture things with an extremely high degree of control, and if atomically precise products will often give significantly higher performance, atomically precise products will perhaps be an attractive target.

### Intuitions for high-performance products

One reason we might expect complex APM to produce a very wide range of complex products is that building things by successively adding small molecules would seem to allow for huge flexibility in products. We see something similar with 3D printers today, which successively add material to a growing structure and can create a wide range of complex structures.

To give some intuition for the claim that atomically precise products can achieve very high performance, the semiconductor industry spends tens of billions of dollars annually on R&D to manufacture chips with increasingly finer-grained features, a pathway that ends with atomic precision (or close to it). (To be clear, I’d imagine that far more impressive products would be possible with flexible atomically precise fabrication.)

As mentioned in the main text, another angle is to consider that, with today’s technology, naturally evolved systems and devices often outperform present-day artificial ones on important dimensions. These evolved systems are certainly not atomically precise (although they contain some atomically precise components), but they show that we are currently some way from the maximum achievable performance along many dimensions. In addition, some people, including Drexler, have argued that evolved systems necessarily look different to designed ones, and that this doesn’t imply that designed systems must be inferior.[^33] A highly flexible manufacturing capability that can exactly produce a vast array of complex products defined down to the last atom might seem able to meet and perhaps dramatically exceed the performance of evolved systems.

### Intuitions for high operating speeds and high throughput

As mentioned in the main text, one reason to think that nanoscale machines might achieve high throughput is that these machines can in principle each operate very rapidly, because they are made of very stiff materials and each operation only needs to involve movements over very short distances.

As was also noted in the main text, another reason is that the machines are not too much bigger than the small molecules they are manipulating during the assembly process. This makes a high rate of production per gram of manufacturing system more plausible than in the case of fabrication using present-day atomic force microscopes, for example, where a machine weighing 0.1 grams (or more) performs assembly operations on single atoms weighing around 10<sup>-23</sup> grams.

In addition to these considerations, the performance of biological machines suggests that complex APM could produce products fast. Some bacterial cells can double in both cell count and total mass of cells roughly every 10 minutes. Cells are not themselves atomically precise, but they include nanoscale atomically precise components, so we can consider this as an example of atomically precise components producing their own mass in product (copies of themselves) in 10 minutes, albeit as part of a larger system that is acting to produce a copy of all of its components.[^34],[^35]

### Intuitions for low cost

As argued in the main text, high throughput could lead to cheap products from complex APM if the machinery uses cheap inputs; is itself cheap; and produces harmless, easily manageable waste.

We might expect the inputs to be cheap if they consist of readily available raw materials, with minimal processing required before they are passed to the APM system.

This might make sense if complex APM machinery is able to deal with minimally processed inputs, mostly requiring only that the right chemical elements are present in the inputs (not necessarily in the right ratios). This could be the case if the machinery was able to cheaply and efficiently do most of the required processing itself, which might seem plausible for complex APM machinery that is able to efficiently produce a wide range of atomically precise products through mechanical assembly.

Inputs containing the right chemical elements might be cheap if only commonly occurring elements are needed. One reason to think that only common elements are needed is that carbon, a relatively abundant element, seems to be an excellent building material: carbon forms diverse atomic-scale structures and has excellent physical properties (for example, it can exist as diamond, graphite, or carbon nanotubes, and diamond is extremely hard and stiff).

The complex APM machinery could be cheap because, once you know how to make it, perhaps you could use it to make lots more machinery, just as you could use it to make any other product.

We might expect the complex APM machinery to produce harmless, easily manageable waste because, as with processing inputs, we might expect that if we can build machinery that is able to efficiently produce a wide range of atomically precise products through mechanical assembly, we can also build similar machinery that can efficiently process waste into a harmless and easily manageable form.

Finally, as mentioned in the main text, we can also consider that naturally evolved systems seem to often be significantly cheaper to manufacture than artificial ones, at least by a rough comparison of energy cost according to the quick investigation by Paul Christiano described in [Simple evolution analogy](https://perma.cc/6RRR-C85Z).

<a id="potential_effects">
## Other potential effects of advanced nanotechnology

Other than the potential effects mentioned in the main text in the section <a href="#effects">Potential effects of advanced nanotechnology</a>, some (perhaps) less important effects of advanced nanotechnology being developed might be:

* **An “extremely powerful surveillance and non-lethal control” scenario**. Advanced nanotechnology might allow states to cheaply manufacture ubiquitous, centrally controlled drones the size of insects or small mammals to monitor and control the world’s population using non-lethal force.[^36] This seems like a plausible outcome to me. This capability might lead to or facilitate [value lock-in](https://perma.cc/LD3E-DQRPn) (probably a very bad outcome), but it also seems possible that it would reduce existential risk by mitigating “vulnerable world type-1” vulnerabilities.

* **Advanced nanotechnology as a TAI capability.** TAI could lead to the rapid development of advanced nanotechnology. This could allow an agent-like AI to quickly create more powerful hardware and thereby gain the ability to rapidly transform the physical world.

* **Impacts on biorisk.** Advanced nanotechnology, or technologies along the path to it, seem likely to make it easier to develop things that could increase or decrease biorisk, including deadly pathogens, DNA sequencing devices, and biosensing devices. It might also enable a highly robust, rapid, local capability to manufacture medical countermeasures in a scenario where a global biological catastrophe has destroyed supply chains and important infrastructure.[^37]

* **Advanced neurotechnology.** Advanced nanotechnology might allow us to monitor the brain at very high resolution, potentially enabling [whole brain emulation](https://perma.cc/AW38-KAHJ) or neuromorphic AI. It seems unclear whether this would be good or bad overall.

* **Cheap energy.** Cheap, powerful manufacturing might enable the fabrication of cheap solar cells and cheap batteries that help to overcome intermittency in solar power, leading to very cheap solar power (although, naively, I’m unsure how large an effect this would be given that advanced nanotechnology wouldn’t on the face of it reduce land and labour costs).

* **Reduced risks from catastrophic climate change.** With advanced nanotechnology, we might be able to return atmospheric CO2 concentrations to pre-industrial levels for a relatively small cost using cheap, high-performance direct air capture devices powered by cheap solar. This could reduce the risk of catastrophic climate change, and also reduce existential risk if we believe that climate change poses such a risk.

* **Improved resilience to global catastrophes.** As mentioned above, advanced nanotechnology might provide a highly robust and powerful local capability to manufacture medical countermeasures during a global biological catastrophe. More generally, the technology could enable greater resilience to global catastrophes by broadly enabling local, rapid production of vital goods, equipment, and infrastructure without requiring pre-existing infrastructure or supply chains, and regardless of environmental damage. One example might be food production without relying on sunlight or global supply chains (see also [resilient foods](https://perma.cc/RE7M-GSKG)). This could reduce the chance that a global catastrophe precipitates an existential catastrophe.

* **Dramatic improvements in medicine.** Aside from an expectation that cheap, powerful manufacturing would be useful for fabricating medical products (just as for most other products), advanced nanotechnology might be particularly useful for developing improved medical interventions. One high-level reason for thinking this is that humans are mostly made of cells, and cellular processes happen at the nanoscale, suggesting that artificial nanoscale devices might be particularly useful.

* **General wealth / economic growth.** On the face of it, if we can make high-performance materials and devices very cheaply, people will on average be very wealthy compared to today (whether this is a deviation from trend GDP growth will, of course, depend on when and how the technology is developed).

* **Social effects.** Advanced nanotechnology could have important social effects, especially if it arrives abruptly. For example, strong economic growth might generally promote cooperation, while rapid technological changes might cause social upheaval.

* **Altering the global balance of power.** Advanced nanotechnology might change the global balance of power. For example, it might dramatically shorten supply chains by enabling highly efficient production with unrefined local materials, leading to a shift in the balance of geopolitical power.


# Footnotes




[^1]: In my opinion, the public work with the most authoritative and detailed description of the APM concept is Drexler’s 2013 book, _[Radical Abundance](https://smile.amazon.com/Radical-Abundance-Revolution-Nanotechnology-Civilization/dp/1610391136)_ (especially chapter 10, and parts of chapters 1 and 2).

[^2]: Drexler claims that (something similar to) complex APM would be able to manufacture products for $1/kg or less and with a throughput of 1kg every 3 hours or less per kg of machinery (for "1/kg or less", see, for example, _[Radical Abundance](https://smile.amazon.com/Radical-Abundance-Revolution-Nanotechnology-Civilization/dp/1610391136)_, 2013, p. 172; for "a throughput of 1kg every 3 hours or less per kg of machinery", see _[Nanosystems](https://www.amazon.com/Nanosystems-P-K-Eric-Drexler/dp/0471575186/)_, 1992, p. 1, 3rd bullet). I set a lower bar for my definition of consequential APM here because I think this lower bar is more than sufficient to imply an extremely impactful technology, while perhaps capturing a larger fraction of potential scenarios over the next few decades.

[^3]: The more certain we are that the development of complex APM naturally implies the development of consequential APM soon afterwards, the less useful it is to distinguish these concepts (I think this partly explains why they are often bundled together). But I’m uncertain enough to find the distinction useful.

[^4]: Someone who read a draft of this post mentioned they felt initially sceptical that it makes sense to think of ribosomes (or other nanoscale objects) as “machines”, and that they found the [Wikipedia page on molecular machines](https://perma.cc/DKX7-23B9) helpful for reducing this scepticism.

[^5]: In addition to showing that such machines are feasible, this suggests that one approach to engineering nanoscale machines doing mechanical assembly might be to use biological machines as the starting point.<br><br> One approach that uses biological machines as the starting point is the approach I associate with synthetic biology, which involves making incremental changes to existing biological machines to achieve some goal (I’ll refer to this as the “synthetic biology approach” from now on, although I don’t know whether synthetic biologists would agree with this characterisation). This approach seems to be very challenging. My impression is that this is because the effect of small modifications is hard to predict, and because biological machines often stop working outside of their usual conditions. Still, I think some people see this as the best approach for developing something like advanced nanotechnology.<br><br> Another approach that uses biological machines as the starting point is the “soft path” approach to APM described by Drexler (see, for example, Appendix II of _[Radical Abundance](https://smile.amazon.com/Radical-Abundance-Revolution-Nanotechnology-Civilization/dp/1610391136)_). This approach also starts with engineering biological molecules such as proteins (or synthetic but somewhat similar molecules), but is quite different to the synthetic biology approach, because the biological molecules are used more as a building material than as active machines in their own right, and are generally completely removed from their biological context. This soft path approach seems like a more plausible path to me than the synthetic biology approach. So far the soft path approach has had far less effort directed to it than the synthetic biology approach, as far as I’m aware.

[^6]: I’m mostly relying on the analysis described in Paul Christiano’s [Simple evolution analogy](https://perma.cc/6RRR-C85Z) for this claim. From that document: <br><br>_I think the typical pattern is for human artifacts to be 2-3 OOM [order of magnitude, i.e. a factor of 10] less efficient than their biological analogs, measured by “How much energy/mass is needed to achieve a given level of performance?”_ <br><br> For example, a top GPU is said to perform roughly 1-2 OOM fewer Flops per unit power than a human brain, and artificial photodetectors are said to require roughly 3-4 OOM as much power as a human eye to attain the same level of performance. Note that the analysis in that document is fairly rough, although I’d be very surprised if it turned out not to be the case that naturally evolved systems often outperform present-day ones on important dimensions.

[^7]: For example, we could imagine a system occupying a 1000nm × 1000nm × 1000nm volume, and composed of nanoscale machines, that can perform one assembly operation at a time. We could fit 1,000,000,000,000 such systems into 1cm³. (Atomic force microscopes are used today to manipulate atoms one at a time, and my impression, from briefly talking to someone who uses atomic force microscopes for their research, is that they are generally around 1cm³ in size or larger (potentially much larger, depending on what you count as the atomic force microscope and what you count as its supporting infrastructure).)

[^8]: Though note that these high frequency, parallel operations involving single molecules each make a tiny amount of progress towards creating a structure of appreciable size, so overall we might expect these machines to make their own mass in product within say minutes, hours, or days, rather than say once per second or 1 billion times per second.

[^9]: According to Paul Christiano’s [Simple evolution analogy](https://perma.cc/6RRR-C85Z): “Manufacturing costs differ by a further 2-4 OOM” (“OOM” stands for “order of magnitude”, i.e. a factor of 10).

[^10]: I haven’t given a large amount of thought to how advanced nanotechnology might deviate from consequential APM, and I can easily see my views changing significantly in the future. Naively, though, here are some ways I imagine the technology might deviate from consequential APM: it might not be the case that most of the assembly machinery is atomically precise; maybe assembly methods or physical phenomena other than mechanical positioning are very important; maybe important components involved in the assembly of nanoscale products are not themselves nanoscale; maybe the assembly machines would not be very stiff; or maybe “control the trajectories of small molecules” wouldn’t be a natural description of the machinery’s operation. <br><br>These alternatives to APM might often be things that are technically not consequential APM but are so similar that they can be treated as equivalent to consequential APM for most practical purposes. But perhaps many have substantial enough differences that the distinction turns out to matter for thinking about nanotechnology strategy.

[^11]:To give a rough quantification of my (very unstable) beliefs here: if we have advanced nanotechnology in 2040, I’d guess that in roughly 80% of cases the advanced nanotechnology doesn’t look like complex APM. This would imply that, in some relevant sense, advanced nanotechnology covers 5x as much of the space of technological possibilities as does APM.

[^12]: For example, we might sometimes be more interested in the question “how likely is it that advanced nanotechnology will be developed by 2040?” than the question “how likely is it that _APM_ will be developed by 2040?”, because advanced nanotechnology has consequences as important as those of APM (or perhaps even more important), and answering the question for advanced nanotechnology might involve similar considerations but have a significantly different answer.

[^13]: This guess of a 70% probability is basically driven by: “It’s hard for me to imagine this not being a really big deal, but I haven’t thought about this that much, and maybe my imagination just isn’t very good.”

[^14]: For example, [this transcript of an 80,000 Hours podcast with Carl Shulman](https://perma.cc/69FQ-M74A) quotes Shulman discussing the Soviets’ apparent willingness to develop bioweapons that they couldn’t protect their own people against (though presumably a weapon that could kill everyone would look less appealing than a weapon that kills some random fraction of the global population; and Soviet decision-makers might have felt that they could protect themselves through physical isolation, for example): <br><br> _It’s hard to know exactly how much work they would put into pandemic things, because… With pandemic pathogens, they’re going to destroy your own population unless you have already made a vaccine for it. <br><br> And so the US eschewed weapons of that sort towards the end of its bioweapons program before it abandoned it entirely, on the theory that they only wanted weapons they could aim. But the Soviets did work on making smallpox more deadly, and defeat vaccines. So, there was interest in doing at least some of this ruin-the-world kind of bioweapons research._

[^15]: We might also expect that the TAI we get might be different if it’s developed using a huge amount of computational resources made available by advanced nanotechnology (other than the differences we’d expect to directly follow from earlier TAI). For example, maybe the TAI we get would be more likely to follow present-day paradigms, like [stochastic gradient descent](https://perma.cc/H7R3-8GFU), which (very speculatively) could have safety implications.

[^16]: Although perhaps some new weapons other than grey goo would also involve nanoscale devices, and you might consider the components of new kinds of computers to be “novel nanoscale devices”.

[^17]: Here’s a quick attempt to brainstorm considerations that seem to be feeding into my views here: "Drexler has sketched a reasonable-looking pathway and endpoint", "no-one has shown X isn't feasible even though presumably some people tried", "things are complicated and usually don't turn out how you expect", "no new physics is needed", "X seems intuitively doable given my intuitions from molecular simulations", "it's hard to be sure of anything", "trend-breaking tech rarely happens but does sometimes".

[^18]: [Richard Jones](https://perma.cc/G93J-7EWG) is a notable example of a highly credentialed person who seems to have engaged seriously with the question of the feasibility of APM. He seems to think that something resembling complex APM is feasible, although he seems sceptical about the feasibility of something with the kind of capabilities described by consequential APM. See, for example, Open Philanthropy’s [A conversation with Richard Jones on September 30, 2014](https://perma.cc/D9B2-YGAR).

[^19]: I’d speculate that there might be a decent minority of now-senior researchers who entered the field around 1995-2005, excited by the vision for nanotechnology laid out in Drexler’s works and the creation of the National Nanotechnology Initiative in the US. Perhaps these researchers nowadays have a vague sense for what Drexler’s ideas are (and probably consider APM-like visions for nanotechnology to be too far in the future to be worth thinking about).

[^20]: Michael Nielsen has written a very nice, relatively quick [introduction to scanning tunnelling microscopy](https://perma.cc/DR3A-5NW3) (scanning tunnelling microscopy is a type of scanning probe microscopy).

[^21]: My perception is that the hard path to APM is less promising than an alternative path called the “soft path” (see footnote 5). This perception mostly comes from what people around me seem to think, and those views in turn perhaps mostly come from Drexler’s view on this. I don’t have much of an inside view here myself; my impression is that deliberate hard path work has been occurring for many years (most notably at Zyvex) without much to show for it, but this seems like only weak evidence, partly because the level of investment has apparently been quite low.

[^22]: For a more thorough overview of recent (and less recent) R&D relevant for advanced nanotechnology, see Adam Marblestone’s [Bottleneck analysis: positional chemistry](https://perma.cc/39E5-LQRJ). The most relevant sections are “Building blocks that emerged in the meantime”, and “Explicit work on positionally directed covalent chemistry”. (Note that the focus of the report is on a technology the author calls “positional chemistry”, which is different to advanced nanotechnology, but is closely related.)

[^23]: Although positional assembly with DNA suprastructures might soon be demonstrated, as a result of [this grant](https://perma.cc/QX4Z-WLCX), which seems to me to represent relevant progress.

[^24]: Of course, this lack of empirical evidence also pushes against high confidence that progress will be very fast if a large research effort emerges. But I expect people will already be inclined not to be confident that progress will be very fast if a large research effort emerges.

[^25]: To be clear, this number does not assume feasibility, unlike my median timeline estimate.

[^26]: As a somewhat independent data point, Daniel Eth, a former colleague of mine at the Future of Humanity Institute who has spent time thinking about APM, told me that he guesses a 1% probability for roughly the event “advanced nanotechnology arrives by 2040 and isn't preceded by advanced AI”, where "advanced AI" is, roughly "AGI or transformative AI or CAIS or some future AI that is a similarly huge deal" (note that AI that dramatically speeds up technological progress doesn't necessarily qualify as advanced AI). Daniel said, “I'd expect [the estimate would] move around a bit, but probably not more than one order of magnitude.”

[^27]: Here are some examples of work from these organisations:<br><br> Foresight Institute: the [list of articles tagged molecular manufacturing](https://web.archive.org/web/20210918221108/https://foresight.org/category/molecular-manufacturing/) includes lots of commentary on relevant (incremental) scientific advances, e.g. [this commentary on a 2014 paper on manipulating atoms with AFM](https://web.archive.org/web/20220503171301/https://foresight.org/building-atom-by-atom-on-insulator-at-room-temperature/). <br><br>Center for Responsible Nanotechnology: [Overview of Current Findings](https://perma.cc/N7KL-QACL) (NB my current weak impression from skimming a few articles is that the material on the Center for Responsible Nanotechnology website probably contains some inaccurate or misleading statements). <br><br>The [IMM website](https://perma.cc/76DH-T5QL) says that Institute for Molecular Manufacturing members contributed to a 2007 report called [Productive Nanosystems: A Technology Roadmap](https://perma.cc/2JHP-64X9).

[^28]:One potential objection might be that points 1 or 2 just stem from general uncertainty about advanced nanotechnology due to a relative lack of attention on the relevant questions; for example, you might think that if we tried a bit harder to reduce our uncertainty, we would likely end up finding that there’s a sufficiently low probability that advanced nanotechnology arrives in the next 20 years without TAI that this area doesn’t seem worth investigating. A counterargument would be that the above is really an argument about which projects to prioritise in this area, rather than an argument for not thinking about this area at all. Similar comments apply to the uncertainty that is driving point 1. Of course, this counterargument only works if you think points 1 and 2 are reasonable positions given our current state of knowledge.

[^29]: Note that an assumption underlying this argument is that there’s not much value in doing nanotechnology strategy work to understand or prepare for scenarios where TAI precedes the development of advanced nanotechnology, because TAI makes everything go crazy such that it’s hard to plan for after that point. However, if you do think such work might be valuable, the case for nanotechnology strategy research looks stronger, because there’s a broader range of future scenarios where this work is relevant. (As mentioned in the main text, it seems reasonable to me to think that work on nanotechnology strategy will be much less useful if advanced nanotechnology is preceded by TAI, but I’m not confident in this and my view feels quite unstable.)

[^30]: Although note that, for example, Drexler has written several books on topics within advanced nanotechnology and the Foresight Institute runs a programme promoting the development of APM, so discussion of advanced nanotechnology would not happen against a background of complete silence on the topic.

[^31]: This isn’t strictly true because some molecules might contain different isotopes; but it doesn’t seem likely that the presence of different isotopes would usually matter much, and rare isotopes could in principle be filtered out if necessary.

[^32]: Provided that there are no errors in the assembly process that lead to incorrect building block placement or bonding. Products could be checked for errors and any errors could be corrected or the misformed products could be discarded; although it’s not clear to me how effective this would be in practice at eliminating errors.

[^33]: In [Biological and Nanomechanical Systems: Contrasts in Evolutionary Capacity](https://perma.cc/36HY-QTG7) (1989), Drexler discusses how and why designed systems differ from evolved ones. These LessWrong posts also make relevant arguments, in the context of TAI: [Building brain-inspired AGI is infinitely easier than understanding the brain](https://perma.cc/8SXW-JJZ8) and [Birds, Brains, Planes, and AI: Against Appeals to the Complexity/Mysteriousness/Efficiency of the Brain](https://perma.cc/F8MC-YCZA).

[^34]: This [2016 Nature Methods article](https://perma.cc/VE2E-69A3) reports bacteria growing with a cell count doubling time of less than 10 minutes. I haven’t found numbers for the rate of total mass doubling, but I understand that cell mass remains roughly constant over successive generations, implying that total mass doubles at roughly the same rate as cell count.

[^35]: Relatedly, Robert Freitas and Ralph Merkle report in [Kinematic Self-Replicating Machines] that ribosomes can produce their own mass in proteins in ~5-12 minutes (Ctrl+F for “If the bacterial ribosome” on the linked page).

[^36]: Drexler describes something along these lines in [The Stealth Threat: An Interview with K. Eric Drexler](https://journals.sagepub.com/doi/full/10.2968/063001018).

[^37]: Though it’s not completely clear to me how useful the “advanced nanotechnology” framing is here, as opposed to, say, something like “advanced biotechnology”.
