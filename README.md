# Context-Aware-Image-Search
This repository contains a context-aware image search system that combines image and text features for enhanced retrieval accuracy. Implemented using ResNet18 for image feature extraction, SpaCy for text feature extraction, and FAISS for efficient similarity searches.

Project Goals:
The primary aim of this project is to develop a context-aware image search system that enhances search accuracy by combining visual features extracted from images with semantic information from associated text descriptions. By integrating these two modalities, the system can provide more accurate and relevant search results, especially in cases where visual features alone might be insufficient to capture the full context of an image

Methodology:
The project utilizes a multi-step approach to achieve context-aware image search:

Image Feature Extraction:
Utilizes a pre-trained ResNet18 model to extract deep visual features from images. ResNet18, a convolutional neural network (CNN), is known for its effectiveness in capturing visual patterns.

Text Feature Extraction:
Implements SpaCy, a natural language processing (NLP) library, to extract semantic features from text descriptions associated with images. SpaCy helps in understanding the context and meaning of the text.

Feature Combination:
The extracted image and text features are concatenated into a single combined feature vector, which encapsulates both visual and semantic information.

FAISS Indexing:
The combined features are indexed using Facebook AI Similarity Search (FAISS) to enable efficient and accurate similarity-based search operations.

Search Functionality:
The system allows users to input an image or a text query, and retrieves the most similar images from the dataset based on the combined features.

Features:
Multi-modal Search: Combines image and text features to improve search relevance.
Efficient Indexing: Uses FAISS for fast and scalable similarity searches.
Modular Design: The code is organized into modular components, making it easy to extend or modify.
Pre-trained Models: Leverages pre-trained ResNet18 and SpaCy models for reliable feature extraction.

License:
This project is licensed under the MIT License - see the LICENSE file for details.
The MIT License is a permissive license that allows you to freely use, modify, and distribute the software, as long as the original author is credited.
