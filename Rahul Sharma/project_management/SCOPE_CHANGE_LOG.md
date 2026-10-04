# Scope Change Log

| Change | Reason / evidence | Impact |
|---|---|---|
| Added traditional Logistic Regression baseline | Feedback required a non-deep-learning comparator | Improved interpretability and baseline context. |
| Expanded from primary CNN to Custom CNN + ResNet18 + EfficientNet-B0 | Stronger comparative evidence and transfer-learning benchmark | Added training, efficiency and paired-comparison evidence. |
| Added validation-only threshold locking | Prevent test-set tuning | Strengthened evaluation integrity. |
| Added duplicate / near-duplicate similarity audit | Leakage/similarity concern | Added strict sensitivity analysis and affected-image evidence. |
| Added bootstrap CIs and paired McNemar tests | Statistical uncertainty/comparison feedback | Added inferential evidence. |
| Added calibration, robustness, mono/poly subgroup and Grad-CAM analyses | Reliability/explainability feedback | Expanded diagnostics and responsible-use discussion. |
| Added safeguarded research interface | Demonstrate end-to-end proof of concept | Explicitly remains non-production. |
