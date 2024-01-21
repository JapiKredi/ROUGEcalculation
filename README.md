# ROUGEcalculation

 ROUGE (Recall-Oriented Understudy for Gisting Evaluation) is a set of metrics commonly used for evaluating the quality of generated text, particularly in the context of natural language generation tasks such as text summarization or machine translation. ROUGE focuses on comparing the generated text with reference (or gold standard) texts to assess the similarity and overlap in terms of content.

There are several ROUGE metrics, and one of the most commonly used ones is ROUGE-N, which measures the overlap of n-grams (contiguous sequences of n items, typically words) between the generated text and the reference text.

Precision (ROUGE-N-P): It measures the proportion of n-grams in the generated text that also appear in the reference text.
Recall (ROUGE-N-R): It measures the proportion of n-grams in the reference text that are also present in the generated text.
F1 Score (ROUGE-N-F): It's the harmonic mean of precision and recall and provides a balanced measure of performance.

Now, let's consider a simple example for ROUGE-1 (unigram) with a generated text and a reference text:

Generated Text: The quick brown fox jumps over the lazy dog.
Reference Text:A quick brown fox jumps over a lazy dog.
In this case, the unigrams (individual words) that overlap are: "the," "quick," "brown," "fox," "jumps," "over," "the," "lazy," "dog." 
There are a total of 9 unigrams in the generated text.

Now, let's calculate ROUGE-1-P, ROUGE-1-R, and ROUGE-1-F:

<img width="345" alt="Screenshot 2024-01-21 at 1 54 53 PM" src="https://github.com/JapiKredi/ROUGEcalculation/assets/88824661/f960674e-d7ae-46ae-8d1f-91b129d441ff">

In this example, the ROUGE-1 precision, recall, and F1 score are all perfect, indicating a complete overlap between the generated text and the reference text in terms of unigrams.
