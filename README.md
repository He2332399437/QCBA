# QCBA
Motor Bearing Fault Diagnosis
This study proposes a multimodal fault identification framework that integrates the semantic modeling capabilities of LLMs with the physical modal feature representation. Specifically, the Qwen model is employed as the semantic branch to abstract underlying patterns within statistical features and extract high-dimensional semantic embeddings. Concurrently, the original time-domain, frequency-domain, and wavelet-domain information of vibration signals is preserved, with local physical features extracted using Convolutional Neural Networks (CNN), Bidirectional Gated Recurrent Units (BiGRU), and Attention mechanisms. Through a multimodal fusion strategy, semantic information and physical features are collaboratively modeled, enhancing the model's capability to identify complex coupled faults and generalize to unseen operating conditions. Experimental results demonstrate that the proposed method achieves a classification accuracy of 99.72% on the Case Western Reserve University (CWRU) dataset, marking a 4% improvement over the state-of-the-art FD-LLM framework utilizing the Qwen model. 

![1746520648305](https://github.com/user-attachments/assets/3d1bcdab-58c7-4969-8f5b-cc0523aad3a1)
This model contains three modules: The model mainly consists of three modules: the Qwen-based semantic modeling module, the physical modality feature extraction module, and the multimodal feature fusion and classification module.

1 dataset
Experimental validation is performed on the publicly available CWRU bearing fault dataset.You need to divide it into ten categories.

2 After the data is prepared, first train the Qwen_train model, and the obtained weights will be used for the subsequent model.

The subsequent content will be continuously improved.
