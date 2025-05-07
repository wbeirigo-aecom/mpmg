[Voltar](indice.md)

**GUIA DE ELABORAÇÃO DA ESPECIFICAÇÃO**

**DE CASO DE USO BATCH DA SECRETARIA DE FAZENDA/DF**

**Versão 2.1**





|<p>**Guia de elaboração de Especificação**</p><p>` `**de Caso de Uso**</p>|![logo_sef](Aspose.Words.9bc485ef-db94-4188-9622-650610722676.002.jpeg)|
| :-: | :-: |

**Histórico de Revisão**

|**Data**|**Versão**|**Descrição**|**Autor**|**Revisor**|
| :-: | :-: | :-: | :-: | :-: |
|05/09/2013|1\.0|Elaboração do guia com orientações e exemplos|Kelly||
|28/11/2013|2\.0|<p>- Atualização da descrição do histórico de revisão</p><p>- Exclusão da descrição do fluxo de eventos para inclusão no fluxo básico</p><p>- Atualização do índice</p><p>- Inclusão de legenda nas regras de negócio</p><p>- Atualização do exemplo do PE1</p>|Daniela||
|22/04/2014|2\.1|- Alteração do texto do item 12 – Aprovação|Daniela||


<No Histórico de Revisões deverá constar a alteração que foi feita no documento, conforme exemplo abaixo. Deve ser indicada a demanda Oasis que solicitou a alteração. A versão do histórico de revisão só dever ser atualizada no momento da entrega do artefato >


|**Data**|**Versão**|**Descrição**|**Autor**|**Revisor**|
| :-: | :-: | :-: | :-: | :-: |
|15/06/2012|1\.6|<p>Atendimento ao OASIS 9999/2013</p><p>- Alteração da RN11, RN35</p><p>- Inclusão das RNs: 49 a 60;</p><p>- Alteração dos fluxos FA2 e FA4</p><p>- Correção ortográfica;</p><p></p>|xxxx|xxxx|

|||
| :- | -: |

|Confidencial|Secretaria de Estado de Fazenda|Página 13 de 13|
| :-: | :-: | :-: |

|||
| :- | -: |

**Especificação de Caso de Uso**

**Índice**

[*<Nome do Caso de Uso>*	4]()

[1.	Descrição	4]()

[2.	Atores	4]()

[3.	Pré-Condições	4]()

[*3.1*	*<nome da pré-condição>*	4]()

[4.	Fluxo de Eventos	4]()

[*4.1*	Fluxo Básico – *<nome do fluxo básico>*	5]()

[*Fluxo Básico – Envio do acompanhamento dos arquivos*	5]()

[4.2	Fluxos Alternativos	6]()

[4.3	Fluxos de Exceção	6]()

[***FE1. Arquivo gerado vazio***	7]()

[5.	Regras de Negócio	8]()

[*\[RN1\] <layout de arquivo (processamento batch)>*	8]()

[*\[RN2\]. Recuperação das notas de empenho*	10]()

[6.	Pós-Condições	11]()

[7.	Pontos de Extensão	11]()

[8.	Requisitos Especiais	11]()

[9.	Referências	12]()

[10.	Observações	12]()

[11.	Aprovação	13]()





**Especificação de Caso de Uso**
# <a name="_toc372641660"></a>***<Nome do Caso de Uso>***
*<O nome do caso deverá ser no infinitivo>*



1. # <a name="_toc423410238"></a><a name="_toc425054504"></a><a name="_ref63222711"></a><a name="_toc95301808"></a><a name="_toc160275819"></a><a name="_toc423410255"></a><a name="_toc425054514"></a><a name="_toc95301816"></a><a name="_toc372641661"></a>**Descrição**
*<Neste item, deverá ser descrito resumidamente o objetivo geral do caso de uso.>*

`	`*Exemplo:*

