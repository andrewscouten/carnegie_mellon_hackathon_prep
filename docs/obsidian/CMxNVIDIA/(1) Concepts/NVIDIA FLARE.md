# NVIDIA Federated Learning Application Runtime Environment (FLARE)

#Tool

An open-source software development kit (SDK) to make it easier for data scientists to use [[Federated Learning]] in their research and real- world applications

Though used heavily for federated deep learning, NVFlare is a generic approach for supporting collaborative computing across multiple clients

## Key Components 

NVFlare is built on a componentized architecture that allows FL workloads to move from research and simulation to real-world production deployment. Some of the key components of this SDK include:

- FL Simulator: for rapid development and prototyping.
- NVFlare Dashboard: for simplified project management, secure provisioning, and deployment, orchestration.
- Reference FL algorithms: (e.g., FedAvg, FedProx, SCAFFOLD) and workflows, like scatter and gather, cyclic, etc.
- Privacy preservation: with differential privacy, homomorphic encryption, and more.
- Specification-based API: for extensibility, allowing customization with plug-able components.
- Tight integration: with other learning frameworks like MONAI, XGBoost, and more.