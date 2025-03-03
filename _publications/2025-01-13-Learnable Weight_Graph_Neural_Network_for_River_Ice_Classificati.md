---
title: "Learnable Weight Graph Neural Network for River Ice Classification"
collection: Publication
category: conferences
permalink: /publication/2025-01-13-Learnable Weight_Graph_Neural_Network_for_River_Ice_Classificati
excerpt: 'This paper proposed a model incorporating a graph neural network (GNN) to distinguish between ice and water from SAR images on the winters of 2017–2021 with emphasis on the Beauharnois Canal and Lake St Lawrence regions of the Saint Lawrence River.'
date: 2025-01-13
venue: 'Journal 1'
paperurl: 'https://www.mdpi.com/2504-3900/110/1/30'
citation: 'Qu, Y.; Soleymani, A.; Sudom, D.; Scott, K.A. Learnable Weight Graph Neural Network for River Ice Classification. Proceedings 2024, 110, 30. https://doi.org/10.3390/proceedings2024110030'
---


Monitoring river ice is crucial for planning safe navigation routes, with ice–water classification being one of the most important tasks in ice mapping. While high-resolutions satellite imagery, such as synthetic aperture radar (SAR), is well-suited to this task, manual interpretation of these data is challenging due to the large data volume. Machine learning approaches are suitable methods to overcome this; however, training the models might not be time-effective when the desired result is a narrow structure, such as a river, within a large image. To address this issue, we proposed a model incorporating a graph neural network (GNN), called learnable weights graph convolution network (LWGCN). Focusing on the winters of 2017–2021 with emphasis on the Beauharnois Canal and Lake St Lawrence regions of the Saint Lawrence River. The model first converts the SAR image into graph-structured data using simple linear iterative clustering (SLIC) to segment the SAR image, then connecting the centers of each superpixel to form graph-structured data. For the training model, the LWGCN learns the weights on each edge to determine the relationship between ice and water. By using the graph-structured data as input, the proposed model training time is eight times faster, compared to a convolution neural network (CNN) model. Our findings also indicate that the LWGCN model can significantly enhance the accuracy of ice and water classification in SAR imagery.
