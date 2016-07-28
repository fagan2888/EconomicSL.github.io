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

**Economic Simulation Platform (ESP)** is a community driven, open-source project to develop a user-friendly
modeling platform and tool stack for building scalable, data-driven, and reproducible agent-based models (ABMs) of economic systems on the JVM using Scala and Akka. It is a suite of tools which allows users to build an agent-based
model of their unique economic system with minimal development using existing plug-and-play modules.

**ESP** is:

- _Data Driven, Calibrated and Validated:_ ESP manages the
flow and storage of both model generated data as well as real-world data. The
user's models will be grounded by their empirical data. Calibration and
validation techniques will permit the user to adjust their model to fall in
line with historical data whilst analytic tools will provide the user data on
the state of the model during run-time.

- _Versatile:_ With multiple entry points, ESP offers users their choice
in the granularity of control required for their research. Non-programmers
may instantiate plug-and-play markets, banks, and individuals via a web
interface. Analysis of agent interactions can be conducted without any
programming on the end-user side. If the user requires more granular
control of their system, they may implement their own types of markets,
banks, etc. By developing classes which meet the ESP's specifications, a user can develop the system to their own specification.

- _Open-Source:_ The development of all ESP libraries will be driven by
the needs of the economics ABM community. All software development will take place in public: from the start of the project all source code for the ESP project will be hosted on GitHub under a permissive
Apache 2.0 license that allows for free use of the software libraries (even
in commercial applications).

- _Modular:_ ESP libraries are structured in a way that minimizes the
amount of development time needed to reconfigure and existing model or
build a completely new model. In order to maximize reuse of code, models
built using our toolkit should be composed of mostly existing components.
Leveraging mostly existing components reduces development time for a
new model.

- _Scalable:_ System size is a key parameter for modeling economic systems
and in order to accurately model the dynamics of some systems, users
may need to build and simulate models that are as close to observed
scale as possible. ESP outsources cluster management to third party
providers. ABMs built using our framework can be \containerized" using
technologies such as Docker or Vagrant and then deployed on a third-party
cloud computing service provider such as AWS, Google Compute Engine,
Heroku, Mesosphere, etc. This third party provider then handles all of
the intricacies involved with scaling up the model on the cluster to meet
our needs.

- _Reproducible:_ ESP is not dependent on access to university or national supercomputers. This enhances the reproducibility research. The ability to containerize an ABM built using ESP's framework means
that researchers not directly involved in developing a model can still access
everything (even down to the operating system) necessary to completely
reproduce that model's output. The container can be used to run the
model locally on a laptop or sent to a third party provider to scale up via
the cloud.
