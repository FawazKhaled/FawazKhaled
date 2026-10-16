# Fawaz Alharbi

**Aspiring ML engineer · Software Engineering student at KFUPM · Co-founder of [Fernas](https://fernasteam.com)**

I build machine learning systems that are fast and small enough to use in real products. My focus is efficient AI: making models cheaper in memory and compute without losing accuracy.

[LinkedIn](https://www.linkedin.com/in/fawaz-khaled-alharbi/) · [Email](mailto:fawaz1harbi@gmail.com) · [Fernas](https://fernasteam.com)

---

## Research

**Token Salience-Driven Pruning for Efficient Long-Context Processing in Large Language Models** *(manuscript)*

I worked as an AI researcher with a professor from the University of California, Berkeley, on making attention in large language models more efficient. The work reduces attention computation and GPU memory use and speeds up inference on long inputs.

## Featured project

### [Face search with ArcFace and binary hashing](https://github.com/FawazKhaled/Facial-Feature-Extraction)

This project turns each face into a 256-bit code, **64× smaller** than its 512-number ArcFace embedding. Faces can then be compared by counting how many bits differ. I compare three ways of making the codes (random projection, ITQ, and a hashing model I trained) on the same held-out test set. The project also includes a live webcam Face ID app built on top of the codes.

| Method (256-bit codes) | precision@10 | Average precision |
|---|---|---|
| Random projection | 0.9316 | 0.8712 |
| ITQ | 0.9517 | 0.9399 |
| Learned model (512 epochs) | 0.9472 | 0.9454 |
| Float embeddings (no hashing) | 0.9540 | 0.9440 |

**Python · PyTorch · InsightFace · ONNX Runtime · SQLite**

## Building at Fernas

I co-founded [Fernas](https://fernasteam.com), a student-founded venture studio in Dhahran that turns students' ideas into real products. Our projects:

- **Scalendars:** a shared calendar for coordinating schedules and deadlines
- **LinkU:** an internship matching platform
- **KFUPM Masar:** campus routing for KFUPM
- **MenaBonka:** a platform that connects japanese companies to saudi talent

I also built the [Fernas website](https://github.com/FawazKhaled/Fernas-Website).

## Learning in public

- **[KAUSTxAI-Training](https://github.com/FawazKhaled/KAUSTxAI-Training):** a step-by-step ladder of projects, from a tested Python records manager to exploratory data analysis with pandas, on the way to machine learning and neural networks.
- **[Best Country Prediction](https://github.com/FawazKhaled/Best-Country-prediction):** a random forest model that suggests a country for a student based on their educational and personal data.
- **[Magic Square Game](https://github.com/FawazKhaled/Magic-Square-Game):** a Tkinter desktop app for building and checking magic squares of any size.

## Tools

**ML and data:** PyTorch · TensorFlow · scikit-learn · NumPy · pandas · ONNX Runtime · InsightFace
**Languages:** Python · Java · C# · C++

## Interests

Efficient AI · attention mechanisms · model compression · retrieval and embeddings · healthcare technology
