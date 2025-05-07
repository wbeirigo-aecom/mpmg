# Sistema de Perícia - MPMG

## Especificação Técnica

## Objetivo

- O objetivo deste documento é aprensetar a especificação técnica do **Sistema de Perícia Animal** solicitado pelo **Ministério Publico do estado de Minas Gerais** (**MPMG**)

## Atores


## Requisitos Funcionais

- **RF001** - Cadastrar e manter questionários
- **RF002** - Cadastrar e manter temas
- **RF003** - Cadastrar e manter peritos
- **RF004** - Cadastrar e manter citações
- **RF005** - Solicitar laudo
- **RF006** - Imprimir check-list
- **RF007** - Editorar laudo
- **RF008** - Alterar data-limite de formalização do laudo
- **RF009** - Visualizar laudo para aprovação
- **RF010** - Formalizar laudos
- **RF011** - Enviar mensagens com laudos não aprovados com data-limite para a aprovação nos próximo **n** dias
- RF012 -  Aplicativo para georeferenciamento
- RF013 -  Integração com bases do IBGE, DataSus, MAPA, SEI, Mendeley
- RF014 -  Dashboard
- RF015 -  Página contendo links úteis
- **RF016** -  Mapa dos locais da perícia
- RF017 -  Campo para anexar aceites recusas,honorário e notas fiscais
- RF018 -  Emissão de nota de recibo de RPA
- RF019 -  Assinatura digital via gov.br
- **RF020** -  Pàgina contendo laudos antigos como referência
- **RF021** -  Padronização do cabeçalho de laudos
- **XXX** Gerar report e configurar Power BI com mapa

### Perfil Administrador

