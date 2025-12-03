---
layout: archive
title: "Research"

permalink: /research/
author_profile: true
---
## Working Papers

[”Decoding Digital Campaigning with Deep Learning: Evidence from India”]({{ site.baseurl }}/files/Das_JMP_Sep15.pdf)


**Summary:**  This paper examines the Bharatiya Janata Party's (BJP) digital advertising advantage on Facebook from 2020-2024, analyzing over 54,000 ads from India's six major parties. The analysis suggests BJP's digital advantage may stem from two mechanisms: (1) consistent use of visual motifs (saffron colors, lotus symbol, Modi's portrait, religious imagery) that create recognizable branding, and (2) intensive geographic microtargeting with content adapted to specific constituencies. Rural-targeted ads display greater visual uniformity compared to more diverse urban appeals. These patterns indicate that right-wing digital dominance may reflect strategic design choices that transform ideological symbols into scalable campaign tools.

**AI/Deep Learning Applications:** Convolutional neural networks to classify party affiliation from images (93.5% accuracy) and video frames (95% video-level accuracy); explainable AI (Integrated Gradients) to identify which visual elements drive predictions; CLIP vision-language model combined with Whisper speech recognition to analyze both visual and audio content from video ads; generative AI (Pixtral-12B multimodal model) to systematically code political messaging features across 15+ dimensions including religious symbolism, party symbols, and rural/urban settings; multimodal classification to predict whether ads target rural vs. urban audiences based on content alone (75% accuracy).

["Urbanization and the Rise of the Right in India"]({{ site.baseurl }}/files/urbanization_rise_of_the_right_India_v2.pdf) with Aditya Dasgupta

**Summary:** Constituencies experiencing urban expansion showed a large relative increase in the vote and seat share of the BJP between 1985-2019, with urbanization responsible for approximately 14.8 percentage points increase in BJP seat share. Using an urban expansion forecasting algorithm to isolate plausibly exogenous variation in the expansion of Indian cities, the study provides evidence that the relationship is plausibly causal. Polling station-level analysis in four states shows that comparing among proximate neighborhoods, the BJP systematically receives more support (approximately 1 to 6 percentage points higher) in polling stations in urban and peri-urban versus rural areas.

**AI/Deep Learning Applications:** Convolutional neural network trained on global patches of data to predict urban expansion based on topographical constraints of elevation and historical urban extent for plausibly exogenous variation in causal identification; and Amazon Textract API to extract electoral results from scanned Form 20 documents for polling station-level analysis.



["Are There Spillovers in the Representation of Excluded Groups?"]({{ site.baseurl }}/files/Spillovers_Das_Dasgupta.pdf) with Aditya Dasgupta

**Summary:** Electing women or Muslim MPs does not improve subsequent representation of these groups in nearby or lower-level elections. Using regression discontinuity analysis of close elections, the study finds largely null effects on candidate entry, vote share, and win probabilities for both vertical spillovers (to nested state constituencies) and horizontal spillovers (to nearby parliamentary constituencies), challenging theories about demonstration and exposure effects.

**AI/Deep Learning Applications:** Bidirectional LSTM trained on 1+ million labeled records to predict candidate religious identity from South Asian names with 99% accuracy, enabling automated classification across thousands of candidate names.

## Other Publications

["AI-Enabled Policy Project (AIPP) Convening: Bringing Together Technology and Policy Experts on Using AI to Improve Policymaking"](https://www.rand.org/pubs/conf_proceedings/CFA4214-1.html) with Emily Lathrop, Anton Shenk, Dulani Woods, Lauren Wagner, Galen Hines-Pierce, Jeff Alstott, Casey Dugan