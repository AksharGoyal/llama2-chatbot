# Mental Health Chatbot

Link to the colab notebook: https://colab.research.google.com/drive/1LeJuwITER2E1JTWZ3HReWqnr8RwTTVzK?usp=sharing  

The project uses llama-3.1 LLM created by Meta Llama which has 8 billion parameters. The user will enter a message describing what they are feeling and the chatbot will internally understand the sentiment and respond accordingly. With the help of ChatPromptTemplate, the bot remembers its context while interacting with the users. Make sure to have your [HuggingFace Access Token](https://huggingface.co/settings/tokens).

You can play with the chatbot by entering a comment containing a positive or negative sentiment. For example, if the user inputs "I am feeling great!", the chatbot will consider the statement as a positive emotion and respond with happiness. If the user enters "Today was the worst day ever.", then the chatbot will understand the human is going through sad or negative emotions and responds with empathy. 

Any input which is off-topic will not be responded to.
The chatbot will serve as a medium to help humans work with their emotions.
