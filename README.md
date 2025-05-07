# Grading Short Answer Type Questions: A Comparative Analysis of Deep Learning vs Heuristic Approaches

## Direction 2 (research oriented. Difficulty level: easy – medium hard)
Classification task for short answer questions. Data is provided in short_answer_grading.zip

In this task, participants were asked with several short answer questions. You will need to train/prompt a model to grade those short answer questions.

You will need to develop and compare three models, such as rule-based model, BERT-based model, and LLM-based model.

## Data description
Test.csv & train.csv: Experiment,Topic,ID,Question,Response,CorrectAnswer,label

You will need the Question, Response, CorrectAnswer, and label to train the model. Label=1 means the response is correct. Label=0 means the response is similar to the correct answer but not precise. Label=-1 means the response is incorrect.

You will test your model performance on Test.csv.
