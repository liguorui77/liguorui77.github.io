---
title: "Dual-domain based Backdoor Attack Against Federated Learning"
collection: publications
permalink: /publication/NeuCom2025
excerpt: ''
date: 2025-01-14
venue: 'Neurocomputing'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0925231225000967'
citation: 'Guorui Li, Runxing Chang, Ying Wang, Cong Wang. Dual-domain based backdoor attack against federated learning. Neurocomputing, 2025, 129424: 1-13.'
---
The distributed training feature and data heterogeneity in federated learning (FL) render it susceptible to various threats, in which the backdoor attack stands out as the most destructive one. By injecting malicious functionality into the global model through poisoned updates, backdoor attacks can generate attacker-desired inference results on the trigger-embedded inputs while behaving normally on other data instances. The current backdoor triggers are of significant visual features that can be easily identified by humans or computers. Meanwhile, the common model update clipping mechanism is too simple and straightforward to be recognized by various defense methods with ease. Aiming at the above shortcomings, we proposed a dual-domain based backdoor attack (DDBA) against FL in this paper. On the one hand, DDBA generates an imperceptible dual-domain trigger for any image by superimposing in its low-frequency region of the amplitude spectrum and then applying a slight spatial distortion subsequently. On the other hand, DDBA truncates the model update dynamically based on a newly designed adaptive clipping mechanism to enhance its stealthiness. Finally, we carried out extensive experiments to evaluate the attack performance and stealth performance of DDBA on four publicly available datasets. The experiment results show that DDBA has excellent attack performance in both single-shot and multiple-shot attack scenarios as well as robust stealth performance under the existing defense methods against backdoor attacks.
