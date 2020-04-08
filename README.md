# moral-salience-modelling
This project aims to develop a model that can simulate an individual's moral salience system. 

keywords: moral foundations theory/hierachical attention networks/bert

Authors: Chiao Sun & Zixin Huang

## Data
- Since tweet raw data is confidential, we cannot add them to this repo. However, you can acquire raw data by filling in customer/access tokens/secrets in ./dataset/text_script.py then run 
```
python text_script.py MFTC_V4.json <desired_output_file_name>
```
You can acquire customer/access tokens/secrets from [here](https://themepacific.com/how-to-generate-api-key-consumer-token-access-key-for-twitter-oauth/994/)

You can acquire iaic, maic, iamc, mamc datasets from Data_Preprocessing.ipynb, following blocks started with comments '#DATASET1,2,3,4'.

# Model
We implemented BERT model to test our hypothesis and models are available in ./models.

## Resources
[Project Proposal](https://docs.google.com/document/d/1G7pX1SYg19CnPkZnnwmk7rifFMNQFOm2QAX-anWPCCg/edit?usp=sharing)

[Architecture Overview](https://docs.google.com/presentation/d/1T557RehWmBy0FW8tDNqsunebp2qDVpwO-tPkMTUTT3Q/edit?usp=sharing)

[Original Dataset](https://psyarxiv.com/w4f72/)

[Technical Report](https://docs.google.com/document/d/1kYm0mFaiNZCYPEOepN8wCJaDU85FmK--_ZcgLtYfSSI/edit?usp=sharing)

[BERT Tutorial](http://mccormickml.com/2019/07/22/BERT-fine-tuning/)
