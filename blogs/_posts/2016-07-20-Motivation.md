---
layout: page
title: "Motivation"
subheadline: "Behind the Scenes"
meta_teaser: "The impetus behind ESP"
teaser: "Why are we building ESP?"
header:
    image_fullwidth: RauwolfMtnCloud.JPG
image:
    thumb:  rockclimbingIcon.jpg
    homepage: carrot.JPG
categories:
    - design
    - overview
---

Failure to predict changes to economic systems is costly. According to the Dallas Federal Reserve Bank %cite Luttrell2013Costs % the recent financial crisis cost the United States on the order of 15 trillion dollars, suggesting a much larger cost for the world as a whole. These costs were significantly
born by the poor, who suffered directly from the downturn in housing markets, which caused many to default.

In recent history, two main techniques have emerged in attempting to predict economic behaviour: a.) Dynamic Stochastic General Equilibrium (DSGE) models, and b.) Agent-based Models (ABM). DSGE models have made significant progress in assessing the microfoundations guiding macro-level behaviour %cite Smets2003 Sungbae2007BaysianDSGE %. Such models offer strong, quantitative economic forecasts grounded by calibration and validation against historic data. However, DSGE models have limitations. They are constructed under the presumption that human behaviour is homogeneous and that economic systems move toward an equilibrium %cite Farmer2009NeedABM %. This rests in stark contrast to the heterogeneous, analytically intractable human behaviour which underlies large-scale economic systems.

ABMs overcome several DSGE obstacles but possess limitations of their own. ABMs allow heterogenous agent behaviour, permitting the researcher to consider the effects of complex micro-level interactions on macro-level behaviour. As such, ABMs have had several successes %cite Klimek2015144 Poledna2014199 Deissenberg2008541 Schelling1971 %. However, whilst ABMs offer heterogeneous behaviour for free, much of the research currently conducted is of a qualitative nature, lacking the calibration and validation required to ground their results. Further, progress in building large-scale models of economic systems has been significantly hindered by the lack of a common modeling platform as well as a common tool stack for data management and analytics. The consequence is that, even when ABMs offer quantitative results, it is difficult to replicate or compare competing models.

In juxtaposing the two methodologies, we believe it is important to note that large-scale micro panel data-sets are becoming increasingly available. Presuming this trend continues, we believe that heterogeneous agent-based models are better placed to leverage such data. However, to exploit this recent deluge of data, agent-based models need to overcome the aforementioned weaknesses. They much strive to offer the microfounded quantitative insight of DSGE models.

### Solution: ESP

Economic Simulation Platform (ESP) is a tool set for building agent-based economic models, which attempts to solve several of the limitations of current ABM models whilst integrating the benefits of DSGE models. The intention of ESP is to provide a collaborative application where users in a variety of economic disciplines can model and analyse agent-based models. ESP combines "Big Data" techniques, particularly machine learning methods capable of taking advantage of large-scale micro panel data sets, with structural economic modeling. Further, ESP offers replicable analysis by presenting a common, modular platform for using ABMs to scrutinize a variety of economic systems.

To the user, the system will be accessed through a web-application, permitting the user to a.) import data, b.) set up their economic components using ESP's plug and play markets and institutions, c.) use machine learning techniques to calibrate their model to fit historic data, and d.) analyse the dynamics of their model over time.

### Bibliography

% bibliography --cited %
