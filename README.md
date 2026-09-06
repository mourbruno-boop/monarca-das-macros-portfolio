# Monarca das Macros

Estudo de caso de um aplicativo desktop para configurar e gerenciar rotinas automatizadas com interface visual, persistência de configurações e motor de execução em Lua.

> Este repositório apresenta a arquitetura, o processo de desenvolvimento e os resultados do projeto. O código comercial, as rotinas completas e os dados específicos dos clientes não são publicados.

![Painel do Monarca das Macros](assets/painel-monarca-das-macros.png)

## Visão geral

O Monarca das Macros nasceu da necessidade de transformar rotinas longas e difíceis de configurar em um fluxo visual mais simples. Antes do aplicativo, cada alteração exigia editar diretamente sequências extensas da automação. A interface passou a centralizar escolhas, validar opções e gerar a configuração utilizada pelo motor em Lua.

O projeto é utilizado em situações reais e evolui a partir de testes, relatos dos usuários e correções realizadas remotamente.

## Minha atuação

- Levantamento das necessidades dos usuários e transformação delas em regras de execução.
- Modelagem de fluxos com etapas, condições, repetições, prioridades e rotas alternativas.
- Desenvolvimento e manutenção de rotinas em Lua para o Smart Macro.
- Criação assistida por IA de uma aplicação desktop com Electron, JavaScript, HTML e CSS.
- Integração entre o aplicativo, arquivos `.cfg` e o motor da automação.
- Testes, diagnóstico de falhas, correções e suporte remoto aos usuários.
- Empacotamento do aplicativo para instalação no Windows.

## Funcionalidades demonstradas

- Configuração de diferentes modos de execução.
- Seleção de slots, teclas, inventário e opções de navegação.
- Organização das ações por categorias.
- Configuração individual de dezenas de etapas do fluxo.
- Tratamento de interrupções e escolha da ação de recuperação.
- Persistência das preferências em arquivo externo.
- Notificações visuais e indicadores do estado da configuração.
- Interface em português voltada a usuários não técnicos.

## Tecnologias e conceitos

| Área | Tecnologias e conceitos |
| --- | --- |
| Aplicativo desktop | Electron, JavaScript, HTML e CSS |
| Motor de automação | Lua e comandos do Smart Macro |
| Configuração | Leitura e gravação de arquivos `.cfg` |
| Distribuição | Aplicativo Windows e instalador NSIS |
| Lógica | Condições, loops, estados, prioridades e recuperação de fluxo |
| Processo | Testes com usuários, depuração, suporte remoto e melhoria contínua |

## Desafios solucionados

### Sincronização entre interface e automação

O aplicativo precisava salvar a configuração no arquivo correto mesmo quando o usuário fechava e abria novamente o programa. A solução incluiu identificar a configuração ativa e manter uma referência para que o motor em Lua carregasse o último arquivo utilizado.

### Fluxos configuráveis

A automação possui dezenas de momentos e comportamentos diferentes. A interface organiza essas escolhas sem exigir que o usuário modifique o código diretamente.

### Recuperação após interrupções

Foram adicionadas regras para detectar interrupções da execução e permitir que o usuário escolha entre retomar a rota ou finalizar o fluxo.

### Evolução sem quebrar configurações existentes

Novas opções foram adicionadas preservando funções anteriores utilizadas pelos clientes, reduzindo o risco de regressões.

## Competências demonstradas

- Raciocínio lógico aplicado a problemas reais.
- Automação de tarefas e criação de macros complexas.
- Tradução de necessidades do usuário em requisitos técnicos.
- Investigação e correção de erros em Lua, JavaScript e Windows.
- Desenvolvimento iterativo com auxílio de inteligência artificial.
- Comunicação com clientes e suporte técnico remoto.

## Privacidade e propriedade intelectual

Este estudo de caso não inclui o código comercial, credenciais, identificadores internos, arquivos de clientes nem rotinas completas de execução. Uma demonstração genérica poderá ser adicionada futuramente para exemplificar a arquitetura sem revelar a implementação protegida.

## Autor

Bruno Francisco de Souza Moura  
São Paulo, SP  
[LinkedIn](https://www.linkedin.com/in/bfsmoura)

