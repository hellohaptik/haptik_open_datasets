# Short Text Similarity Dataset

This dataset contains sample of messages exchanged by humans with conversational agent over chat interface. Every row in dataset contains a pair of text and it's corresponding similarity label annotated by human agents. Each pair was labelled by 3 human agents and final label is decided based on vote count.

### What is different about this dataset and when to use it?

1. It contains text messages exchanged by humans to get some task done and hence is as close as possible to what you can expect while deploying your algorithm in production environment.
2. It can be best used to evaluate generalized/ open domain word representatons while using them for interpreting data received from natural language interface.
3. It can also be used to evaluate syntactic and semantic similarity algorithms for short text.
4. Unlike ideal datasets which are mostly generated from news, emails, etc., and contains well structured english sentences, this dataset contains anomalies in sentence structure, spelling mistakes, etc. which are common on messaging/voice interface.
5. Dataset contains close to 5k records and can be primarily used as test data for general similarity approaches.

### Each row in this dataset contains following fields

1. `ID` - Unique identifier for the pair of messages.

2. `Message 1` - Short text sent to the conversational agent.

3. `Message 2`- Short text to be compared with Message 1 (Taken from training data of the conversational agent/bot).

4. `Label` - Category labelled by human agent. It's value can be amongst any of the following -

   1. `similar` - Message 1 and Message 2 shows strong semantic similarity.

   2. `dissimilar` - Message 1 and Message 2 are strongly dissimilar.

   3. `ambiguous` - Human agents could not agree on similarity and interpretation of this pair is either subjective or contextual.

      

      

   