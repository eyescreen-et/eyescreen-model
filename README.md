# EyeScreen ET: Model

Training, evaluation and mobile conversion of AI models that grade diabetic retinopathy from retinal images, for the EyeScreen ET screening system.

**Status:** in development

## Plan
- **Mobile model:** MobileNetV3 fine-tuned on APTOS 2019, converted to TensorFlow Lite for offline use in the Android app
- **Server models:** ResNet-50, EfficientNet and RETFound fine-tuned and compared on APTOS, EyePACS and mBRSET
- **Evaluation:** quadratic weighted kappa (5 grades), and sensitivity and specificity for referable diabetic retinopathy (moderate or worse)

## Datasets
Datasets are not included in this repository. Download them from their original sources and follow each dataset's terms:
- [APTOS 2019 Blindness Detection](https://www.kaggle.com/competitions/aptos2019-blindness-detection)
- [EyePACS (Kaggle Diabetic Retinopathy Detection)](https://www.kaggle.com/c/diabetic-retinopathy-detection)
- [mBRSET (PhysioNet, credentialed access)](https://doi.org/10.13026/qxpd-1y65)

## Tech
Python, PyTorch, TensorFlow Lite, Kaggle notebooks

*Research prototype. Not a medical device.*
