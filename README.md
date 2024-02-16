# Microsoft Azure AI Fundamentals Bootcamp

## Tabela de conteúdos

- [Visão geral](#visão-geral)
  - [Conceitos fundamentais de IA](#conceitos-fundamentais-de-ia)


## Visão geral

Esse é um bootcamp gratuito realizado pela instituição de ensino on-line [dio.me](https://www.dio.me/) e que tem como objetivo preparar os seus participantes para a realização da prova de certificação AI-900, da Microsoft.

## Conceitos fundamentais de IA

### Aplicações da IA no cotidiano
- Análise de resultados e reconhecer padrões a partir de dados existentes (Ex.: Previsão de vendas)
- Extração de informações de quaisquer fontes, afim de obter conhecimento (Ex.: Coleta de dados em tempo real para auxílio na tomada de decisões)
- Compreensão da linguagem e participação em conversas (Ex.: Chatbots e assistentes virtuais)
- Reconhecimento de eventos anormais e tomada de decisões baseado nisso (Ex.: Monitoramento de tráfego em tempo real)
- Interpretação de informações visuais (Ex.: Windows Hello)

### Machine Learning
- Modelos preditivos treinados com dados e estatísticas, visando obter insights futuros (tendências, maior período de vendas por época do ano etc)

### Visão computacional
- Capacidade da IA de interpretar o mundo visual através de vídeos e imagens
- Ao treinar uma IA para reconhecer um determinado objeto, é preciso treiná-la para entender o que é aquele objeto e o que **não é** aquele objeto

### Cargas de trabalho
- Carga de trabalho é o nome dado às tarefas ou atividades que sistemas de inteligência artificial são capazes de realizar. Elas variam de acordo com complexidade, escopo, capacidade do sistema e necessidade
- Processamento de linguagem natural, desde interpretação até à validação da linguagem escrita ou falada (análise e classificação de e-mails em spams e não-spams; ofensividade dos usuários nas redes sociais)
- Inteligência de documentos, conceito que se refere à capacidade de entender e extrair informação de documentos digitais de forma automática. Ex.: interpretação de texto, reconhecimento de padrões, extração de entendidas e relacionamentos etc
- Mineração de conhecimento, sendo a extração de informações a partir de grandes conjuntos de dados (datasets). Visando identificar tendências, insights e conhecimentos ocultos nos dados.
- IA generativa, que se refere à sistemas com a capacidade de criar, gerar ou produzir novos conteúdos que são "indistinguíveis" de criações humanas. (Ex.: ChatGPT)

## Ferramentas

### Versionamento de código
- Sistemas de Controle de Versão: controlam as versões de um arquivo ao longo do tempo.
  - Registra o histórico de atualização do arquivo;
  - Gerenciando alterações, data, autor;
  - Organiza, controla e garante segurança.
- Os VCS (Version Control System) podem ser classificados como Centralizado e Distribuído.
  - Centralizado: Apenas um servidor contendo todos os arquivos do projeto. Ex.: CVS e Subversion.
  - Distribuído: Surgiu para solucionar o caso dos sistemas centralizados onde, caso o servidor ficasse inacessível, você perde acesso total ao seu projeto. Nele, a versão também é mantida de forma local, possibilitando alterações mesmo com o server offline. (Ex.: Git e Mercurial)
    - Cada clone é um backup;
    - Possibilita o trabalho de forma flexível;
    - Possível realizar adições, alterações e exclusões sem dispor de conexão à rede.
### Git
  - Criado por Linus Torvalds (Linux) e sua equipe
  - Ferramenta gratuita e de código aberto
  - Trabalha com ramificações (branching) e fusões (merging)
    - <code>git init</code>: inicia um repositório local;
    - <code>git clone</code>: clona um repositório existente na web;
    - <code>git pull</code>: traz as últimas alterações subidas na web para seu repo local;
    - <code>git commit</code>: "oficializa" suas alterações locais;
    - <code>git push</code>: sobe as alterações locais para a web.
### GitHub
- Criado por Chris Wanstrath, J. Hyett, Tom Preston-Werner e Scott Chacon
- Plataforma de hospedagem de código para controle de versão com o Git
