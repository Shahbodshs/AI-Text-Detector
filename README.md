# AI-Text-Detector
## __ Explanations for the code: __ 
I first called several datasets that were created for such tasks(i will put the dataaset links below) ,then used Bert-cased version to fine tune the model and learn the sequences of words,
then detect whether the text is generated or written by humans. 
I wanted to use Longformer model or Bigbird for such task since they have much better capability for learning the long sequence datas, but since thoes moddel are very large
i couldnt work with thoes models with the knowledge i have.(But i will definitely try later on to do such task). 

## Datasets : 
1- [LLM - Detect AI Generated Text Dataset](https://www.kaggle.com/datasets/sunilthite/llm-detect-ai-generated-text-dataset) 
2- [DAIGT V2 Train Dataset](https://www.kaggle.com/datasets/thedrcat/daigt-v2-train-dataset)
3- [LLM Generated Essays for the Detect AI Comp!](https://www.kaggle.com/datasets/radek1/llm-generated-essays)

## Other ideas: 
My tought process at first was to use a hybrid method for generating such models, to caputre both simpple and complicated relation ships between words and either simple NN for final prediction
or use weighted average for the predictions or make the model learn to how to use the prediction in the best way 


## Model: 
as i said i have fine-tuned a BERT-cased version model. 
you can download the model from here: 
[Bert for detecting AI generated text](https://www.kaggle.com/models/shahbodsobhkhiz/ai-detector-shs)
## Updates:
Here i will talk about the further approaches and updates if any were made.  
