---
layout: default
title: Week 4
parent: Updates
---

## Week 4

The data was successfully cleaned up, and arranged into the format shown in the following image. The labels on the left hand side represent the individual genes, and each column is labeled with a cellid. The 1's in the matrix represent instances of individuals containing a positive diagnosis of Alzheimer's that also represent the given gene being expressed. While the image is currently only showing a small subset of the total dataset, this information was obtained for each individual entry in the diagnosis column.

<img width="765" alt="Image3" src="https://user-images.githubusercontent.com/113469617/226229332-17b48a72-5e67-486e-9154-22d1ca7d249a.png">

Separate matrices were saved for each of the variables of interest present in the original count matrix, such as broadcelltype and subcluster. The initial neural net will just be run on the diagnosis column, but I ran into some issues today with using keras. I did some research and found that there are many packages available within R for making neural net models, but if needed I will look into alternative methods or request for pre-labeled data from the lab if need be. 
