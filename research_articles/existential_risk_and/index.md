---
layout: default
title: "'Existential Risk and Growth' Deep Dive #2 - A Critical Look at Model Conclusions"
---

'Existential Risk and Growth' Deep Dive #2 - A Critical Look at Model Conclusions
=================================================================================

_This is the second report in a three-part series summarising, critiquing, and suggesting variants and extensions of Leopold Aschenbrenner’s working paper called [Existential risk and growth](https://globalprioritiesinstitute.org/wp-content/uploads/Leopold-Aschenbrenner_Existential-risk-and-growth_.pdf). The series is written by me and Alex Holness-Tofts, with input from Phil Trammell (any errors in this report are due to me). Alex summarised the model and results from the paper [in the first report](https://forum.effectivealtruism.org/posts/CsL2Mspa6f5yY6XtP/updated-6-21-existential-risk-and-growth-summary), and wrote about possible extensions and variations to the model [in the third report](https://forum.effectivealtruism.org/posts/YCKk5a6WYMBdzM37Q/existential-risk-and-growth-deep-dive-3-extensions-and) (you can see the current report on the Effective Altruism Forum [here](https://forum.effectivealtruism.org/posts/vLrkh5ybNAaMj5rtk/existential-risk-and-growth-deep-dive-2-a-critical-look-at))._

Summary
=======

The main purpose of this report is to help the reader understand how seriously they should take the conclusions from the paper, and to highlight some conclusions that we think are robust.

Key points

*   Some common objections to the model are weak, but we think that there are some (perhaps less common) strong objections.
*   Because of this, we don’t think that the paper should cause you to change your views much regarding most of the implications of the model found in the paper. Replacing the simplifying assumptions that the model makes with other, equally reasonable ones can easily mean that the conclusions presented in the paper no longer follow.
*   We draw some more limited conclusions that we think are robust. These are: i) that making people better off makes them care more about preserving their future compared to getting more consumption today, increasing the amount that society would optimally spend on existential risk reduction; ii) that if you think the sign of the impact of economic growth on existential risk won’t change over time, you’re not sure whether the sign is positive or negative, and you think that economic growth is inevitable, you might as well speed up economic growth; iii) it’s not the case that moving from a “rule of thumb” allocation where spending on existential risk reduction stays constant over time to an allocation that varies optimally over time never makes much difference to existential risk; and iv) that you don’t have to believe in a suspiciously long or detailed list of ad-hoc claims about past and future technological developments in order to conclude that world history will include a ‘time of perils’ - the conclusion comes from the relatively simple model presented in the paper, for plausible model parameters.
*   We think work in this area, i.e. using theoretical models to investigate the connection between economic growth and existential risk, is important. This is because i) any weak evidence that this work might generate is still valuable, ii) similarly, weaker but more robust conclusions that this work might point to are valuable, and iii) there might be value from the signalling to academics and philanthropists from serious attempts at doing this.

Introduction and preliminary comments
=====================================

In this report we

*   List the major conclusions that follow from the model described in the Existential Risk and Growth paper, and categorise them by robustness. Note that this includes some interesting conclusions that are not spelled out in the paper.
*   List some common (and less common) objections to the model, respond to them, and identify which are strong and which are weak.
*   Briefly make the case for doing work of this kind, i.e. using theoretical models to investigate the link between economic growth and existential risk.

The primary audience we have in mind is people who are interested in knowing what conclusions can be drawn from the paper, and how robust these conclusions are. The report is written such that, hopefully, non-economists with a range of technical knowledge can understand it.

I wrote this report in consultation with Phil Trammell and Alex Holness-Tofts. “We” in this report refers to our collective judgement.

I should mention that Alex and I don’t have economics backgrounds, although Phil does, and, in addition, Phil supervised the writing of the paper. Ideally, someone who is an expert both in economic growth theory and existential risk would do a really deep analysis of the model presented in the paper, but in the absence of this we feel that giving our thoughts on this is useful.

Note that we are aware of a few minor errors in the current draft of the paper. It seems possible that fixing these will change one or more of the conclusions that follow from the model assumptions. However, for the purposes of this report we’ll assume that this isn’t the case, and address the model conclusions as currently given in the paper (alongside conclusions that aren’t explicitly mentioned in the paper).

Finally, while we are spending a lot of this report emphasising the limitations of the model, we want to stress that we think that the work done in the paper is valuable, and that further work in this area has the potential to be valuable. We discuss our reasons for thinking this in the last section of the report.

