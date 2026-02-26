# Pieter Barkema
## 👋 About Me

**Research Scientist on Human and Machine Perception, and Computational Learning - developer of PCNportal.**

---

## 🚀 Key Projects & Products

### [PCNportal](https://pcnportal.dccn.nl/) | Lead Software Engineer
**A scalable platform for Machine Learning & Transfer Learning for Brain-Mapping at large scale.**

* **The App** Architected the portal to act as a **collaborative model repository**, allowing researchers worldwide to host and share their own pre-trained models. This design enables global scalability and standardized model deployment.
* **Large-Scale Learning and Inference:** Engineered the backend to handle Bayesian models trained on **10,000+ brain scans** across heterogeneous data collection sites, and facilitate **Transfer Learning** on user data. 
* **Engineering:** Implemented a distributed backend using **Docker** and **Flask**, capable of handling parallelized computation jobs on remote servers.
* **Impact:** Published in [*Wellcome Open Research*](https://wellcomeopenresearch.org/articles/8-326).
* **Tech:** Python, Flask, Docker, Shell (HPC/Torque). **[Code here](https://github.com/predictive-clinical-neuroscience/PCNportal)** 

### [Visual Perception Lab: Postdiction](https://github.com/VisualPerceptionLab/Postdiction) | Lead Scientist
**Code for analysis of ultra-high resolution brain activity data used for Scientific Publishing.**
* As lead Scientist and creator of this lab-owned project, I created a codebase for collecting real-time brain data (7T fMRI / MEG) during an experiment that induces audiovisual illusions with millisecond precision in humans.
* I developed a pipeline to analyze this ultra high dimensional time series data and decode visual illusions from brain activity - resulting into a peer-reviewed publication (Barkema et al., 2025).
* **Impact:** [*Talk at top conference VSS*](https://www.youtube.com/watch?v=UetvGUnviXQ).
* **Tech:** MATLAB, Bash, PsychToolBox, SPM.

### [DeepCount-UQ](https://github.com/PBarkema/pCCN_Movement_Counter) | Developer & ML Engineer
**Uncertainty-Quantified action counting in unconstrained video using Deep Learning.**
* **Challenge:** Deep learning model for counting human movement and self-relection in "wild" videos (varying angles, lighting).
* **Innovation:** A probabilistic Convolutional Neural Network (CNN): the model does not learn a simple yes/no but a probability distribution. In noisy video, it says *"I am only x% certain that I counted n actions"*.
* **Math:** Built using **PyTorch**, with a **temporal convolutional backbone** to track motion cycles, and **channel attention** to deal with angles.
* **Impact:** A "bridge" project used to translate Uncertainty Theory into industry-standard **Uncertainty Quantification (UQ)** practices.
* **Tech:** PyTorch, TorchVision, NumPy, OpenCV, HuggingFace.

### [Neuro-UQ](https://github.com/PBarkema/Hippo-UQ) | Creator & Researcher (in progress)
**Biologically-inspired Bayesian model for Uncertainty Quantification and OOD Detection.**
* **The Concept:** Simulates how the human hippocampus tracks uncertainty and detects context switches, looking inside the "black box" of belief updating.
* **AI Alignment & Safety:** Motivated by challenges in safe decision-making, this project explores out-of-distribution (OOD) detection and mechanistic interpretability in the brain by separating irreducible environmental noise from model ignorance.
* **Innovation:** Demonstrates how high-precision priors cause a system to suppress unexpected sensory evidence; providing a biological analog to AI "hallucination" under overconfidence.
* **Tech:** Python, SciPy, NumPy, Matplotlib, Exact Bayesian Inference.

### [CCI Analysis Pipeline](https://github.com/PBarkema/Donders-IV-code-portfolio) | Inventor & Lead Dev
**Novel statistical framework for quantifying information from noisy brain responses.**
* **Innovation:** Invented the **Cross-Category Information (CCI)** metric to investigate "nuisance noise" in neural time series data (MEG).
* **Math:** Uses **Manifold Learning** and **Subspace Alignment** to prove that trial-by-trial neural variability is structured and functionally relevant to object recognition.
* **Scalability:** Optimized for High-Performance Computing (HPC) to process multi-terabyte datasets.
* **Tech:** Python (NumPy, SciPy), PCA, Bash.

---

## 💻 Technical Expertise
* **Languages:** Python (Primary), MATLAB, C#, Shell/Bash, SQL.
* **Research Stack:** PyTorch, TorchVision, HuggingFace, MNE-Python, Scikit-Learn, pymc3.
* **Infrastructure:** Docker, HPC (Slurm/Torque), Git/CI-CD, Flask, Jupyter.
* **Domains:** Machine Vision, Probabilistic Learning, Big Data Computing, Experiments.

---

## 📖 Publications & Resources
* **Paper:** [PCNportal: a web interface for facilitating normative modelling](https://wellcomeopenresearch.org/articles/8-326)
* **Paper:** [Early visual cortex encodes multisensory postdictive perception with retinotopic specificity: a layer-specific fMRI study](https://jov.arvojournals.org/article.aspx?articleid=2810028)
* **Paper:** [Evidence for embracing normative modeling](https://elifesciences.org/articles/85082)
* **Software:** [PCNportal GitHub Repository](https://github.com/predictive-clinical-neuroscience/PCNportal)
### 📬 Connect with Me
* **Focus:** Open to discussions on AI/ML Research roles, Research Engineering and Computational Neuroscience.
* **Location:** London, United Kingdom.
