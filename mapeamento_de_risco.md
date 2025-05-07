[Voltar](indice.md)

# Mapeamento de Risco

## Demanda por recursos de disco ao longo da operação

A inclusão de anexos nos laudos é um fator de risco tendo em vista o consumo de recursos de disco. Será solicitada uma estimativa do espaço ocupado por laudo, com os dados em mãos, podemos projetar a capacidade em disco necessária

## Implementação do questionário

O sistema prevê a elaboração de questionários que serão atribuídos a temas, que por sua vez serão respondidos durante a elaboração do laudo.

Estamos sugerindo a criação do questionário através de uma ferramenta de criação de formulários.
O nome da ferramenta é [forms.js](https://bpmn.io/toolkit/form-js/) e será disponibilizada no site, devidamente traduzida em Português do Brasil.

- **Risco**:
  - Realização de testes que comprovem a viabilidade técnica da solução;

## Persistência de vídeo

Um dos requisitos da aplicação é persistir arquivos de vídeos, por serem arquivos de tamanho considerável, os mesmos precisam passar por um processo de otimização. Acreditamos que a melhor forma de armazena-los é utilizando-se do YouTube.

Desta forma, quando o perito, enviar um arquivo de vidéo, ele será enviado para uma conta privada que retornará o link arquivo.

- **Risco**:
  - O upload pelo sistema irá funcionar?
  - Pessoas não autorizadas realmente não terão acesso ao conteúdo?
  - O Youtube prevê um limite de vídeos para contas privadas?
  - Incerteza para medir o esforço de implantação;

## Riscos relacionadoas à funcionalidades ligadas ao laudo

### Revisão gramatical

- O sistema deverá realizar a revisão gramatical do texto final do laudo:
- **Risco**

  - Encontrar uma biblioteca que realize a revisão gramatical para o protuguês do Brasil;
  - Testar a eficácia da funcionalidade;
  - Incerteza para medir o esforço de implantação;

### Substituição dinâmica  a partir de templates

- O sistema prevê a utilização de templates de forma a tornar dinâmica a elaboração de textos.
  O perito poderá altera um template anteriormente criado para o tema escolhido, personalizando o laudo seguindo suas necessidades.
- **Risco**

  - Verificar se a solução é prática do ponto de vista da usabilidade;
  - Incerteza no tempo de definição das variáveis, podendo afetar no esforço

## Formatação do texto dentro das regras da ABNT (Associação Brasileira de Normas Técnicas)

- O sistema prevê que o texto final esteja formatado seguindo as regras da [Norma Técnica Código – ABNT NBR 14724](https://www.normasabnt.org/abnt-nbr-14724/)
- **Risco**

  - Encontrar a biblioteca correta;
  - Validar com a equipe eficiencia da formatação;
  - Incerteza na complexidade da solução e tempo de desenvolvimento.
- Referências:

  - [limarka](https://github.com/abntex/limarka)

[Voltar](indice.md)