Conclusions that depend on contentious model assumptions
========================================================

Some of the following conclusions depend on the chosen values of the model parameters 𝜀, 𝛽, and 𝛾. To get a feel for these parameters, note that 𝜀 controls how strongly the total production of consumption goods influences existential risk, while 𝛽 controls how strongly the total production of safety goods influences existential risk. For both parameters, a bigger value means a bigger effect. 𝛾 is the constant in the agent’s [isoelastic utility function](https://en.wikipedia.org/wiki/Isoelastic_utility). Loosely speaking, 𝛾 controls how sharply the utility gain from an extra bit of consumption falls off as consumption increases. A bigger 𝛾 means a sharper fall-off. We discuss the role of 𝜀 and 𝛽 in more detail in the next subsection. (the [first report in the series](https://forum.effectivealtruism.org/posts/CsL2Mspa6f5yY6XtP/updated-6-21-existential-risk-and-growth-summary#1__Setup) also gives much more detail and context regarding these parameters)

The conclusions we’ll discuss in this section, and which depend on contentious model assumptions, are:

1.  The scale effect (𝜀 vs 𝛽) is centrally important for determining whether we will avert existential catastrophe

    *  If we live in a world where 𝜀 > 𝛽 and 𝛾 is small, or where 𝜀 >> 𝛽, existential catastrophe is inevitable
    *  Otherwise, i) there’s a chance that existential catastrophe is averted, and ii) there is an existential risk Kuznets curve, which means that history will contain a 'time of perils'. Note that this conclusion is highly relevant for the case for existential risk reduction, which many people in the Effective Altruism community think is a highly valuable cause area.

3.  Empirically, 𝜀 < 𝛽 is unlikely, 𝜀 > 𝛽 and 𝜀 >> 𝛽 both seem plausible
4.  Unless we're confident that 𝜀 >> 𝛽, we might as well act on the hope that 𝜀 > 𝛽; in that world we might be able to unlock an astronomically valuable future, whereas our future will necessarily be curtailed if 𝜀 >> 𝛽.

A reasonable question that you might ask is “how much should the work in this paper move me towards believing these conclusions?”.

A starting point is that if you believe that the assumptions the model makes are an accurate reflection of the world, you should take the conclusions seriously.

Given our own beliefs about the assumptions, we think that these conclusions are not very robust. We think that the work in the paper should move you a bit, but not much, towards believing these conclusions, assuming that you were previously ambivalent towards them.

Alternative assumptions that lead to different conclusions
----------------------------------------------------------

A key assumption is that the hazard rate is determined by the following equation
\\[\delta_t=\bar{\delta} C_t^\epsilon H_t^{-\beta},\\]
where \\(\delta_t\\) is the hazard rate at time \\(t\\), \\(C_t\\) is total consumption production at time \\(t\\), \\(H_t\\) is total safety production at time \\(t\\), and 𝜀, 𝛽 and \\(\bar{\delta}\\) are constant model parameters.

This is a vast simplification compared to the complex ways we might imagine the state of the world influencing existential risk in reality. To be clear, this isn’t to say that it might not turn out to be roughly right - we just don’t have much empirical evidence here.

Because of this equation, in the model the values that we choose for 𝜀 and 𝛽 are crucially important for the prospects of humanity’s long-run survival, _even assuming that people coordinate perfectly and don’t discount future value_.

There are some quite plausible ways that the real world might break this assumed equation for the hazard rate, in ways that mean that the conclusions listed above no longer follow:

*   𝜀 and 𝛽 might change over time, or as technological sophistication changes
    *   For example, let’s assume that the model is completely correct, except that 𝜀 and 𝛽 can change over time. Let’s also assume that the safety technologies we have now are not very potent compared to future ones, such that 𝜀 >> 𝛽 now, but later on we will have 𝛽 > 𝜀. This seems perfectly plausible (for example, maybe mature, well functioning AGI technology will greatly increase safety). Then, if we believe the model (including the part that says that 𝜀 and 𝛽 are constant), and we have what we believe is perfect knowledge of 𝜀 and 𝛽 (by observing their current-day values), we’ll conclude that we’re in the regime where existential catastrophe is inevitable, whereas in fact it isn’t.
    *   This highlights a difficulty with doing an analysis that leads to a conclusion about likely real-world values of 𝜀 and 𝛽 (such as conclusion 2) - even if we’re sure that the hazard rate is modelled well by the hazard rate equation, it’s not clear that the values we estimate using historical data will apply in the future.

