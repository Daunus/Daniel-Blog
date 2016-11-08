---
layout: post
title:  "Why Peter R’s Fee Market Wont Work"
permalink:  "why-peter-fee-market-wont-work"
date:   2015-11-30 20:08:35 -0200
categories: economics bitcoin
---


<p>At the first Scaling Bitcoin conference Peter R presented his ideas on why a fee market would exist without a block size limit. You can see his presentation here: https://www.youtube.com/watch?v=ad0Pjj_ms2k.</p>

<p>He is wrong and I will explain why.</p>

<p>Peter says that a non-zero supply curve exists because increasing block size increases cost to miners due to higher orphan rate. I have also heard a variation of this argument with increasing block size being constrained by hardware resources, internet bandwidth etc.</p>

<p>Theoretically these arguments are correct, practically they are not.</p>

<p>The effect of block size on these costs is almost negligible.</p>

<p>The supply curve is not exactly flat but very close to it. It is practically (if not theoretically)  flat and at zero. In reality a fee market will not form.</p>

<p>As an example, we have a supply and demand curve for oxygen but there is no real market for it because its impractical for something so cheap with such a flat and low curve. Yes, Oxygen does have a supply curve because humans are capable of increasing its supply at an increasing cost.</p>

<p>When curves meet at extremes the market breaks down.</p>

<p>No block size limit would simply result in huge blocks and a much more centralised node network, that can be easier influenced by governments.</p>

<p>But lets ignore all of the above for a second.</p>

<p>Peter also says we need at least 2 mining pools, for a market to form based on the orphan rate cost. Of course you hardly have much of a market with 2 pools, or 5-10 pools. That is what we have now. You can not have a real efficient market for orphan rates with only a few participants at one end.</p>

<p>Furthermore, orphan rate is a result of block propagation and can be decreased by moving pools closer together geographically. That is obviously very negative if we are trying to prevent mining centralisation.</p>

<p>To quote Gregory Maxwell:</p>

> > How could you have written at such length and complexity but ignoring the simple expident miners have of simply centeralizing their operation around larger pools to lower their costs– an activity they previously performed, in practice, not just theory (which was walked back by handing them more efficient relay mechenisms) and which is simple, easy, and which reduces those marginal costs to 0 at the limit (e.g. all miners served off a particular host) — after I specifically called you out on this previously?   Doubly so when your analysis gives provides a framework for analyizing the profitibility of moving from one point on that income tradeoff graph to another (e.g. the lost income from failing to centeralize)….


<p>You might ask, why can a fee market form with fixed block-size supply then? After-all we still have only a small number of pools? The reason is, that in Peter’s model the cost variable is due to the differing orphan rate between pools. That is not true for fixed block size. There is no variable for the supply curve. Thats why the supply curve is a straight vertical line.</p>

<p>Finally Peter refers to the block size limit as some ‘artificial centrally controlled limit’.</p>

<p>He does raise a good and important point here. In the situation of a fee-market based on limited block size, what would be the mechanism for changing the block-size limit and who would have control? The solutions from Peter R or others did not satisfy me personally. It is a valid question though. Are we to have a hard-fork each time we decide the fees are getting too high or low?  Do we implement code to allow a semi-centralised authority to decide? These do not seem like good solutions.</p>

<p>To say it is a centrally controlled limit is wrong however. To change the limit needs the consensus of the network i.e. nodes. Core developers have some limited ability to influence people, but ultimately they can not force through any change by themselves, they need the networks tacit agreement. Nobody and everybody controls the limit. Its control is decentralised (and therefore hard to change).</p>

<p>Finally there is nothing exceptionally artificial about the limit. Bitcoin itself is artificial, the 21 million limit is also an arbitrary artificial limit. Humans set the parameters of Bitcoin, its supply and its block size limit. The problem and difference is the 21 million limit does not have to change. Block size limit might have to, how will that be decided?</p>
