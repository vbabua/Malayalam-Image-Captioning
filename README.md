# Malayalam-Image-Captioning

## Overview
Welcome to the Malayalam Image Captioning Project! This repository houses an innovative approach to generating captions in Malayalam for images, combining advanced techniques in natural language processing and computer vision. Our project leverages the power of neural networks, specifically the Vision Transformer (ViT) and models like BERT and GPT-2, to interpret images and generate relevant, context-aware captions in Malayalam.

## Project Highlights
- 🌟 **Innovative Integration**: Combines ViT with GPT-2 and BERT for effective image captioning in Malayalam.
- 📚 **Extensive Dataset**: Utilizes a translated version of the Flickr30k dataset, creating a unique Malayalam dataset for image captioning.
- 📈 **Advanced Evaluation**: Employs BLEU, METEOR, and Cosine Similarity metrics for comprehensive performance analysis.
- 🤖 **AI at the Forefront**: Sets a precedent for Malayalam language processing in AI, enhancing accessibility and inclusivity.

## Architecture

**ViT + GPT-2 Architecture**  
![ViT + GPT-2 Architecture](images/vit_gpt2.png)

**ViT + BERT Architecture**  
![ViT + BERT Architecture](images/vit_bert.png)

## Contents
- `Translation.ipynb`: A notebook that uses Google Cloud Translation API for translating English captions into Malayalam.
- `Data_Preparation.ipynb`: Essential scripts for preparing the dataset, including segregating images into train, validation, and test sets, and processing captions.
- `Fine_Tuning_ViT_+_BERT.ipynb`: Notebook showcasing the fine-tuning of a combined ViT and BERT architecture for Malayalam image captioning.
- `Fine_Tuning_ViT_+_GPT2.ipynb`: Demonstrates the fine-tuning process for a ViT and GPT-2 based model, tailored for the Malayalam language.
- `Evaluation.ipynb`: Evaluation scripts to assess the performance of the models using various metrics.

## Project Structure
```
/malayalam-image-captioning
│
├── notebooks/
│   ├── Translation.ipynb
│   ├── Data_Preparation.ipynb
│   ├── Fine_Tuning_ViT_+_BERT.ipynb
│   ├── Fine_Tuning_ViT_+_GPT2.ipynb
│   └── Evaluation.ipynb
│
└── README.md
```

## Getting Started
To get started with this project:
1. Clone this repository.
2. Ensure you have all the necessary dependencies installed. These include `transformers`, `datasets`, `torch`, `PIL`, and others as specified in the notebooks.
3. Follow the notebooks in order to understand the data preparation, model training, and evaluation steps.

## License
This project is open-sourced under the [MIT License](https://github.com/vbabua/Malayalam-Image-Captioning/blob/main/LICENSE).
