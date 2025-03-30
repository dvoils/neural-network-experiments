# Anomaly Detection in Bitcoin Transaction Graphs Using Variational Graph Autoencoders

This project builds and trains a VGAE using the Elliptic Bitcoin dataset to detect anomalous transactions in a temporal financial graph. The system learns meaningful latent representations of transactions based on their features and connectivity by modeling the transaction network as a graph. A subgraph of early time steps is used for unsupervised training, after which test transactions are embedded and scored based on their distance from the centroid of known licit transactions in latent space. The model achieves strong performance on unseen future data, highlighting its potential for real-time fraud and anomaly detection in blockchain networks.

<a href="https://colab.research.google.com/github/dvoils/neural-network-experiments/blob/main/elliptic.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



---

# Convolutional Neural Networks for Autoencoders
This project demonstrate how to use a CNN autoencoder to denoise images. It trains a CNN to remove noise from MNIST handwritten digit images and demonstrates encoding, decoding, and minimizing the difference between the original and reconstructed images. The results are visualized by comparing original, noisy, and denoised images.

<a href="cnn-auto-encoder.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open Notebook"/>
</a>

---

# Arrival and Service Rates in Queues
Using the exponential distribution to model and simulate queueing systems. It explores arrival and service rates, their impact on stability, and the probability of waiting times. Python simulations and visualizations demonstrate queue behavior and the memoryless property of this distribution.


<a href="https://colab.research.google.com/gist/dvoils/79f70b73f2374d4d6c3abbe4169027d8/arrival-and-service.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

