INFO:__main__:Processed response from Scout API: The encoder in the image consists of the following components:

*   **Input Embedding**: This is where the input data is embedded into a higher-dimensional space.
*   **Multi-Head Attention**: This is a mechanism that allows the model to attend to different parts of the input sequence simultaneously.     
*   **Add & Norm**: This is a layer that adds the output of the multi-head attention mechanism to the input and normalizes it.
*   **Feed Forward**: This is a fully connected feed-forward network that transforms the output of the previous layer.
*   **Add & Norm (again)**: This is another layer that adds the output of the feed-forward network to the previous output and normalizes it.   

These components are repeated N times, as indicated by the "Nx" label. The output of the encoder is then passed to the decoder.

Therefore, the encoders in this picture are:

*   **Multi-Head Attention**
*   **Feed Forward**
*   **Add & Norm** (which appears twice)

These three components, repeated N times, make up the encoder.
{'scout': 'The encoder in the image consists of the following components:\n\n*   **Input Embedding**: This is where the input data is embedded into a higher-dimensional space.\n*   **Multi-Head Attention**: This is a mechanism that allows the model to attend to different parts of the input sequence simultaneously.\n*   **Add & Norm**: This is a layer that adds the output of the multi-head attention mechanism to the input and normalizes it.\n*   **Feed Forward**: This is a fully connected feed-forward network that transforms the output of the previous layer.\n*   **Add & Norm (again)**: This is another layer that adds the output of the feed-forward network to the previous output and normalizes it.\n\nThese components are repeated N times, as indicated by the "Nx" label. The output of the encoder is then passed to the decoder.\n\nTherefore, the encoders in this picture are:\n\n*   **Multi-Head Attention**\n*   **Feed Forward**\n*   **Add & Norm** (which appears twice) \n\nThese three components, repeated N times, make up the encoder.'}