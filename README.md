
# nanogpt-lecture

Code created in the [Neural Networks: Zero To Hero](https://karpathy.ai/zero-to-hero.html) video lecture series, specifically on the first lecture on nanoGPT. Publishing here as a Github repo so people can easily hack it, walk through the `git log` history of it, etc.


### License

MIT

# Notes about branch dev

Dataset created by myself with some of the books of Jose Marti. The dataset is of very bad quality since it's mostly based on OCR over pdfs and no data preprocessing was performed.My goal was to prepare a proof of concept to make transformers spell out in spanish with the style of Marti. The file Marti.txt show the results. Mission acomplished, I would say.

# Save best and last model

I have modify the original gpt.py file to be able to save and load the best and last model, as well as using a random seed for inference. Also added the option to provide an initial prompt.

# encoder

As suggested by @Karpathy, I've changed the encoder to tiktokens.
