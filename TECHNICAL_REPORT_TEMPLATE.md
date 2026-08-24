# DS5201 Project 2 Technical Report

## 1. Introduction
- Problem context
- Why this image classification task matters
- Purpose of this project
- Three approaches compared

## 2. Dataset Description
- Dataset name/source
- Number of classes/images
- Images per class
- Image dimensions
- Class distribution
- Why dataset is suitable

## 3. Data Preprocessing and Augmentation
- Train/validation/test split
- Normalization and resizing
- Label encoding
- Class balance assessment
- Augmentation methods and rationale
- Augmented image examples

## 4. CNN Architecture from Scratch
- Architecture table (layer-by-layer)
- Total/trainable parameters
- Optimizer, learning rate, batch size, loss
- Regularization and Early Stopping setup
- Design decisions and justification

## 5. Transfer Learning Model
- Selected pretrained architecture and why
- Pretrained weights source
- Input preprocessing requirements
- Frozen layers and custom head design
- Total/trainable parameters

## 6. Fine-Tuning Strategy
- Layers unfrozen vs kept frozen
- Fine-tuning learning rate and optimizer
- Early Stopping configuration
- Rationale for strategy

## 7. Experimental Results
- Training/validation accuracy and loss curves
- Best validation accuracy
- Test accuracy/loss
- Precision, recall, F1-score
- Epochs completed and training time
- Consolidated comparison table

## 8. Comparative Analysis
- Explain differences in model behavior
- Analyze generalization and overfitting patterns
- Discuss complexity vs performance

## 9. Confusion Matrix and Classification Report
- Confusion matrix of best model
- Per-class precision/recall/F1
- Most confused class pairs and reasons

## 10. Misclassified Images
- At least 10 errors
- True label, predicted label, confidence
- Error pattern analysis

## 11. Critical Reflection (400–500 words)
Address all required prompts:
1. Why CNNs are suitable for image classification
2. Advantages of scratch CNN
3. Advantages of transfer learning
4. Why transfer learning helps small datasets
5. Whether fine-tuning improved performance
6. Effect of augmentation
7. Evidence of overfitting
8. Influence of model complexity
9. When to choose scratch CNN
10. What would change with more data/compute

## 12. Conclusion
- Summarize major findings
- Directly answer: scratch CNN vs transfer learning for this task

## 13. References
- Dataset
- Pretrained model documentation
- Relevant papers
- External libraries/tools
