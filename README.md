# Content Generator
Tools and Techniques: Python, Pytorch, Streamlit, GPT-2  

Description:  
To build a content generator to generate Ad slogans/tagline, Brand description and interesting Names for the business.   
A language model, GPT-2 is applied to generate the contents.   
The model will take the name and short description of the company and output contents such as a short description about the company and slogans based on the industry.
Data was collected from various websites, cleaned, and preprocessed.   
Fine-tuning of the GPT-2 model is performed with pytorch and transformers. Various versions of GPT-2 such as ‘tiny-gpt2’, ‘distilgpt2’, ‘gpt2-small’, ‘gpt2’ and ‘gpt2-medium’ were tried and finally ‘gpt2’ was used.  
The GPT-2 was slightly adjusted by introducing two special delimiter tokens to separate between company description and the creative content.  
The objective function is to minimize the cross-entropy, so the dataset is split into train and test validation set to ensure cross-entropy is decreasing for new data.  
Streamlit app framework was used to create the web app. 
![image](https://user-images.githubusercontent.com/16983515/119693692-00a12800-bdf9-11eb-9264-6a688c9ebdaa.png)
