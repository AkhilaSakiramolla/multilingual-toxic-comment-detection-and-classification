Social media and online platforms have provided individuals
with the means to put forward their thoughts and freely express
opinions on various matters. Lately, there have been several
instances where this freedom of speech is misused to spread
hate and hurtful comments causing more harm than good.
Disrespectful comments containing explicit language can be
categorized into Toxic, Severely Toxic, Obscene, Threat, In-
sult, and Identity Hate.

To protect users from being exposed to this offensive
language, companies now need to start flagging comments
and filtering out content or blocking users found guilty to
prevent more cases. Several Machine Learning models have
been developed and deployed to filter out the unruly language
and protect internet users from becoming victims to online
harassment and cyberbullying.

There have been a few kaggle competitions and work done
on finding best methods to classify comments into different
categories, attempts at removing unintended bias that creeps
into models associating names of frequently attacked identities
with toxicity. Here we attempt to apply the vast research
on multilingual translation to classify comments in different
languages.

This paper is a comprehensive comparative analysis where we
investigate how a deep learning model trained on toxic comments
in English generalizes to other popular languages. We used
the dataset from a Kaggle competition hosted by Conversation-
alAI/Jigsaw “Multilingual Toxic Comment Classification”.
We start with LSTM and Bi-LSTM models for baseline and
try multiple complex architectures such as BERT and its various
versions. We found that XLM-RoBERTa performed best with
0.913 AUC score on validation set which contains 3 languages.
