# Thesis_Abbreviation_Disambiguation
Effects of Abbreviation Disambiguation on the Classification of CCR/EHR

We summarize the key findings and insights derived from our research endeavors, offering a co-
herent and concise representation of our contributions to the broader academic and professional
community within the field.

Prior to presenting a synopsis of the work undertaken, it is essential to reiterate the initial
research inquiry, which is as follows: 
How does the utilization of disambiguation techniques in other words disambiguating abbrevia- tions influence the accuracy and interpretability of
classifying unstructured clinical case records in medical domain?

In conclusion, our research into the ”Effects of Abbreviation Disambiguation on Unstructured Clinical Case Reports” has revealed a subtle yet promising impact of abbreviation disambigua-tion on clinical case report classification models.
The results obtained from the various models and techniques employed in this study have shed light on the critical role of abbreviation disambiguation in the context of classification tasks,
particularly in the domain of biomedical data analysis. These findings underscore the significant positive impact that abbreviation disambiguation has on enhancing the accuracy and reliability
of predictive models, as observed across multiple scenarios

Dataset used is MACROBATT which is available in the Annotate_fuzzy_severity_outcome_check folder. 200 pdf case reports along with 200 already annotated .ann files are also available there.  

For Classification we have use three diferrent types with 5 different models  
Zero-shot classification - facebook/bart-large-mnli and cross-encoder/nli-roberta-base  
SVM (Support Vector Machines)  
Fine-tuning BERT models - bert-base-uncased and emilyalsentzer/Bio-ClinicalBERT  
For Disambiguation we used ACROBERT  

Once after checking the performance of models with raw data we check the perfoemace of the models with disambiguated data. We then compare the results and evaluate.

The Datasets as well as the code files are placed in the respective folders.
