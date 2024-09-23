Case Study

In this case study, I presented Mistral7B with a combination of text, ASCII art, and binary data representative of pixels in a bitmap. Rather than relying on image patches, which are typically used for processing visual data, I utilized the ability of a language model to tokenize inputs. Each character, broken down into tokens, allowed Mistral7B to interpret and process them as part of the same input. This demonstrates that LLMs, with the right instructions, can handle multimodal processing without the need for visual patches. Instead, the model interprets these symbols as tokens, allowing it to generalize and respond coherently.

A key advantage of utilizing an LLM to process visual data is transfer learning, which allows a model trained on one set of data to be fine-tuned for different tasks and dramatically reducing the time and resources required for retraining. Yosinski et al. (2014) demonstrated that transferring knowledge from one neural network to another not only speeds up learning but also improves performance across multiple domains. Furthermore, the human mind, housed within it's own neural network is a valuable training tool and should be included as a vital element within the transfer learning process.
ASCII, Binary, Pixels, Bitmaps, and Word Processors

While computers cannot "see," they can recognize patterns and rules. My inspiration for this training came from ASCII art, which uses printable characters to create computer graphics, and from my son’s worksheet of binary images from his elementary school gifted courses. However, challenges arose from the design of word processors and web interfaces, which include white space, limited character sets, and varying input/output sizes.

Despite setbacks, I eventually provided the model with the necessary context to succeed despite these limitations. The instructions I crafted used principles of bitmapping, alpha channels, encoder, decoder, and convolutional processes. I offered examples of rough images made up of characters mapped to a grid. To isolate specific characters based on opacity, I drew inspiration from Photoshop's alpha channels, which select pixels in an image based on levels of black and white. Each pixel contains a numeric value in its alpha channel, typically ranging between 0 and 1. A value of 0 makes the pixel fully transparent, revealing the pixels beneath, while a value of 1 makes it completely opaque.

I also emphasized the importance of understanding white space—the empty characters between sentences and words—which enabled the LLM to isolate basic shapes provided in ASCII art and binary images.
Training Large Language Models for Multimodality

In my research, I used Mistral7B, a language model with 7 billion parameters, to investigate how LLMs can handle multimodal inputs. My focus was to determine if Mistral7B could be trained with structured prompts that included text and symbolic data, specifically ASCII art and binary representations. The reliance on characters was primarily due to the limitations of the LLM interface's character set.

This case study demonstrated that even for a model like Mistral7B, the right instructions can enable it to handle complex multimodal inputs. Mistral7B adapted to the prompts, successfully synthesizing ASCII art with the text instructions and producing context-driven responses.
Reverse Engineering and Black Box Concepts in Multimodal Training

The training process can be likened to reverse engineering a black box. While we may not fully understand the internal workings of an LLM, we can observe its outputs and infer how it handles data. This method allows us to refine the model’s ability to synthesize diverse inputs.

Expanding the parameters used in training can enhance a model’s multimodal abilities. In the case of visual processing, incorporating different levels of luminosity would add additional layers of complexity to an image. Furthermore, using the case study as a basis for tokenizing other forms of data, such as audio frequencies, can also be explored.
Conclusion: Multimodal Training with Human Insight

This experiment highlights how LLMs can be trained to handle multimodal inputs through well-defined, context-driven instructions. By incorporating text, ASCII art, and binary data, I demonstrated that even smaller models like Mistral7B can successfully process and synthesize diverse data types.

I believe the true strength in training generative models comes from human intuition and passion - not just algorithms and subject matter expertise. These strengths are what drove me to use unconventional training methods and they also underscore my belief that breakthroughs and innovation stem from human experience. 
