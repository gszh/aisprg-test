---
title: "When Fairness Meets Privacy: Exploring Privacy Threats in Fair Binary Classifiers via Membership Inference Attacks"
date: 2024-08-01
# Schedule page publish date (NOT publication's date).
publishDate: 2024-08-01
authors: ["Huan Tian", "Guangsheng Zhang", "Bo Liu", "Tianqing Zhu", "Ming Ding", "Wanlei Zhou"]

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract: "While in-processing fairness approaches show promise in mitigating bias predictions, their potential impact on privacy leakage remains under-explored. We aim to address this gap by assessing the privacy risks of fairness-enhanced binary classifiers with membership inference attacks (MIAs). Surprisingly, our results reveal that these fairness interventions exhibit increased resilience against existing attacks, indicating that enhancing fairness does not necessarily lead to privacy compromises. However, we find current attack methods are ineffective as they typically degrade into simple threshold models with limited attack effectiveness. Following this observation, we discover a novel threat dubbed Fairness Discrepancy Membership Inference Attacks (FD-MIA) that exploits prediction discrepancies between fair and biased models. This attack reveals more potent vulnerabilities and poses significant privacy risks to model privacy. Extensive experiments across multiple datasets, attack methods, and representative fairness approaches confirm our findings and demonstrate the efficacy of the proposed attack method. Our study exposes the overlooked privacy threats in fairness studies, advocating for thorough evaluations of potential security vulnerabilities before model deployments."
# Summary. An optional shortened abstract.
summary: ""

featured: true
publication: "*Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence, {IJCAI-24}*"
publication_short: "IJCAI"
tags: ["Fairness", "Privacy", "Membership Inference Attacks"]
doi: ""
url_pdf: https://www.ijcai.org/proceedings/2024/0057.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false
---