<a name="_toc95301809"></a><a name="_toc160275820"></a>		*Este caso de uso permite ao ator realizar a inclusão, alteração, exclusão e consulta de subitens de despesas e grupos de elementos de despesas.*

1. # <a name="_toc372641662"></a>**Atores**
`	`*<Deve ser indicado os atores que tenham interação com o caso de uso. Normalmente, para processamento batch, deve ser colocado “Não se aplica”.>*

`	`*Exemplos:*

`		`*Não se aplica.*


1. # <a name="_toc95301810"></a><a name="_toc160275821"></a><a name="_toc372641663"></a>**Pré-Condições**
   1. ## <a name="_toc372641664"></a>***<nome da pré-condição>***
*<A pré-condição é um estado observável pelo usuário, mas não é o evento que inicia o caso de uso, podendo ser considerada uma premissa. Este tipo de informação somente deve ser incluído na especificação quando for aplicável.>*
\*


`	`*Exemplo:*
##
`		`***3.1 Recebimento de arquivo***

- *Deverá ser verificado se o arquivo esperado do Banco do Brasil foi recepcionado.*
1. # <a name="_toc95301812"></a><a name="_toc160275823"></a><a name="_toc372641665"></a>**Fluxo de Eventos**

   1. ## <a name="_toc95301813"></a><a name="_toc160275824"></a><a name="_toc372641666"></a>**Fluxo Básico – *<nome do fluxo básico>***
      Este caso de uso se inicia <descrição do início do caso de uso>

*<Descrever “quem” e “para quê” o caso de uso é iniciado para realizar a especificação dos*

*Fluxos>*

`	`*Exemplos:*

1. *Este caso de uso se inicia quando o o sistema BFI é alimentado com um novo benefício concedido.*
1. *Este caso de uso inicia-se quando o robô dentro do seu ciclo temporizador identifca que o horário previsto para ínicio do ciclo foi alcançado*

`	`FB1. <Descrição do passo 1 do fluxo básico>. [RN999] [FA1] [FA2] [FA3]

`	`FB2. <Descrição do passo 2>. [RNG999] [FE1] [M99]

FB3.  Finaliza caso de uso.

*< No Fluxo Básico deverá estar descrito todo o processamento que a funcionalidade deverá executar. Deverá ser mencionado no seu conteúdo onde o sistema recupera as informações e quais são elas, o que sistema grava, lista, envia, etc. **Sempre** deve ser mencionado o destino e a origem das informações.>*


`	`*Exemplo:*
## <a name="_toc210531857"></a><a name="_toc286072027"></a>		***<a name="_toc372641667"></a>Fluxo Básico – Envio do acompanhamento dos arquivos***
1. *O sistema recupera as seguintes informações no arquivo de configuração do robô:*
   1. *Pasta onde devem ser gravados os arquivos de LOG;*
   1. *Horário do próximo ciclo;*
   1. *Lista de destinatários de e-mail do LOG de processamento;*
1. *O sistema verifica a existência de arquivos gerados e/ou recebidos desde o último processamento;*
1. *O sistema recupera as seguintes informações do Cadastro de LOG da integração;*
   1. *Nome do arquivo;*
   1. *Indicador do tipo da ação – E Enviado ou R Recebido;*
   1. *Data do envio/recebimento do arquivo;*
   1. *Indicador da situação do processamento do arquivo – P Processado com sucesso ou X Processado com erro.*
1. *O sistema envia e-mail para a lista de destinatários com as seguintes informações:*
   1. *Data do processamento;*
   1. *Quantidade de arquivos recebidos com sucesso;*

***[Relação de arquivos recebidos com sucesso contendo a seguinte informação]***

1. *Nome do arquivo recebido com sucesso;*
1. *Quantidade de arquivos recebidos com erro;*

***[Relação de arquivos recebidos com erro contendo a seguinte informação]***

1. *Nome do arquivo recebido com erro;*
1. *Quantidade de arquivos enviados com sucesso;*

