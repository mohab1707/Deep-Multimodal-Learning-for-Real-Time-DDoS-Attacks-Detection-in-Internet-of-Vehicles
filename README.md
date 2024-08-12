# Deep-Multimodal-Learning-for-Real-Time-DDoS-Attacks-Detection-in-Internet-of-Vehicles
In this project, we introduce a novel Deep Learning Multimodal (DML) approach aimed at enhancing cybersecurity within Intelligent Vehicles (IoV) by effectively detecting Distributed Denial of Service (DDoS) attacks. Our approach utilizes advanced deep learning techniques to analyze and integrate multiple data modalities, offering a robust solution to a critical cybersecurity challenge in intelligent transportation systems. Additionally, our method addresses the limitations of existing benchmarks, particularly the VeReMi Extension dataset, by overcoming data-related issues and improving upon state-of-the-art methods.
## 1. Simulation Platform
To generate our custom training and validation datasets, we utilized the F2MD framework. For details on the modifications made to the architecture of this framework, please refer to [F2MD](./F2MD/).
## 2. Data Preprocessing
The Train and Validation Datasets are generated using the F2MD framework on the Real-time Simulation LuSTMini scenario with 80% attacker density to ensure a balanced dataset. These datasets contain the BSMs message content and the plausibility checks as extra features.
For an in-depth explanation of the preprocessing datasets, refer to the [Data Preprocessing notebook](./DataPreprocessing.ipynb).
## 3. Training/Validation Datasets
refer to [Training/Validation Datasets](https://mega.nz/folder/QfVxWaCK#cShZeamAUvdzMV2PoFmtnQ).
## 4. The Proposed DML Approach
For details on the implementation, refer to [Proposed DML Architecture](./ProposedDML.ipynb).

