
# CFObras - Sistema de Gestão de Obras

## Visão Geral
O **CFObras** é uma solução completa para o gerenciamento eficiente de obras, que oferece uma visão detalhada do progresso de projetos de construção. O sistema foi projetado para auxiliar tanto na gestão de recursos, equipamentos e mão de obra, quanto no acompanhamento de cronogramas, orçamentos e relatórios operacionais. Ele facilita a comunicação entre equipes de campo e os gestores, garantindo que todas as fases das obras sejam controladas em uma única plataforma.

## Principais Funcionalidades
- **Acompanhamento de Obras**: Permite monitorar todas as etapas do projeto, desde a fase inicial até a entrega final.
- **Gestão de Recursos e Equipamentos**: Controle o uso e o estado de equipamentos e materiais, garantindo a otimização dos recursos em campo.
- **Controle de Custos**: Acompanhe em tempo real o orçamento das obras, garantindo transparência e eficiência no uso dos recursos financeiros.
- **Relatórios Detalhados**: Gere relatórios personalizados sobre o progresso das obras, o estado dos equipamentos, a alocação de recursos e muito mais.
- **Comunicação em Tempo Real**: Facilita a comunicação entre gestores e equipes de campo, melhorando a coordenação do trabalho.

## Estrutura do Projeto
O projeto **CFObras** é composto por três frentes principais, cada uma desempenhando um papel essencial para garantir uma experiência completa e integrada:

### 1. **API**
A API do CFObras foi desenvolvida utilizando **NestJS** e serve como o coração do sistema, responsável por gerenciar toda a lógica de negócios, armazenamento de dados e integração com outras partes da solução. A API também oferece endpoints para o gerenciamento de equipamentos, funcionários e informações de cada obra.

### 2. **Aplicativo Móvel (App)**
O aplicativo do CFObras, desenvolvido em **React Native**, foi criado para ser usado diretamente no campo, permitindo que as equipes realizem o registro de atividades, check-ins de equipamentos, atualizações de status das obras e relatórios de problemas em tempo real. A mobilidade do app garante que os dados sejam sincronizados com a API central, dando aos gestores uma visão completa e atualizada da obra.

### 3. **Frontend (Interface Web)**
A interface web do CFObras foi construída utilizando **Vue.js** e serve como o painel administrativo do sistema. Os gestores de obras podem acessar todas as informações críticas, acompanhar o status dos projetos, visualizar relatórios e tomar decisões baseadas em dados. O painel web é a principal ferramenta para gerenciar e visualizar as operações de cada obra, além de permitir uma gestão completa dos recursos.

## Público-Alvo
O CFObras é voltado para construtoras, incorporadoras e empresas que desejam aprimorar a gestão de suas obras, garantindo maior controle sobre o andamento do projeto, a utilização de equipamentos e a alocação de recursos humanos.

## Tecnologias Utilizadas
- **API**: NestJS
- **App Móvel**: React Native
- **Frontend**: Vue.js
- **Banco de Dados**: MongoDB
- **Ferramentas de Integração**: Firebase para notificações push
- **Outros**: Docker para a gestão de ambientes conteinerizados

## Conclusão
O **CFObras** oferece uma solução robusta e integrada para o gerenciamento de obras, permitindo às empresas maior eficiência no uso de recursos, melhor acompanhamento de prazos e uma visão clara do estado atual de cada projeto. Ao utilizar uma abordagem modular com API, aplicativo móvel e uma interface web, o CFObras é uma ferramenta essencial para empresas que buscam modernizar e otimizar seus processos de construção.
