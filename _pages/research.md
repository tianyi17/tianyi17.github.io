---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-3E74C49H73"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-3E74C49H73');
</script>
<!-- Currently under construction-->


## Vision
In this rapidly evolving technological age, my passion lies in enhancing the safety and sustainability of Transportation Cyber-Physical Systems (T-CPS). Companies at the forefront of transportation are now technologically driven. I envision a harmonious blend where research interlinks transportation with computation, deploying computer science techniques to navigate challenges indigenous to traditional transportation engineering. My past and future research interests in T-CPS are summarized in the figure below.

![Research Overview](https://github.com/tianyi17/tianyi17.github.io/blob/master/files/research_chart_618.png)
*Figure: Overview of my Ph.D. research (red) and prospective directions (gold) for a smarter and more sustainable T-CPS. The central column represents core disciplines and technologies. The left and right columns depict the micro and macro perspectives, respectively. Key research issues anchor the bottom, while overarching applications crown the top.*


### 1. Modeling and Learning Driving Behavior
My research focuses on understanding microscopic driving behaviors, using deep learning to classify drivers and ACC vehicles based on car-following behaviors. This work forms the foundation for understanding the intricacies of transportation systems and predicting their dynamics.

I have developed new methods for classifying ACC vehicles and AVs, enhancing traffic dynamics analysis. One strategy involves model-based calibration for vehicle trajectory analysis, and the other uses deep learning classifiers for quick vehicle type identification from short trajectory sequences. [Li et al. 2021](https://ieeexplore.ieee.org/abstract/document/9564462), [Li et al. 2023](https://dl.acm.org/doi/abs/10.1145/3603369), [Stern et al. 2017](https://arxiv.org/abs/2312.07003). I have also created RACER, a deep learning car-following model that integrates Rational Driving Constraints (RDC) to ensure physical feasibility and realistic driving behavior predictions. RACER distinguishes itself by adhering strictly to these constraints, demonstrating its utility in producing more accurate and realistic models. [Li et al. 2023](https://arxiv.org/abs/2312.07003).

### 2. Cybersecurity in Intelligent Transportation Systems
The emergence of AVs introduces cybersecurity risks to vehicle safety and system integrity.

My work includes analyzing the impact of cyberattacks on ACC vehicles, particularly their effects on traffic dynamics and fuel consumption, using car-following model simulations. I've developed a detection technique using Generative Adversarial Networks (GANs) to distinguish between normal and abnormal traffic patterns, identifying potential cyber intrusions. My research also involves simulating targeted cyberattacks using Reinforcement Learning (RL), focusing on their diverse impacts and informing strategies to counter such threats. [Li et al. 2023](https://arxiv.org/abs/2310.17091).

### 3. Data-Driven Approaches in Modern Transportation Analysis
My work extends beyond microscopic studies into data analytics, addressing broader traffic challenges. Emphasizing the importance of data collection and mining for efficient transportation systems.

I have undertaken a significant data collection effort at 18 intersections in Minnesota, creating the United States' most extensive dataset on pedestrian-driver-yielding behavior. The results highlight critical factors influencing these interactions, informing intersection design decisions aligned with Vision Zero's safety objectives. [Li et al. 2021](https://dl.acm.org/doi/abs/10.1145/3459609.3460524), [Li et al. 2023](https://arxiv.org/abs/2312.15113). In light of the challenges faced by traditional taxi services due to the rise of Transportation Network Companies (TNCs) and the COVID-19 pandemic, I have focused on optimizing taxi utilization in Chicago. My research develops strategies for predicting short-term demand and reducing unnecessary travel (deadhead miles), thus supporting more efficient and sustainable urban transportation, particularly under disruptive conditions like the pandemic. [Li et al. 2022](https://journals.sagepub.com/doi/full/10.1177/03611981211059769), [Li et al. 2023](https://dl.acm.org/doi/abs/10.1145/3576914.3587708), [Li et al. 2020](https://ascelibrary.org/doi/abs/10.1061/9780784483169.024).

## Future Research Directions
My future research will build upon the themes previously discussed, focusing on integrating machine learning with transportation priors and conducting comprehensive field experiments with automated vehicles.

### Harnessing Machine Learning with Transportation Priors in T-CPS
Addressing the complexities of urban traffic management, I plan to develop machine learning models that incorporate transportation priors, going beyond traditional and current car-following models.

### Sustainable & Equitable T-CPS
My focus will also include strengthening systems against cyber threats in advanced vehicular systems, building attack-resistant frameworks, and identifying network vulnerabilities.

### Empirical Insights: Large-Scale Data Collection and Field Experiments with AVs
My research will delve into the interaction between physical infrastructure, digital systems, and human elements in urban cyber-physical systems. This involves conducting experiments with automated vehicles to understand the effects of various automation levels on transportation ecosystems, focusing on aspects like cooperative traffic control, infrastructure-enabled sensing, and concerns related to traffic equity and privacy.




## References
[^1]: [Li, T., & Stern, R. (2021). Classification of adaptive cruise control vehicle type based on car following trajectories. In 2021 IEEE International Intelligent Transportation Systems Conference (ITSC), pp. 1547-1552, IEEE.](https://ieeexplore.ieee.org/abstract/document/9564462)
[^2]: [Li, T., & Stern, R. (2023). Car-following-response based vehicle classification via deep learning. ACM Journal on Autonomous Transportation Systems.](https://dl.acm.org/doi/abs/10.1145/3603369)
[^3]: [Stern, R. et al. (2017). Dissipation of stop-and-go waves via control of autonomous vehicles: Field experiments. Transportation Research Part C: Emerging Technologies.](https://arxiv.org/abs/2312.07003)
[^4]: [Li, T., & Stern, R. (2023). RACER: Rational Artificial Intelligence Car-following-model Enhanced by Reality. Presented at NeurIPS 2023 workshop on Machine Learning and the Physical Sciences.](https://arxiv.org/abs/2312.07003)
[^5]: [Li, T., & Stern, R. (2021). Leveraging video data to better understand driver-pedestrian interactions in a smart city environment. In Proceedings of the Workshop on Data-Driven and Intelligent Cyber-Physical Systems, pp. 6-11, ACM.](https://dl.acm.org/doi/abs/10.1145/3459609.3460524)
[^6]: [Li, T., & Stern, R. (2023). Understanding driver-pedestrian interactions to predict driver yielding: Field experiments in Minnesota. Dataset available at ResearchGate.](https://arxiv.org/abs/2312.15113)
[^7]: [Li, T., & Stern, R. (2022). Taxi Utilization Rate Maximization by Dynamic Demand Prediction: A Case Study in the City of Chicago. Transportation Research Record: Journal of the Transportation Research Board.](https://journals.sagepub.com/doi/full/10.1177/03611981211059769)
[^8]: [Li, T., & Stern, R. (2023). Assessing the Impact of Disruptive Events on Urban Mobility: A Case Study of Chicago Taxis during COVID-19. In Proceedings of Cyber-Physical Systems and Internet of Things Week 2023, pp. 141-145, ACM.](https://dl.acm.org/doi/abs/10.1145/3576914.3587708)
[^9]: [Li, T., & Stern, R. (2020). "Centralized” Taxi Services in Big Metropolitan Areas: Evidenced by Chicago Data. In International Conference on Transportation and Development 2020, pp. 287-299, ASCE.](https://ascelibrary.org/doi/abs/10.1061/9780784483169.024)


<br/>
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=mOLq8ml6_8GeJFfRaOGlKt1qOHfyBzpQU0YGiQEZeOA'></script>


