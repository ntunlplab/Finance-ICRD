# ICRD: Investor's Claim-Rationale Dataset
# Introduction
There are two tasks in the ICRD. We separate the datasets into three parts, including Train/Dev/Test.

(1) Premise Detection

In the premise detection task, we aim at identifying whether the given sentence is a premise. There are two keys for each instance. "sentence" is the given sentence. If the value of "ans" is 0, means the given sentence is not a premise.  If the value of "ans" is 1, means the given sentence is a premise.     

(2) Claim-Premise Inference

When given a claim and a sentence, models are asked to predict whether the given sentence is the premise of the claim. There are three keys for each instance. "claim" is the given claim and "compare_sent" is the other given sentence. If the value of "ans" is 0, means the given sentence is not a premise of the given claim.  If the value of "ans" is 1, means the given sentence is a premise of the given claim.       

# Format
Read JSON file using Python
```python
import json

with open("ICRD-PremiseDetection-Dev.json", "r", encoding = "utf-8") as f:

    data = json.load(f)  
```

# Download
Please write us an email with the agreement. Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/ICRD/ICRD_agreement.pdf) to download the agreement of ICRD.

Email Address: cjchen@nlg.csie.ntu.edu.tw

# How to Cite the Corpus
Please cite the following paper when referring to the ICRD in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, and Hsin-Hsi Chen. 2021. Evaluating the Rationales of Retail Investors. In Proceedings of The Web Conference 2021 (WWW 2021).
# License
ICRD is licensed under the [Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
