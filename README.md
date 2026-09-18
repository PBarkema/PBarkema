# Pieter Barkema
## 👋 About Me

**Research Scientist linking Behaviour to Internal Representations in Humans and Machines**

---

## 🚀 Key Projects & Products

### [Visual Perception Lab: Postdiction](https://github.com/VisualPerceptionLab/Postdiction) | PhD Research - Lead Scientist
**Decoding human perception from ultra-high dimensional internal representations in brain data for Scientific Publishing.**

* **Experiment:** As lead Scientist and creator of this lab-owned project, I created a codebase for collecting real-time ultra precise brain data (7T fMRI / MEG) during an experiment that induces audiovisual illusions with millisecond precision in humans.
* **Biological white-box**: I developed a pipeline to analyze this ultra high dimensional time series data and decode human perception from brain activity using mechanistic interpretability methods - resulting into a peer-reviewed publication (Barkema et al., 2026).
* **Impact:** [*Talk at top conference VSS*](https://www.youtube.com/watch?v=UetvGUnviXQ).
* **Tech:** MATLAB, Bash, PsychToolBox, SPM.

### [PCNportal](https://pcnportal.dccn.nl/) | Lead Software Engineer
**A scalable platform for Machine Learning for linking Brain Data to mental health symptoms at large scale.**

* **App:** Built portal to be a **collaborative model repository**, allowing researchers worldwide to host and share their own pre-trained models. This design enables global scalability and standardized model deployment.
* **Large-Scale Learning and Inference:** Optimised backend to handle Bayesian models trained on **10,000+ brain scans** across heterogeneous data collection sites, and facilitate **Transfer Learning** on user data. 
* **Engineering:** Implemented a distributed backend using **Docker** and **Flask**, capable of handling parallelized computation jobs on remote servers.
* **Impact:** Published in [*Wellcome Open Research*](https://wellcomeopenresearch.org/articles/8-326) and [*eLIFE*](https://elifesciences.org/articles/85082), contributed to open-source toolkit [*PCNtookit*](https://github.com/predictive-clinical-neuroscience/PCNtoolkit).
* **Tech:** Python, Flask, Docker, Shell (HPC/Torque). **[Code here](https://github.com/predictive-clinical-neuroscience/PCNportal)** 

### [Neuro-UQ](https://github.com/PBarkema/Neuro-UQ) | PhD Research - Lead Scientist
**Linked Statistical Simulations of Uncertainty Quantification to internal neural activation vectors of Hippocampus.**
* **Biological white-box:** Statistical simulations of how the human hippocampus computes uncertainty and detects context switches, linking simulated parameters to internal representations in human brain data.
* **AI Alignment & Safety:** Motivated by challenges in safe decision-making, this project explores out-of-distribution (OOD) detection in the brain by separating irreducible environmental noise from model ignorance.
* **Innovation:** Demonstrates how high-precision priors cause a system to suppress unexpected sensory evidence - analogical to AI 'hallucination' due to overconfidence.
* **Tech:** Python, SciPy, NumPy, Matplotlib, Exact Bayesian Inference.

### [DeepCount-UQ](https://github.com/PBarkema/pCCN_Movement_Counter) | Two-month Independent Project
**Uncertainty-Quantified action counting in unconstrained video using Deep Learning.**
* **Challenge:** Deep learning model for counting human movement and self-relection in videos (varying angles, lighting).
* **Innovation:** A probabilistic Convolutional Neural Network (CNN): the model does not learn a simple yes/no but a probability distribution. In noisy video, it says *"I am only x% certain that I counted n actions"*.
* **Math:** Built using **PyTorch**, with **temporal convolutions** to track motion cycles, and **channel attention** to deal with angles.
* **Impact:** A "bridge" project used to translate Uncertainty Theory into industry-standard **Uncertainty Quantification (UQ)** practices.
* **Tech:** PyTorch, TorchVision, NumPy, OpenCV, HuggingFace.

### [Brain Internal State Dimensionality & Variability](https://github.com/PBarkema/Donders-IV-code-portfolio) | MSc Thesis
**Statistical framework for quantifying informative vectors from noisy brain responses.**
* **Methods Development** Invented the **Cross-Category Information (CCI)** metric to investigate 'nuisance noise' in neural time series data (MEG).
* **Math:** Used **Manifold Learning** and **Subspace Alignment** to prove that trial-by-trial variation in internal states are structured and functionally relevant to object recognition.
* **Scalability:** Optimized for High-Performance Computing (HPC) to process multi-terabyte datasets.
* **Tech:** Python (NumPy, SciPy), PCA, Bash.

---

## 💻 Technical Expertise
* **Languages:** Python (Primary), MATLAB, C#, Shell/Bash, SQL.
* **Research Stack:** Inspect, Codex, PyTorch, TorchVision, HuggingFace, MNE-Python, Scikit-Learn, pymc3.
* **Infrastructure:** Docker, HPC (Slurm/Torque), Git/CI-CD, Flask, Jupyter.
* **Domains:** AI Safety, Human Perception, Experiments, Probabilistic Learning, Big Data Computing.

---

## 📖 Publications & Resources
* **Paper:** [PCNportal: a web interface for facilitating normative modelling](https://wellcomeopenresearch.org/articles/8-326)
* **Paper:** [The post-hoc montage of perception: deep layers of primary visual cortex encode postdictive percepts](https://www.biorxiv.org/content/10.64898/2026.09.04.749457v1)
* **Paper:** [Evidence for embracing normative modeling](https://elifesciences.org/articles/85082)
* **Software:** [PCNportal GitHub Repository](https://github.com/predictive-clinical-neuroscience/PCNportal)
### 📬 Connect with Me
* **Focus:** Open to discussions on AI Safety/ML Research roles, Research Engineering and Computational Neuroscience.
* **Location:** London, United Kingdom.