***[Relação de arquivos enviados com sucesso contendo a seguinte informação]***

1. *Nome do arquivo enviado com sucesso;*
1. *Quantidade de arquivos enviados com erro;*

***[Relação de arquivos enviados com erro contendo a seguinte informação]***

1. *Nome do arquivo enviado com erro;*
1. *O caso de uso é encerrado;*

1. ## <a name="_toc95301814"></a><a name="_toc160275825"></a><a name="_toc372641668"></a>**Fluxos Alternativos**

**FA1. <Nome do fluxo alternativo>**

`		`No(s) passo(s) <número do(s) passo(s) do fluxo básico ou do fluxo alternativo onde existe a possibilidade de ocorrência de um fluxo alternativo > do <fluxo básico ou fluxo alternativo>, caso <descrição da condição de ocorrência do fluxo alternativo>, devem ser executados os seguintes passos:

FA.1.1. <Descrição do passo do fluxo alternativo>.

FA.1.2. <Descrição do passo do fluxo alternativo>.

FA.1.3. <Descrição do passo do fluxo alternativo>.

FA.1.4. Finaliza caso de uso ou Retorna ao passo FB?? do Fluxo Básico ou do Fluxo Alternativo FA?? ou Fluxo de Exceção FE??.

*<No fluxo alternativo deverá estar descrito o número dos passos do fluxo básico ou do fluxo alternativo onde existe a possibilidade de ocorrência de um fluxo alternativo>*



1. ## <a name="_toc95301815"></a><a name="_toc160275828"></a><a name="_toc372641669"></a>**Fluxos de Exceção**

**FE1. <Nome do fluxo de exceção>**



FE.1.1. <Descrição do passo do fluxo de exceção>.

FE.1.2. <Descrição do passo do fluxo de exceção>.

FE.1.3. <Descrição do passo do fluxo de exceção>.

FE.1.4. Finaliza caso de uso ou Retorna ao passo FB?? do Fluxo Básico ou do Fluxo Alternativo FA?? ou Fluxo de Exceção FE??.

*< O nome do fluxo deve ser objetivo e representar claramente a exceção;*

*- As exceções devem tratar todos os problemas possíveis e situações que interrompam a execução do caso de uso;*

*- As exceções não necessariamente encerram o caso de uso, mas elas devem impedir a continuidade do fluxo.*

*- Cada exceção ou erro exclusivo podem ser capturados como um Fluxo de Exceção. A principal informação a ser captada é: qual deve ser a experiência dos atores quando ocorrerem exceções?.>*

*Exemplo:*

`		`***<a name="_toc372641670"></a>FE1. Arquivo gerado vazio***

