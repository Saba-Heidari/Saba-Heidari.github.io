---
title: "Age encoded adversarial learning for pediatric CT segmentation"
collection: publications
category: manuscripts
permalink: /publication/Age Encoded Adversarial Learning for Pediatric CT Segmentation
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-03-27
venue: 'Bioengineering'
slidesurl: '[http://academicpages.github.io/files/slides1.pdf](https://www.mdpi.com/2306-5354/11/4/319)'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Gheshlaghi, Saba Heidari, Chi Nok Enoch Kan, Taly Gilat Schmidt, and Dong Hye Ye. "Age encoded adversarial learning for pediatric CT segmentation." Bioengineering 11, no. 4 (2024): 319.'
---

Organ segmentation from CT images is critical in the early diagnosis of diseases, progress monitoring, pre-operative planning, radiation therapy planning, and CT dose estimation. However, data limitation remains one of the main challenges in medical image segmentation tasks. This challenge is particularly huge in pediatric CT segmentation due to children’s heightened sensitivity to radiation. In order to address this issue, we propose a novel segmentation framework with a built-in auxiliary classifier generative adversarial network (ACGAN) that conditions age, simultaneously generating additional features during training. The proposed conditional feature generation segmentation network (CFG-SegNet) was trained on a single loss function and used 2.5D segmentation batches. Our experiment was performed on a dataset with 359 subjects (180 male and 179 female) aged from 5 days to 16 years and a mean age of 7 years. CFG-SegNet achieved an average segmentation accuracy of 0.681 dice similarity coefficient (DSC) on the prostate, 0.619 DSC on the uterus, 0.912 DSC on the liver, and 0.832 DSC on the heart with four-fold cross-validation. We compared the segmentation accuracy of our proposed method with previously published U-Net results, and our network improved the segmentation accuracy by 2.7%, 2.6%, 2.8%, and 3.4% for the prostate, uterus, liver, and heart, respectively. The results indicate that our high-performing segmentation framework can more precisely segment organs when limited training images are available.
