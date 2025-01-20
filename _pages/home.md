---
#title:  "Welcome"
#page width can be adjusted in assts/css/main.scss - some strange interactio nwith max-width there and max-width here in the div tags. the div tags work now
layout: archive
classes: wide
permalink: /
hidden: true
author_profile: true
comments: true
---

<span style="text-align: justify; margin: auto;">
I'm a Postdoctoral Research Fellow at the Land, Environment, Economics and Policy Institute at the University of Exeter Business School. I specialize in environmental economics and policy, and my current research focuses on biodiversity conservation and land use. I combine microeconometric methods and quasi-experimental research designs with geospatial data analysis.
</span>

<span  style="text-align: justify; margin: auto;">
I received my PhD in Economics from the University of Gothenburg in 2023. Before my education in economics, I obtained a Master of Laws degree from the University of Helsinki, and I worked at the Finnish Ministry of the Environment where I advised on matters related to EU environmental policy and law.
</span>

[**CV**](/assets/pdf/CV_short.pdf)

<br/>

## Working papers

__Evaluation of Wetland Area Gains and Losses under the US Clean Water Act__<br>
_(with Jessica Coria, João Vaz, and Yann Clough)_ ([Link](/assets/pdf/draft-mitigation-banks.pdf))

<div style="display: flex; justify-content: center; align-items: flex-start; max-width: 1000px; margin: auto;">
    <div style="flex: 1; text-align: justify;">
        <span style="font-size: 14px;">
        Offsetting policies reconcile development and conservation objectives by allowing environmental losses in some locations, given that the losses are compensated with equivalent gains elsewhere. We quantify net losses of wetland area under the US Clean Water Act compensatory mitigation program, which is the most extensive and longest-running environmental offsetting program in the world. A unique feature of the program is how most of the compensation is financed through a market mechanism where permittees purchase compensation credits that specialized firms have generated from wetland restoration activities. We measure environmental outcomes at these restoration sites using high-resolution satellite imagery and land cover change data. In particular, we measure wetland area gains at 400 restoration sites that were established over 1995–2020. Comparing realized compensation projects to planned but withdrawn projects in a difference-in-differences framework, we find that the majority of the environmental gains would not have occurred in absence of dedicated conservation activities. We also find that the market mechanism allocates the type and location of conservation activities according to the opportunity cost of land use. Nonetheless, the wetland area gains appear insufficient to compensate for the wetland area losses regulated within the program. This makes it unlikely that the program will achieve its environmental goals in the long term.
        </span>
    </div>
    <div style="flex: 1;">
        <img src="https://villeinkinen.github.io/assets/images/figure_mbsiteperformance.PNG" alt="Mitigation bank site example" style="width: 100%; height: auto;">
        <div style="font-size: 12px;">Wetland gains at an offsetting site</div>
    </div>
</div>

## Work in progress

__Forest conservation policy, additionality, and socio-environmental implications__<br>
_(with Sarah Meier and Ben Balmford)_

<div style="text-align: justify; max-width: 800px; margin: auto;">  
<span style="font-size: 14px;">This study evaluates the effectiveness of protected areas established in Bolivia between 1990 and 2023 by combining machine learning and matching methods with a difference-in-differences design. Bolivia serves as a compelling case study, having experienced a 27% increase in primary forest loss in 2023 which is its highest level on record for the third consecutive year. As a first step in our analysis, we train a Random Survival Forest model predicting deforestation risk at annual intervals 20 years into the future. This approach explicitly models forest survival duration with right-censored data and is novel in its application to deforestation. The algorithm non-parametrically combines a wide array of features, such as forest density, proximity to anthropogenic land use, topography, and climatic variables to predict deforestation risk scores at a 1 km spatial resolution. We find that PAs in Bolivia have been systematically placed in regions with relatively low baseline deforestation risk and that this tendency has increased over the past three decades. In the second step of the analysis, we implement a staggered difference-in-differences design for evaluating the causal effect of protected areas established in Bolivia. We pre-process the estimation sample by matching treated and control units based on predicted deforestation risk. Furthermore, we analyse treatment effect heterogeneity along the distribution of predicted deforestation risk. Additionally, we assess the impact of protected area establishment on economic activity, biodiversity, and carbon stocks.</span> 
</div>

