# open-domain-hindi-chatbot
This is a experimentation work to build an open domain chatbot for hindi Language.

## Data used
- The original data is from  [Daily-Dialog Dataset](https://aclanthology.org/I17-1099/)
- We have preprocessed and modified the data, post that translated the data using [AI4Bharat Indic Trans Model](https://ai4bharat.org/indic-trans). You can find the translation script in the repo.
- Download the [en-indic model](https://drive.google.com/file/d/1r0dC2V4QxRH1Fd9KPvv6lREzJuvMlOQl/view?usp=sharing)
- You can find the Modified data in the /data directory.


## Architectures
We have compared 4 different architecture in incremental fashion.
1. Sequence-Sequence(Bi-GRU)
2. Sequence-Sequence(Bi-GRU) + Attention
3. Sequence-Sequence(Bi-GRU) + TCN + Attention
4. Sequence-sequence(Transformer)

## Pretrained Embeddings
Fastext Pretrained Hindi Embeddings were also used to see if it can contribute to enhance the model's performance.

## Results
Yet to be added.

### Note
It's a part of my Mtech research work at NIT Silchar.

### Reference 
The code and experiment is highly influenced by
1. [Pytorch chatbot tutorial](https://pytorch.org/tutorials/beginner/chatbot_tutorial.html)
2. [Fawaz sammani Transfomer Chatbot Tutorial](https://github.com/fawazsammani/chatbot-transformer)
