# AWS AI Foundational

![1766814521091](https://github.com/user-attachments/assets/b87d90f4-0085-4fe8-83aa-b29508c4a5f0)

---

## 1. Learning Techniques

- **Self-Supervised Learning**  
  Learns patterns from *unlabelled data* without explicit labels.

- **Transfer Learning**  
  Uses knowledge from a pre-trained model to improve a related task.

- **Incremental Learning**  
  Updates a model with new data without retraining from scratch.

- **Reinforcement Learning (RL)**  
  An agent learns through **trial and error** by maximizing rewards.

---

## 2. Data Types

- **Labeled Data**  
  Data with correct answers or tags.

- **Unlabeled Data**  
  Raw data without labels.

- **Semi-Supervised Data**  
  Combination of some labeled data and lots of unlabeled data.

---

## 3. Model Training & Evaluation

- **Training**  
  Model learns by adjusting weights using techniques like gradient descent.

- **Validation**  
  Used during training to tune hyperparameters and avoid overfitting.

- **Inference**  
  Using a trained model to make predictions on new data.

- **Overfitting**  
  Performs well on training data but poorly on new data.

- **Underfitting**  
  Performs poorly on both training and new data.

---

## 4. Performance Metrics

- **Confusion Matrix**  
  Shows true positives, true negatives, false positives, and false negatives.

- **Precision**  
  Accuracy of positive predictions.

- **Recall (Sensitivity)**  
  Ability to find all positive cases.

- **F1 Score**  
  Balance between Precision and Recall.

- **RMSE (Root Mean Squared Error)**  
  Measures average prediction error magnitude.

- **MAE (Mean Absolute Error)**  
  Average absolute difference between predictions and actual values.

- **BLEU Score**  
  Measures quality of machine translation (0–1 scale).

---

## 5. Core ML Concepts

- **Artificial Intelligence (AI)**  
  Machines performing tasks that need human intelligence.

- **Machine Learning (ML)**  
  Algorithms that learn from data.

- **Deep Learning (DL)**  
  ML using deep neural networks.

- **Generative AI (GenAI)**  
  Models that generate new content (text, images, audio).

---

## 6. Model Types

- **Neural Networks**  
  Multi-layer models that learn complex patterns.

- **Convolutional Neural Networks (CNNs)**  
  Best for images and visual data.

- **Recurrent Neural Networks (RNNs)**  
  Best for sequential data like text and time series.

- **Generative Adversarial Networks (GANs)**  
  One model generates data, another tries to detect fake data.

- **Diffusion Models**  
  Generate data by removing noise step-by-step.

- **BERT**  
  Understands word context using bidirectional transformers.

- **Large Language Models (LLMs)**  
  Non-deterministic models that generate varied responses.

---

## 7. Classification Types

- **Binary Classification**  
  Yes / No prediction.

- **Multi-Class Classification**  
  One label from many classes.

- **Multi-Label Classification**  
  Multiple labels for a single instance.

---

## 8. Clustering & Dimensionality Reduction

- **Clustering**  
  Groups similar data points (unsupervised learning).

- **K-Means**  
  Unsupervised clustering algorithm.

- **K-Nearest Neighbors (KNN)**  
  Supervised algorithm based on nearest neighbors.

- **Dimensionality Reduction**  
  Reduces number of features to simplify models.

---

## 9. Prompting Techniques

- **Zero-Shot Prompting**  
  No examples provided.

- **Few-Shot Prompting**  
  A few examples provided.

- **Negative Prompting**  
  Tells the model what to avoid.

- **Chain-of-Thought Prompting**  
  Breaks problems into logical steps.

- **Prompt Engineering**  
  Designing prompts to improve model output.

---

## 10. Bias Types

- **Sampling Bias**  
  Data does not represent real-world diversity.

- **Measurement Bias**  
  Data collection process is flawed.

- **Exclusion Bias**  
  Important data is missing.

- **Confirmation Bias**  
  Only data supporting beliefs is considered.

- **Labeling Bias**  
  Human errors in labeling data.

---

## 11. AWS AI & ML Services

- **Amazon Bedrock**  
  Foundation model access with on-demand or batch inference.

- **Amazon Bedrock Guardrails**  
  Detects sensitive content (PII) using rules and regex.

- **Amazon SageMaker**  
  End-to-end ML platform.

- **SageMaker JumpStart**  
  Pre-trained models and ML solutions.

- **SageMaker Clarify**  
  Detects bias in datasets and models.

- **SageMaker Ground Truth**  
  Human-in-the-loop data labeling.

- **Ground Truth Plus**  
  Fully managed, high-quality labeling service.

- **SageMaker Model Monitor**  
  Tracks model performance in production.

- **SageMaker Model Dashboard**  
  Central view of all models and endpoints.

- **SageMaker Feature Store**  
  Central repository for ML features.

- **SageMaker Canvas**  
  No-code ML model building.

---

## 12. Amazon Q

- **Amazon Q Developer**  
  Helps with coding, debugging, and optimization.

- **Amazon Q Business**  
  Enterprise AI assistant using company data.

- **Amazon Q in QuickSight**  
  Natural language BI dashboard creation.

- **Amazon Q Apps**  
  Build internal GenAI apps using natural language.

---

## 13. Computer Vision & NLP

- **Amazon Rekognition**  
  Image and video analysis.

- **Amazon Textract**  
  Extracts structured data from scanned documents.

- **Amazon Comprehend**  
  NLP service for sentiment, entities, and classification.

---

## 14. Speech & Audio

- **Amazon Polly**  
  Text-to-speech service.

- **WaveNet**  
  Deep learning model for audio generation.

---

## 15. Hardware Accelerators

- **AWS Trainium**  
  Optimized for model training.

- **AWS Inferentia**  
  Optimized for inference.

---

## 16. Key Comparisons & Notes

- **Trainium → Training**  
- **Inferentia → Inference**  
- **Reinforcement Learning → Trial and Error**  
- **Real-Time Inference** → Low latency, interactive  
- **Batch Inference** → Large data, no immediate response needed  
- **LLMs are Non-Deterministic** → Same prompt, different outputs

---
