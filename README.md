Task 2: Language-Agnostic Emotion Classification from Speech Files

"For Task 2, I received .wav speech files from the SpeechX team. My objective was to perform language-agnostic emotion classification.

Since ML-related operations couldn't be performed in the BNP environment, I designed the entire approach and executed the model training and evaluation on my personal laptop. I shared the GitHub repository link with Barani for reference.


---

My Approach:

1. Model Used:

Pretrained Model: firdhokk/speech-emotion-recognition-with-openai-whisper-large-v3 (Hugging Face)

Datasets: RAVDESS, SAVEE, TESS, URDU

Emotion Labels: Angry, Disgust, Fearful, Happy, Neutral

Achieved Accuracy: 91.99%



2. I also experimented with 4 other pre-trained models to ensure robustness and comparative performance.




---

Workflow:

1. Data Preparation and Baseline Models

Preprocessed and labeled datasets

Evaluated multiple pre-trained models

Selected the best model based on accuracy and generalization



2. Fine-tuning Pre-trained Models

Fine-tuned the selected model with a smaller, curated dataset

Evaluated performance for signs of overfitting or improvement



3. Training a New Model

Configured a model to train from scratch

Required larger datasets and more tuning

Tested and validated results



4. Comparison and Final Decision

Compared metrics from all models and approaches

Finalized the best-performing method and documented it





---

Self-Initiated Learning: Music Classification Project

"In parallel, to strengthen my understanding of Hugging Face’s audio tools, I followed a music classification tutorial from the official Hugging Face Audio Course. I fine-tuned a lightweight encoder-only transformer model using a small dataset on Google Colab’s free T4 GPU.

This was a self-learning exercise to build confidence with Hugging Face workflows—such as dataset preprocessing, model fine-tuning, and evaluation—which helped me apply those learnings to my main emotion classification task."


---

Next Steps:

"I'm exploring how this emotion classification model can be integrated with BNP systems, subject to overcoming the current infrastructure constraints."
