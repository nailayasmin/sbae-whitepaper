# Front matter

<!-- Source: FAO. 2024. Good practices in sample-based area estimation. White paper. cc9276en -->

<!-- PDF page 4 | printed page front matter -->

**REQUIRED CITATION:**

Jonckheere, I., Hamilton, R., Michel, J.M. & Donegan, E., eds. 2024. *Good practices in sample-based area estimation*. White paper. Rome, FAO. https://doi.org/10.4060/cc9276en

The designations employed and the presentation of material in this information product do not imply the expression of any opinion whatsoever on the part of the Food and Agriculture Organization of the United Nations (FAO) concerning the legal or development status of any country, territory, city or area or of its authorities, or concerning the delimitation of its frontiers or boundaries. The mention of specific companies or products of manufacturers, whether or not these have been patented, does not imply that these have been endorsed or recommended by FAO in preference to others of a similar nature that are not mentioned.

The views expressed in this information product are those of the author(s) and do not necessarily reflect the views or policies of FAO.

ISBN 978-92-5-138531-9

© FAO, 2024

Some rights reserved. This work is made available under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 IGO licence (CC BY-NC-SA 3.0 IGO; https://creativecommons.org/licenses/by-nc-sa/3.0/igo/legalcode).

Under the terms of this licence, this work may be copied, redistributed and adapted for non-commercial purposes, provided that the work is appropriately cited. In any use of this work, there should be no suggestion that FAO endorses any specific organization, products or services. The use of the FAO logo is not permitted. If the work is adapted, then it must be licensed under the same or equivalent Creative Commons licence. If a translation of this work is created, it must include the following disclaimer along with the required citation: “This translation was not created by the Food and Agriculture Organization of the United Nations (FAO). FAO is not responsible for the content or accuracy of this translation. The original [Language] edition shall be the authoritative edition.”

Disputes arising under the licence that cannot be settled amicably will be resolved by mediation and arbitration as described in Article 8 of the licence except as otherwise provided herein. The applicable mediation rules will be the mediation rules of the World Intellectual Property Organization http://www.wipo.int/amc/en/mediation/rules and any arbitration will be conducted in accordance with the Arbitration Rules of the United Nations Commission on International Trade Law (UNCITRAL).

**Third-party materials.** Users wishing to reuse material from this work that is attributed to a third party, such as tables, figures or images, are responsible for determining whether permission is needed for that reuse and for obtaining permission from the copyright holder. The risk of claims resulting from infringement of any third-party-owned component in the work rests solely with the user.

**Sales, rights and licensing.** FAO information products are available on the FAO website (www.fao.org/publications) and can be purchased through publications-sales@fao.org. Requests for commercial use should be submitted via: www.fao.org/contact-us/licence-request. Queries regarding rights and licensing should be submitted to: copyright@fao.org.

<!-- PDF page 5 | printed page front matter -->

# Abstract

Reducing Emissions from Deforestation and Forest Degradation, and the role of conservation, sustainable management of forests and enhancement of forest carbon stocks in developing countries (REDD+), as well as greenhouse gas reporting for the agriculture, forestry and other land use sector, requires land use changes to be characterized to estimate the associated greenhouse gas emissions or absorptions. It is becoming increasingly common to generate these estimates using sample-based area estimation (SBAE). This technique has been widely used in recent years in the generation of activity data  –  particularly for estimating areas of deforestation – for REDD+ measuring, reporting and verification. However, implementing countries and agencies have repeatedly highlighted the lack of guidance on how to address certain frequently encountered issues with this approach. This paper responds to this need by addressing the most urgent technical issues faced by countries relating to SBAE, such as how to best monitor forest dynamics other than deforestation, how to account for variability between interpreters looking at the same sample unit, how to define the sample unit to use, and how many assessments are needed per sample unit. These issues were identified and prioritized based on a review of country experience and online expert consultations in March 2020. For each issue, a description and recommendations are provided. Existing good practices are consolidated, and new good practices are proposed as solutions where appropriate. The paper also indicates areas for future research which should be pursued to answer the remaining questions surrounding area estimation.

This paper seeks to enable donors, academia, and countries that currently use or want to use SBAE for generating activity data for REDD+ or for other national or international reporting purposes, to delve into current good practice and existing literature, as well as gain a better understanding of the most pressing research needs in the area. The paper moreover will give non-experts an overview of area estimation, as well as its applications and limitations.

<!-- PDF page 10 | printed page front matter -->

# Acknowledgements

This paper was written by the following National Forest Management (NFM) team members at the Food and Agriculture Organization of the United Nations (FAO) headquarters: Inge Jonckheere, José Maria Michel, Emily Donegan, Erik Lindquist, Rémi d’Annunzio and Andreas Vollrath. It was also written by Randy Hamilton from SilvaCarbon.

Furthermore, specific sections were written by the following external experts: Frédéric Achard, Charles Scott, Andrew Lister, Ron McRoberts, Steve Stehman, Pontus Olofsson, German Obando-Vargas, Christophe Sannier, Andres Espejo and Paul Patterson.

Editing of this white paper was done by Inge Jonckheere, Randy Hamilton, José Maria Michel, and Emily Donegan.

Copyediting was completed by Alex Gregor and Rachel Golder, with graphic design by Roberto Cenciarelli and Lorenzo Catena. Sara Maulo and Vanessa Vertiz supported the publication process. This paper was produced by FAO thanks to finance from the Global Forest Observations Initiative (GFOI), the World Bank and the Department for Energy Security and Net Zero of the United Kingdom of Great Britain and Northern Ireland.

<!-- PDF page 11 | printed page front matter -->

# Abbreviations

| | |
|---|---|
|eSBAE|ensemble sample-based area estimation|
|FAO|Food and Agriculture Organization of the United Nations|
|FREL|Forest Reference Emission Level|
|GFOI|Global Forest Observations Initiative|
|IPCC|Intergovernmental Panel on Climate Change|
|LULC|land use and land cover|
|MGD|Methods and Guidance Document|
|NFI|national forest inventory|
|PSU|primary sampling unit|
|QA/QC|quality assurance/quality control|
|REDD+|Reducing Emissions from Deforestation and Forest Degradation, and the role of conservation, sustainable management of forests and enhancement of forest carbon stocks in developing countries|
|SBAE|sample-based area estimation|
|SRS|simple random sampling|
|STR|stratified random sampling|
|SYS|systematic sampling|
|UNFCCC|United Nations Framework Convention on Climate Change|

<!-- PDF page 12 | printed page front matter -->

# Units and formulae

| | |
|---|---|
| CV | coefficient of variation |
| $h$ | stratum |
| ha | hectare |
| k | kilometre |
| k² | square kilometre |
| m | metre |
| m² | square metre |
| $N$ | number of sample units |
| $M$ | number of population units (points) within a sample unit |
| $\hat{p}$ | estimated proportion of area |
| $p_h$ | proportion of area of stratum (h) that is deforestation based on the reference classification |
| $\hat{P}_i$ | proportion of points in the class of interest on plot |
| $\hat{P}_R$ | estimator of the proportion of the attribute of interest |
| $\hat{P}_{RS}$ | stratified or post-stratified sampling estimator |
| $R$ | region |
| $SU$ | sample unit |
| $V(\hat{p})$ | potential impact of omission errors on the variance |
| $v(\hat{P}_R)$ | variance estimator under simple random sampling |
| $v_s(\hat{P}_{RS})$ | variance estimator for the stratified estimator |
| $v_{PS}(\hat{P}_{RS})$ | variance estimator for the post-stratified estimator |
| $W_h$ | proportion of area in stratum h for the study region |
