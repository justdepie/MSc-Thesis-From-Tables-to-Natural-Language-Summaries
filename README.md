Notebook Guide: \
-The Data Preparation notebook includes all the preprocessing and transformations made to convert the tables to text for the ToTTo dataset. \
-The Modeling Current Version notebook includes the modeling code for ToTTo. \
-The QTSumm All notebook includes everything I did for QTSUmm (preprocessing + modeling). 

Info:\
The goal is to provide table summaries that provide only the requested information.\
The evaluation metrics used are: METEOR, ROUGE and SacreBleu. \
Regarding ToTTo the models were evaluated on the whole test set as well as the top 5 most populated domains. \
This is a Capstone Project conducted in partnership with the company Incelligent IKE. \
For Llama2 7B chat there are no available results as the GPU RAM needs for inference exceed the available 40GB. 

For more information please check the Thesis Presentation file and the Thesis Report. 

Demo for ToTTo (T5-base generated summaries vs provided reference summaries): \
![image](https://github.com/justdepie/MSc-Thesis-From-Tables-to-Natural-Language-Summaries/assets/129097001/fc894dd8-bb8f-4c4e-8809-38aa5598566e)

To verify that the given information is valid, the corresponding Wikipedia Tables are provided:\
1st Table (Snippet):\
![image](https://github.com/justdepie/MSc-Thesis-From-Tables-to-Natural-Language-Summaries/assets/129097001/8e48f2b2-496f-4c33-9724-e13f042c9d77)

2nd Table: \
![image](https://github.com/justdepie/MSc-Thesis-From-Tables-to-Natural-Language-Summaries/assets/129097001/c9884945-a5aa-43d7-82f7-ee5c384c5fd0)

3rd Table: \
![image](https://github.com/justdepie/MSc-Thesis-From-Tables-to-Natural-Language-Summaries/assets/129097001/6e16abe0-bf2b-4fbe-9df1-a01c93bf62c5)



