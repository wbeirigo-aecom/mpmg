
<style>
  .img {display: block;
        margin-left: auto;
        margin-right: auto;
        }
</style>

# Editar laudo

# Descrição

Permite ao ator editar o laudo, cadastrando todas as informações necessárias para sua elaboração.

# Atores

Perito

# Pré-condições

- O usuário deve estar autenticado no sistema.
- O laudo deve estar atribúido ao usuário.
- O status do laudo deve estar como (cadastrado/em elaboração/em revisão)

# Fluxo Básico - Exibir a tela

- O usuário escolhe a opção visualizar laudos.
- O sistema exibe uma tela contendo um grid com todos os laudos atribuídos ao usuário.
- O usuário seleciona um laudo que deseja editar;
- O Sistema exibe tela contendo;
  - **Informações sobre o laudo**
  - **Campo com a data de ocorrência do fato** - Preenchimento obrigatório
  - **Responder Questionário** Que permite acessar a tela para resposta de questionário;
  - **Adiciona citações** - Que permite adicionar citações existentes;
  - **Adicionar documentos** - Que direciona à tela de cadastro de documentos;
  - **Adicionar individuos** - Que direciona para a tela de importação da planilha de individuos;
  - **Adicionar questionários PPBEA** - Que direciona a tela para adicionar novos questionários;
  - **Tela de edição de templates** - Que permite a elaboração do laudo com base em substiuição das variáveis.
    - **Botão de correção ortográfica** - Que verifica a ortografia do laudo;
    - **Botão de visualização do laudo** - Que permite a visualização do laudo com as devidas substituiçoes;

