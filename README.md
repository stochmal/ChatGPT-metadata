## ChatGPT metadata
### main

| Metadata | Description | Examples | Common Values |
| --- | --- | --- | --- |
| Prompt | The text used to initiate the conversation | "What's your favorite color?" | N/A |
| Model | The name or ID of the GPT model used to generate the response | "gpt-2", "davinci", "curie" | N/A |
| Temperature | Controls the creativity of the generated response | 0.5, 1.0, 1.5 | 0.1-1.5 |
| Top k | Controls the number of most likely words to be used in the response | 10, 50, 100 | 10-100 |
| Top p | Controls the diversity of the generated response | 0.5, 0.9, 0.95 | 0.1-0.95 |
| Presence penalty | Controls the presence of specific words in the generated response | {"penalty": 0.5, "words": \["apple", "banana"\]} | 0.1-1.0 |
| Frequency penalty | Controls the repetition of the generated response | 0.5, 0.75, 1.0 | 0.1-1.0 |
| Stop sequence | Specifies a sequence of tokens that will stop the generation | "END\_OF\_SENTENCE\_TOKEN", "###" | N/A |
| Timeout | Specifies a time limit for generating the response | 10, 30, 60 | N/A |
| Max tokens | Limits the length of the generated response in tokens | 50, 100, 200 | 10-2048 |
| Max characters | Limits the length of the generated response in characters | 500, 1000, 2000 | 10-65,536 |
| Best of | Specifies the number of responses to generate and returns the highest scoring one | 1, 3, 5 | 1-10 |
| Logprobs | Returns the log probabilities for each token in the generated response | true, false | true/false |
| Echo | Echoes the prompt in the generated response | true, false | true/false |
| Expand | Expands all occurrences of a token to a list of similar tokens | {"text": "color", "expand\_to": \["red", "blue"\]} | N/A |
| Metadata | Includes additional metadata to be used in the generation process | {"genre": "science fiction", "author": "Asimov"} | N/A |
| Topp | Same as Top p, but with a different calculation for determining the size of the set of candidates | 0.5, 0.9, 0.95 | 0.1-0.95 |
| Nucleus Sampling | Same as Top p, but instead of selecting the top k words with probabilities greater than a given threshold, it selects the minimum set of words necessary such that the total probability mass is greater than or equal to the threshold | 0.5, |  |

### additional

 | Metadata | Description | Example Values | Common Values |
 | --- | --- | --- | --- |
 | Purpose | The goal or intention behind the prompt | "Generate creative writing prompts", "Answer customer questions" | Varies based on use case |
 | Context | The setting or situation in which the prompt will be used | "In a job interview setting", "In a casual conversation with a friend" | Varies based on use case |
 | Domain | The specific field or topic area that the prompt should relate to | "Artificial Intelligence", "Financial Planning" | Varies based on use case |
 | Audience | The intended audience for the prompt | "Adults", "Children ages 8-12" | Varies based on use case |
 | Tone | The emotional or tonal qualities of the prompt, such as formal or informal, serious or playful, positive or negative | "Formal and professional", "Playful and lighthearted" | Varies based on use case |
 | Style | The stylistic approach for the prompt, such as descriptive, narrative, expository, or persuasive | "Descriptive and vivid", "Expository and informative" | Varies based on use case |
 | Level of detail | The amount of information and specificity to be included in the prompt | "Highly detailed and specific", "General and broad" | Varies based on use case |
 | Level of complexity | The degree of complexity in the prompt, such as basic, intermediate, or advanced | "Basic and straightforward", "Advanced and technical" | Basic, Intermediate, Advanced |
 | Length | The desired length of the prompt, such as word count or character count | "100 words", "500 characters" | Varies based on use case |
 | Max Tokens | The maximum number of tokens (words or subwords) allowed in the generated text. Models may produce an error if the length of the output exceeds this value. | 1024, 2048, 4096 | Varies based on the model and use case |
 | Format | The format or structure of the prompt, such as a question, statement, or dialogue | "Question and answer format", "Dialogue between two people" | Varies based on use case |
 | Examples | Examples or templates of the type of prompt being requested or desired | "Write a story about...", "What is the definition of..." | Varies based on use case and type of prompt |
 | Keywords | Relevant keywords to be included in the prompt for search engine optimization or other purposes | "Travel, adventure, tourism", "Marketing, social media, branding" | Varies based on use case |


