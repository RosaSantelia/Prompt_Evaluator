🚀 Prompt Evaluation Tool


This Python script evaluates the quality of generated text by comparing it with reference text using three key metrics:

✅ BLEU: Measures lexical similarity (word overlap)

⚠️ Toxicity: Estimates the probability that the generated text is offensive (using Detoxify)

🧠 Semantic Similarity: Measures how close in meaning two texts are (using Sentence Transformers)


🛠️ Usage

- Install dependencies and all required libraries

- Configure input CSV path

- Set the csv_path variable in the script to point to your CSV file

- The CSV must contain two columns: reference and generated

- Execute the script to compute the evaluation metrics


📊 Outputs:

🎨 Color-coded table displaying BLEU, Toxicity, and Semantic Similarity scores for each prompt.

💾 CSV file named prompt_evaluation_results.csv containing all computed scores.

📈 Bar chart visualizing the scores across prompts.

![image](https://github.com/user-attachments/assets/ea84ba3f-4edd-4f6d-a316-7a87f80cd5b1)

⚙️ Customization:

✂️ Modify tokenization or smoothing methods for BLEU calculation as needed.

🔄 Swap toxicity or embedding models for different evaluation needs.

📊 Enhance visualizations with additional charts or interactive features.

