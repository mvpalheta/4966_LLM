# Converse com as resoluções 4.966/2021 e 309/2023 do Bacen
Este repositório tem como finalidade compartilhar os códigos utilizados no desenvolvimento de um pequeno exercício de utilização de modelos LLM. Neste caso, foi desenvolvida uma aplicação onde é possível "conversar" com as resoluções 4.966/2021 e 309/2023 do Banco Central do Brasil. Estas resoluções dispõem sobre os novos conceitos e os critérios contábeis aplicáveis a instrumentos financeiros, que irão vigorar a partir de 1º de janeiro de 2025, sendo de extrema importância para o Sistema Financeiro Nacional.

No caso da aplicação apresentada neste repositório, foi utilizada o framework Llamaindex em conjunto com o LLM gpt-3.5-turbo. Llamaindex é um framework simples e flexível que permite conectar fontes de dados privadas e/ou customizadas a diversos LLMs. O resultado disto é que as respostas fornecidas pelos LLMs são mais relevantes e específicas ao contexto de negócio desejado. No caso deste exercício foi utilizado o framework Llamaindex em conjunto com o LLM gpt-3.5-turbo.

O exercício se torna mais interessante tendo em vista que o LLM gpt-3.5-turbo foi treinado com dados anteriores à divulgação das resoluções utilizadas. Sendo assim, até o momento (10/2023) o ChatGPT público não possui  informações relativas a elas, não sendo capaz de responder questionamentos sobre as resoluções 4.966 e 309.

Neste [blog post](https://blog.streamlit.io/build-a-chatbot-with-custom-data-sources-powered-by-llamaindex/) você encontra um tutorial sobre como construir este tipo de app.

# Organização do repositório

**.streamlit:** Esta pasta contém o arquivo no formato .toml que guarda a chave necessária para consultar a API do LLM utilizado (neste caso é o gpt-3.5-turbo da OpenAI). Para tanto, é necessário criar uma conta no site do LLM de interesse para obter a chave de utilização da API. ATENÇÃO: Alguns LLMs possuem um período de teste sem custo e após isto é cobrado pelo uso.

**data:** Esta pasta contém os dados utilizados pelo Llamaindex para "treinar" o LLM utilizado. Neste caso, são os arquivos PDF das **Resoluções 4.966/2021, 309/2023, 219/2022 e Instrução Normativa 236/2022**, mas poderiam ser outros formatos. Para utilização de arquivos PDF é necessário ter o pacote PYPDF instalado, pois é utilizado no background pelo Llamaindex, ainda que ele não seja importado diretamente no script.

**main_app.py:** Arquivo com a aplicação de assistente virtual.

**requirements.txt:** Arquivo com os pacotes necessários para uso da aplicação.

Espero que tanto a aplicação quanto os códigos disponibilizados aqui sejam úteis para alguém. Estou à disposição para esclarecer dúvidas, receber críticas construtivas e/ou sugestões através do e-mail mvpalheta@gmail.com. **Abraços**.
