# TRANSFORMER GENERAL ARCHITECTURE

- Mainly 2 blocks : Encoder and Decoder
- **Encoder** - Receives an input and builds a representation of it (its features). This means that the model is optimized to acquire understanding from the input.
- **Decoder** - The decoder uses the encoder’s representation (features) along with other inputs to generate a target sequence. This means that the model is optimized for generating outputs.
![img_3.png](images/img_3.png)
- Encoder-only models: Good for tasks that require understanding of the input, such as sentence classification and named entity recognition.
- Decoder-only models: Good for generative tasks such as text generation.
- Encoder-decoder models or sequence-to-sequence models: Good for generative tasks that require an input, such as translation or summarization
- 