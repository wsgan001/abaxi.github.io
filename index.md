---
layout: default
title: Arjun Bakshi
---

I am a Ph.D. student at the [Department of Computer Science and Engineering, at The Ohio State University](https://cse.osu.edu/), working with [Professor Kannan Srinivasan](http://web.cse.ohio-state.edu/~athreya.14/) as a part of the [CoSyNe group](http://web.cse.ohio-state.edu/~athreya.14/cosyne/Publications.htm).

I'm interested in the application of machine learning to problems in wireless communication. I have also worked on problems in network/graph mining, and text mining. Before joining OSU, I received my MS in [Computer Science from the University Of Cincinnati](https://ceas.uc.edu/academics/departments/electrical-engineering-computer-science.html).


# Projects and publications
[Google scholar](https://scholar.google.com/citations?user=QFQtz74AAAAJ&hl=en&oi=ao)

## **Pattern Based Community Detection in Graph Datasets:**
The goal of this project is to add supervision to the process of community detection in large graphs. We extract telltale patterns from a small seed set of communities and use them to greatly improve the quality of detected communities.

### Abstract:
In recent years there have been a few semi-supervised community detection approaches that use community membership information, or node metadata to improve their performance. However, communities have always been thought of as clique-like structures, while the idea of finding and leveraging other patterns in communities is relatively unexplored. Online social networks provide a corpus of real communities in large graphs which can be used to understand dataset specific community patterns. In this paper, we design a way to represent communities concisely in an easy to compute feature space. We design an efficient community detection algorithm that uses size and structural information of communities from a training set to find communities in the rest of the graph. We show that our approach achieves 10% higher F1 scores on average compared to several other methods on large real-world graph datasets, even when the training set is small.


![](/assets/vs_rand.png)
*Unique patterns discovered by Bespoke*

+ **Arjun Bakshi**, Srinivasan Parthasarathy, Kannan Srinivasan, "Semi-Supervised Community Detection Using Structure and Size", IEEE International Conference on Data Mining, ICDM 2018. 
[paper](pdfs/bespoke_icdm18_paper.pdf)
[slides](https://docs.google.com/presentation/d/1_qJpRIZyGJ8cWcuHPOkQ0dsPef91KUn0abPSIrh_qcw/edit?usp=sharing)
[code](https://github.com/abaxi/bespoke-icdm18)



## **Full Duplex System for Vehicular Networks:**
Communication systems in vehicular networks face issues like dynamic environment, fast changing network size and membership, and high coordination costs. This project addresses those issues, and enables full-duplex communication between cars that is resilient to interference from other broadcast messages. The system is well suited for short road safety messages.

### Abstract:
Reliable and timely delivery of periodic V2V (vehicle-to-vehicle) broadcast messages is essential for realizing the benefits of connected vehicles. Existing MAC protocols for ad hoc networks fall short of meeting these requirements. In this paper, we present, CoReCast, the first collision embracing protocol for vehicular networks. CoReCast provides high reliability and low delay by leveraging two unique opportunities: no strict constraint on energy consumption, and availability of GPS clocks to achieve near-perfect time and frequency synchronization. Due to low coherence time, the channel changes rapidly in vehicular networks. CoReCast embraces packet collisions and takes advantage of the channel dynamics to decode collided packets. The design of CoReCast is based on a preamble detection scheme that estimates channels from multiple transmitters without any prior information about them. The proposed scheme reduces the space and time requirement exponentially than the existing schemes. 

![](/assets/corecast.png)
+ Tanmoy Das, Lu Chen, Rupam Kundu, **Arjun Bakshi**, Prasun Sinha, Kannan Srinivasan, Gaurav Bansal, and Takayuki Shimizu. "CoReCast: Collision Resilient Broadcasting in Vehicular Networks."  ACM International Conference on Mobile Systems, Applications, and Services, ACM MobiSys, 2018. 
[paper](pdfs/corecast_paper.pdf)
[video](https://youtu.be/mnB5LLZ65-0) [slides](https://docs.google.com/presentation/d/1_4JhVW_e0ZPUS_aX9biOc1z62ycGODTLeYhNrWhhrz0/edit?usp=sharing)

## **Low Latency MAC for IoT Devices:**
A MAC protocol designed specifically for IoT traffic in a dense IoT deployment. It eliminates the large channel access delay experienced by such devices by making interference power predictable across space and time, and adapting to an appropriate rate and modulation.

### Abstract

The future Internet of Things (IoT) networks are expected to be composed of a large population of low-cost devices communicating dynamically with access points or neighboring devices to communicate small bundles of delay-sensitive data. To support the high-intensity and short-lived demands of these emerging networks, we propose an Efficient MAC paradigm for IoT (EMIT). Our paradigm bypasses the high overhead and coordination costs of existing MAC solutions by employing an interference-averaging strategy that allow users to share their resources simultaneously. In contrast to the predominant interference-suppressing approaches, EMIT exploits the dense and dynamic nature of IoT networks to reduce the spatio-temporal variability of interference to achieve low-delay and high-reliability in service. This paper introduces foundational ideas of EMIT by characterizing the global interference statistics in terms of single-device operation and develops power-rate allocation strategies to guarantee low-delay high-reliability performance. 

![](/assets/emit.png)
*Compared to CSMA, the variation in interference across space and time is reduced under the proposed scheme (EMIT)*

+ **Arjun Bakshi**, Lu Chen, Kannan Srinivasan, C. Emre Koksal, and Atilla Eryilmaz. " EMIT: An efficient MAC paradigm for the Internet of Things." IEEE International Conference on Computer Communications, IEEE INFOCOM, 2016.
[paper](pdfs/emit_paper.pdf)



## **Quantitative Image Analysis of Brain Tumor Histopathology:**
High throughput medical imaging generates images that are good candidates for automated, data driven analysis. This project presents a pipeline for efficiently identifying patterns that can be used to detect gene expression
from H&E stained biopsy images. The pipeline first identifies and segments cells present in the images. It then extracts local and global feactures based on patterns in cell count, density and layout that can be used for correlation analysis with gene expression data.

![](/assets/GLBio.png)


## **BiClustering on ChIP-Seq Data**
### Abstract:
In this paper we present a novel framework capable of finding statistically significant biclusters on ENCODE ChIP sequencing datasets. Our goal is to discover low biclusters with low variance in terms of gene expression, which in theory shold point to coherent functional modules.

+ Chao Wu, **Arjun Bakshi**, Bruce Aronow, Anil Jegga, and Raj Bhatnagar. "A Biclustering Algorithm to Discover Functional Modules from ENCODE ChIP-Seq Data." IEEE International Conference on Data Mining Workshops, IEEE ICDM Workshops, 2013.
[paper](https://scholar.google.com/citations?user=QFQtz74AAAAJ&hl=en&oi=ao)

## **Learning Cost-Sensitive Rules for Classification Tasks**
### Abstract:
Building accurate classifiers is very desirable for many KDD processes. Rule-based classifiers are appealing because of their simplicity and their self-explanatory nature in describing reasons for their decisions. The objective of classifiers generally has been to maximize the accuracy of predictions. When data points of different classes have different misclassification costs it becomes desirable to minimize the expected cost of the classification decisions. In this paper we present an algorithm for inducing a rule based classifier that (i) shifts the class boundaries so as to minimize the cost of misclassifications and (ii) refuses to announce a class decision for those regions of the data space that are likely to contribute significantly to the expected cost of decisions. 

+ **Arjun Bakshi**, and Raj Bhatnagar. "Learning cost-sensitive rules for non-forced classification." IEEE International Conference on Data Mining Workshops, IEEE ICDM Workshops, 2012.
[paper](https://scholar.google.com/citations?user=QFQtz74AAAAJ&hl=en&oi=ao)



# Courses Taught

- CSE 1110 - Introduction to Computing Technology
  - Graduate Teaching Assistant

- CSE 5243 - Introduction to Data Mining
  - Graduate Teaching Assistant
  - Received Elenor Quinian Memorial Award for teaching

- CSE 5461 - Computer Networking and Internet Technologies

# Course Projects


+ Predicting the "helpfulness" of Amazon Reviews:
[slides](https://docs.google.com/presentation/d/1fxXWPxNNeV9c5zqxdEiUX27nIq6ALii8faHdaOBVy3k/edit?usp=sharing)
[report](pdfs/NLPreport.pdf)

+ Portuguese Dialect Detection:
[slides](https://docs.google.com/presentation/d/1JAzfN5wm6fkmCNdzuuPRly91Iyj5fIutCtfOqEabBz8/edit?usp=sharing)
[report](pdfs/ProtugueseReport.pdf)