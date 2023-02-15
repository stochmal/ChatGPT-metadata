# ChatGPT-metadata
very useful metadata to get better responses tailored to your requirements


Metadata	Description	Examples	Common Values
Prompt	The text used to initiate the conversation	"What's your favorite color?"	N/A
Model	The name or ID of the GPT model used to generate the response	"gpt-2", "davinci", "curie"	N/A
Temperature	Controls the creativity of the generated response	0.5, 1.0, 1.5	0.1-1.5
Top k	Controls the number of most likely words to be used in the response	10, 50, 100	10-100
Top p	Controls the diversity of the generated response	0.5, 0.9, 0.95	0.1-0.95
Presence penalty	Controls the presence of specific words in the generated response	{"penalty": 0.5, "words": ["apple", "banana"]}	0.1-1.0
Frequency penalty	Controls the repetition of the generated response	0.5, 0.75, 1.0	0.1-1.0
Stop sequence	Specifies a sequence of tokens that will stop the generation	"END_OF_SENTENCE_TOKEN", "###"	N/A
Timeout	Specifies a time limit for generating the response	10, 30, 60	N/A
Max tokens	Limits the length of the generated response in tokens	50, 100, 200	10-2048
Max characters	Limits the length of the generated response in characters	500, 1000, 2000	10-65,536
Best of	Specifies the number of responses to generate and returns the highest scoring one	1, 3, 5	1-10
Logprobs	Returns the log probabilities for each token in the generated response	true, false	true/false
Echo	Echoes the prompt in the generated response	true, false	true/false
Expand	Expands all occurrences of a token to a list of similar tokens	{"text": "color", "expand_to": ["red", "blue"]}	N/A
Metadata	Includes additional metadata to be used in the generation process	{"genre": "science fiction", "author": "Asimov"}	N/A
Topp	Same as Top p, but with a different calculation for determining the size of the set of candidates	0.5, 0.9, 0.95	0.1-0.95
Nucleus Sampling	Same as Top p, but instead of selecting the top k words with probabilities greater than a given threshold, it selects the minimum set of words necessary such that the total probability mass is greater than or equal to the threshold	0.5,	

