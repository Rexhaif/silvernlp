# silvernlp
Some ideas for ideal deepnlp framework
1. Total reproduceability, setting all the seeds by default and from single function
2. Robust reporting:
2.1. To stdout
2.2. To .txt file
2.3. To Tensorboard
2.4. To Telegram, Slack, Discord etc.
2.5. Combined reporting(multiple destinations at once)

3. No custom file formats, custom data loading, data loading is a developer part
4. Model-Agnostic interface (Model just have to meet input shape and output shape requirments, specified by task)
5. Custom Loss Support
6. Build-in and custom metrics
7. Built-in word-level and char-level embeddings helpers
8. Pluggable layers of contextual embeddings
9. All the recent techniques implemented (QRNN, SRU, Attention, Self-Attention, Transformer-Block, Positional-encoding, FP16 fine-tuning)
10. ~ Quantization
11. ~ Production-side inference tools(serving, hubs, versioning)
