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

Failure to predict changes to economic systems is costly. According to the Dallas Federal Reserve Bank [(Luttrell et al., 2013)](#Luttrell) the recent financial crisis cost the United States on the order of 15 trillion dollars, suggesting a much larger cost for the world as a whole. These costs were significantly
born by the poor, who suffered directly from the downturn in housing markets, which caused many to default.

In recent history, two main techniques have emerged in attempting to predict economic behaviour: a.) Dynamic Stochastic General Equilibrium (DSGE) models, and b.) Agent-based Models (ABM). DSGE models have made significant progress in assessing the microfoundations guiding macro-level behaviour ([Smets and Wouters, 2003](#Smets2003); [An and Schorfheide, 2007](#An2007)). Such models offer strong, quantitative economic forecasts grounded by calibration and validation against historic data. However, DSGE models have limitations. They are constructed under the presumption that human behaviour is homogeneous and that economic systems move toward an equilibrium ([Farmer and Foley, 2009](#Farmer2009)). This rests in stark contrast to the heterogeneous, analytically intractable human behaviour which underlies large-scale economic systems.

ABMs overcome several DSGE obstacles but possess limitations of their own. ABMs allow heterogenous agent behaviour, permitting the researcher to consider the effects of complex micro-level interactions on macro-level behaviour. As such, ABMs have had several successes ([Klimek et al., 2015](#Klimek2015); [Poledna et al., 2014](#Poledna2014); [Deissenberg et al., 2008](#Deissenberg2008); [Schelling, 1971](#Schelling1971)). However, whilst ABMs offer heterogeneous behaviour for free, much of the research currently conducted is of a qualitative nature, lacking the calibration and validation required to ground their results. Further, progress in building large-scale models of economic systems has been significantly hindered by the lack of a common modeling platform as well as a common tool stack for data management and analytics. The consequence is that, even when ABMs offer quantitative results, it is difficult to replicate or compare competing models.

In juxtaposing the two methodologies, we believe it is important to note that large-scale micro panel data-sets are becoming increasingly available. Presuming this trend continues, we believe that heterogeneous agent-based models are better placed to leverage such data. However, to exploit this recent deluge of data, agent-based models need to overcome the aforementioned weaknesses. They much strive to offer the microfounded quantitative insight of DSGE models.

### Solution: ESP

Economic Simulation Platform (ESP) is a tool set for building agent-based economic models, which attempts to solve several of the limitations of current ABM models whilst integrating the benefits of DSGE models. The intention of ESP is to provide a collaborative application where users in a variety of economic disciplines can model and analyse agent-based models. ESP combines "Big Data" techniques, particularly machine learning methods capable of taking advantage of large-scale micro panel data sets, with structural economic modeling. Further, ESP offers replicable analysis by presenting a common, modular platform for using ABMs to scrutinize a variety of economic systems.

To the user, the system will be accessed through a web-application, permitting the user to a.) import data, b.) set up their economic components using ESP's plug and play markets and institutions, c.) use machine learning techniques to calibrate their model to fit historic data, and d.) analyse the dynamics of their model over time.

### Bibliography
<ul>
<li>
<a name="An2007"></a> An, S., Schorfheide, F., 2007. Bayesian analysis of dsge models. Econometric
Reviews 26 (2-4), 113-172.
</li>

<li><a name="Deissenberg2008"></a> Deissenberg, C., van der Hoog, S., Dawid, H., 2008. Eurace: A massively
parallel agent-based model of the european economy. Applied Mathematics and Computation 204 (2), 541 { 552, special Issue on New Approaches in Dynamic Optimization to Assessment of Economic and Environmental
Systems. URL http://www.sciencedirect.com/science/article/pii/S0096300308003019
</li>

<li><a name="Farmer2009"></a> Farmer, J. D., Foley, D., 2009. The economy needs agent-based modelling. Nature 460, 685-686. URL http://dx.doi.org/10.1038/460685a
</li>

<li><a name="Klimek2015"></a> Klimek, P., Poledna, S., Farmer, J. D., Thurner, S., 2015. To bail-out or to
bail-in? answers from an agent-based model. Journal of Economic Dynamics and Control 50, 144 { 154, crises and ComplexityComplexity Research Initiative for Systemic InstabilitieS (CRISIS) Workshop 2013.
URL http://www.sciencedirect.com/science/article/pii/S0165188914002097
</li>

<li><a name="Luttrell"></a>Luttrell, D., Atkinson, T., Rosenblum, H.], 2013. Assessing the costs and consequences of the 2007?09 nancial crisis and its aftermath. Economic Letter 8 (sep). URL https://ideas.repec.org/a/fip/feddel/y2013isepnv.8no.7.html
</li>

<li> <a name="Poledna2014"></a>Poledna, S., Thurner, S., Farmer, J. D., Geanakoplos, J., 2014. Leverage-induced systemic risk under basle ii and other credit risk policies. Journal of
Banking & Finance 42, 199-212. URL http://www.sciencedirect.com/science/article/pii/S0378426614000521
</li>

<li><a name="Schelling1971"></a> Schelling, T. C., 1971. Dynamic models of segregation. The Journal of Mathematical Sociology 1 (2), 143-186.
</li>

<li>
<a name="Smets2003"></a> Smets, F., Wouters, R., 2003. An estimated dynamic stochastic general equilibrium model of the euro area. Journal of the European Economic Association 1 (5), 1123 { 1175. URL http://search.ebscohost.com.ezproxy1.bath.ac.uk/login.aspx?direct=true&db=bth&AN=12285012&site=ehost-live
</li>

</ul>
