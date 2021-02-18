# Predicting the Perception of Above-the-Fold Time in Web Browsing

## Plausibly Complete Time (PCT) implementation

## Objective
PCT is a metric that estimates ATF time for a user’s perception of websites with and without animations. PCT can be integrated with SpeedIndex to  improves the prediction  of SpeedIndex for websites with and without animations.

## Contributors
Dr. Hamed Jahromi
Dr. Declan Delaney
Dr. Andrew Hines 

## How to cite?

If you want to cite the metric, please cite the following paper:

[1] Jahromi, H.Z.; Delaney, D.; Hines, A. A Sign of Things to Come: Predicting the Perception of Above-the-Fold Time in Web Browsing. Future Internet 2021, 13, 50. https://doi.org/10.3390/fi13020050

### BibTeX:
@Article{fi13020050,

AUTHOR = {Jahromi, Hamed Z. and Delaney, Declan and Hines, Andrew},\n
TITLE = {A Sign of Things to Come: Predicting the Perception of Above-the-Fold Time in Web Browsing},
JOURNAL = {Future Internet},
VOLUME = {13},
YEAR = {2021},
NUMBER = {2},
ARTICLE-NUMBER = {50},
URL = {https://www.mdpi.com/1999-5903/13/2/50},
ISSN = {1999-5903},
ABSTRACT = {Content is a key influencing factor in Web Quality of Experience (QoE) estimation. A web user’s satisfaction can be influenced by how long it takes to render and visualize the visible parts of the web page in the browser. This is referred to as the Above-the-fold (ATF) time. SpeedIndex (SI) has been widely used to estimate perceived web page loading speed of ATF content and a proxy metric for Web QoE estimation. Web application developers have been actively introducing innovative interactive features, such as animated and multimedia content, aiming to capture the users’ attention and improve the functionality and utility of the web applications. However, the literature shows that, for the websites with animated content, the estimated ATF time using the state-of-the-art metrics may not accurately match completed ATF time as perceived by users. This study introduces a new metric, Plausibly Complete Time (PCT), that estimates ATF time for a user’s perception of websites with and without animations. PCT can be integrated with SI and web QoE models. The accuracy of the proposed metric is evaluated based on two publicly available datasets. The proposed metric holds a high positive Spearman’s correlation (rs=0.89) with the Perceived ATF reported by the users for websites with and without animated content. This study demonstrates that using PCT as a KPI in QoE estimation models can improve the robustness of QoE estimation in comparison to using the state-of-the-art ATF time metric. Furthermore, experimental result showed that the estimation of SI using PCT improves the robustness of SI for websites with animated content. The PCT estimation allows web application designers to identify where poor design has significantly increased ATF time and refactor their implementation before it impacts end-user experience.},
DOI = {10.3390/fi13020050}
}