__Accounting for carbon additionality in the presence of deforestation and regrowth__<br>
_(with Ben Balmford, Sarah Meier, Lorenzo Sileci, Zden&#283;k Ples&#283;k, Charles Palmer, Diana Weinhold, Sabrina Eisenbarth, Lykke Andersen, Fabiana Argando&ntilde;a, and Ben Groom)_

<div style="display: flex; justify-content: center; align-items: flex-start; max-width: 1000px; margin: auto;">
    <div style="flex: 1; text-align: justify;">
        <span style="font-size: 14px;">
        This study develops a methodological framework that integrates high-resolution remote sensing data with machine learning techniques to predict the potential additionality of forest conservation and reforestation interventions in the tropical biomes of South America. By modeling forest cover dynamics explicitly, we generate annual future predictions of deforestation and regrowth probabilities. These probabilities have a direct additionality interpretation that can guide intervention targeting. We also convert the probabilities into expected pathways of carbon storage, both in physical and monetary terms. Our approach allows for a direct comparison of expected outcomes under business-as-usual scenarios against those enhanced by conservation interventions. This provides a powerful tool for governments, NGOs, and private stakeholders to optimize their forest conservation strategies, ensuring that limited resources are directed where they can achieve the greatest environmental and financial impact.
        </span>
    </div>
    <div style="flex: 1;">
        <img src="https://villeinkinen.github.io/assets/images/sa-s-hat-forest-diff.png" alt="South America intervention targeting" style="width: 80%; height: auto;">
        <div style="font-size: 12px;">The map highlights locations where forest conservation is predicted to have high potential additionality</div>
    </div>
</div>

__The Effect of Water Resource Protection on Construction Employment in the United States__

<div style="text-align: justify; max-width: 800px; margin: auto;">
<span style="font-size: 14px;">The Clean Water Rule, an executive order enacted in 2015, expanded the scope of waters that are federally protected under the Clean Water Act. I use a difference-in-differences framework to compare construction employment between the 22 states where the Rule was implemented and the 28 states where it was never implemented due to litigation in regional courts. I find that the overall effect of the Rule on construction employment was negligible, likely due to how states with stringent pre-existing state-level regulations selected into implementing the Rule. However, a negative effect appears in states that had unsuccessfully litigated against the Rule. Furthermore, the decrease in construction activity was most prominent in counties where low-cost compliance options through environmental offset markets were limited. The regulator should take steps to avoid supply shortages and monopolistic conditions in the compensation credit market without compromising its environmental integrity.</span> 
</div>

__Offsetting biodiversity: What drives the choice of offset mechanism in the US Wetland Mitigation Program?__<br>
_(with Jessica Coria and João Vaz)_

<div style="text-align: justify; max-width: 800px; margin: auto;">
<span style="font-size: 14px;">This paper examines offset method decisions under the US wetland mitigation program and compares the cost effectiveness of prescriptive on-site and market-based off-site approaches. By measuring costs through land values and benefits through flood control values, we highlight a clear trade-off between these two mechanisms. Prescriptive on-site compensation incurs higher costs but delivers greater benefits, while market-based off-site compensation leads to lower costs but also reduced benefits. Our analysis also reveals that cost minimization heavily influences the regulator's choice of offset method, while flood control benefits appear to be absent from policy determinations. This finding, combined with the increased adoption of third-party offsets, reveals an overreliance on the market mechanism. Although policy guidelines explicitly state that decisions should be based on both the costs and benefits of alternative offset methods, our findings indicate that regulatory decisions overlook the flood control benefits of prescriptive offsets, thereby deviating from the policy rule.</span> 
</div>




