
# DATA 512 - Human Centered Data Science
## Assignment 2 : Bias in Data
### Introduction

The goal is to identify potential sources of bias in a corpus of human-annotated data, and describe some implications of those biases. The corpus used iscalled the Wikipedia Talk corpus, and it consists of three datasets. Each dataset contains thousands of online discussion posts made by Wikipedia editors who were discussing how to write and edit Wikipedia articles. Crowdworkers labelled these posts for three kinds of hostile speech: “toxicity”, “aggression”, and “personal attacks”. Many posts in each dataset were labelled by multiple crowdworkers for each type of hostile speech, to improve accuracy.
For the purpose of this explatory analysis, the datasets used are:
Toxicity - 160k labeled comments from English Wikipedia by approximately 10 annotators via Crowdflower on a spectrum of how toxic the comment is (perceived as likely to make people want to leave the discussion) to how healthy to conversation the contribution is.
Aggression - 100k labeled comments from English Wikipedia by approximately 10 annotators via Crowdflower on how aggressive the comment was perceived to be along with some demographic data for each crowd-worker.

### Data

This data can be found on [Figshare](https://figshare.com/articles/dataset/Wikipedia_Talk_Corpus/4264973) .

Cite
Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2017): Wikipedia Talk Corpus. figshare. Dataset. https://doi.org/10.6084/m9.figshare.4264973.v3

### Packages

- numpy : (https://numpy.org/)
- pandas : (https://pandas.pydata.org/)
- matplotlib : (https://matplotlib.org/)
- requests : (https://requests.readthedocs.io/en/master/)

### Files

- output : Directory containing all visualizations
- data: Directory containing all data

#### License

 [MIT LICENSE](https://opensource.org/licenses/MIT)
