This is the basic work about topic merge.(my master thesis)
The dataset is too large to be uploaded, please check it in the paper <# Hate speech dataset from a white supremacist forum>.


The core idea of this project is to classify text data into different topics, as the distribution and characteristics of hate speech vary across topics.
In some topics, certain expressions are more likely to be offensive or discriminatory, while in others, similar words may not constitute hate speech. Therefore, relying solely on individual text can lead to misclassification.

To address this issue, I incorporated topic information into the model, enabling it to consider not only the content of the target text but also the label distribution and contextual patterns of other samples within the same topic. This allows the model to better estimate the likelihood that a given text constitutes hate speech.
