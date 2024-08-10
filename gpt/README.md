# Generative Pre-Trained Transformer (GPT)
### GPT 3.0 vs 3.5 vs 4.0
GPT-3.5 is just a finely tuned model of GPT 3.0. It's not a whole new model with new training data, but rather it uses different tuning parameters. GPT 4.0 is a new model with new training data. It's 20x more expensive than GPT 3.5!

### Prompt -> Output
GPT is a language model that uses deep learning to generative text. We give it a prompt, then it will complete that prompt.

#### Example
Prompt: "Why did the chicken cross the"

Output: "road"

#### Example
Prompt: "Write a sentence explaining credit cards"

Output: "A credit card is a payment card issued by a financial institution that allows the cardholder to borrow funds up to a certain limit to make purchases, which must be repaid later with interest if not paid in full by the due date."

### How GPT 3.0 was trained
GPT-3 was trained on over 45TB, 500 billion tokens, of text data. It includes subset of the CommonCrawl Dataset, which crawls across the web and archives the data set. It also trained on two databases of online books, all of the English-language Wikipedia, all outbound links from Reddit with >3 Karma.

GPT-3 has 175 billion parameters and 800gb just to store the model. It costed $4.6 million in GPU costs to train the model.

### Completion vs Chat
There are two main ways we can interact with GPT models: Completion vs Chat.

Completion expects a single text prompt and only supports GPT-3.5.

Chat expects a list of messsages and supports GPT-3.5 and GPT-4.

### Deep-diving into the model
To learn about the internal workings of GPT as a deep learning model, read the GPT-Transformer.md file.