<a name="_ref209862664"></a><a name="_ref211161568"></a>*Este fluxo alternativo se inicia quando: No passo [**FB1**](#_ref226447612) o sistema verifica que não existe nenhuma nota de empenho emitida para a data de execução do processo batch;*

1. *O sistema verifica que não existe nenhuma informação a ser apresentada nos arquivos;*

1. *O sistema gera os arquivos PTBSIGMA, PTBSIGMADE e PTBSIGMAST sem nenhuma informação;*

1. *O caso de uso é finalizado;*





1. # <a name="_toc372641671"></a>**Regras de Negócio**

<a name="rn1"></a><a name="_ref324433688"></a><a name="_ref357756768"></a>*< Neste item, deverão ser colocadas as regras de negócio envolvidas no processamento. O  layout de arquivos de entrada e saída deverão colocados  antes da especificação das regras  de negócios envolvidas na funcionalidade>*

*<Deverá ser seguido o template da tabela de especificação abaixo>*

*<O conteúdo dos campos da tabela estão exemplificados na tabela a seguir>*

*<Deverá ser marcado com “X” a regra  de cada campo. Deverá ser indicado se o campo é:*

`	`***O -** Preenchimento obrigatório*

*< Quando o caso de uso for documentado após a implementação da funcionalidade/sistema, o conteúdo das regras de negócio deverá descrever a origem e destino das informações trabalhadas.>*

`			`*Exemplo:*

`				`*- Informação recuperada do SIGEP - Cadastro do Órgão – Sigla Órgão*

`				`*- Informação incluída no SIGEP - Cadastro de Funcionários – Nome Pessoa*

`				`*- Informação consultada no SIGEP - Cadastro de Histórico de Férias – Data de Fruição Inicial*


## <a name="_toc160275843"></a><a name="_toc372641672"></a>***[RN1] <layout de arquivo (processamento batch)>***

*Exemplo: Gerar Arquivo Nota de Empenho - SIGGO*

||<p>***Legenda***</p><p>***N.** - Número seqüencial do Atributo. **O -** Preenchimento obrigatório* </p>|||||||||
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|***N.***|***Nome do Atributo***|***O*** |***Descrição do Conteúdo***|***Tipo***|***Domínio***|***Tamanho***|***Máscara***|***Regra*** ||
|***Parâmetros de entrada***||||||||||
|[RN1.1]|*Data de execução do processamento*|*X* |*Data que o processamento batch está sendo executado*|*D*|*N/A*|*8*|*DDMMAAAA*|*A data de processamento deve ser a data corrente.*||
|***Header*** ||||||||||
|[RN1.2]|*Data de emissão*|*X* |*Data de geração do arquivo*|*Date*|*N/A*|*8*|*DDMMAAAA*|*A data de emissão deve ser igual a data de execução do processamento*||
|***Detalhe*** ||||||||||
|[RN1.3]|*Código do credor*|*X*|*Código do credor da nota de empenho* |*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.4]|*Código do evento*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.5]|*Código da função*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.6]|*Código da subfunção*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.7]|*Código do programa*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.8]|*Código do projeto*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.9]|*Código do subtítulo*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.10]|*Código da natureza*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.11]|*Modalidade*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.12]|*Número da nota de empenho original*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.13]|*Valor do documento*|||*N*|*N/A*|*15,2*|*N/A*|*N/A*||
|[RN1.14]|*Número do processo*|||*A*|*N/A*|*10*|*N/A*|*N/A*||
|[RN1.15]|*Código da unidade gestora*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.16]|*Código da gestão*|||*N*|*N/A*|*5*|*N/A*|*N/A*||
|[RN1.17]|*...*|||||||*N/A*||
|***Trailler*** ||||||||||
|[RN1.18]|*Qtde de Registros lidos*|||*N*|*N/A*|*10*|*N/A*|||
|[RN1.19]|*Hora da execução*|||*T*|*N/A*||*99:99:99*|||
|<p>**N/A –** Não se Aplica.</p><p>Tipo: **A** – Alfanumérico, **N** – Numérico, **I** – Inteiro, **D** – Decimal, **TS** – TimeStamp, **DT** – Data, **LK** – Link, **BT** – Botão, **SU** - .Seleção Única, **SM** – Seleção Múltipla, **LO** – Lista de Opções.</p>||||||||||
##

## <a name="_ref217294770"></a><a name="_toc372641673"></a>***[RN2]. Recuperação das notas de empenho***
*O sistema recupera informações de notas de empenho emitidas onde a data de emissão seja igual a data de execução do processo batch e o código da natureza da despesa seja igual a 339030  ou 339092 ou 449052 ou 449092.*
1. # <a name="_toc160275845"></a><a name="_toc372641674"></a>**Pós-Condições**

   ***6.1. <nome da pós-condição>***

   `	`<Descrição da pós-condição>.

   *<Pós-condição é a descrição do estado do sistema após a execução do caso de uso.* *A pós-condição de um caso de uso deve ser verdadeira independentemente dos fluxos alternativos que foram executados; não deve ser verdadeira apenas para o fluxo principal. Ao fazer uso deste recurso em casos de uso que possuem pontos de extensão, é preciso garantir que os passos definidos no caso de uso de “extensão” não violem a pós-condição definida. Este tipo de informação somente deve ser incluído na especificação quando for aplicável. A pós-condição deve ser relevante e não o objetivo do caso de uso.>*

