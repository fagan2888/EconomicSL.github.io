---
layout: page
title: "Current projects"
sidebar: right
meta_title: "Active Projects"
subheadline: "Who is using Economic Simulation Library?"
teaser: ""
header:
  image_fullwidth: "busanSuburb.jpg"
permalink: "/projects/"
---
There are several projects which are planning on using ESL. It is our hope that these varied use cases both: 1.) test the generalizability of our library, and 2.) result in the instantiation of a wide breadth of common economic components which future users can employ.

**Amlin Project --- ABM of the Insurance Sector**

This project, in cooperation with [MS Amlin](http://www.amlin.com/), will employ Economic Simulation Library to investigate the insurance market. The insurance market is comprised of many of the foundational components of ESL, such as insurance contracts, insurance markets, and the balance sheets of a variety of players. Further, given the heterogeneity of behaviour witnessed within the insurance sector, there is a natural synergy for attempting to better understand insurance markets through the agent-based perspective of Economic Simulation Library.

We are focusing on a couple of research questions: Is there increased systemic risk in the insurance industry if all companies use the historically best model for assessing risk? How does diversification to second-best models affect systemic risk and profitability? Is there a generalization of the Kelly criterion for the insurance industry? What are the endogenous causes of insurance cycles?

**Financial Stress Testing**

Stress tests were instituted at many central banks (such as at the Bank of England, the
Federal Reserve, and the European Central Bank) as an integral part of their regulatory
framework a few years after the financial crisis, which took place in 2007-2008. The
financial crisis showed that banks and other financial institutions are able to default,
bring down other financial institutions, and thereby affect the real economy. Stress tests
aim to assess the resilience of the financial system and individual institutions therein.
The stress test outcome-based regulatory actions are meant to help such a crisis
happening again.

Although the current regulatory stress tests have brought back confidence in the
financial system, have given insight into the previously opaque balance sheets, and
have provided a useful mechanism for recapitalizing banks, stress tests have a few
significant shortcomings due to which these are not able to accurately assess the actual
systemic risk in the financial system. First, stress tests do not take into account
interconnections (e.g. interbank exposure, common asset holdings, derivative
exposures) between financial institutions. Therefore, contagion (i.e. spread of stress),
which was the main driver of defaults in the financial crisis, is not captured. Instead, the
stress tests shock balance sheets. Second, the stress tests focus on one type of
financial institution (e.g. bank stress tests, pension fund stress tests, insurer stress
tests), instead of taking all the tightly interconnected types of financial institutions in
the financial system into account.

To address these shortcomings we are collaborating with the Bank of England, and
some other central banks, to develop a system-wide stress test that does take into
account different types of financial institutions and their interconnections. In particular,
based on empirical observations and data sources (e.g. EU, UK) we are developing an
Agent Based Bodel (ABM) of the financial system. We model:
<ul>

<li> Agents (as a balance sheet composed of financial contracts)</li>
<li> Financial contracts (stipulating the interconnections between financial institutions)</li>
<li> Binding constraints (such as those coming from regulation, e.g. leverage constraint,
these constrain financial institution in their behavior)</li>
<li> Profit-seeking behavior </li>
<li> Financial markets (i.e. the venues where two counterparties match and agree upon
financial contracts). </li>
</ul>

Given that the model is initialized with regulatory data on the financial system, the
model can be used for stress testing purposes to assess the stability of the financial
system. In particular, one can define a systemic risk measure and assess the sensitivity
of this measure to various parameters in the financial system. For example, one can
assess how the stability is influenced by various regulations (such as the level of the
minimum leverage of banks), the structure of the multiplex network (e.g. does crowding
into a particular asset class magnify systemic risk?), and the path of the credit
intermediation chain (i.e. does a more complex chain of credit creation via various nonbanks
increase systemic risk compared to a simpler credit intermediation chain?).
