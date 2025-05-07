
# Solicitar laudos

# Descrição

Permite ao ator solicitar um laudo indicado os peritos, o tipo de tema e eventuais questões adicionais.

# Atores

Administrador

# Pré-condições

- O usuário deve estar autenticado no sistema.
- O usuário deve pertencence ao grupo de atores.

# Fluxo Básico - Exibir a tela

O usuário escolhe a opção solicitar laudo.
O sistema exibe uma tela contendo as informações a serem cadastradas.

- Descrição - Campo livre
- Loclaização - A partir do endereço o usuário obtem a geolocalização do laudo.
- Tema - Escolhido via dropbox
- Peritos - Podem ser selecionados um ou mais peritos
- Questões Adicionais - Questões que o usário deseja acrescentar além das herdadas pelo tema

# Fluxos Alternativos

- Pesquisa de Peritos
- Pesquisa de questões

# Fluxos de Exceção

- Não se aplica

# Regras de Negócio

- Não se aplica

# Pós-Condições

- Ao confirmar a inclusão da solicitação o sistema:
  - Registra a solicitação com os campos do formulário;
  - Coloca o status como "cadastrado";
  - Preenche o campo data cadastro com a data de hoje;
  - Preenche o campo data_limite com a data de hoje mais trinta dias corridos;
  - Com base no template escolhido:
    - Cria as perguntas referentes a solicitação;
    - Cria o template de laudo;
    - Copia as citações;

# Pontos de Extensão

- Não se aplica

# Requisitos Especiais

- Não se aplica

# Referências

- Não se aplica

# Observações

- Não se aplica

# Tela

## Tela de Cadastro

[![image](https://img.plantuml.biz/plantuml/svg/hPBFIiGm4CRF5leEmteKPBSggATTT0_2geXxArqOan42QLEIT15idyQ39uy-GL_CIRlKFx32eg5q9iqtdT-4Ro-EfiwZzGwrZwCuUewZ9Ma4IU2CLa9vR5_R5nC-BB2IXYK7dGnuNP8JLlM26aQmROrw-M4VO4avddF1AYGm7a-I5GoAPlZxmWZKVHfwXdXT5SnKAbD_DkDiGwESjyeFPvkkjm-Ex3gCyKxknraJPkONzxqgN4dUM78CiCzxoOGt9YSEixwOQuwJevh1BEMWIbVb88qs5fpoW3bvrgQGmVn9w4fPrf-Tdi0k1SoIpYJFQ0gqMGTsLv7peJtCcL2qRuzAuA-GavqGaxy2VhjWBWVT6sMx7xuQupzL39F2FUerMiZgz08BmMOEc4ttJAcGmUaV)](https://editor.plantuml.com/uml/hPBFIiGm4CRF5leEmteKPBSggATTT0_2geXxArqOan42QLEIT15idyQ39uy-GL_CIRlKFx32eg5q9iqtdT-4Ro-EfiwZzGwrZwCuUewZ9Ma4IU2CLa9vR5_R5nC-BB2IXYK7dGnuNP8JLlM26aQmROrw-M4VO4avddF1AYGm7a-I5GoAPlZxmWZKVHfwXdXT5SnKAbD_DkDiGwESjyeFPvkkjm-Ex3gCyKxknraJPkONzxqgN4dUM78CiCzxoOGt9YSEixwOQuwJevh1BEMWIbVb88qs5fpoW3bvrgQGmVn9w4fPrf-Tdi0k1SoIpYJFQ0gqMGTsLv7peJtCcL2qRuzAuA-GavqGaxy2VhjWBWVT6sMx7xuQupzL39F2FUerMiZgz08BmMOEc4ttJAcGmUaV)

## Tela de Pesquisa

[![image](https://img.plantuml.biz/plantuml/svg/u-JbSYWkIImgAKxCAU7bgkRbKW22WDJYmjBCuiHY2BTQ6qA3sNxvkQar2aeAA419eKOXsgcqE3cnABOMeHXTCmZeeNB1IfGnnJnJW4Q2x09IZeUN7zwQMeofIC74oBX6mIU_A3LN8REWk3HN8IK_9xz8eJYpH24nDxK4v2g5M8NWr9pKvCpylCGYB4POMfWgK6X6BLuVGcMX550Io798pKi1XJW0)](https://editor.plantuml.com/uml/u-JbSYWkIImgAKxCAU7bgkRbKW22WDJYmjBCuiHY2BTQ6qA3sNxvkQar2aeAA419eKOXsgcqE3cnABOMeHXTCmZeeNB1IfGnnJnJW4Q2x09IZeUN7zwQMeofIC74oBX6mIU_A3LN8REWk3HN8IK_9xz8eJYpH24nDxK4v2g5M8NWr9pKvCpylCGYB4POMfWgK6X6BLuVGcMX550Io798pKi1XJW0)

# Aprovação
