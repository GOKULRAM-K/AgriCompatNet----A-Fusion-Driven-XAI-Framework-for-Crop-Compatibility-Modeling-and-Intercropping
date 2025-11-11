## This work is the main part of a Research Work done by Gokul Ram K and Dr. Vignesh
# Abstract:
Sustainable agriculture increasingly depends on intelligent systems capable of modeling
complex inter-crop relationships under dynamic environmental conditions. This study
introduces AgriCompatNet, a novel hybrid framework for interpretable crop-pair com-
patibility analysis that integrates agronomic knowledge with data-driven learning. Four
original algorithmic components are proposed: (i) the Nutrient Balance Index (NBI) for
quantifying nutrient proportionality, (ii) the Environmental Resilience Score (ERS) for
measuring climatic adaptability, (iii) the Crop Compatibility Index (CCI) that fuses nu-
trient complementarity and conflict dynamics through a logistic formulation, and (iv) the
AgriCompatNet architecture itself, which unifies these indices within an explainable ma-
chine learning pipeline. The framework was trained and validated on a curated dataset of
2,200 crop instances and evaluated across 2.4 million generated crop-pair combinations.
Experimental results demonstrate a predictive performance of R2 = 0.93, surpassing con-
ventional KNN, K-Means, and Random Forest baselines. Extensive explainable AI (XAI)
analysis using SHAP, ICE, and interaction heatmaps reveals that conflict penalty and nu-
trient balance are the dominant compatibility drivers. A controlled sensitivity simulation
under ±10% environmental perturbations confirms the model’s robustness and ecological
consistency.

<p align="center">
  <img src="images/1_Graphical Insights.png" alt="AgriCompatNet Framework"
       width="950" height="800" style="border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.15);">
  <br>
</p>


#Authors:
1. Gokul Ram K - gokulram.k2023@vitstudent.ac.in
2. Dr. Vignesh U - vignesh.u@vit.ac.in
