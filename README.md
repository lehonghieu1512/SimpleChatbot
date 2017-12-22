# SimpleChatbot
Chatbot is used for basic communication in Vietnamese
This chatbot is made up from 2 algorithms which are doc2vec and neuron network
Doc2vec is a state-of-the-art algorithm which specializes in converting texts into vectors while keeping semantics and word order in a particular text length.
Neuron network is used for classifying input texts as to which type of questions they should belong to.
Each class is composed by many sentences which carry the same content but different in paraphrasing. As such, neuron model will try to capture the way the sentences are paraphrased and put them into the same class and produce the satisfactory answers for users. Thanks to the properties of doc2vec, if there are 2 sentences which comprise the same words but in different order, they will definitely be classified into 2 distinct classes. 
In this experiment, the model can perform with the accuracy of roughly 85% in training dataset. As the dataset for doc2vec that I have collected is too poor in size but with a wide range of words that the model cannot manage to perform well.
Hope this chatbot will offer you an overall idea on how to make a simple chatbot.
