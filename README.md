# Numerical Analysis and Phase Portrait of the Simple Harmonic Oscillator

The simple harmonic oscillator is governed by the linear second-order differential equation $m\ddot{x} + kx = 0$, describing systems where a restoring force is proportional to displacement. Its solution exhibits sinusoidal motion with a natural frequency $\omega_0 = \sqrt{k/m}$. Numerical integration methods, such as `solve_ivp`, can be used to simulate the system’s dynamics over time. The resulting phase portrait reveals closed elliptical trajectories, indicating periodic motion and conservation of total mechanical energy in the absence of damping.

<a href="https://colab.research.google.com/github/dvoils/neural-network-experiments/blob/main/sho.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Oscillatory Systems: Linear to Nonlinear

Oscillators follow differential equations with periodic solutions. Linear systems like the simple pendulum ($\ddot{\theta} + \frac{g}{L} \theta = 0$) have constant frequency, while nonlinear versions ($\sin\theta$ or $x^3$ terms) show amplitude-dependent behavior. Systems like the Duffing oscillator require elliptic functions or simulation, revealing complex, real-world dynamics beyond simple harmonic motion.

<a href="https://colab.research.google.com/github/dvoils/neural-network-experiments/blob/main/osc_dyn.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


---

# Hodgkin–Huxley Dynamics: Phase Space and Firing Patterns
The Hodgkin–Huxley model describes how electrical signals are generated and propagated in neurons, using equations that capture the flow of ions through specialized channels in the cell membrane. This mathematical framework explains how neurons respond to external inputs, either remaining silent, firing once, or entering a rhythmic spiking pattern. By simulating these equations, it’s possible to visualize how voltage changes over time, how ion channel behavior shapes the neuron’s response, and how different levels of stimulation produce distinct electrical activity.

<a href="https://colab.research.google.com/github/dvoils/neural-network-experiments/blob/main/hodgkin_huxley.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

# Neuronal Ion Channel Dynamics

Neuronal firing patterns arise from the interplay of voltage- and calcium-dependent currents. Extensions of the Hodgkin-Huxley model include persistent sodium ($I_{\text{NaP}}$), A-type potassium ($I_A$), and calcium currents modeled by the GHK equation. These currents enable spike delay, postinhibitory rebound, and adaptation via calcium-activated potassium currents ($I_C$, $I_{\text{AHP}}$), shaping complex neural responses.

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

