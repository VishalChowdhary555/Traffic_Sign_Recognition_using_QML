Traffic Sign Recognition Using Variational Quantum Circuits
Project Overview
This project focuses on building a Traffic Sign Recognition (TSR) system using Variational Quantum Circuits (VQCs) to explore the intersection of classical and quantum machine learning. The German Traffic Sign Recognition Benchmark (GTSRB) dataset serves as the primary dataset, and the hybrid quantum-classical approach is employed to classify traffic signs accurately.

The aim is to leverage quantum computing's potential to enhance feature extraction and decision-making in advanced driving assistance systems (ADAS).

Motivation
Traffic Sign Recognition is a critical component of Advanced Driving Assistance Systems (ADAS) and autonomous vehicles. While classical machine learning algorithms have made significant progress in this domain, quantum computing offers a promising new paradigm for solving complex problems. By integrating quantum machine learning techniques with classical neural networks, we can potentially enhance the efficiency and accuracy of TSR systems, paving the way for quantum-driven advancements in ADAS.

Methodology
Dataset:

GTSRB (German Traffic Sign Recognition Benchmark) dataset is used.
Preprocessed with data normalization and resizing to make it suitable for quantum computation.
Hybrid Model:

A classical Convolutional Neural Network (CNN) is combined with a Variational Quantum Circuit (VQC).
The CNN extracts spatial features from images.
The VQC processes these features using a parameterized quantum circuit, aiding in feature learning.
Quantum Circuit Design:

Quantum circuit consists of rotation and entanglement gates.
Trainable parameters of the circuit are optimized using gradient descent.
Training and Optimization:

The model is trained using PyTorch for classical layers and Pennylane for quantum layers.
Loss function: CrossEntropyLoss.
Optimizer: Adam with a learning rate of 0.001.
Evaluation:

The model is evaluated on the test set to determine accuracy and performance.
Iterative tuning is performed to improve accuracy.
Features
Quantum-Enhanced Learning: Demonstrates the potential of quantum computing in real-world applications.
Hybrid Architecture: Combines the strengths of classical and quantum systems.
Simulation-Ready: The project is simulation-based and does not require quantum hardware, making it accessible for experimentation.
Challenges
Achieving high accuracy on a complex dataset like GTSRB using a hybrid quantum-classical model.
Handling data encoding and compatibility between classical data structures and quantum circuits.
Balancing training complexity and model scalability in a hybrid setup.
Results
The initial model achieved a baseline accuracy of 59.6%. Through iterative improvements, the accuracy was further refined. The project demonstrates the feasibility of using Variational Quantum Circuits for traffic sign recognition and highlights areas for further optimization.

Future Scope
Extending the approach to other computer vision tasks.
Exploring different quantum encodings and circuit architectures for better performance.
Implementing the system on quantum hardware for real-world testing.
