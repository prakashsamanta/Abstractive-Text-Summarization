# Abstractive-Text-Summarization-using-Attention-Layer
## Problem Statement
In recent years, the volume of textual data has rapidly increased, which has generated a valuable resource for extracting and analysing information. To retrieve useful knowledge within a reasonable time period, this information must be summarised.

A Machine Learning model is developed that can automatically deliver accurate summaries of longer textdata and those summaries can be useful, for digesting such large amounts of information in a compressed form, could be useful in many fields

## What is Abstartctive Summarization? How is it different from Extractive Summarization?
The process of producing summaries from the huge sets of information while maintaining the actual context of information is called Text Summarization. The summary should be fuent and concise throughout. There are two types of summarizations - Extractive Summarization and Abstractive Summarization.

In Extractive Summarization, we focus on the vital information from the input sentence and extract that specic sentence to generate a summary. There is no generation of new sentences for summary, they are exactly the same that is present in the original group of input sentences.

On the contrary, Abstract Summarization takes an exact sentence to generate a summary. It focuses on the vital information of the original group of sentences and generates a new set of sentences for the summary. This new sentence might not be present in the original sentence.

##Future Scope
1. Training for more epochs
2. Increase the training dataset size and build the model : The generalization capability of a deep learning model enhances with an increase in the training dataset size
3. Bi-Directional LSTM : Capable of capturing the context from both the directions and results in a better context vector
4. Beam Search Strategy : for decoding the test sequence instead of using the greedy approach (argmax)
5. Implement pointer-generator networks and coverage mechanisms
