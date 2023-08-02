# Noise-Aware-Weight-Perturb
Wait, what’d ya say? - Noise Aware DNN Training An Examination of Generalizability, Robustness, and Quantization

Current literature surrounding deep-neural-networks (DNNs) lacks exploration
into the effect that post-training, model-weight perturbation has on the
performance. We seek to analyze this effect by evaluating the impact that
weight-perturbation has on model generalizability and quantization.

We also seek to employ various preventative methods to attempt to mitigate
impact that weight-perturbation has on a model's performance. The
preventative methods are:
* Naive noise-aware training
* Sharpness-Aware Minimization (SAM)
* SAM with multi-step weight perturbation training

This project was completed for ECE 661 - Computer Engineering Machine Learning and Deep Neural Nets at Duke University (Fall 2022)
