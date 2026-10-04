# Joel Alfaro Sanchez

Artificial Intelligence student at **Universitat Politècnica de Catalunya (UPC)**.

University team projects exploring how data, learning algorithms and knowledge models can support practical decisions. The repositories cover the path from data preparation and model evaluation to interactive applications, alongside robotics and control experiments.

## Featured projects

| Project | Problem and outcome | Technologies |
| --- | --- | --- |
| [SAMO — Agrovoltaic Decision Support](https://github.com/joelalfaroupc/PIA_lab) | Connects sensor models, interpretable rotation rules and a dashboard for crop/energy scenarios. An offline policy experiment increased the study's IEC metric from 0.258 to 0.320; this is a simulated estimate. | Python · Streamlit · scikit-learn · PyTorch |
| [Hotel Cancellation Decision Support](https://github.com/joelalfaroupc/hotel-cancellation-decision-support) | Turns cancellation predictions and six traveler profiles into expert recommendations in a booking dashboard. Archived XGBoost test F1: **0.7906**. | Python · XGBoost · scikit-learn · JavaScript |
| [Barcelona Tourism Data Pipeline](https://github.com/joelalfaroupc/BDA_DataPipeline) | Organizes nine urban datasets into five data zones with reusable analytical tables. Temporal calendar-availability prediction reached RMSE **0.0713**, versus **0.1159** for the baseline; availability is not confirmed bookings. | Python · PySpark · DuckDB |
| [Dental Implant Detection & Segmentation](https://github.com/joelalfaroupc/dental-implant-detection-segmentation) | Combines classical MATLAB image processing with YOLOv8 detection and ResNet18 U-Net segmentation. Archived detection mAP50: **0.995** on 35 validation images with pseudo-annotations; clinical generalization remains untested. | MATLAB · PyTorch · Ultralytics · OpenCV |
| [Catalan Semantic Similarity](https://github.com/joelalfaroupc/catalan-semantic-similarity) | Compares sentence representations across **33 archived configurations**, including shared-weight Siamese networks and custom attention pooling. Best archived validation Pearson correlation: **0.5044**. | Python · TensorFlow · fastText · spaCy |
| [Inverted Pendulum Control & Estimation](https://github.com/joelalfaroupc/inverted-pendulum-control) | Explores stabilization, reference tracking and state estimation through **seven simulation models** covering PID, LQR, Kalman filtering and LQG. Includes the technical report and independent linear-model checks. | MATLAB · Simulink · Control Theory |

## Explore by topic

**Deep learning and language**

- [Time-Budgeted Image Classification](https://github.com/joelalfaroupc/time-budgeted-image-classification) — compact 12-class CNN under a ten-minute CPU training budget, preserving the original checkpoint and **78.26% recorded validation accuracy**.
- [Neural Language Understanding](https://github.com/joelalfaroupc/neural-language-understanding) — intent classification and slot filling on ATIS, with archived academic experiments and a separately evaluated joint BiGRU baseline.

**Knowledge and decision-making**

- [Barcelona Tourism Knowledge Graph](https://github.com/joelalfaroupc/Semantic-Data-Management-for-AI) — RDF/RDFS, SPARQL and exploratory clustering of **73 neighborhoods**, extending the tourism pipeline with a semantic model.
- [Case-Based Menu Recommendation](https://github.com/joelalfaroupc/case-based-menu-recommender) — multilingual semantic retrieval, rule-based adaptation and feedback-driven retention across **102 stored cases**.
- [Azamon — Shipping Optimization](https://github.com/joelalfaroupc/azamon-shipping-optimization) — constrained parcel assignment through hill climbing and simulated annealing, with seeded cost/satisfaction experiments.
- [Redflix — Movie Planning](https://github.com/joelalfaroupc/redflix-movie-planning) — **five PDDL variants** for narrative dependencies, parallel viewing and daily time limits, with seeded problem generation and archived planner outputs.

**Robotics and reinforcement learning**

- [Event Guide Robot](https://github.com/joelalfaroupc/event-guide-robot) — semantic navigation and ArUco visual-search architecture for TurtleBot3. Navigation was tested on hardware; complete visual-search hardware validation is pending.
- **Lunar Landing — DDPG & TD3** — continuous-control agents in PyTorch with learning curves, archived evaluations, policy videos and tools for seeded experiments. Repository publication is pending.

## About the projects

Each README explains the problem, implementation, results, setup and limitations. Archived academic results are distinguished from later reproducibility checks; offline simulations and pseudo-label evaluations retain their evaluation context.

These are university team projects. Team credits and source references are preserved; forks retain their upstream history, while standalone editions document their source snapshots.
