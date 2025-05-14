# Emotion-PaperReview
**Main paper:** [Automatic facial expression recognition based on MobileNetV2 in Real-time](https://ieeexplore.ieee.org/abstract/document/4624313)

## Methodology of the Original Paper
The original paper proposes a facial expression recognition (FER) system using MobileNetV2\cite{origin}. Key techniques include:  

1. Face Extraction: The FaceBoxes algorithm is used to detect and crop faces, removing background noise.  
2. Two-Stage Fine-Tuning: MobileNetV2 is fine-tuned on FER datasets (FER2013, CK+, and JAFFE) to improve performance.  
3. Island Loss: A joint supervision method combining softmax and island loss enhances the model's ability to distinguish between emotions.

## Key Results of the Original Paper
The system achieves 97.98\% accuracy on FER2013, 91.44% on CK+, and 95.24% on JAFFE, outperforming several methods. Its real-time performance (3.87 ms/frame) makes it suitable for practical applications. Our project references this methodology for the facial module, while speech and fusion modules are developed independently.


