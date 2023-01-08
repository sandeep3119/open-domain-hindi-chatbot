# open-domain-hindi-chatbot
This is a experimentation work to build a open domain chatbot for hindi Language.

## Data used
- The original data is from  [Daily-Dialog Dataset](https://aclanthology.org/I17-1099/)
- We have translated the data using [AI4Bharat Indic Trans Model](https://ai4bharat.org/indic-trans). You can find the translation script in the repo.
- You can find the Preporcessed data in the /data directory.


## Architectures
We have compared 3 different architecture in incremental fashion.
1. Sequence-Sequence(Bi-GRU)
2. Sequence-Sequence(Bi-GRU) + Attention
3. Sequence-sequence(Transformer)

## Results
Yet to be added.

## Reference 
The code and experiment is highly influenced by
1. [Pytorch chatbot tutorial](https://pytorch.org/tutorials/beginner/chatbot_tutorial.html)
2. [Fawaz sammani Transfomer Chatbot Tutorial](https://github.com/fawazsammani/chatbot-transformer)

