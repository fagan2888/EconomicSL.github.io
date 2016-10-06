---
layout: page
sidebar: right
title: "Overview"
meta_title: "Economic Simulation Platform"
subheadline: "A toolkit for building models of economic systems"
teaser: ""
header:
  image_fullwidth: header_unsplash_5.jpg
permalink: "/overview/"
---

**Economic Simulation Library (ESL)** is a open-source project to develop a user-friendly software library for building agent-based models (ABMs) of economic systems. The goal is to build a Java library which acts as a starting point for a variety of economic models. In the near term, this will come in the form of several abstract classes of constructs commonly found in economic models, including balance sheets, contracts, and markets. We are then constructing an API for how these classes interact. For example, the requirements of a contract (e.g. a mortgage needs to be paid) can automatically alter the balance sheets of the involved parties. We are hoping that this basic foundation will save agent-based modelers time by implementing several dynamics which are shared across a variety of economic ABMs.

Long-term, we hope that common implementations of our library can be used to create 'plug and play' economic models. For example, an individual might want to model a housing market where run-of-the-mill banks decide whether to offer mortgages to buyers with varied balance sheets. The intent is that, once someone has developed each of the component parts using our framework, other modelers will be able to quickly plug those components into their own model.

We are just starting to build models with our library. As such, we would be very interested in contributions both in the form of use-cases as well as from parties willing to consider using our framework for building their own models. Feel free to [contact us]({{site.url}}/contact/) if you interested in hearing more!  

<h4 style="text-align: center;" markdown="1">**A bit more detail**</h4>

ESL is founded on a belief that many agent-based economic models require a few common components. By building an infrastructure for creating these components, we hope to enable modelers to quickly generate their complex models. Below is a brief description of our core components. A more in depth description is available in our design document.   

!({{site.urlimg}}uml_esl.jpg)

**Agents**

Agents represent the decision-making parties in economic systems, including individuals, firms, government entities, etc. They may propose, accept, and fulfill or – depending on the setting  - violate _contracts_. Each agent is equipped with a _balance sheet_ into which their assets, liabilities and contracts are recorded.

**Balance sheets**

The balance sheet of an actor is intended to maintain the list of items belonging to that agent, their assets, their liabilities, and their other contracts, e.g. the tangible assets of the agent, the agent’s debt, or their contract to share certain information with another agent.

**Contracts**

Contracts are a commitment by an agent, usually  involving a counterparty. The commitment defines actions which have to be taken by the agent at a certain time, e.g. to transfer a quantity of a good to another agent. ESL shall, however, also allow for more sophisticated designs, such as smart contracts  which specify conditional clauses that become effective contingent upon certain events. Contracts may effect changes to the agent's balance sheets, e.g. transferring an asset from one agent to another; ensuring consistency is of paramount importance in this operation.

As long as a user writes their contracts to our API specifications, then ESL automatically handles the manipulation of agent balance sheets in the background. This will allow users to ignore the implementation details of balance sheet manipulation and focus on the nuances of their model.

**Markets**

A market acts as a trading ground for contracts and goods. A market collects bid and sell orders for a certain class of items, maintains an order book and operates a matching engine that matches orders. Different choices for matching engines are provided. For example, if a user wishes to have use a continuous double auction, then they can pull our implementation, associate the contracts specific to their model and run the simulation.

<h4 style="text-align: center;" markdown="1">**Long-term goals**</h4>

**Modularity**

Initially, Economic Simulation Library will consist of abstract markets, balance sheets, etc. In order to instantiate a model, a user will need to implement the details of their model by extending the abstract classes. However, as instantiations of these classes are developed, they can be used in other models. For example, once a generic fixed-bond contract is implemented, then users can pull the contract and plug it into their own model. The hope is that once enough instantiations of common components have been implemented, then a researcher with limited programming skills will still be able to develop a complex model by plugging in existing components.  

**Data Driven, Calibrated and Validated**

ESL will eventually help manage the flow and storage of both model generated data as well as real-world data. The
user's models will be grounded by their empirical data. Calibration and validation techniques will permit the user to adjust their model to fall in line with historical data whilst analytic tools will provide the user data on the state of the model during run-time.