*   Some present-day consumption technologies are (presumably) significantly safer than others, and in practice we might be able to shift production to these safer technologies. In the language of the model, you could think of this as society choosing to manipulate 𝜀 (similar comments apply for safety technologies).
    *   You can imagine a similar scenario to the one above, where we start off with 𝜀 >> 𝛽, but then society shifts consumption production to focus on goods based on safer technologies. In that way, per capita consumption is maintained at an acceptable level, but existential risk is lower for a given level of total consumption, such that 𝜀 is effectively lowered, and we can consider ourselves to be in a 𝛽 > 𝜀 situation.

Conclusions that may depend on contentious model assumptions
============================================================

1.  If we’re in a world where there’s an existential risk Kuznets curve:

    * A period of faster economic growth reduces overall existential risk in the long run (even though, if it happens on the upward part of the Kuznets curve, it increases risk in the short term). Conversely, slower economic growth increases overall existential risk.
    * On the other hand, a temporary boom followed by a bust, where the economy reverts back to its normal path after a period above trend, increases existential risk (a temporary bust followed by a boom decreases it).

3.  More generally, making people better off makes them care about preserving their future more relative to increasing consumption today, and so increases the amount society is willing to spend on existential risk reduction.
4.  Reducing the rate at which people discount their future utility is probably an easier way to reduce existential risk than increasing the growth rate (depending on what you think the likely range for 𝛾 is).
5.  Moving from a “rule of thumb” allocation where spending on existential risk reduction stays constant over time to an optimal allocation (whether future value is discounted or not) can create the possibility of averting existential catastrophe, where previously existential catastrophe was inevitable.

In general, it’s not clear to us whether or not these conclusions would change under reasonable modifications to the hazard rate equation, or to other parts of the model.

That being said, given what we know at the moment, we think that these conclusions are perhaps slightly more robust than the ones listed in the previous section, but still not very robust. And as with the previous conclusions, we think that the work in the paper should move you a bit, but not much, towards believing these conclusions, assuming that you were previously ambivalent towards them.

Conclusions that we believe are robust
======================================

