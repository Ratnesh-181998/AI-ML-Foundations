# transformers-
transformer 

<img width="858" height="1044" alt="image" src="https://github.com/user-attachments/assets/ce1b34f7-eb2f-4bba-8bf4-8e78d8237855" />

Transformers look complex until you follow the flow.

At their core, they turn text into numerical representations, identify relationships between tokens, build context, and predict what should come next.

The process begins with tokenization, where text is divided into smaller units. Embeddings convert those tokens into vectors, while positional encoding preserves their order.

Self-attention then allows each token to examine other relevant tokens. Queries, keys, and values calculate those relationships, while attention weights determine where the model should focus.

Multi-head attention expands this further by learning several relationships simultaneously.

Inside each transformer block:

↳ Feed-forward networks process every token
↳ Residual connections preserve earlier information
↳ Layer normalization stabilizes training
↳ Context windows define how much information the model can consider

The architecture can include encoders, decoders, or both. Encoders build contextual representations, while decoders generate outputs token by token. Masked attention prevents the model from seeing future tokens, and cross-attention connects the decoder with source information.

Before real use, models go through pretraining to learn broad language patterns. Fine-tuning then adapts them to particular tasks or domains.

During inference, the model receives a prompt, calculates probabilities across possible tokens, selects the next token, and repeats the process until the response is complete.

Understanding these concepts makes LLMs feel less like magic and more like engineering.

<img width="862" height="1096" alt="image" src="https://github.com/user-attachments/assets/89e8e0a9-de18-4147-9866-7d94ddeeb59a" />
