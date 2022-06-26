# IgnitionHacksSigma
My submission for the IgnitionHacks (Sigma Division) Hackathon.

## Specs
- Selected Model: ASGD Weight-Dropped LSTM (AWD-LSTM) pretrained on a text generation algorithm made by me on the dataset.
- Tokenizer: fast.ai's BaseTokenizer (Understands the significance of all-caps, repition in words, etc.)
- Library: fast.ai by Jeremy Howard
- Data Split: 90%-10% (10% was used for cross-validation)
- Training Time: ~ 5 hrs (2.5 hrs for classification algorithm and 2.5 hrs text generation algorithm)

## Improvements
- Training on the full dataset (Not feasible because of time restrictions)
- Refining Learning Rates

## Future Research/Developments
- Using transformers instead of AWD-LSTM's (prevent potential exploding gradients)
- Use GPT-3 (because its awesome)
- Visualizing more than just the learning rate optimizer

