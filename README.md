# Hodgkin–Huxley Dynamics: Phase Space and Firing Patterns
The Hodgkin–Huxley model describes how electrical signals are generated and propagated in neurons, using equations that capture the flow of ions through specialized channels in the cell membrane. This mathematical framework explains how neurons respond to external inputs, either remaining silent, firing once, or entering a rhythmic spiking pattern. By simulating these equations, it’s possible to visualize how voltage changes over time, how ion channel behavior shapes the neuron’s response, and how different levels of stimulation produce distinct electrical activity.

<a href="https://colab.research.google.com/github/dvoils/neural-network-experiments/blob/main/hodgkin_huxley.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

# Neuronal Ion Channel Dynamics
Ion channel dynamics in neurons, as described by and extended beyond the Hodgkin-Huxley (HH) model, shape a wide range of spiking behaviors through the interplay of voltage-dependent sodium, potassium, and leak currents. Additional currents, like the persistent sodium current $I_{\text{NaP}}$) and A-type potassium current $I_A$, introduce phenomena such as sustained depolarization and spike delays by modulating excitability over time. Calcium currents, particularly those through low-threshold T-type channels, are better modeled using the Goldman-Hodgkin-Katz (GHK) equation due to the steep calcium gradient and their permeability-based behavior. These channels enable postinhibitory rebound—where hyperpolarization removes inactivation, allowing a rebound spike. High-threshold calcium channels (e.g., $I_L$ open during spikes and drive longer-term calcium entry, which in turn activates potassium currents like $I_C$ and the slower, voltage-independent $I_{\text{AHP}}$. These calcium-activated potassium currents provide spike repolarization and long-term adaptation, enabling neurons to adjust firing rates in response to sustained input.

<a href="https://colab.research.google.com/github/dvoils/neural-network-experiments/blob/main/ion_channels.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

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

