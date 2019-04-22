# silvernlp
Some ideas for ideal deepnlp framework
- [ ] Total reproduceability, setting all the seeds by default and from single function
- [ ] Tokenization stuff, Basic, Wordpiece, Byte-pair etc
- [ ] Pipeline object, saveable vocabs, encoders, classifiers, all-in-one
- [ ] Customizable earlystopping
- [ ] Robust reporting:
  -  To stdout
  -  To .txt file
  -  To Tensorboard
  -  To Telegram, Slack, Discord etc.
  -  Combined reporting(multiple destinations at once)
- [ ] Novel lr_scheduling policies(one-cycle, etc)

- [ ] No custom file formats, custom data loading, data loading is a developer part
- [ ] Model-Agnostic interface (Model just have to meet input shape and output shape requirments, specified by task)
- [ ] Custom Loss Support
- [ ] Build-in and custom metrics
- [ ] Built-in word-level and char-level embeddings helpers
- [ ] Pluggable layers of contextual embeddings
- [ ] All the recent techniques implemented (QRNN, SRU, Attention, Self-Attention, Transformer-Block, Positional-encoding, FP16 fine-tuning)
- [ ] ~ Quantization
- [ ] ~ Production-side inference tools(serving, hubs, versioning)
