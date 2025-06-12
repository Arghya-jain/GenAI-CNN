# Detect AI Generated Text using GenAI

## About
This project is part of the **Samsung PRISM** initiative and focuses on Detect AI Generated Text using GenAI. The models, **CNN,LSTM,BERT,Random Forest** , are fined tuned, trained and test on text classification dataset. This results in a more efficient models with reduced computational costs while maintaining high performance. CNN and LSTM has achieved **state-of-the-art results** around 90% accuracy in detecting both AI generated and Human written texts,while BERT and Random Forest models are performing Decent with accuracy around 60% to 70%

## Installation and Setup

### Prerequisites
To set up the project, follow these steps:

1. Clone the repository:
   ```sh
   git repo link https://github.ecodesamsung.com/SRIB-PRISM/CITB_24GAI08CITB_GenAI_Detect_AI_Generated_Text.git
   ```
2. From drive:
   - for the models that have been uploaded to drive.
   - this was done due to model size being more than 100mb.
   - which is not possible to push in the git.
   - Link for Random Forest
   ```sh
   https://drive.google.com/drive/folders/17Qn007sW1p5UeH5-u3lGPSN4D7wmppZo?usp=sharing
   ```
   - Link for BERT
   ```sh
   https://drive.google.com/drive/folders/1zidEsk3-10EpjcJCJ3XytztTr2A7Oc__?usp=sharing
   ```
3. Install the required dependencies from
   requirements.txt
   
## How to Start

1. **Open the downloaded folder with VS Code**

2. **Move to the Working Directory**

3. **Add the Trained Model**
   - comes with the fine tuned model file no need for training!

4. **Run the Application**
   ```sh
   python app.py
   ```
   - After execution, a local URL link will appear in the terminal.
   - Open the link in a browser to access the interface.
   - use chatgpt or similar AI tool to generate ai text, then copy paste in the text area.
   - use any kind of human written text, paste in text area.
   - The website will dispay the result with certain confidence score whether the provided text is HUMAN OR AI written

## Datasets
| Dataset | Download Link |(optional)
|---------|--------------|
| **kaggle** | [Download](https://www.kaggle.com/datasets/shanegerami/ai-vs-human-text/data)|

## Model Performance

| Model Name               | Dataset | Training acurracy | Detection accuracy |
|--------------------------|---------|-------------------|--------------------|
| CNN                      | kaggle  |       95%         |         90%        |
| LSTM                     | kaggle  |       92%         |         90%        |
| BERT                     | kaggle  |       78%         |       60%-75%      |
| Random Forest            | kaggle  |       85%         |       60%-70%      |  

---