[![image](https://img.plantuml.biz/plantuml/svg/lLXVRzis47ytuEz0f40VXCHM9NlBZ22mx3Y6CMTncg9x2Dg05Hc7Y2Ig99KcY_T5zbRiOTY0FkuJ-8ljA5cMP2cnaoQZ3DWaxm_lViSxdUkrhbHOA8azLQ_jINNhqVrwJKyF69uAxAExUWsX7dQlfe970UbpZmlqwk87UDhrsk_0rLooNR4Wn9g9X0pPfbclAQOyYWQ4pV-Q_yaHeSZ34U7rsYN5X0ha3Fh7H_NQ1USAPgTCAkfZJJQXOlxDPHWTJOw6ithDnQ5YF41zFaYPxlPSVPYEe6HV7n8bPqt6tKTa6AFWWWiVW-v_gKH3AZ2JXf4HwT4eJky-6iPO7x6pIcWObctPErPxTGDyK9R12ge9J-mkopoWqXM9TmoZWrmUIEeggYA1C64XaouBfeXwJ6qZIOcMH5aaVKuUDCCmte4ZjSGn5zH7B9GHm1A39vb2sASApO3iL64LIKsu48i0WP2BDT8Fi8fXwcE2fHBnsSqtJRFLj4oh3P9ps2oeFUOpHMD2gscsOyAIbbKzO-vYZ_s6AnsqatVH3ZYf0Og1QVw7fnY44KGnGBvajNQRffsSpp8xThk4uWCMn-44CSaKBqMGtMxPRRlLXYFSx-mL5jks89hG8rWsED-nouMO_nF0jO7eHGPuOukGfkytRs5iRI3XW0QHPgy8_mGFunVk0uP8YrxTZSTM9LT_SgYPSboLTCUVv0hPXYeQQrYUcUr1PEvtSsudjwgpnKb4fKvlyw-2SJGH3408iGTH-p1chyg7ooMKDPPLZXbwIsN8eIhetyT2yQcOVxrWBY-hkZTojn_AOqj5YnGn5PG6-tkltKlgNksZOkxOUtsp_rAAK_dfyld_Pc7b-cEk-rc2Kg1BQ25sFgoFDhXdVQOMbMbTDQm8i16XWM8G4Kbc1JFViJ2DjHawv86Yoran6cTep8AhiiWJqpBFdTuevHfJXfOYZfo9ayskiHTHz6OnkrHATffDUWCrowCDb_kDJw9fjyoVB7itkltocNwfqhRxu_dmvzDKv5iAzKxXAK0zGwFUS91fSv370LINUjvJjAq3qI7C1UImG1aY6o08UPgxaGymS8bmG6-uBANhxmVoQT2D_DYHoUG5m9eS7APRtmsF7k_dtmZDCkMii313ai2pt7l105WYkjaD7WM4NJCIwRUHnzU8Cl836Sx_TXbDx3o5aCeyqcWqoYASarzRxS7nagZ7hrd05vCYxfj2sy-Lh5LiDuPlY5KMmaNqdWMdpF6R0RLIsIUzWVEakwhLWgrHwcBz7bOaqMjGjS5pEYEiHomkQ1J1VGrmkkOuphFTr4hvlPqdooz1NQL0ot_PYre1w0QHi1KtPA67TGTKIHCtdQXBugphOWx1Y_KdtnDbLI9tvxjf2Yui9LZacUDMIlTiNBS9J3UIFkhw-dq_P7mR4QPqUwCfkWGQSJqfT6IfvJWslPFVwdxEUwNIljpFipuSW2Qf9_U6YJy0ScVlcOoobc_PEPTzlFXQo3qxnTur5h68FWuWRS0a_d-YImEY_z3u3m00)](https://editor.plantuml.com/uml/lLXVRzis47ytuEz0f40VXCHM9NlBZ22mx3Y6CMTncg9x2Dg05Hc7Y2Ig99KcY_T5zbRiOTY0FkuJ-8ljA5cMP2cnaoQZ3DWaxm_lViSxdUkrhbHOA8azLQ_jINNhqVrwJKyF69uAxAExUWsX7dQlfe970UbpZmlqwk87UDhrsk_0rLooNR4Wn9g9X0pPfbclAQOyYWQ4pV-Q_yaHeSZ34U7rsYN5X0ha3Fh7H_NQ1USAPgTCAkfZJJQXOlxDPHWTJOw6ithDnQ5YF41zFaYPxlPSVPYEe6HV7n8bPqt6tKTa6AFWWWiVW-v_gKH3AZ2JXf4HwT4eJky-6iPO7x6pIcWObctPErPxTGDyK9R12ge9J-mkopoWqXM9TmoZWrmUIEeggYA1C64XaouBfeXwJ6qZIOcMH5aaVKuUDCCmte4ZjSGn5zH7B9GHm1A39vb2sASApO3iL64LIKsu48i0WP2BDT8Fi8fXwcE2fHBnsSqtJRFLj4oh3P9ps2oeFUOpHMD2gscsOyAIbbKzO-vYZ_s6AnsqatVH3ZYf0Og1QVw7fnY44KGnGBvajNQRffsSpp8xThk4uWCMn-44CSaKBqMGtMxPRRlLXYFSx-mL5jks89hG8rWsED-nouMO_nF0jO7eHGPuOukGfkytRs5iRI3XW0QHPgy8_mGFunVk0uP8YrxTZSTM9LT_SgYPSboLTCUVv0hPXYeQQrYUcUr1PEvtSsudjwgpnKb4fKvlyw-2SJGH3408iGTH-p1chyg7ooMKDPPLZXbwIsN8eIhetyT2yQcOVxrWBY-hkZTojn_AOqj5YnGn5PG6-tkltKlgNksZOkxOUtsp_rAAK_dfyld_Pc7b-cEk-rc2Kg1BQ25sFgoFDhXdVQOMbMbTDQm8i16XWM8G4Kbc1JFViJ2DjHawv86Yoran6cTep8AhiiWJqpBFdTuevHfJXfOYZfo9ayskiHTHz6OnkrHATffDUWCrowCDb_kDJw9fjyoVB7itkltocNwfqhRxu_dmvzDKv5iAzKxXAK0zGwFUS91fSv370LINUjvJjAq3qI7C1UImG1aY6o08UPgxaGymS8bmG6-uBANhxmVoQT2D_DYHoUG5m9eS7APRtmsF7k_dtmZDCkMii313ai2pt7l105WYkjaD7WM4NJCIwRUHnzU8Cl836Sx_TXbDx3o5aCeyqcWqoYASarzRxS7nagZ7hrd05vCYxfj2sy-Lh5LiDuPlY5KMmaNqdWMdpF6R0RLIsIUzWVEakwhLWgrHwcBz7bOaqMjGjS5pEYEiHomkQ1J1VGrmkkOuphFTr4hvlPqdooz1NQL0ot_PYre1w0QHi1KtPA67TGTKIHCtdQXBugphOWx1Y_KdtnDbLI9tvxjf2Yui9LZacUDMIlTiNBS9J3UIFkhw-dq_P7mR4QPqUwCfkWGQSJqfT6IfvJWslPFVwdxEUwNIljpFipuSW2Qf9_U6YJy0ScVlcOoobc_PEPTzlFXQo3qxnTur5h68FWuWRS0a_d-YImEY_z3u3m00)

## Fluxos Alternativos

### Tela de Questionário

- Ao acessar a tela de questionários o sistema exibe as questãoes e permite que o usuário preencha com as respostas.
- O sistema salvar o conteúdo sem que todas as questões sejam preenchidas, eventuais questões sem preencher serão indicadas no grid de questionário.
- Cada questão possui um campo icone [i] que quando clicado exibe detalhes da pergunta

[![image](https://img.plantuml.biz/plantuml/svg/lLNDRjD04BvRyZkCWeJ0jBLhnmX5LLH8AYu9BKeFbQ8qMhpJTbNRQtRNI2NDYt137118I3m3VZ76ZY46Qedmqyt1ZlJzp7upwxMjVMsOCfh51i1WpEOlSzH6o9Gf8MrhJvkh6FksLIA6Wfqhbi32jW2UiEZoNCayvGCPImLtpXxIBxIj9R7SxxHBaMQi9F5CmAxdsPOH9aOu9Y_W2Czhk-9jvNU1ZAE2nmU3mx5jdKbfwDz4Q8D91Jz2LNoA18FnqVYfRKKiAyama0VVE5Ln08jJnncnd4juzkMpuy1UL5RPUn7ds7SSF_23RJzqd1MuN8upH1qfKRmltad7wK4aKusHGPChO5naGaSYFGUCXTa2ZHn86qMk4ydNAZjDmMCgkbGQIOK9Y4pd54CLbXO6M886hWasCSpakWJMSjI899EgHNN8J1N5W76cZQfgzNPTh-lwdX-IOhrLXRnVesEH28CLq7Uzi0Asg8zan6BncjqOmtOpY6sAOeViY5IyYOsW1j6Ce5fJ_KUk5wogyhrUSBDbutLnIbhKOM6aRhQcN47O3SAW6v9jUvm_KOB0fqR3RrAMwzVhLIc7aLIg-9ZIlFLeX3XtayIzebL3wyVE3u_5WyQ6VF8kCsrptsgPid9WxuhqJFORLKrFPW33N6XWkK4GAbTOwuaK56OABp3bPNv_Iu8DISls289_6S4zkB_vRlwCTB8XQVdBIF-_63hpUGUc7adI5tLskoteh8z1vxQTiN46WPdY0xGLqrpDBynqmk9NJCteY4y7B8te5bApPNLfxLCxorlkAm00)](https://editor.plantuml.com/uml/lLNDRjD04BvRyZkCWeJ0jBLhnmX5LLH8AYu9BKeFbQ8qMhpJTbNRQtRNI2NDYt137118I3m3VZ76ZY46Qedmqyt1ZlJzp7upwxMjVMsOCfh51i1WpEOlSzH6o9Gf8MrhJvkh6FksLIA6Wfqhbi32jW2UiEZoNCayvGCPImLtpXxIBxIj9R7SxxHBaMQi9F5CmAxdsPOH9aOu9Y_W2Czhk-9jvNU1ZAE2nmU3mx5jdKbfwDz4Q8D91Jz2LNoA18FnqVYfRKKiAyama0VVE5Ln08jJnncnd4juzkMpuy1UL5RPUn7ds7SSF_23RJzqd1MuN8upH1qfKRmltad7wK4aKusHGPChO5naGaSYFGUCXTa2ZHn86qMk4ydNAZjDmMCgkbGQIOK9Y4pd54CLbXO6M886hWasCSpakWJMSjI899EgHNN8J1N5W76cZQfgzNPTh-lwdX-IOhrLXRnVesEH28CLq7Uzi0Asg8zan6BncjqOmtOpY6sAOeViY5IyYOsW1j6Ce5fJ_KUk5wogyhrUSBDbutLnIbhKOM6aRhQcN47O3SAW6v9jUvm_KOB0fqR3RrAMwzVhLIc7aLIg-9ZIlFLeX3XtayIzebL3wyVE3u_5WyQ6VF8kCsrptsgPid9WxuhqJFORLKrFPW33N6XWkK4GAbTOwuaK56OABp3bPNv_Iu8DISls289_6S4zkB_vRlwCTB8XQVdBIF-_63hpUGUc7adI5tLskoteh8z1vxQTiN46WPdY0xGLqrpDBynqmk9NJCteY4y7B8te5bApPNLfxLCxorlkAm00)

### Tela de pesquisa e cadastro de citações

- Esta tela exibe as citações cadastradas e permite o cadastro de novos registros.

[![image](https://img.plantuml.biz/plantuml/svg/dP7DJiCm3CVlaV8ErdP4OkDZ22I4jfK98L6Oj2FYO2NUY9Os9KaFQEtpSEB84_J5I5hOrEkSW_-syukTPEeyMkzGUu22t4Uf779sw_odfZlEOk5UuSPY1ZlE0EOejXjhobmcHXiBm_LLM1FEwa2DzjXMvGL6I1OApiPZphpocc2vR_5EACd2R96yf9ojZV4XMYddAKEGSQTjleL2I9Vf0sS22wzC3ebP_3FjF02xPvDH1GFesG0gU9sNJg1zYpB1N90EGVr7dNJ-j7DjQdZGZp90yU3WPirNyqFkK8nsUNvHmPEnb84gN1aksZw7Knum8nzRhaYJ23E7fdtsvde2Hy5rR-Qwao4vfLp6d_e5)](https://editor.plantuml.com/uml/dP7DJiCm3CVlaV8ErdP4OkDZ22I4jfK98L6Oj2FYO2NUY9Os9KaFQEtpSEB84_J5I5hOrEkSW_-syukTPEeyMkzGUu22t4Uf779sw_odfZlEOk5UuSPY1ZlE0EOejXjhobmcHXiBm_LLM1FEwa2DzjXMvGL6I1OApiPZphpocc2vR_5EACd2R96yf9ojZV4XMYddAKEGSQTjleL2I9Vf0sS22wzC3ebP_3FjF02xPvDH1GFesG0gU9sNJg1zYpB1N90EGVr7dNJ-j7DjQdZGZp90yU3WPirNyqFkK8nsUNvHmPEnb84gN1aksZw7Knum8nzRhaYJ23E7fdtsvde2Hy5rR-Qwao4vfLp6d_e5)

- Para imagens web, o sistema deverá converter a resolução para **720 DPI** (pontos por polegada), qualidade padrão para web. Isto otimiza a utilização de espaço em disco ao mesmo tempo que garante a qualidade das imagens. Além do tratamento de qualidade, o sistema também fara a estração de metadados do arquivo, extraindo a geolocalização e a data/hora da obtenção da imagem.
- Para vídeos, o sistema realizará de forma automática o upload para o Youtube, retornando o link gerado.

[![image](https://img.plantuml.biz/plantuml/svg/bLJTQjim5But-1qEtPreR5UEnmWbD4kotIHheFkvA4lHB3KJjIrFaakxj2-osrqC1eKzm_9YEtAo9WvPmwGB-yZd-yvtVYpVEp6MQMjOPW6gCbECNp3zfPBNwY9Z5LU-TspiRIQwlkUS1fBDDCjXxdi0BrbwDTEgAdXVPKh3iyldk1FVkqTK-0YxaaN978YN4ewYoFUij9c0TtKuu09O8MwK0QvW5VEpO5new0txfsFVkrJAedKcZHKvSu29q8k7L38OJyQlVIzbfPMgWBuQ_iNK0jThFYLavBZXpUzVXC1nwXHtFcMLw192OngtQ4984qJ8G9XKoyMFnNT5I0TILHYHMc4h3OpBKffK5ZCGcRI7O0Ht6GXPcLpn9bEmJVmM4t6C8wL53h8q5PQdBgAH5bWkBDoXsvbbjZBESKKBM85IwJti0sRhClKPPyRgMdjq54Rja4OqGUPL-bhmxiexaxcqedQaOPJKZdkYZ5JAClcLxInFQxD0BInHW64HjFYMMObDn5aIUWsbBy8eNggZKIT-EdImtLlanOcGLfdj5heL9-quYTi9olXtkNV0ufZYOC1_mEwRvjrIsccgj5xyB71UEpXwd8Tv7jxYGlSruD48TZrgefxxJJOpd6yIx6mAQcZHE8YesuVGQaS1NHhx1bIMoerGldZWIzsO3KpVeodKT39uDVsWD9zkfnmq4jfn6ZJKDsFsbXTF7UjW_U70JSvvjafCVqJpV5XSItnzAXgU1FLLT28AxkwkFm00)](https://editor.plantuml.com/uml/bLJTQjim5But-1qEtPreR5UEnmWbD4kotIHheFkvA4lHB3KJjIrFaakxj2-osrqC1eKzm_9YEtAo9WvPmwGB-yZd-yvtVYpVEp6MQMjOPW6gCbECNp3zfPBNwY9Z5LU-TspiRIQwlkUS1fBDDCjXxdi0BrbwDTEgAdXVPKh3iyldk1FVkqTK-0YxaaN978YN4ewYoFUij9c0TtKuu09O8MwK0QvW5VEpO5new0txfsFVkrJAedKcZHKvSu29q8k7L38OJyQlVIzbfPMgWBuQ_iNK0jThFYLavBZXpUzVXC1nwXHtFcMLw192OngtQ4984qJ8G9XKoyMFnNT5I0TILHYHMc4h3OpBKffK5ZCGcRI7O0Ht6GXPcLpn9bEmJVmM4t6C8wL53h8q5PQdBgAH5bWkBDoXsvbbjZBESKKBM85IwJti0sRhClKPPyRgMdjq54Rja4OqGUPL-bhmxiexaxcqedQaOPJKZdkYZ5JAClcLxInFQxD0BInHW64HjFYMMObDn5aIUWsbBy8eNggZKIT-EdImtLlanOcGLfdj5heL9-quYTi9olXtkNV0ufZYOC1_mEwRvjrIsccgj5xyB71UEpXwd8Tv7jxYGlSruD48TZrgefxxJJOpd6yIx6mAQcZHE8YesuVGQaS1NHhx1bIMoerGldZWIzsO3KpVeodKT39uDVsWD9zkfnmq4jfn6ZJKDsFsbXTF7UjW_U70JSvvjafCVqJpV5XSItnzAXgU1FLLT28AxkwkFm00)

## Upload de Individuos

- Os indivíduos serão enviados via arquivo em Excel (.xlsx), os dados serão armazenados em formato Json, de forma a permitir a exibição em grid independete da quantidade de colunas e nome dos campos.
- O primero campo será o código de referência do animal, e não poderá se repetir dentro do arquivo, o sistema fara a validação, rejeitando arquivos inconsistêntes.

[![image](https://img.plantuml.biz/plantuml/svg/ZLJ1Jjj04BrRyZ-CwAMrY6DiN5KfGj0GLPMW8D6UK44hxuQEi7VDxZg2fln8RrKF5PKuzWlyOvrr7EBGfAeJoTdDcpUpRzwix-qPoxGrBBS0LPahnY-OlgvmeYvoLd7bUpl6tkPYr_SSw03PfMO5J7qFu0tBhYwrgYGVgbnfU3P-IP_Kz-ueglyOTeMoP2w8bmXRKUHx5cqku6EJ3hW0b1mdzGElb06ke4tyMJ0kDEoFXiT7lZTMojBg58qL1NDH9qBN3naoE3evUkjx6IijAWb3DPh7K9MkJe3fEGJ1EpbMkc3rp_gtCF1MQ8Oc26O0zuIBdzFp83XqLGowW228apZfnMbtyswUOnw7IsdcnrdcEH0cqqYG7_J7038bZSYii9K6nh54aw6y196ZtGGZk6CHM9b2yPNb1i47qiGn7Iej2i3IL2HtqnI35bWXB7mbsAbbjZ8EsD81YLaglORrWDb6wI7Zp5ZTr1fjzQFjVXp5AJ7kP2x7G0k-sw9pBD2A1XZtexG1Bh5t-GzLndBymbOAqUjAqICnGaf8GVMtt28vWDn8BNmCZL_resHMLnmDadIfGojRJ5na8RHgoGL9kfsaoNPAATUBsO4dIKokWF-4_wEMuqnfNV-Iv6Xo7N3UBuh-BJrjJFiAEuxUdqtgan5Qu-bEhzmmkBPR9bsl5fWUl1Tq8P0hSWOAAbFLtpKgqABfKtj3k7pj9G5IGMDtgs1qauaSdeStkNdnkijvJ4BCfhPK54fDTfDyNL5sPcYPLvBUH5FV5o159ennQPbnvfVa_UkA4aAfiH2e6Iou0Ufxg2owuZWXw9e1v49Q76F6D1rXeSicp4vCV98yuo9BeScjI3iJHjhGk7QfEPsMMBWouKf1d_IlRGQrhaiITXSRiEBP85kVvUqaw4zT_FHi92T8cmuoP9BqfSNT6lw_lKKxOVEb7tkafBl1_m00)](https://editor.plantuml.com/uml/ZLJ1Jjj04BrRyZ-CwAMrY6DiN5KfGj0GLPMW8D6UK44hxuQEi7VDxZg2fln8RrKF5PKuzWlyOvrr7EBGfAeJoTdDcpUpRzwix-qPoxGrBBS0LPahnY-OlgvmeYvoLd7bUpl6tkPYr_SSw03PfMO5J7qFu0tBhYwrgYGVgbnfU3P-IP_Kz-ueglyOTeMoP2w8bmXRKUHx5cqku6EJ3hW0b1mdzGElb06ke4tyMJ0kDEoFXiT7lZTMojBg58qL1NDH9qBN3naoE3evUkjx6IijAWb3DPh7K9MkJe3fEGJ1EpbMkc3rp_gtCF1MQ8Oc26O0zuIBdzFp83XqLGowW228apZfnMbtyswUOnw7IsdcnrdcEH0cqqYG7_J7038bZSYii9K6nh54aw6y196ZtGGZk6CHM9b2yPNb1i47qiGn7Iej2i3IL2HtqnI35bWXB7mbsAbbjZ8EsD81YLaglORrWDb6wI7Zp5ZTr1fjzQFjVXp5AJ7kP2x7G0k-sw9pBD2A1XZtexG1Bh5t-GzLndBymbOAqUjAqICnGaf8GVMtt28vWDn8BNmCZL_resHMLnmDadIfGojRJ5na8RHgoGL9kfsaoNPAATUBsO4dIKokWF-4_wEMuqnfNV-Iv6Xo7N3UBuh-BJrjJFiAEuxUdqtgan5Qu-bEhzmmkBPR9bsl5fWUl1Tq8P0hSWOAAbFLtpKgqABfKtj3k7pj9G5IGMDtgs1qauaSdeStkNdnkijvJ4BCfhPK54fDTfDyNL5sPcYPLvBUH5FV5o159ennQPbnvfVa_UkA4aAfiH2e6Iou0Ufxg2owuZWXw9e1v49Q76F6D1rXeSicp4vCV98yuo9BeScjI3iJHjhGk7QfEPsMMBWouKf1d_IlRGQrhaiITXSRiEBP85kVvUqaw4zT_FHi92T8cmuoP9BqfSNT6lw_lKKxOVEb7tkafBl1_m00)

## Dados do PPBEA

- O questionário do PPBEA serão alimentados por uma outra externa, e os resultados serão exibidos nesta tela.

## Template

- Responsável pela geração do documento final, utiliza de substituição para permitir a elaboração de documentos flexiveis.
- O template permitirá a inclusão dos seguintes campos de metadadados, estas informações podem ser exibidas na ordem que o usuário desejar e de forma separada para cada grupo de idens citados abaixo:
  - Informações de cabeçalho
  - Dados do questionário
  - Citações
  - Indivíduos
  - Resultado do PPBEA

### Exemplo de preenchimento de laudo

```jinja
Laudo N° {{laudo.numero}}
Descrição: {{laudo.descricao}}

Peritos:
{{perito.1}}
{{perito.2}}

O fato ocorreu em localizacao.municipio no distrito de localização.ditrito no dia de {{fato.ocorrencia}}
O local do ocorrido já foi notícia em vários veículos de comunicação, conforme relacionado abaixo:

1) {{citacao.2393}}
2) {{citacao.3043}}

Diversos orgãos de fiscalização e regulação já se manifetaram quanto a ilegalida desta prática:

1) {{citacao.2393}}
2) {{citacao.3043}}

Abaixo segue a relação de indivíduos que sofreram violência:
{% for individuo em individuos %}
  {{individuo[i]}}
{% end for %}
```

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

# Telas

## Tela principal de edição

# Aprovação
