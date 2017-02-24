---
layout: page
title: "Current projects"
sidebar: right
meta_title: "Active Projects"
subheadline: "Who is using Economic Simulation Library?"
teaser: ""
header:
  image_fullwidth: "iowa_suburb_header.png"
permalink: "/projects/"
---
There are several projects which are planning on using ESL. It is our hope that these varied use cases both: 1.) test the generalizability of our library, and 2.) result in the instantiation of a wide breadth of common economic components which future users can employ.


**Agent-Based Model of the Insurance Sector**

This project, in cooperation with [MS Amlin](http://www.amlin.com/), will employ the Economic Simulation Library to investigate the insurance sector. In fact, the insurance market is comprised of many of the foundational components of ESL, such as insurance contracts, insurance markets, and the balance sheets of a variety of players. Furthermore, given the heterogeneity of behaviour witnessed within the insurance sector, there is a natural synergy for attempting to better understand insurance markets through the agent-based perspective of Economic Simulation Library.

In particular, we are focusing on these research questions: Is there increased systemic risk in the insurance industry if all companies use the historically best model for assessing risk? How does diversification to second-best models affect systemic risk and profitability? Is there a generalization of the Kelly criterion for the insurance industry? What are the endogenous causes of insurance cycles?


**Financial Stress Testing**

Stress tests were instituted at many central banks (such as the Bank of England, the Federal Reserve, and the European Central Bank) as an integral part of their regulatory framework a few years after the financial crisis, which took place in 2007-2008. This financial crisis showed that banks and other financial institutions are able to default, bringing down other financial institutions, and thereby affect the real economy. Stress tests aim to assess the resilience of the financial system and individual institutions therein. The stress test outcome-based regulatory actions are meant to prevent such a crisis happening again.

Although the current regulatory stress tests have brought back confidence in the financial system, have given insight into the previously opaque balance sheets, and have provided a useful mechanism for recapitalizing banks, stress tests have a few significant shortcomings due to which these are not able to accurately assess the actual systemic risk in the financial system. First, stress tests do not take into account interconnections (e.g. interbank exposure, common asset holdings, derivative exposures) between financial institutions. Therefore, contagion (i.e. spread of stress), which was the main driver of defaults in the financial crisis, is not captured. Instead, the stress tests shock balance sheets. Second, the stress tests focus on one type of financial institution (e.g. bank stress tests, pension fund stress tests, insurer stress tests), instead of taking all the tightly interconnected types of financial institutions in the financial system into account.

To address these shortcomings we are collaborating with the Bank of England, and some other central banks, to develop a system-wide stress test that does take into account different types of financial institutions and their interconnections. In particular, based on empirical observations and data sources (e.g. EU, UK) we are developing an Agent-Based Bodel (ABM) of the financial system. We model:
<ul>
<li> Agents (as a balance sheet composed of financial contracts)</li>
<li> Financial contracts (stipulating the interconnections between financial institutions)</li>
<li> Binding constraints (such as those coming from regulation, e.g. leverage constraint, these constrain financial institution in their behavior)</li>
<li> Profit-seeking behavior </li>
<li> Financial markets (i.e. the venues where two counterparties match and agree upon financial contracts). </li>
</ul>

Given that the model is initialized with regulatory data on the financial system, the model can be used for stress testing purposes to assess the stability of the financial system. In particular, one can define a systemic risk measure and assess the sensitivity of this measure to various parameters in the financial system. For example, one can assess how the stability is influenced by various regulations (such as the level of the minimum leverage of banks), the structure of the multiplex network (e.g. does crowding into a particular asset class magnify systemic risk?), and the path of the credit intermediation chain (i.e. does a more complex chain of credit creation via various nonbanks increase systemic risk compared to a simpler credit intermediation chain?).


**An agent-based model of UK housing market**

This project, developed in collaboration with the Bank of England, is trying to build an Agent-Based Model (ABM) of the UK housing market. The work took as a starting point an earlier ABM of the Washington DC housing market, which used a wealth of data for calibration, and managed to accurately match many aspects of the housing market over a long forecasting period.

Our housing ABM is a comprehensive model of the UK housing market: it simulates a large pool of households with realistic life-cycles, inheritance of properties, and buy-to-let investors, and it models the rental market in detail. Many data sources have been used to calibrate the model, including market data from private organisations like Zoopla, government household surveys, and Bank of England confidential data.

The model has already been put to use by the Bank of England in order to simulate what-if scenarios and to predict the most likely effect of possible macro-prudential policies. Some of these results, together with a description of the model, have already been published as a [working paper](http://www.bankofengland.co.uk/research/Pages/workingpapers/2016/swp619.aspx). In the future we will expand the model to include a variety of new data sources, more realistic mortgage dynamics, and more robust decision rules for the agents. Furthermore, we will refactor the model in terms of the Economic Simulation Library described here.


**Quantifying the economic roles of infrastructure**

This work is part of the [MISTRAL project (Multi-Scale Infrastructure Systems Analytics)](http://www.itrc.org.uk/), whose aim is to develop and demonstrate a highly integrated analytics capability to inform strategic infrastructure decision making across scales, from local to global. Our particular goal within this project is to study and quantify the inter-relationship between infrastructure and economic activity. Indeed, whilst there are a growing number of empirical studies of the relationship between infrastructure investment and economic growth, the mechanisms by which infrastructure influences economic activity are not well understood in quantitative terms. Part of the difficulty derives from the fact that infrastructure delivers services to businesses and society through networks, and thus any appraisal needs to take place at a system scale. Furthermore, infrastructure can have non-marginal economic effects, and infrastructure investments are often intended to promote structural change, innovation, and social well-being. Infrastructure systems therefore present well-known, but still unresolved, challenges from the perspective of economic appraisal.

This project will try to tackle this knowledge gap by using an agent-based modelling approach in order to provide a reasonably complete account of the economy whilst resolving the physical roles of infrastructure in a way that can be directly connected to the engineering systems models developed elsewhere within MISTRAL. As a first step, we will extend the agent-based model of the UK housing market described above in order to take into account the necessary spatial and geographical aspects allowing us to capture the location decisions of households. Our second step will be to model the coupling between the location decisions of households and firms, with different forms of infrastructure influencing the decision-making processes of both types of agents. Finally, we will use this understanding to enable a rigorous appraisal of the benefits and risks of infrastructure investment.
