# WTFAcademy ChatBot

该代码仓库包含了WTF Academy的ChatBot的代码，包括了使用Pinecone和Chroma的两个版本。

## [WTFAcademyChatBot.ipynb](./WTFAcademyChatBot.ipynb)

该Python notebook演示了如何利用langchain的QA chain，结合Pinecone来实现WTF Academy的Solidity课程的语义化搜索。
使用时，请在WTFAcademyChatBot.ipynb中设置有效的OpenAI API Key和Pinecone API Key和Env
```
OPENAI_API_KEY = ''
PINECONE_API_KEY = ''
PINECONE_API_ENV = ''
```

## [WTFAcademyChatBotChroma.ipynb](./WTFAcademyChatBotChroma.ipynb)

该Python notebook演示了如何利用langchain的QA chain，结合Chroma来实现WTF Academy的Solidity课程的语义化搜索。
使用时，在.env中设置有效的OpenAI API Key即可。