[![](https://img.plantuml.biz/plantuml/svg/TPDDJiCm48NtaNA74SkgbPAKLbqX0XJKHQMAY0DCuw6riEDYkmj070QnOCKfSZ76gGYe6A_Yb_dU_6XyxZnQlzSgJHJTU_06hDniFGXfgVRID6dY7cIpGuiQTbW_u8Og_wG8mdziDehI16jlB9H2oqOwRr7m3HsWq6dIXy5ojRo1bpG1FdVL_BAivd0o6DnUPra-6C08Bb5Wm2qGQ6myMNZSamjLj6zM6dSINBlug4lnduidZJzm4ON7_y4xijB_oZsEufCEhuoIjUIHWiAzC3qpYJApZYaLPs52e4TGKajF8CoHmInca6UTmRMn6fLy_ixQbvfdHrJGnap0WZlRM6m_sdS3jT6mHaSkf5rStCo7SCMrL7itX6MvAeTGpHVyIO8KFVNcntC8scamlqAtNHkqeWyzZOHEG-WITyXP7IXJe-G2C8ox_Qmbzl3qBrpa0LwXiARXlWzjSF4rhgdzGBNb6nqDe-2TUULL5Hf6tOgFpWwh111HYwWwZggJg3gBgNaMLQE-FCoOEktLWr1q3N1dvzG8ViXV)](https://editor.plantuml.com/uml/TPDDJiCm48NtaNA74SkgbPAKLbqX0XJKHQMAY0DCuw6riEDYkmj070QnOCKfSZ76gGYe6A_Yb_dU_6XyxZnQlzSgJHJTU_06hDniFGXfgVRID6dY7cIpGuiQTbW_u8Og_wG8mdziDehI16jlB9H2oqOwRr7m3HsWq6dIXy5ojRo1bpG1FdVL_BAivd0o6DnUPra-6C08Bb5Wm2qGQ6myMNZSamjLj6zM6dSINBlug4lnduidZJzm4ON7_y4xijB_oZsEufCEhuoIjUIHWiAzC3qpYJApZYaLPs52e4TGKajF8CoHmInca6UTmRMn6fLy_ixQbvfdHrJGnap0WZlRM6m_sdS3jT6mHaSkf5rStCo7SCMrL7itX6MvAeTGpHVyIO8KFVNcntC8scamlqAtNHkqeWyzZOHEG-WITyXP7IXJe-G2C8ox_Qmbzl3qBrpa0LwXiARXlWzjSF4rhgdzGBNb6nqDe-2TUULL5Hf6tOgFpWwh111HYwWwZggJg3gBgNaMLQE-FCoOEktLWr1q3N1dvzG8ViXV)

### Perfil Perito

[![](https://img.plantuml.biz/plantuml/svg/RLGzYzj04Eq5-W_3bIOEbedjSnFE62UaE31dadvkjPO7xuVONPjyaF-I8qKWVPgq-cCtAyMw8AzKI3pDUpFpPbPtFg0B9wtoJCbzW631KNK8K9AJ8f0rUUQFP6fqgA56SSHAxi8N9I5-HrCfcMSeWdMmbOwOZnxgzYtF-X2utzw_Xszv1dnzt6tMgzq6RaQZXtUJoPlH2CQmnX9zSEX0WaOJf0D10PjVpH_fRw9e6vjKcBSA7tJjI1Fp3b8Snufyw7dp96_HyZObrneJApoLjgSiafHbI_b4_eIAlbv84Eq1h9qznuf_lgWiKof5qIKsPs85M2df0lPD5iM04x4fnyEgLYGmqFbVmifP9_VIIIC8jJIXprjC4ngpgB5jdYeo2CAonuPBLsIE7fg_GT9B2RC4VH7fQzJrfLqZFtFvA2G5wUCwd3pwLmThh6kU75cUfB7S6Ep92_nFVMXjn6wZ-aQJzsmVb1qrFbcN7blaORlg9MuJ4ilM8--vlN3Y0akgU8CKiCjGsVFhHzVJXsDXR3hfxFani2VErtEpWIf-2glvX4JJcz_HzOlYT99dt_ceyD99ZJ0Ul-r62P1dtMcuO7671yWy4RL8OCjhZ1VZ6fibi8GUUtwD9NAmCz1sTyUEjB-AU3y3)](https://editor.plantuml.com/uml/RLGzYzj04Eq5-W_3bIOEbedjSnFE62UaE31dadvkjPO7xuVONPjyaF-I8qKWVPgq-cCtAyMw8AzKI3pDUpFpPbPtFg0B9wtoJCbzW631KNK8K9AJ8f0rUUQFP6fqgA56SSHAxi8N9I5-HrCfcMSeWdMmbOwOZnxgzYtF-X2utzw_Xszv1dnzt6tMgzq6RaQZXtUJoPlH2CQmnX9zSEX0WaOJf0D10PjVpH_fRw9e6vjKcBSA7tJjI1Fp3b8Snufyw7dp96_HyZObrneJApoLjgSiafHbI_b4_eIAlbv84Eq1h9qznuf_lgWiKof5qIKsPs85M2df0lPD5iM04x4fnyEgLYGmqFbVmifP9_VIIIC8jJIXprjC4ngpgB5jdYeo2CAonuPBLsIE7fg_GT9B2RC4VH7fQzJrfLqZFtFvA2G5wUCwd3pwLmThh6kU75cUfB7S6Ep92_nFVMXjn6wZ-aQJzsmVb1qrFbcN7blaORlg9MuJ4ilM8--vlN3Y0akgU8CKiCjGsVFhHzVJXsDXR3hfxFani2VErtEpWIf-2glvX4JJcz_HzOlYT99dt_ceyD99ZJ0Ul-r62P1dtMcuO7671yWy4RL8OCjhZ1VZ6fibi8GUUtwD9NAmCz1sTyUEjB-AU3y3)




## Funcionalidades não mapeadas

### Aplicativo para groreferenciamento

- Demandaria a utilização de um software livre, que gravaria o andamento e exportaria para o sistema

### Integração com bases do IBGE, DataSus, MAPA, SEI, Medeley

- Precisa detalhar melhor

### Dashboard

- Alternativamente, o sistema pode gerar um arquivo Excel que posteriormente seri interpretado pelo Power BI.
- Tarefas
  - Criar rotina que exporta pa o excel
  - Power BI
    - Criar banco de dados semantico
    - Criar dashboards

### Página contendo links úteis

- Criar funcionalidade mantenho o cadastro de links úteis [Descrição/URL]
- Criar página que exibe os itens cadastrados na página anterior

### Mapa dos locais da perícia

- Ao editar o laudo, o sistema de geolocalizar o local da perícia
- Criar funcionalidade que exibe no mapa os locais de perícia filtrando por (Cidade/Perito/Período de OcorrÇencia/Tema/Status)

### Criação de uma funcionalidade de eventos

Se enventualmente criada, a funcionalidade de eventos poderá ser utilizada para registrar as datas de solicitação, alteração, mudança de data-limite e aprovação.

- Campo para solicitar aumento do prazo de perícia
  - Um evento que solicita ao administrador a alteração, que fica pendente até ele remarcar o evento

- Campo para anexar aceites recusas,honorário e notas fiscais
  - Um evento que anexa documentos

- Emissão de nota de recibo de RPA
  - Uma funcionalidade que emite o RPA e registra na tabelas de evento

### Assinatura digital via gov.br

- Após a formalização o sistema deve aplicar a assinatura no documento oficial

### Pàgina contendo laudos antigos como referência

- Funcionalidade de tema, deve permitir o cadastro de laudos de exemplo
- Página que exibe os laudos e permite filtrar por tema

### Padronização do cabeçalho de laudos

- Funcionalidade que permite criar e editar o template para o cabeçalho do laudo, todos os laudos passam a utilizar o cabeçalho padrão

## Requisitos não funcionais

- Segurança dos dados
- Segurança:
  - Cadastro de usuários e grupos de usuários;
  - Autenticação de dois fatores;
  - Autorização;
- Armazenamento:
  - As mídias exceto vídeo serão armazendas no disco local do ambiente;
  - O sistema utilizará o MinIO, um software gratudo para gerenciamento de arquivos;
  - Os vídeos serão persistidos no Youtube em uma conta privada;
  - As informações transacionais serão persistidas no PostgresSQL;
- Interfaçe visual:
  - Cada tela deve possuir um ícone (i) que ao ser clicado direciona o usuário a uma tela com orientações sobre o funcionamento da tela e como preenche-la corretamente.
  - Mail:
    - O MPMG deverá fornecer um e-mail que será utilizado como remetente das mensagens de alerta.
  - Disponibilixação de certificado digital (SSL) para garantir a segurança das páginas do sistema (https://)
  - Criação de um subdomínio **sistema**.mpmg.br

### Configuração do Host

| Recurso                | Especificação                      |
| ---------------------- | ---------------------------------- |
| VCPUs                  | 8                                  |
| Memória RAM            | 32 GB                              |
| Linguagem              | Python                             |
| Espaço em disco        | 1 TB **(sujeito a confirmação)**   |
| Banco de Dados         | Postgres 17.04                     |
| Acesso à internet      |                      |

### Plataforma

Todas as soluções propostas são OpenSource e sua utilizaçãp no incorrem em custos para o MPMG.

| Serviço                     | Produto                            |
|-----------------------------|------------------------------------|
| Sist.Operacional            | Linux Ubuntu 24.04                 |
| Gerenciamento de Containers | Dokcer 28.0.4                      |
| Linguagem                   | Python                             |
| Framework                   | Fast-API                           |
| Banco de Dados              | Postgres 17.04                     |
| Servidor de identidade      | Keycloak 26.1.3                    |
| Servidor de Arquivos        | MinIO 2025-03-12T18-04-18Z         |
| Servidor WEB                | Nginx nginx-1.26.3                 |
| forms.js                    | [bpmn-io](https://github.com/bpmn-io/form-js) |

## Fatores de risco do projeto

### Demanda por recursos de disco ao longo da operação

A inclusão de anexos nos laudos é um fator de risco tendo em vista o consumo de recursos de disco. Será solicitada uma estimativa do espaço ocupado por laudo, com os dados em mãos, podemos projetar a capacidade em disco necessária

### Implementação do questionário

O sistema prevê a elaboração de questionários, que serão tribuídos a temas, que por sua vez serão respondidos durante a elaboração do laudo.

Estamos sugerindo a criação do questionário através de uma ferramenta de criação de formulários.
O nome da ferramenta é [forms.js](https://bpmn.io/toolkit/form-js/) e será disponibilizada no site, devidamente traduzida em Português do Brasil.

- **Risco**:
  - Realização de testes que comprovem a viabilidade técnica da solução;

### Persistência de vídeo

Um dos requisitos da aplicação é persistir arquivos de vídeos, por serem arquivos de tamanho considerável, os mesmos precisam passar por um processo de otimização. Acreditamos que a melhor forma de armazena-los é utilizando-se do YouTube.

Desta forma, quando o perito, enviar um arquivo de vidéo, ele será enviado para uma conta privada que retornará o link arquivo.

- **Risco**:
  - O upload pelo sistema irá funcionar?
  - Pessoas não autorizadas realmente não terão acesso ao conteúdo?
  - O Youtube prevê um limit de vpideos para contas privadas?
  - Incerteza para medir o esforço de implantação;

### Funcionalidades ligadas ao laudo

#### Revisão gramatical

- O sistema deverá realizar a revisão gramatical do texto final do laudo:

- **Risco**
  - Encontrar uma biblioteca que realize a revisão gramatical para o protuguês do Brasil;
  - Testar a eficácia da funcionalidade;
  - Incerteza para medir o esforço de implantação;

#### Substituição dinâmica  a partir de templates

- O sistema prevê a utilização de templates de forma a tornar dinâmica a elaboração de textos.
O perito poderá altera um template anteriormente criado para o tema escolhido, personalizando o laudo seguindo suas necessidades.

- **Risco**
  - Verificar se a solução é prática do ponto de vista da usabilidade;
  - Incerteza no tempo de definição das variáveis, podendo afetar no esforço

### Formatação do texto dentro das regras da ABNT (Associação Brasileira de Normas Técnicas)

- O sistema prevê que o texto final esteja formatado seguindo as regras da [Norma Técnica Código – ABNT NBR 14724](https://www.normasabnt.org/abnt-nbr-14724/)

- **Risco**
  - Encontrar a biblioteca correta;
  - Validar com a equipe eficiencia da formatação;
  - Incerteza na complexidade da solução e tempo de desenvolvimento.

- Referências:
  - [limarka](https://github.com/abntex/limarka)

## Diagramas

### Componentes

#### **Host**

![aaa](midia/componentes_01.jpeg)

#### **Container**

![aaa](midia/componentes_02.jpeg)

#### **Application**

![aaa](midia/componentes_03.jpeg)

### ***Arquitetura***

![aaa](midia/Arquitetura.jpeg)

## Observações

- Lista de requisitos funcionais
- Gráfico de casos de uso
- Revisar os casos de usos
