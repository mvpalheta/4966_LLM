# Converse com as resoluções 4.966/2021 e 309/2023 do Bacen
Este repositório tem como finalidade compartilhar os códigos utilizados no desenvolvimento de um pequeno exercício de utilização de modelos LLM. Neste caso, foi desenvolvida uma aplicação onde é possível "conversar" com as resoluções 4.966/2021 e 309/2023 do Banco Central do Brasil. Estas resoluções dispõem sobre os novos conceitos e os critérios contábeis aplicáveis a instrumentos financeiros, que irão vigorar a partir de 1º de janeiro de 2025, sendo de extrema importância para o Sistema Financeiro Nacional.

No caso da aplicação apresentada neste repositório, foi utilizada o framework Llamaindex em conjunto com o LLM gpt-3.5-turbo. Llamaindex é um framework simples e flexível que permite conectar fontes de dados privadas e/ou customizadas a diversos LLMs. O resultado disto é que as respostas fornecidas pelos LLMs são mais relevantes e específicas ao contexto de negócio desejado. No caso deste exercício foi utilizado o framework Llamaindex em conjunto com o LLM gpt-3.5-turbo.

O exercício se torna mais interessante tendo em vista que o LLM gpt-3.5-turbo foi treinado com dados anteriores à divulgação das resoluções utilizadas. Sendo assim, até o momento o ChatGPT público não possui  informações relativas a elas, não sendo capaz de responder questionamentos sobre as resoluções 4.966 e 309.

Neste [blog post](https://blog.streamlit.io/build-a-chatbot-with-custom-data-sources-powered-by-llamaindex/) você encontra um tutorial sobre como construir este tipo de app. 
