# Feedback-Effective-Argument-Prediction
### What it is?
#### It's a effective argument predfiction model which classifies each argument based on following discourse elements commonly found in argumentative writing -
- Lead - an introduction that begins with a statistic, a quotation, a description, or some other device to grab the reader’s attention and point toward the thesis
- Position - an opinion or conclusion on the main question
- Claim - a claim that supports the position
- Counterclaim - a claim that refutes another claim or gives an opposing reason to the position
- Rebuttal - a claim that refutes a counterclaim
- Evidence - ideas or examples that support claims, counterclaims, or rebuttals.
- Concluding Statement - a concluding statement that restates the claims
into following 3 catgories -
- Ineffective
- Adequate
- Effective

### How to use?
#### Create a dataframe with discourse_text and discourse_type columns containing argument and type of discourse type respectively. Then feed it to inference_fn with model and device. Output is a dataframe containing 3 columns as per each to be classify category which shows the probability of argument being from each 3 catgory
