Prompt Engineering is the process of designing effective input prompts to guide a Large Language Model (LLM) to generate the desired response. 
It involves structuring the prompt in a way that improves the model's accuracy, creativity, and relevance.

Different prompting techniques influence the quality of the model's output, such as:

Zero-Shot Prompting
One-Shot Prompting
Few-Shot Prompting


Parameters for LLM Generation

Temperature (temperature) : Controls randomness in token selection.
Temperature	Controls randomness	Lower = deterministic, Higher = creative

Top-K Sampling (top_k) : Limits token selection to the top k most probable tokens.
Top-K	Limits token choices	Lower = precise, Higher = diverse

Top-P Sampling (top_p, Nucleus Sampling): Dynamically selects the smallest set of tokens whose cumulative probability ≥ top_p.
Top-P	Dynamically limits choices	Lower = strict, Higher = freeform

Beam Search: Instead of selecting the highest-probability token at each step, beam search explores multiple possible sequences before selecting the best one.
Beam Search	Searches for best sequence	Higher beams = More accurate but slow

Added templates and usage of BOS and EOS
