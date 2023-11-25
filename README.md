# Projeto Hackathon

### Tech-Titans-Hackathon

O projeto consiste no desenvolvimento e organização de sistemas Front-end e Back-end.
A prosposta estabelecida para o projeto é um Sitema de Controle Hackathon, elaborado com o objetivo de cumprir as exigências propostas como: Aparência das telas, funcionalidade dos sistemas, resolução de problemas, organização do grupo e apresentação.

Equipe:

- [Davy Moreira Sebolt](https://github.com/Rascro)
- [Gilherme Halter Nunes](https://github.com/GuilhermeHalter)
- [Miguel Bochi Barros](https://github.com/MiguelBochi)
- [Juan Petersson Borges Padilha](https://github.com/alujuan)
- [Wedley Silva Schmoeller](https://github.com/WedleySilva)


Links do projeto:

- [Documentação (esse documento)](https://github.com/Hackathon-Organization/Base-ProjetoHackathon)
- Backend: [Repositório](https://github.com/Hackathon-Organization/back-hackathon.git) e [Publicação](https://back-hackathon-dev-nhbx.4.us-1.fl0.io/api/)
- Frontend-Mobile: [Repositório](https://github.com/Hackathon-Organization/frontend-mobile-hackathon) e [Publicação](https://)
- Frontend-web: [Repositório](https://github.com/Hackathon-Organization/frontend-web-hackathon) e [Publicação](https://)

# Desenvolvimento do Projeto

O Hackathon Management System é um sistema desenvolvido para facilitar a organização, execução e avaliação de hackathons. Este sistema visa otimizar o processo desde a inscrição dos participantes até a premiação das equipes vencedoras. Ele oferece funcionalidades abrangentes, incluindo cadastro de participantes, formação de equipes, submissão de projetos, avaliação por jurados, anúncio de vencedores, feedback dos participantes e relatórios estatísticos.

**Motivo da Escolha:**
Considerando o contexto do projeto proposto, o Hackathon Management System é a escolha ideal, pois atende diretamente às necessidades da TechConnect Solutions, a empresa organizadora de hackathons. Ao optar por esse modelo, estamos alinhando o sistema de desenvolvimento às especificidades do evento, proporcionando uma experiência aprimorada para participantes, jurados e organizadores. O sistema será uma ferramenta eficaz para gerenciar inscrições, formação de equipes, submissões de projetos e todas as fases críticas de um hackathon. Além disso, a geração de relatórios estatísticos fornecerá insights valiosos para melhorar futuros eventos.


# Situação Problema

Atualmente, a TechConnect Solutions enfrenta desafios significativos em relação à eficiência operacional na organização de hackathons. O processo manual de gerenciamento desde a inscrição dos participantes até a premiação das equipes tem se mostrado suscetível a erros, atrasos e falta de integração. A seguir, detalhamos a situação-problema em diferentes aspectos:

**Inscrição e Formação de Equipes:**

As inscrições dos participantes são realizadas manualmente, demandando tempo e esforço da equipe organizadora.
A formação de equipes é descentralizada, o que pode resultar em equipes desbalanceadas em termos de habilidades.

**Comunicação e Informações Descentralizadas:**

A comunicação com os participantes, informações sobre cronograma e desafios são transmitidas principalmente por e-mail, o que pode levar a mal-entendidos e informações desatualizadas.
As informações relevantes para os participantes, jurados e organizadores estão dispersas em diferentes canais.

**Avaliação Manual e Tempo de Anúncio de Vencedores:**

A avaliação dos projetos é realizada manualmente por jurados, consumindo tempo considerável.
O anúncio dos vencedores após a avaliação também é um processo que poderia ser mais eficiente.

**Feedback dos Participantes e Melhoria Contínua:**

A coleta de feedback dos participantes é realizada de maneira pouco estruturada, dificultando a identificação de áreas de melhoria.
O processo de análise pós-evento carece de dados consolidados para embasar decisões estratégicas de melhoria contínua.

# Descrição da proposta

O Hackathon Management System proposto visa transformar a organização e execução de hackathons pela TechConnect Solutions, solucionando os desafios identificados na situação-problema. Este software será uma ferramenta centralizada, intuitiva e eficiente, abordando as áreas críticas do processo de gestão de hackathons.
O software se concentrará na automação e otimização das etapas-chave dos hackathons, desde a inscrição dos participantes até o anúncio dos vencedores. Ele proporcionará uma experiência integrada, cobrindo aspectos como cadastro de participantes, formação de equipes, submissão de projetos, avaliação por jurados, feedback dos participantes e geração de relatórios estatísticos.

**Níveis de Usuário:**

- Participantes:

    Cadastro e inscrição em hackathons.</br>
    Acesso a informações sobre desafios, cronograma e regras.</br>
    Submissão de projetos e acompanhamento do status.</br>
    Feedback pós-evento.
    
- Jurados:

    Avaliação de projetos com base em critérios predefinidos.</br>
    Acesso a informações detalhadas sobre os projetos.</br>
    Contribuição para o processo de seleção dos vencedores.

- Organizadores:

    Gerenciamento centralizado de inscrições e participantes.</br>
    Facilitação na formação equipes, se necessário.</br>
    Acompanhamento do progresso do evento em tempo real.</br>
    Anúncio automático dos vencedores.</br>
    Coleta estruturada de feedback dos participantes.


# Regras de negócio

  - Cadastro de Avaliadores: </br>
        **R.N. 01:** Somente usuários cadastrados como avaliadores podem acessar o sistema de avaliação. </br>
        **R.N. 02:** O cadastro de avaliadores deve incluir informações como nome, e-mail, especialidade e senha.

  - Atribuição de Grupos: </br>
        **R.N. 03:** Cada avaliador pode ser designado para avaliar um ou mais grupos de hackathon. </br>
        **R.N. 04:** Deve permitir a atribuição do mesmo grupo a mais de um avaliador.

  - Avaliação de Projetos: </br>
        **R.N. 05:** Cada avaliador deve fornecer notas individuais para os critérios de avaliação predefinidos. </br>
        **R.N. 06:** As notas atribuídas pelos avaliadores devem ser numéricas e estar dentro de uma faixa específica, por exemplo, de 1 a 10. </br>
        **R.N. 07:** Cada grupo deve receber avaliação de pelo menos três avaliadores.

  - Classificação dos Grupos: </br>
        **R.N. 08:** A classificação dos grupos deve ser baseada na média ponderada das notas recebidas. </br>
        **R.N. 09:** Em caso de empate na média das notas, o grupo com maior pontuação no critério de originalidade deve ser classificado mais alto. </br>
        **R.N. 10:** A classificação final deve ser exibida de forma clara e acessível para todos os participantes.

  - Limite de Membros por Grupo: </br>
        **R.N. 11:** Cada grupo pode ter no máximo 5 membros. </br>
        **R.N. 12:** Não é permitido adicionar ou remover membros de um grupo após o início do hackathon.

  - Visualização de Resultados: </br>
        **R.N. 13:** Os resultados finais, incluindo classificações e notas, devem ser disponibilizados de forma transparente após a conclusão do processo de avaliação. </br>
        **R.N. 14:** Os participantes devem ter acesso apenas aos resultados gerais, sem visualização das notas individuais atribuídas pelos avaliadores.

  - Prazos de Avaliação: </br>
        **R.N. 15:** Deve ser estabelecido um prazo claro para que os avaliadores concluam suas avaliações. </br>
        **R.N. 16:** Caso um avaliador não conclua suas avaliações dentro do prazo estipulado, medidas devem ser tomadas para garantir a pontualidade do processo. </br>

  - Feedback aos Grupos: </br>
        **R.N. 17:** Após a divulgação dos resultados, os grupos devem ter acesso a feedback construtivo sobre seus projetos, destacando pontos fortes e áreas de melhoria.

  - Backup de Dados: </br>
        **R.N. 18:** Realizar backups regulares das notas e classificações atribuídas pelos avaliadores para evitar perda de dados críticos.

 - Reavaliação em Caso de Contestação: </br>
        **R.N. 19:** Caso um grupo conteste sua avaliação, deve ser estabelecido um procedimento para reavaliação por parte de um comitê independente.

# Requisitos funcionais

**RF001:** Cadastro de Participantes

Descrição: O sistema deve permitir que os participantes se cadastrem fornecendo informações como nome, e-mail, habilidades técnicas e preferências de equipe.</br>
Dados Necessários: Nome, E-mail, Habilidades Técnicas, Preferências de Equipe.</br>
Usuários: Participantes.

**RF002:** Formação de Equipes

Descrição: O sistema deve facilitar a formação de equipes, permitindo que os participantes se associem a equipes existentes ou criem novas equipes.</br>
Dados Necessários: Equipes existentes, Número de participantes por equipe.</br>
Usuários: Participantes.

**RF003:** Submissão de Projetos

Descrição: Os participantes devem ser capazes de submeter seus projetos através do sistema, fornecendo uma descrição detalhada e materiais necessários.</br>
Dados Necessários: Descrição do Projeto, Materiais do Projeto.</br>
Usuários: Participantes.

**RF004:** Avaliação de Projetos

Descrição: O sistema deve permitir que um painel de jurados avalie os projetos com base em critérios predefinidos, atribuindo uma pontuação a cada projeto.</br>
Dados Necessários: Critérios de Avaliação.</br>
Usuários: Jurados.

**RF005:** Anúncio de Vencedores

Descrição: Após a avaliação, o sistema deve anunciar automaticamente as equipes vencedoras com base nas pontuações atribuídas pelos jurados.</br>
Dados Necessários: Pontuações dos Projetos.</br>
Usuários: Organizadores.

**RF006:** Feedback dos Participantes

Descrição: Os participantes devem poder fornecer feedback sobre o evento e as equipes, contribuindo para a melhoria contínua.</br>
Dados Necessários: Comentários, Avaliação do Evento.</br>
Usuários: Participantes.

**RF007:** Relatórios Estatísticos

Descrição: O sistema deve gerar relatórios estatísticos após cada hackathon, fornecendo insights sobre o desempenho das equipes, participação e feedback recebido.</br>
Dados Necessários: Dados de Participação, Pontuações dos Projetos.</br>
Usuários: Organizadores, Analistas.

**RF008:** Comunicação Automática

Descrição: O sistema deve enviar automaticamente e-mails e notificações para os participantes, informando sobre datas importantes, atualizações e resultados.</br>
Dados Necessários: Informações do Evento, Resultados.</br>
Usuários: Participantes, Organizadores.

# Requisitos não funcionais

- Segurança:

**R.N.F. 01:** Garantir a confidencialidade dos dados sensíveis por meio de criptografia forte. </br>
**R.N.F. 02:** Implementar autenticação e autorização robustas, com monitoramento constante.

- Atuação:

**R.N.F. 03:** Implementar estratégias de cache para redução da carga no servidor.

- Escalabilidade:

**R.N.F. 04:** Capacidade de suportar aumento de 50% no número de usuários simultâneos.

- Disponibilidade:

**R.N.F. 05:** Implementar monitoramento proativo para rápida resolução de problemas.

- Manutenção:

**R.N.F. 06:** Manter documentação do código atualizada para futuras atualizações.

- Portabilidade:

**R.N.F. 07:** Compatibilidade com os navegadores mais recentes (Chrome, Firefox, Safari) e dispositivos móveis (iOS, Android). </br>
**R.N.F. 08:** Interface responsiva para diferentes tamanhos de tela.

- Usabilidade:

**R.N.F. 09:** Interface intuitiva, com feedback claro e mensagens de erro compreensíveis. </br>
**R.N.F. 10:** Conduzir testes de usabilidade com usuários reais.

- Compatibilidade:

**R.N.F. 11:** Compatibilidade com sistemas operacionais Windows, MacOS e Linux. </br>
**R.N.F. 12:** Garantir compatibilidade com versões mais recentes de navegadores e dispositivos.

- Conformidade:

**R.N.F. 13:** Implementar Swagger para documentação eficiente da API.

- Integração:

**R.N.F. 14:** Utilizar Axios para requisições HTTP assíncronas no frontend web. </br> 
**R.N.F. 15:** Integrar frontend mobile em React Native eficazmente com o backend Django. </br>
**R.N.F. 16:** Assegurar integração correta com bancos de dados MySQL e PostgreSQL. </br>

- Hospedagem:

**R.N.F. 17:** Utilizar ferramenta Flow para hospedagem do backend Django, garantindo infraestrutura confiável e escalável.

# Diagrama de Classe

<img src="img/Modelagem-Hackathon-V3.png">

# Sobre o Projetos

O (nome do projeto) contém três projetos diferentes:

1. `frontend-mobile-hackathon`: Um projeto front-end em React Native.
2. `frontend-web-hackathon`: Um projeto front-end em Vue.js.
3. `back-hackathon`: Um projeto back-end em Django REST framework (DRF) com PDM.
4. `documentacao-hackathon`: Documentação do Projeto.

# Padronização de Commits

Este projeto segue os devidos padrões de Commit:

```bash
    <tipo>(<escopo>): <mensagem>
```

- Onde:

  - **tipo**: descreve a natureza do commit (por exemplo, feat para uma nova funcionalidade, fix para correção de bugs, docs para documentação e create para criação de projeto).
  - **escopo**: opcional, refere-se à parte do projeto afetada pela mudança.
  - **mensagem**: é uma descrição concisa e clara da alteração.

- Alguns exemplos de padronização dos commits:

  **Criando projeto ou arquivo:**

```bash
    git commit -m "create(main): criação da main"
```

  **Adicionando uma nova funcionalidade:**

```bash
    git commit -m "feat(auth): adiciona autenticação de usuário"
```

**Corrigindo um bug:**

```bash
    git commit -m "fix(nav): corrige problema de navegação no menu"
```

**Atualizando a documentação:**

```bash
    git commit -m "docs(readme): atualiza instruções de instalação"
```

**Refatorando código:**

```bash
    git commit -m "refactor(utils): otimiza função de manipulação de strings"
```

**Removendo Arquivo:**

```bash
    git commit -m "delete(src): deletando arquivos"
```

# Comandos Úteis e Plugins

**Comandos Vue:**

- Tutoriais: [Vue Aula eduardo](https://eduardo-da-silva.github.io/aula-desenvolvimento-web/intro/criar-aplicacao-vuejs.html)
- Criar o projeto: "npm init vue@latest ."
- Instalar dependências:"npm install"
-Rodar o Projeto:"npm run dev"

**Comandos React:**

- Tutoriais: [React Aula eduardo](https://eduardo-da-silva.github.io/aula-desenvolvimento-mobile/)
- Criar o projeto: "npx create-expo-app Hackathon ."
- Instalar dependencias:"npm install"
- Rodar o Projeto:"npm run start"

**Comandos Django:**

**Plugins:**
