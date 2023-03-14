# Stack Overflow Multi-class Text Classification

This notebook trains a sentiment analysis model to classify the tags for a programming question on Stack Overflow based on the text of the question. This is an example of multi-class classification, an important and widely applicable kind of machine learning problem.
</br></br>
We'll use the Stack Overflow questions dataset that contains the text of 16,000 programming questions from the Stack Overflow. These are split into 8000 questions for training and 8000 question for testing. The training and testing sets are balanced, meaning they contain an equal number of question for each programming language.

This dataset is an extract from the public Stack Overflow dataset for use as a tutorial on tensorflow.org.

It contains the body of 16,000 posts on four languages (Java, Python, CSharp, and Javascript), which are equally divided into train and test.

The keywords "Java", "Python", "CSharp" and "JavaScript" have been replaced in each post by the word "BLANK" in order to increase the difficulty of this dataset in classification examples.