*Exemplo:*

*Todos os procedimentos executados pelo robô, além de serem enviados por e-mail, ficarão registrados numa cópia idêntica do arquivo de LOG na pasta indicada no arquivo de configuração do robô.*



1. # <a name="_toc160275847"></a><a name="_toc372641675"></a>**Pontos de Extensão**

   ***PE1. <nome do ponto de extensão>***

   `	`<Descrição do ponto de extensão>.

   *<Nos relacionamentos entre casos de uso com estereótipo <<extensão>>, caso este caso de uso seja a*

   *“base”, indicar a existência de pontos de extensão nesta seção.>*

   `	`*Exemplo:*

   `		`***PE1.  Ativação do Registro de Ponto***

`	`*No passo 5 do FA6, caso o Configurador do Ponto Eletrônico solicita a ativação dos registros de ponto vinculados a Norma do Ponto Eletrônico, deve-se extender o Caso de Uso “Manter Versão do Registro de Ponto” e retorna ao passo 6 do FA6.*


1. # <a name="_toc160275849"></a><a name="_toc372641676"></a>**Requisitos Especiais**

   `	`***8.1. <nome do requisito especial>***
   ***

   ***
   `	`<Descrição do requisito especial>.

   *<Normalmente, um requisito especial é um requisito não funcional que é específico de um caso de uso, mas que não é especificado, de maneira fácil ou natural, no texto do fluxo de eventos do caso de uso. Entre os exemplos de requisitos especiais estão incluídos requisitos legais e reguladores, padrões de aplicativo e atributos de qualidade do sistema a ser criado incluindo requisitos de usabilidade, confiabilidade, desempenho ou suportabilidade. Além disso, outros requisitos — como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design — também podem ser informados.>*

*Exemplos:*

***8.1. Nível de Segurança***

*As informações deste caso de uso possuem nível se segurança #20 – Confidencial.*

***8.2. Disponibilidade em ambiente***

*O caso de uso deve estar disponível no ambiente Intranet.*

***8.3. Registro da operação***

*O sistema deve registrar a operação e gravar informação para auditoria (log).*

***8.4. Desempenho***

*O tempo de resposta máxima para emissão do relatório é de 8 segundos.*


1. # <a name="_toc160275850"></a><a name="_toc372641677"></a>**Referências**

   *<As referências são todos os documentos mencionados em qualquer outra parte desta **Especificação de Caso de Uso**>*

   - Documento de visão (SEFDF\_SISGEPAT\_GRS\_DVS)

   - Lista de Mensagens (SEFDF\_SISGEPAT\_GRS\_MSI)

   - Regra de Negócio Geral (SEFDF\_SISGEPAT\_GRS\_RNG)

   - ...

1. # <a name="_toc160275851"></a><a name="_toc372641678"></a>**Observações**
   *<Este item do documento poderá ser usado para explicitar outras informações úteis ao desenvolvimento, teste ou implementação do caso de uso, mas que não devem estar inclusos nos fluxos de eventos*
1. # <a name="_toc150855230"></a><a name="_toc67979871"></a><a name="_toc153848494"></a>**<a name="_toc372641679"></a>Aprovação**
Este documento foi elaborado pela Cast Informática e apresentado ao gestor técnico para conferência e possíveis alterações. Considero que o mesmo está finalizado e pode ser homologado.

Brasília, <dia> de <mês> de <ano>.



**<nome do gestor operacional>**

Subsecretaria <nome da subsecretaria>

Gestor Operacional do <nome do sistema>



**<nome do gestor técnico>**

Subsecretaria <nome da subsecretaria>

Gestor Técnico do <nome do sistema>



#
[Voltar](indice.md)