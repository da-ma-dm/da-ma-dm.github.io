---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

# Invited Talk
- Predicting the future onset of Alzheimer’s disease using neuroimaging and genomics through stratified multi-modal feature ensemble and deep survival analysis.  Invite Health Informatics Seminar Series at Duke University, February 2022.
- Developing a retinal imaging tool to diagnose Alzheimer’s.  Invited speaker at The ASRP Exchange Program, Alzheimer’s Society Research Program, Canada, July 2021.
- Quantitative analysis of Alzheimer’s disease classification and longitudinal prediction.  Invited Seminar at Shenzhen University School of Biomedical Engineering Health Science Center in Guangdong, China, June 2019.
- Mouse brain morphometry: image processing and analysis of preclinical MRI. Invited Seminar at University of Cardiff in Welsh, UK, August 2015.

# Presentations
## Oral
- Ma D, Lu D, Heisler M, Dabiri S, Lee S, Ding GW, Sarunic MV, Beg MF. Cascaded Deep Neural Networks for Retinal Layer Segmentation of Optical Coherence Tomography with Fluid Presence, Medical Image with Deep Learning (MIDL) 2020 (presentation video)
- Ma D, Lu D, Popuri K., Beg MF, Cardoso MJ, M.A. Zuluaga, M Modat, Powell N, Wiseman F, Tybulewicz V, Fisher E, Lythgoe MF, Ourselin S: Grey matter sublayer thickness estimation in the mouse cerebellum. Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2015 644-651. (presentation video)
- Ma D, Cardoso MJ, Modat M, Powell N, H. Holmes, Lythgoe MF, and Ourselin S: Multi-atlas segmentation applied to in vivo mouse brain MRI. Medical Image Computing and Computer-Assisted Intervention (MICCAI) 2012 Workshop on Multi-Atlas Labeling.

## Poster
- Ma D., Popuri K., Wang L, Lockhart S.N., Craft S, Gurcan M, Beg M.F.. Distinctive age-related longitudinal dementia progression patterns using a machine-learning-based MRI biomarker. Alzheimer's Association International Conference (AAIC) 2022
- Mirabnahrazam, G., Ma, D., Lee, S., Popuri, K., Lee, H., & Cao, J., & Wang, L., & Galvin, J. E., & Beg, M. F.. Imaging Genetic Biomarker Development Using Machine Learning for Alzheimer's Disease Prediction. Organization for Human Brain Mapping (OHBM) 2022. 
- Mirabnahrazam, G., Ma, D., Beaulac, C., Lee, S., Popuri, K., Lee, H., & Cao, J., & Wang, L., & Galvin, J. E., & Beg, M. F.. Deep-Learning-Based Multi-modal Survival Analysis for Alzheimer’s Disease. Organization for Human Brain Mapping (OHBM) 2022. 
- Mirabnahrazam, G., Ma, D., Beaulac, C., Lee, S., Popuri, K., Lee, H., & Cao, J., & Wang, L., & Galvin, J. E., & Beg, M. F.. Predicting Alzheimer’s disease progression in healthy and MCI subjects using multi-modal deep learning approach. submitted to the Alzheimer's Association International Conference (AAIC) 2022
- Siadati M, Miao Y, Athwal A, Ma D, Mammo Z, Ju MJ. Contrast-enhanced motion-free volumetric retinal structure and angiography reconstruction using optical coherence tomography intensity-based volume registration and averaging process. Investigative Ophthalmology & Visual Science ARVO Annual Meeting. 2022 Jun 1;63(7):228-F0075.
- Mirabnahrazam G, Ma D, Sieun Lee, Karteek Popuri, Jiguo Cao, Lei Wang, James E Galvin, Mirza Faisal Beg. Effective Feature Learning of Multi-modal Genetic and Neuroimaging Data for Prediction of Future Conversion to Alzheimer’s Disease: A Machine Learning Based Study. Alzheimer's Association International Conference 2021
- Mirabnahrazam, G., Ma, D., Lee, S., Popuri, K., Lee, H., & Cao, J., & Wang, L., & Galvin, J. E., & Beg, M. F. (2021). A Machine Learning Based Multi-modal Imaging Genetic Study to Predict Future Progression and Conversion to Alzheimer’s Disease. Clinical Trials on Alzheimer’s Disease Conference. 2021
- Sangha O, Lee S, Ma D, Karteek Popuri, Lei Wang, Mirza Faisal Beg. Effects of CSF Biomarkers on Cortical Thickness in Males and Females. Alzheimer's Association International Conference 2021
- Yu T, Ma D, Lo J, Ju MJ, Beg MF, Sarunic MV. Effect of Optical Coherence Tomography Acquisition Sampling Rate Towards Diabetic Retinopathy Severity Classification. In2021 IEEE Photonics Conference (IPC) 2021 Oct 18 (pp. 1-2). IEEE.
- Yu T, Ma D, Lo J, WaChong C, Chambers M, Beg MF, Sarunic MV. Progress on combining OCT-A with deep learning for diabetic retinopathy diagnosis. International Society for Optics and Photonics. 2021
- Yu T, Lo J, Ma D, Zang P, Owen J, Wang RK, Lee AY, Jia Y, Sarunic MV. Collaborative Diabetic Retinopathy Severity Classification of Optical Coherence Tomography Data through Federated Learning. Investigative Ophthalmology & Visual Science. 2021 Jun 21;62(8):1029-.
- Ma D, Jenkins L, Yee E, Popuri K, Chauss G, Wang L., Probst S, Beg MF. Blinded clinical evaluation of automatic methods for FDG-PET in Alzheimer's Disease classification. Alzheimer's Association International Conference 2020
- Ma D, Nagarajan R, Ratra D, Lee S, Sarunic MV, Beg MF, Accurate retinal layer segmentation, thickness estimation and fluid detection on structural and angiographic optical coherence tomography for assessment of diabetic retinopathy. EIVOC 2020
- Ma D, Shi H, Nie Y, Beg MF, Pei J, Cao J. Using Longitudinal Functional Principle Component Analysis early prediction of Alzheimer’s type Disease. EMBEC 2020
- Ma D, Kumar M, Heisler M, Raman R, Sarunic MV, Beg MF. Automatic Differential diagnosis of polypoidal choroidal vasculopathy (PCV) from Age-related macular degeneration (AMD) using Deep Neural Network. ARVO 2020 
-   Ma D, Popuri K, Wang L, Beg Mirza Faisal. Machine-learning-based Alzheimer's Disease dementia score using structural MRI neurodegeneration patterns-independent validation on ADNI, AIBL, OASIS and MIRIAD. Alzheimer's Association International Conference. 2020


{% if site.talkmap_link == true %}
<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>
{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
