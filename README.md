# Image-caption-generator
This repository contains a script for generating captions for images using the VisionEncoderDecoderModel from Hugging Face's Transformers library. It uses a pre-trained ViT-GPT2 model, which combines a Vision Transformer (ViT) for image feature extraction and GPT-2 for text generation. The script processes images using the ViTFeatureExtractor, converts them to RGB mode if necessary, and extracts pixel values for the model. Captions are generated using the model's generate method with beam search and are decoded into human-readable text using the tokenizer. The predict_step function takes a list of image paths, processes each image, generates captions, and returns them as a list of strings. Here's a simple usage example: predictions = predict_step(['sample2.jpg']); print(predictions).





