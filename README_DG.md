Projeto de Equidade de Gênero - Desafio de Governança de Dados

## DG = Data Governance / Governança de Dados

Este projeto tem como objetivo explorar dados sobre equidade de gênero a partir de um arquivo CSV fornecido. As soluções serão submetidas via GitHub usando governança de dados com OpenMetadata em um ambiente Docker.

Instruções para as Participantes:
1. **Download dos Dados**:

Baixe o arquivo CSV fornecido no repositório e salve-o em seu computador.

2. **Exploração dos Dados**:

Antes de começar a resolver o desafio, explore os dados para entender sua estrutura e conteúdo.
Utilize softwares como Excel, Google Sheets ou ferramentas de análise de dados como Python (pandas), R ou qualquer outra de sua preferência.

3. **Resolução do Desafio**:

Utilize as habilidades de análise de dados e programação (se necessário) para resolver o desafio proposto.
Documente seu processo de resolução, incluindo qualquer código desenvolvido, análises realizadas e conclusões alcançadas.

4. **Submissão da Solução**:

Após concluir a resolução do desafio, submeta sua solução no GitHub.

## Instruções para Configuração do Ambiente:
1. Instalação do Docker:

Certifique-se de ter o Docker instalado em seu sistema. Você pode encontrar instruções de instalação para diferentes sistemas operacionais [aqui]([URL_do_link](https://www.docker.com/products/docker-hub/))
.

**Windows**:

Acesse o site oficial do Docker para Windows: [Docker Windows](https://www.docker.com/products/docker-desktop/).

Clique no botão "Download for Windows" para baixar o instalador.

Execute o arquivo baixado para iniciar o instalador do Docker.

Siga as instruções do instalador, aceitando os termos de uso e selecionando as opções padrão, a menos que tenha um motivo específico para alterá-las.

Durante a instalação, o Docker Desktop será baixado e instalado automaticamente.

Após a conclusão da instalação, reinicie o seu computador.

Após reiniciar, o Docker Desktop será iniciado automaticamente. Você verá um ícone do Docker na bandeja do sistema, indicando que o Docker está em execução.

**macOS**:

Acesse o site oficial do Docker para macOS: [Docker macOS](https://www.docker.com/products/docker-desktop/).

Clique no botão "Download for macOS" para baixar o instalador.

Execute o arquivo baixado (Docker.dmg) para montar o volume do instalador.

Arraste o ícone do Docker para o ícone de Aplicativos para instalar o Docker.

Abra o Docker a partir do Launchpad ou da pasta Aplicativos.

Durante a instalação, você pode ser solicitado a conceder permissões ao Docker para instalar componentes adicionais.

Após a instalação, o Docker será iniciado automaticamente. Você verá um ícone do Docker na barra de menus, indicando que o Docker está em execução.

**Linux**:

Para sistemas Linux, as instruções de instalação podem variar dependendo da distribuição específica que você está usando. Aqui está um guia geral:

Acesse o site oficial do Docker para Linux: [Docker Linux](https://www.docker.com/products/docker-desktop/).

Siga as instruções específicas para a sua distribuição Linux. Geralmente, isso envolve a execução de comandos em um terminal para adicionar o repositório do Docker, instalar o pacote Docker Engine e iniciar o serviço Docker.

Após a instalação, você pode precisar adicionar seu usuário ao grupo "docker" para executar comandos Docker sem precisar de permissões de superusuário. Isso pode ser feito com o seguinte comando:

````
sudo usermod -aG docker $USER
````

Faça logout e login novamente para que as alterações tenham efeito.

Para verificar se a instalação foi bem-sucedida, execute o comando:

````
docker --version
````

Isso exibirá a versão do Docker instalada em seu sistema.

2. **Clone do Repositório**:

Clone este repositório para sua máquina local usando o seguinte comando:
  
````
  git clone https://github.com/seu-usuario/nome-do-repositorio.git`
````

3. **Configuração do OpenMetadata e Governança de Dados**:

Instalação e Configuração do OpenMetadata:

Siga as instruções específicas do OpenMetadata para configurar o ambiente usando Docker. Geralmente, isso envolve a execução de comandos Docker para baixar e iniciar os contêineres necessários.

[Open Metadata](https://docs.open-metadata.org/v1.3.x)

4. **Definição de Metadados**:

Antes de importar os dados, defina os metadados relevantes para o conjunto de dados de equidade de gênero. Isso pode incluir informações como o título do conjunto de dados, descrição, autor, licença e qualquer outro metadado pertinente.

4.1 Classificação e Rotulagem:

Determine as classificações e rótulos apropriados para os dados de acordo com as políticas de governança de dados da sua organização ou requisitos específicos do projeto. Isso pode envolver a definição de níveis de confidencialidade, sensibilidade e qualquer outra classificação relevante.
Catalogação de Dados:

Use as ferramentas fornecidas pelo OpenMetadata para catalogar os dados de equidade de gênero. Isso geralmente envolve a criação de um registro no catálogo de dados, onde as informações sobre o conjunto de dados são armazenadas, incluindo metadados, classificações e localização física do arquivo.

4.2 Mapeamento de Dados:

Se necessário, mapeie os campos do arquivo CSV para os atributos correspondentes no esquema de dados do OpenMetadata. Isso garante consistência e precisão na interpretação dos dados durante a análise.

4.3 Políticas de Acesso e Controle:

Estabeleça políticas de acesso e controle para os dados de equidade de gênero. Isso pode incluir a definição de permissões de acesso baseadas em funções, grupos ou usuários específicos, garantindo que apenas pessoas autorizadas possam visualizar ou modificar os dados.

4.4 Auditoria e Monitoramento:

Configure recursos de auditoria e monitoramento para rastrear atividades relacionadas aos dados de equidade de gênero. Isso ajuda a garantir a conformidade com as políticas de governança de dados e identificar qualquer atividade suspeita ou não autorizada.

5. **Documentação de Governança de Dados**:

Documente todas as etapas de governança de dados realizadas, incluindo definições de metadados, classificações, políticas de acesso e controle, auditoria e monitoramento, entre outros. Isso garante transparência e replicabilidade no gerenciamento dos dados ao longo do tempo.
Consulte a documentação oficial do OpenMetadata para obter detalhes sobre como configurar e executar o serviço usando Docker.

6. **Importação dos Dados**:

Após configurar o OpenMetadata, importe os dados de equidade de gênero fornecidos para o ambiente.
Siga as instruções específicas do OpenMetadata para importar dados de um arquivo CSV.

7. **Resolução do Desafio**:

Use as funcionalidades do OpenMetadata para acessar e analisar os dados durante a resolução do desafio.

8. **Submissão da Solução**:

Por favor, siga as instruções abaixo para contribuir com sua solução para o desafio:

8.1. **Clone o Repositório**: Clone este repositório para o seu ambiente de desenvolvimento local usando o seguinte comando:
    ```
    git clone https://github.com/nome-do-seu-usuario/nome-do-repositorio.git
    ```

8.2. **Crie uma Branch**: Crie uma branch separada para trabalhar em sua solução utilizando o comando:
    ```
    git checkout -b DG-seu-nome
    ```

Consulte a documentação oficial do OpenMetadata para obter informações detalhadas sobre como usar suas funcionalidades.
GitHub Ajuda:

Se você não estiver familiarizado com o GitHub, consulte a documentação oficial ou procure tutoriais online para obter ajuda sobre como clonar repositórios, criar branches, fazer commits e enviar solicitações pull.

- Certifique-se de seguir as melhores práticas de governança de dados.
- Se tiver alguma dúvida ou problema durante o desenvolvimento de sua solução, sinta-se à vontade para entrar em contato com a comunidade IT Girls ou seu grupo para obter ajuda.
- Este é um ambiente de aprendizado colaborativo. Aproveite a oportunidade para aprender com os outros, trocar experiências e aprimorar suas habilidades em engenharia de dados.
