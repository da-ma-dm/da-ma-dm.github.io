---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

1. Yee E, Ma D, Popuri K, Chen S, Lee H, Chow V, Ma C, Wang L, Beg MF. 3D hemisphere-based convolutional neural network for whole-brain MRI segmentation. Computerized Medical Imaging and Graphics. 2022 Jan 1;95:102000. 
2. Mirabnahrazam G, Ma D, Lee S, Popuri K, Lee H, Cao J, Wang L, Galvin JE, Beg MF, Initiative  the ADN. Machine Learning Based Multimodal Neuroimaging Genomics Dementia Score for Predicting Future Conversion to Alzheimer’s Disease. Journal of Alzheimer’s Disease. IOS Press; 2022 Jan 1;87(3):1345–1365. 
3. Mirabnahrazam G, Ma D, Beaulac C, Lee S, Popuri K, Lee H, Cao J, Galvin JE, Wang L, Beg MF, Initiative  the ADN. Predicting Time-to-conversion for Dementia of Alzheimer’s Type using Multi-modal Deep Survival Analysis. arXiv:220501188 [cs] [Internet]. 2022 May 2 [cited 2022 May 4]; Available from: http://arxiv.org/abs/2205.01188
4. Ma D, Kumar M, Khetan V, Sen P, Bhende M, Chen S, Yu TTL, Lee S, Navajas EV, Matsubara JA, Ju MJ, Sarunic MV, Raman R, Beg MF. Clinical explainable differential diagnosis of polypoidal choroidal vasculopathy and age-related macular degeneration using deep learning. Computers in Biology and Medicine. 2022 Apr 1;143:105319. 
5. Yee E, Ma D, Popuri K, Wang L, Beg MF, Initiative  and for the ADN, Ageing  and the AIB and L flagship study of. Construction of MRI-Based Alzheimer’s Disease Score Based on Efficient 3D Convolutional Neural Network: Comprehensive Validation on 7,902 Images from a Multi-Center Dataset. Journal of Alzheimer’s Disease. IOS Press; 2021 Jan 1;79(1):47–58. PMCID: PMC9159475
6. Sangha O, Ma D, Popuri K, Stocks J, Wang L, Beg MF. Structural volume and cortical thickness differences between males and females in cognitively normal, cognitively impaired and Alzheimer’s dementia population. Neurobiology of Aging. 2021 Oct 1;106:1–11. 
7. Ma D, Yee E, Stocks JK, Jenkins LM, Popuri K, Chausse G, Wang L, Probst S, Beg MF. Blinded Clinical Evaluation for Dementia of Alzheimer’s Type Classification Using FDG-PET: A Comparison Between Feature-Engineered and Non-Feature-Engineered Machine Learning Methods. J Alzheimers Dis. 2021;80(2):715–726. PMCID: PMC8978589
8. Popuri K, Ma D, Wang L, Beg MF. Using machine learning to quantify structural MRI neurodegeneration patterns of Alzheimer’s disease into dementia score: Independent validation on 8,834 images from ADNI, AIBL, OASIS, and MIRIAD databases. Hum Brain Mapp. 2020 Oct;41(14):4127–4147. PMCID: PMC7469784
9. Ma D, Lu D, Popuri K, Wang L, Beg MF, Alzheimer’s Disease Neuroimaging Initiative. Differential Diagnosis of Frontotemporal Dementia, Alzheimer’s Disease, and Normal Aging Using a Multi-Scale Multi-Type Feature Generative Adversarial Deep Neural Network on Structural Magnetic Resonance Images. Front Neurosci. 2020 Oct 22;14:853. PMCID: PMC7643018
10. Ma D, Lu D, Heisler M, Dabiri S, Lee S, Ding GW, Sarunic MV, Beg MF. Cascade dual-branch deep neural networks for retinal layer and fluid segmentation of optical coherence tomography incorporating relative positional map. In: Arbel T, Ben Ayed I, de Bruijne M, Descoteaux M, Lombaert H, Pal C, editors. Proceedings of the third conference on medical imaging with deep learning [Internet]. PMLR; 2020. p. 493–502. Available from: https://proceedings.mlr.press/v121/ma20a.html
11. Ma D, Cardoso MJ, Zuluaga MA, Modat M, Powell NM, Wiseman FK, Cleary JO, Sinclair B, Harrison IF, Siow B, Popuri K, Lee S, Matsubara JA, Sarunic MV, Beg MF, Tybulewicz VLJ, Fisher EMC, Lythgoe MF, Ourselin S. Substantially thinner internal granular layer and reduced molecular layer surface in the cerebellar cortex of the Tc1 mouse model of down syndrome – a comprehensive morphometric analysis with active staining contrast-enhanced MRI. NeuroImage. 2020 Dec 1;223:117271. PMCID: PMC8417772
12. Ma D, Popuri K, Bhalla M, Sangha O, Lu D, Cao J, Jacova C, Wang L, Beg MF, Alzheimer’s Disease Neuroimaging Initiative. Quantitative assessment of field strength, total intracranial volume, sex, and age effects on the goodness of harmonization for volumetric analysis on the ADNI database. Hum Brain Mapp. 2019 Apr 1;40(5):1507–1527. PMCID: PMC6449147


{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u> 
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
