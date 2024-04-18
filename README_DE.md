# Desafio de Engenharia de Dados: Equidade de Gênero

## DE = Data Engineer / Engenharia de dados

Bem-vindas ao Desafio de Engenharia de Dados sobre Equidade de Gênero! Neste projeto, iremos trabalhar juntas para realizar análises e processamento de dados relacionados à equidade de gênero, utilizando técnicas de engenharia de dados.

## Sobre o Desafio

O objetivo deste desafio é explorar um conjunto de dados sobre equidade de gênero e aplicar técnicas de engenharia de dados para preparar os dados para análise posterior. O conjunto de dados contém informações sobre equidade de gênero em diferentes áreas, como educação, emprego, saúde, entre outros.

## Instruções para Contribuição

Por favor, siga as instruções abaixo para contribuir com sua solução para o desafio:

1. **Clone o Repositório**: Clone este repositório para o seu ambiente de desenvolvimento local usando o seguinte comando:
    ```
    git clone https://github.com/nome-do-seu-usuario/nome-do-repositorio.git
    ```

2. **Crie uma Branch**: Crie uma branch separada para trabalhar em sua solução utilizando o comando:
    ```
    git checkout -b DE-seu-nome
    ```

3. **Análise e Exploração de Dados**: Utilize ferramentas de análise de dados, como Jupyter Notebook ou qualquer outra ferramenta de sua preferência, para explorar o conjunto de dados e entender sua estrutura e conteúdo.

4. **Engenharia de Dados**: Realize as seguintes etapas de engenharia de dados no conjunto de dados:
   - Limpeza de dados: Remova dados duplicados, ausentes ou inconsistentes.
   - Transformação de dados: Converta os tipos de dados, renomeie colunas, aplique filtros, etc.
   - Integração de dados: Se necessário, integre múltiplos conjuntos de dados relacionados.

5. **Criação de Interface com Streamlit**: Use o Streamlit para criar uma interface de usuário interativa para visualizar os dados processados. Siga as etapas abaixo:
   - Instale o Streamlit em seu ambiente de desenvolvimento:
     ```
     pip install streamlit
     ```
   - Crie um script Python com o Streamlit para carregar e exibir os dados processados. Exemplo:
     ```python
     import streamlit as st
     import pandas as pd

     # Carregando os dados processados
     data = pd.read_csv('caminho_para_seus_dados_processados.csv')

     # Exibindo os dados na interface do Streamlit
     st.write(data)
     ```
   - Execute o script Python usando o comando:
     ```
     streamlit run seu_script.py
     ```
   - Visualize a interface do Streamlit no navegador e verifique se os dados estão sendo exibidos corretamente.

6. **Dockerização do Projeto**: Para facilitar a reprodução do ambiente de desenvolvimento, você pode dockerizar o projeto. Siga as etapas abaixo:
   - Crie um arquivo Dockerfile na raiz do projeto com as instruções para criar a imagem Docker. Exemplo:
     ```
     FROM python:3.8
     WORKDIR /app
     COPY requirements.txt .
     RUN pip install -r requirements.txt
     COPY . .
     CMD ["streamlit", "run", "seu_script.py"]
     ```
   - Crie um arquivo requirements.txt listando as dependências do projeto, incluindo o Streamlit.
   - Construa a imagem Docker usando o comando:
     ```
     docker build -t nome-do-projeto .
     ```
   - Execute o contêiner Docker usando o comando:
     ```
     docker run -p 8501:8501 nome-do-projeto
     ```

7. **Documentação**: Documente o processo de engenharia de dados, criação da interface com o Streamlit e dockerização do projeto, explicando as etapas realizadas e justificando suas decisões. Isso pode ser feito através de comentários no código ou em um documento separado.

8. **Adicione os Arquivos**: Após concluir sua solução, adicione os arquivos ao stage do Git usando o comando:
    ```
    git add .
    ```

9. **Faça um Commit das Alterações**: Faça um commit das alterações com uma mensagem descritiva usando o comando:
    ```
    git commit -m "Adiciona solução do desafio de engenharia de dados por Seu Nome"
    ```

10. **Envie sua Solução**: Envie sua solução para o repositório remoto no GitHub utilizando o comando:
    ```
    git push origin DE-seu-nome
    ```

11. **Revisão e Feedback**: Após enviar sua solução, aguarde a revisão da equipe responsável pelo projeto.
## Informações Adicionais

- Certifique-se de seguir as melhores práticas de engenharia de dados, garantindo a qualidade e integridade dos dados processados.
- Se tiver alguma dúvida ou problema durante o desenvolvimento de sua solução, sinta-se à vontade para entrar em contato com a comunidade IT Girls ou seu grupo para obter ajuda.
- Este é um ambiente de aprendizado colaborativo. Aproveite a oportunidade para aprender com os outros, trocar experiências e aprimorar suas habilidades em engenharia de dados.