1.  Making people better off makes them care about preserving their future more relative to increasing consumption today, and so increases the amount society _would optimally_ spend on existential risk reduction (this increased inclination (assuming optimality) for society to spend money to preserve its own existence can be thought of as a civilisational analogue of the smaller-scale increased willingness of individuals to spend money to extend their lives).
2.  If you think that i) economic growth is more or less inevitable, ii) the sign of the impact of economic growth on existential risk won’t change over time, and iii) you’re not sure whether the sign is positive or negative, then you might as well speed up economic growth. In that world, most of the value comes from worlds where economic growth reduces existential risk, because in worlds where economic growth increases existential risk, we’re doomed anyway.
    * Also, this is generally true for inevitable trends with an unknown, but constant, impact on risk
    * (Phil has made this point in [his blog](https://philiptrammell.com/blog/45/); note, though, that it’s not at all clear that the sign of the impact of economic growth on existential risk won’t change over time)
4.  It’s not the case that moving from a “rule of thumb” allocation where spending on existential risk reduction stays constant over time to an optimal allocation that varies over time (whether people discount future value or not) never makes much difference to existential risk.
5.  You don’t have to believe in a suspiciously long or detailed list of ad-hoc claims about past and future technological developments in order to conclude that world history includes a ‘time of perils’; it appears in the simple world described in the paper with a moderate 𝜀 > 𝛽 scale effect.

We consider the final point to be especially important because, in our view, the plausibility of a ‘time of perils’ is extremely action-relevant from a longtermist perspective. We can consider this time of perils as an existential risk version of the environmental Kuznets curve, where environmental degradation rises at first, but eventually falls as society becomes richer and more willing to spend on measures that improve environmental quality.

Note also that conclusion 3 is in contrast to what is found in some previous work (Martin and Pindyck (2015, 2019) and Aurland-Bredesen (2019)) on catastrophe mitigation, which concludes that you don’t want to change the fraction of total output spent on safety much as you get richer. The difference comes from the fact that this previous work considers fractional losses to consumption, rather than existential catastrophe.

Objections to the model
=======================

Common objections that we believe are not strong
------------------------------------------------

**Objection**: Why is it sensible to assume risk depends on the level of production in the consumption and safety sectors, rather than the rate of increase of production in the consumption and safety sectors?  
**Response**: Consider the implications of spending 10x more on electricity production, of which 20% is power plants burning more fossil fuels and 80% is some extremely expensive (with our current tech) carbon capture that makes all the new production zero-net-emissions. Or spending 10x more on AI development than we currently do, of which only 20% goes to adding new capabilities and 80% goes to running extremely computationally expensive (with our current tech) proof-checking procedures that verify that the new code does exactly what we expect. It seems like that wouldn’t increase risk, even though the rate of increase of spending on consumption production is high. The intuition that speed is risky, if you pick it apart, is at least largely driven by the thought that risks come from increasing production in the consumption sector, before you had the time to research how to develop safety measures accordingly (increasing  \\(B_t\\)) and then maintain the relevant safety infrastructure (\\(h_t\\)).

**Objection**: There is no capital in the model, but in reality capital is an important determinant of production, as well as labour.  
**Response**: We think this is unlikely to change the important results of the model (although it would be interesting to include capital in the model, in order to model philanthropic investment).

**Objection**: In the model, it is assumed that people live forever and that they don’t have any descendants that they care about. This is clearly unrealistic.  
**Response**: While there is a class of economic models that model generations more realistically (called overlapping generations models), we don’t think that using this kind of approach would change the important results of the model.

**Objection**: The model says that, for parameter values that are likely to be realistic (specifically, if 𝜀 > 𝛽, or 𝛾 is large), society will eventually allocate almost everyone into the safety sector. But it seems implausible that in the long run almost everyone will be working on safety.  
**Response**: We’re not sure that that scenario is so implausible. You could imagine a future where advanced technology led to the production of really great consumer goods, but also to the possibility of very dangerous goods, such that almost everyone had to be employed, say, monitoring the use of the dangerous goods (or doing research into how to monitor them better).

**Objection**: Given differential technological progress, it might matter a whole lot whether a potentially risky technology is developed sooner or later. If later, the probability increases that we found corresponding risk-mitigating technologies in the meantime. But it seems to be the case that according to the model, speeding up growth always decreases long-run risk (at least, given our uncertainty in the model parameters)  
**Response**: Slowing growth within the model corresponds to reducing the population growth rate. This leads to a reduction in both the rate of consumption technology discovery and the rate of safety technology discovery (ignoring changes to employee allocation). So, within the model, to reduce growth is not to cause differential technological progress. Rather, within the model, promoting differential technological progress means allocating a greater share of scientists to safety technology.

Moderately strong / possibly strong objections
----------------------------------------------

**Objection**: The model is an approximation of how the world is now and how we think it might be in the future. But how sure are we that things won’t have qualitatively changed in, say, 500 years’ time  
**Response**: Sure, we do need to assume that the world hasn’t changed so radically in 500 years’ time that the model is no longer applicable. If you think society will radically change in some way, you’d have to think carefully about whether the assumptions the model makes would still apply. One thing in favour of the model, though, is that it isn’t very closely fitted to the way society is currently organised, so you might expect it to be more resilient to radical changes to society than it would otherwise be.

**Objection**: Why should existential risk depend on the total amount of consumption rather than per capita consumption? Surely what matters is how much resources each individual has, rather than the total amount of stuff produced  
**Response**: If you think that the important thing for existential risk is how much each individual produces rather than how much everyone produces collectively, then you shouldn’t find the model very convincing. On the surface though, it seems plausible to us that total consumption would be more important. In any case, note that Phil has created [an alternative model](https://philiptrammell.com/static/ExistentialRiskAndExogenousGrowth.pdf) that is relevant here. Phil’s model assumes a fixed population (and exogenous productivity growth), which means that per capita consumption only differs from total consumption by a constant factor, so that it doesn’t really matter which one existential risk depends on. That model results in similar conclusions to Aschenbrenner’s one, except that existential catastrophe is no longer inevitable for 𝜀 >> 𝛽, provided that 𝛾 is not too small (but NB this result is provisional while potential errors in Aschenbrenner’s paper are checked). See the Appendix for more discussion of the role of population in the model.

**Objection**: I think the level of technological development should be important for existential risk, but the model doesn’t account for this  
**Response**: The choice to use the level of consumption production rather than the level of consumption technology as an input to the hazard rate equates, roughly speaking, to assuming that existential risk comes from things being produced rather than research being done (e.g. due to lab accidents) or technology being available. It would be interesting to explore a model where the hazard rate depends explicitly on the level of technological development.

**Objection**: In the model, population grows forever at a constant rate. But, in reality we expect population growth to rapidly decline over the next century. This being the case, how can the model tell us anything about reality?  
**Objection**: In the model, economic growth is ultimately driven by population growth. Is there strong evidence for this being true in the real world?  
**Response**: Phil has created [an alternative model](https://philiptrammell.com/static/ExistentialRiskAndExogenousGrowth.pdf) that doesn’t assume exponential population growth, and found that this does lead to different results in some cases. Specifically, the model results in similar conclusions to Aschenbrenner’s one, except that existential catastrophe is no longer inevitable for 𝜀 >> 𝛽, provided that 𝛾 is not too small (but NB this result is provisional while potential errors in Aschenbrenner’s paper are checked). See the Appendix for a more detailed discussion.

**Objection**: In the model, society allocates workers between the four possible occupations (consumption worker, consumption scientist, safety worker, safety scientist) according to whatever maximises utility. Isn’t this vastly optimistic? It’s hard to imagine that we are currently at an optimal allocation, even for people with a non-zero discount rate.  
**Response**: We are probably not particularly close to the optimal allocation at the moment. If you believe the model assumptions other than Optimal Allocation, you can consider that the model gives us what happens in a “best case” for coordination on existential risk mitigation. It would be interesting to look at the non-optimal allocation case. This might give you information about how valuable moving towards the optimal allocation would be.

**Objection**: In the model, we assume that everyone knows the true 𝜀 and 𝛽 values, so that society can allocate resources accordingly. But in reality it seems like it would be hard to be very confident about what these values are.  
**Response**: It might be interesting to model this uncertainty explicitly. If you think that people have roughly the right central estimates, but with some uncertainty, our guess is that this wouldn’t change the big picture results very much, but it might change the detailed results in interesting ways. If you think that people are biased in one direction, it seems clear that this can qualitatively change the results (for example, if people think they’re in a regime where they should be transferring labour from safety to consumption, when in fact the opposite is true). In that case, modelling this explicitly could shed light on the value of educating people about existential risk.

**Objection**: It doesn’t seem sensible to have the same 𝛼 parameter for the good production functions in the safety and consumption sectors.  
**Response**: Our guess is that allowing the two sectors to have different parameters rather than a single 𝛼 parameter doesn’t change the important results of the model. However, it might be interesting (and fairly easy) to try this out.

Strongest objections
--------------------

**Objection**: 𝜀 and 𝛽 aren’t really fixed / the hazard rate is determined in a far more complex way than what is in the model. In the end, the likely path of the hazard rate will come down to details about which technologies get developed in which order, how dangerous they turn out to be, and things like how stable and robust important institutions are. The model can’t capture these things.  
**Objection**: In the 𝜀 >> 𝛽 case, we face a choice between extinction on the one hand, and devoting so much of our resources to safety that we live lives worse than death on the other. But surely with perfect coordination (which we assume in the model), there’s some chance we could organise society in such a way that we have lots of “safe” technology / goods and none of the “dangerous” ones, such that we live lives worth living and in safety. A cartoon example might be a world where advanced technologies are all banned, and we move all resources currently spent on luxury goods to carbon capture.  
**Objection**: According to the model, the scale effect, i.e. 𝜀 vs 𝛽, is centrally important for determining whether we will avert existential catastrophe. But isn’t this just an artefact of the model, which follows from the assumed relationship between existential risk, total consumption, and total safety production?  
**Response**: We think these all point towards important things, which we discussed in the earlier section called “Conclusions that depend on contentious model assumptions” (note that we don’t necessarily agree with every assertion made in these objections).

**Objection**: Eliezer Yudkowsky's [argument](https://www.greaterwrong.com/posts/FS6NCWzzP8DHp4aD4/do-earths-with-slower-economic-growth-have-a-better-chance) that work for building an unsafe AGI parallelizes better than work for building a safe AGI, and that unsafe AGI benefits more in expectation from having more computing power than safe AGI, both imply that slower growth is better from an AI x-risk viewpoint.  
**Response**: This can be thought of as a concrete example of the general point (also raised in the three previous objections) that the hazard rate equation in the model represents quite a strong assumption about the relationship between technology and existential risk. If you think that the argument described in the objection is definitely right, the model probably can’t tell you very much.

Why we think work in this area is useful
========================================

While we think that the work in the paper represents very weak evidence for the conclusions that follow only from the detailed assumptions of the model, we want to make the argument that work of the kind done in the paper, on theoretical models connecting economic growth to existential risk, is useful.

We claim that weak evidence that shifts your beliefs a bit is still valuable, especially when it addresses questions as important as the ones we’re considering here. Similarly, there is value in conclusions that are weaker (in the sense that assuming that they’re true changes your beliefs about the world less than “stronger” conclusions would) but more robust, like the ones we’ve drawn in the “Conclusions that we believe are robust” section of this report.

Currently, most work on understanding existential risk makes granular and specific arguments about particular technologies or political situations. However, more general and abstract models, like Aschenbrenner’s, give us a different flavor of insight about existential risk. Whichever is your preferred approach, it might be that a mixed strategy, where both approaches are used, can give more robust conclusions (particularly where the approaches converge).

Exploring both approaches in parallel also has high information value given the high stakes and our uncertainty about which approach might be more fruitful.

Generally, the stronger your beliefs about the link between economic growth and existential risk, the less useful work like this will be. For example, if you’re certain that potentially dangerous Artificial General Intelligence will arrive in the next 20 years, and that economic growth will speed up its arrival, but not speed up safety work, you probably won’t learn as much from models of economic growth and existential risk as someone who is more agnostic on this point. On the other hand, if you’re more uncertain about when transformative technologies are likely to be developed, and what the effect of economic growth on these technologies and their regulation might be, theoretical models connecting economic growth to existential risk would shift your beliefs more.

Since there is a wide range of views out there, both within the Effective Altruism community and outside it, we think that this work is likely to be useful for many people.

A separate consideration is one of signalling / marketing: it might be the case that creating an academic literature on the impact of economic growth on existential risk will mean that academics, philanthropists and, eventually, policymakers and the general public take existential risk more seriously.

Acknowledgements
================

Thanks to Toby Newberry and Hamish Hobbs (and probably others) for feedback on earlier drafts of this.

References
==========

**Martin, Ian W. R. and Robert S. Pindyck**, “Averting Catastrophes: The Strange Economics of Scylla and Charybdis,” _American Economic Review_, October 2015, _105_ (10), 2947-2985.

**_ and _**, “Welfare Costs of Catastrophes: Lost Consumption and Lost Lives,” July 2019. Working Paper 26068, National Bureau of Economic Research.

**Aurland-Bredesen, Kine Josefine**, “The Optimal Economic Management of Catastrophic Risk.” PhD dissertation 2019.

Appendix: the role of population growth
=======================================

Two features of the model that you might find unintuitive are

1.  population growth is necessary for sustained economic growth (without population growth, economic growth eventually stagnates), and
2.  population grows at a constant rate forever.

Feature (1) is inherited from the economic growth model that the Existential Risk and Growth model is based on, which is known as the Jones model; whether (1) is true or not in the real world doesn’t seem to be a settled issue. Meanwhile, feature (2) contradicts population growth forecasts pretty clearly.

At first glance, feature (2) in particular might seem to count against the model pretty strongly.

However, the combined effect of these features on economic growth is just to make the economy grow consistently over time at some fairly steady rate (unless there’s a dramatic change in the number of people employed in the consumption sector). The exact rate of economic growth doesn’t seem to be very important for the conclusions we draw from the model, so it appears that the effect that these features have on economic growth is pretty unimportant, as long as you think that the economy will continue to grow at a roughly constant rate.

Still, we might worry that exponentially increasing population drives a lot of the results through a means other than its effect on the economic growth rate. The argument is this: the hazard rate depends on total consumption production, while utility depends on per capita consumption production. As the population increases, either total consumption has to increase in proportion, or per capita consumption production needs to decrease. But there’s a minimum acceptable level of per capita consumption production (in order to keep utility positive), so eventually we’ll reach a point where total consumption has to increase in proportion to population increase. So it’s not surprising that catastrophe is inevitable in the 𝜀 >> 𝛽 case - this only comes about because we artificially forced population to keep increasing.

But, it turns out that catastrophe would be inevitable in the 𝜀 >> 𝛽 case even without population growth, because without population growth you can’t shift people into the safety sector fast enough to reduce the hazard rate fast enough to prevent existential catastrophe eventually happening.

However, while the simple argument given above is wrong, Phil has worked through the consequences of [a model without exponentially increasing population and with exogenous economic growth](https://philiptrammell.com/static/ExistentialRiskAndExogenousGrowth.pdf) (so, economic growth that is not driven by population growth), and found that this does change some of the results. In particular, existential catastrophe is no longer inevitable for 𝜀 >> 𝛽, provided that 𝛾 is not too small (but NB this result is provisional while potential errors in Aschenbrenner’s paper are checked) .