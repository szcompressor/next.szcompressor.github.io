---
title: Lossy Compression for scientific data
date: 2019-12-31
description: >
    
---


Large-scale numerical simulations and experiments are generating very large datasets that are difficult to analyze, store and transfer. This problem will be exacerbated for future generations of systems. Data reduction becomes a necessity in order to reduce as much as possible the time lost in data transfer and storage. Lossless and lossy data compression are attractive and efficient techniques to significantly reduce data sets while being rather agnostic to the application. This tutorial will review the state of the art in lossless and lossy compression of scientific data sets, discuss in detail two lossy compressors (SZ and ZFP) and introduce compression error assessment metrics. The tutorial will also cover the characterization of data sets with respect to compression and introduce Z-checker, a tool to assess compression error.

More specifically the tutorial will introduce motivating examples as well as basic compression techniques, cover the role of Shannon Entropy, the different types of advanced data transformation, prediction and quantization techniques, as well as some of the more popular coding techniques. The tutorial will use examples of real world compressors (GZIP, JPEG, FPZIP, SZ, ZFP, etc.) and data sets coming from simulations and instruments to illustrate the different compression techniques and their performance. This 1/2 day tutorial is improved from the evaluations of the two highly attended and rated tutorials given on this topic at ISC17 and SC17.