# 2020-2021-research-with-Roest-Lab
Peak Detection On Data Independent Acquisition Mass Spectrometry Data With Semisupervised Convolutional Transformers

Liquid Chromatography coupled to Mass Spectrometry (LC-MS) based methods are commonly used for high-throughput, quantitative measurements of the proteome (i.e. the set of all proteins in a sample at a given time). Targeted LC-MS produces data in the form of a two-dimensional time series spectrum, with the mass to charge ratio of analytes (m/z) on one axis, and the retention time from the chromatography on the other. The elution of a peptide of interest produces highly specific patterns across multiple fragment ion traces (extracted ion chromatograms, or XICs). In this paper, we formulate this peak detection problem as a multivariate time series segmentation problem, and propose a novel approach based on the Transformer architecture. Here we augment Transformers, which are capable of capturing long distance dependencies with a global view, with Convolutional Neural Networks (CNNs), which can capture local context important to the task at hand, in the form of Transformers with Convolutional Self-Attention. We further train this model in a semisupervised manner by adapting state of the art semisupervised image classification techniques for multi-channel time series data. Experiments on a representative LC-MS dataset are benchmarked using manual annotations to showcase the encouraging performance of our method; it outperforms baseline neural network architectures and is competitive against the current state of the art in automated peak detection.
