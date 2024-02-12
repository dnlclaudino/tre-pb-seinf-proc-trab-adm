![center](../figuras/tre-pb-cabecalo-padrao-stic-coinf-seinf.png)

<table align="right" border="0">
  <tr>
    <td align="center" valign="top">
      <a href="./README.md">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones/sumario.png?raw=true" heigh="60" width="60"><br>Sumário<br>desta Fonte
      </a>
    </td>
    <td align="center" valign="top">
      <a href="../README.md">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones/icone-casa2.png?raw=true" heigh="60" width="60"><br>Início deste <br>Repositório
      </a>
    </td>
    <td align="center" valign="top">
        <img src="https://github.com/dnlclaudino/imagens/blob/master/icones-aplicativos/pdf/pdf.png?raw=true" heigh="60" width="60"><br>Baixar em PDF
    </td>
  </tr>
</table><br><br><br><br><br><br><br>

# Processo de Trabalho: Planejar Gestão das Contratações

<center><b>SUMÁRIO</b></center>

<!-- TOC updateonsave:false -->

- [Processo de Trabalho: Planejar Gestão das Contratações](#processo-de-trabalho-planejar-gestão-das-contratações)
  - [1. Identificação do Processo](#1-identificação-do-processo)
  - [2. Delimitação do Processo](#2-delimitação-do-processo)
    - [2.1 Evento Inicial](#21-evento-inicial)
    - [2.2 Resultado](#22-resultado)
    - [2.3 Fornecedor(es)](#23-fornecedores)
    - [2.4. Entradas / Insumos](#24-entradas--insumos)
    - [2.5 Clientes](#25-clientes)
    - [2.6 Saídas / Produtos](#26-saídas--produtos)
  - [3. Etapa / Entrega / Atividade do Processo](#3-etapa--entrega--atividade-do-processo)
  - [4. Identificação de Oportunidade de Melhorias](#4-identificação-de-oportunidade-de-melhorias)
        - [Orientações](#orientações)
  - [5. Modelagem do Processo ( Mapa do Processo )](#5-modelagem-do-processo--mapa-do-processo-)
  - [Metodologia](#metodologia)

<!-- /TOC -->
<!-- /TOC -->

## 1. Identificação do Processo

- **ID do Processo de Trabalho**: <span style="background-color:yellow">PTADM-GA-001</span>
- **Nome do Processo**: <span style="background-color:yellow">Planejar Gestão das Contratações</span>
- **Objetivo do Processo**:
  - <span style="background-color:yellow">**Apresentar** o processo SEI para gestão das Contratações na unidade (SEINF);</span>
  - <span style="background-color:yellow">**Definir** critérios de monitoramento dos respecticos processos de licitação e contratações diretas;</span>
  - <span style="background-color:yellow">**Elaborar** os DFDs das Contratações em seus processos específicos;</span>
  - <span style="background-color:yellow">**Aprovar** os DFDs das Contratações em seus processos específicos;</span>
  - <span style="background-color:yellow">**Identificar** eventuais riscos relacionados a **<u>todos</u> os procedimentos da fase <u>preparatória</u>** dos processos de licitação e contratações diretas</span>
    - Observação: Riscos específicos de cada contratação serão identificados e tratados no âmbito dos seus respectivos processos SEI;</span>
- **Leis e normas aplicáveis ao processo**:
  - **Normas Jurídicas Externas:**
    - <span style="background-color:yellow">**[Lei 14.133/2021](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14133.htm)** - Lei de Licitações e Contratos Administrativos (NLLC);</span>
    - <span style="background-color:yellow">**[Lei Complementar 123/2006](https://www.planalto.gov.br/ccivil_03/leis/lcp/lcp123.htm)** - Institui o Estatuto Nacional da Microempresa e da Empresa de Pequeno Porte, entre outras disposições;</span>
    - <span style="background-color:yellow">**[Lei 9.784/1999](https://www.planalto.gov.br/ccivil_03/leis/l9784.htm)** - Regula o processo administrativo no âmbito da Administração Pública Federal;</span>
    - <span style="background-color:yellow">[Decreto-Lei 4.657/1942](https://www.planalto.gov.br/ccivil_03/decreto-lei/del4657.htm) - Lei de introdução às Normas Brasileiras (LINDB);</span>
    - <span style="background-color:yellow">[Resolução CNJ nº 468/2022](https://1drv.ms/b/s!Au-CrfNP6c0bhqpkiw-zpIXV87Q-nQ?e=MYOyav) - Dispõe sobre **DIRETRIZES** para as contratações de Solução de Tecnologia da Informação e Comunicação pelos órgãos submetidos ao controle administrativo e financeiro do Conselho Nacional de Justiça
  - **Normas Jurídicas Internas:**</span>
    - <span style="background-color:yellow">**[Resolução TSE Nº 23.702/2022](https://www.tse.jus.br/legislacao/compilada/res/2022/resolucao-no-23-702-de-9-de-junho-de-2022)** - Dispõe sobre a Política de Governança das Contratações na Justiça Eleitoral e dá outras providências;</span>
    - <span style="background-color:yellow">**[Resolução TRE-PB nº 14/2022](https://apps.tre-pb.jus.br/normas-portal/doc?tipo=norma&cod=1639&nom=TRE-PB-resolucao-14-2022.pdf)** - Institui a Política de Governança de Contratações do TRE-PB;</span>
    - <span style="background-color:yellow">**[Instrução Normativa TRE-PB nº 01/2018](https://apps.tre-pb.jus.br/normas-portal/doc?tipo=norma&cod=1101&nom=TRE-PB-instrucaonormativa-01-2018.pdf)** - Regulamenta os procedimentos de contratação no âmbito do TRE-PB;</span>
    - <span style="background-color:yellow">**[Portaria TRE-PB nº 321/2023](https://apps.tre-pb.jus.br/normas-portal/doc?tipo=norma&cod=1896&nom=tre-pb-portaria-321-2023.pdf)** - Ratifica os Planos Anuais de Contratação (PACONT 2024) referente às contratações administrativas ordinárias, de TIC e de Eleições no âmbito deste Tribunal para o exercício de 2024;</span>
- **Unidade de gestão do processo**: <span style="background-color:yellow">SEINF</span>
- **Áreas envolvidas**:
  - <span style="background-color:yellow">COINF</span>
  - <span style="background-color:yellow">AGGTIC</span>
  - <span style="background-color:yellow">STIC</span>
  - <span style="background-color:yellow">SAO</span>
- **Unidade de mapeamento do processo**: <span style="background-color:yellow">SEINF</span>
- **Tipo do Processo, Especificação e Classificação por Assuntos – Sistema SEI**
  - **Tipo de processo:** <span style="background-color:yellow">Aquisição de Bens e Serviços: Planejamento de Contratações</span>
  - **Especificação:** <span style="background-color:yellow">Gestão das Contratações (Licitações e Contratações Diretas) na SEINF AAAA (PACONTAAAA)</span>
  - **Classificação por Assuntos:**
    - <span style="background-color:yellow">01.01.02.01 - Processo referente ao monitoramento e avaliação de Gestão</span>
- **Metodologia Adotada:**
    - <span style="background-color:yellow">Para verificar a **metodologia** adotada na elaboração deste mapeamento, consulte a seção "[Metodologia](#metodologia)" no final deste documento.</span>
- **Observações Adicionais:**
    - <span style="background-color:yellow">Atualmente, este processo de trabalho envolve apenas o trabalho a ser realizado a partir de janeiro do ano seguinte a elaboração do PACONT;</span>
    - <span style="background-color:yellow">Idealmente, a **gestão de contratações** deve começar, em tempo hábil, antes da elaboração do **plano anual de contratações (PACONT)**, conforme disposto na <a href="https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14133.htm#art12vii">Lei 14.133/2021, art. 12, VII</a>;</span>

<p style="page-break-before: always;">nova página</p>

## 2. Delimitação do Processo

### 2.1 Evento Inicial

<div style="background-color:yellow">

<b>Exemplos</b>

Este processo de trabalho é iniciado a partir do **evento inicial #1** OU a partir do **evento inicial #2**.

- **Evento Inicial #1:**
  - **Depois:**
    - Aprovação pelo Comitê de Governança de Contratações do **Plano Anual de Contratações (PACONT)**; e
  - **Antes:**
    - Elaboração da **Proposta de Orçamento** para o ano subsequente ao PACONT (veja <a href="https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14133.htm#art12vii">Lei 14.133/2021, art. 12, VII</a>);
- **Evento Inicial #2:**
  - Por determinação da Coordenadoria de Infraestrutura (COINF)


</div>

### 2.2 Resultado

<div style="background-color:yellow">

<b>Exemplos</b>

- Processo SEI de **gestão das contratações** iniciado, contendo:
  - As **diretrizes** para as contratações da SEINF;
  - Os **critérios de monitoramento** das contratações estabelecidos;
  - **Eventuais requisitos adicionais** identificados e caracterizados;
- **Documentos de Formalização de Demandas (DFDs)** iniciados e aprovados em seus processos SEI específicos;
- O **primeiro monitoramento** apresentado à COINF;
- Planejamento das contratações atualizado e comunicado (SEINF/COINF);

</div>

### 2.3 Fornecedor(es)

<div style="background-color:yellow">

<b>Exemplos</b>

- **AGGTIC / STIC**
  - PDTIC 2024/2025
- **COINF**
  - Revisão, ajustes e aprovação dos documentos de planejamento de Contratações (licitações e contratações diretas);
- **SAO**
  - PACONT 2024

</div>

### 2.4. Entradas / Insumos

<div style="background-color:yellow">

<b>Exemplos:</b>

- [Anexo II do PACONT Preliminar ou Definitivo](https://www.tre-pb.jus.br/++theme++justica_eleitoral/pdfjs/web/viewer.html?file=https://www.tre-pb.jus.br/transparencia-e-prestacao-de-contas/gestao-de-contratacoes/planos-de-contratacoes/arquivos/2024/tre-pb-plano-de-contratacoes-de-tic-2024/@@download/file/tre-pb-plano-de-contratacoes-de-tic.pdf) vigente
- [Plano Estratégico Institucional](https://www.tre-pb.jus.br/++theme++justica_eleitoral/pdfjs/web/viewer.html?file=https://www.tre-pb.jus.br/transparencia-e-prestacao-de-contas/planejamento-e-gestao/planejamento-estrategico/arquivos/tre-pb-plano-estrategico-2021-2026/@@download/file/tre-pb-plano-estrategico-2021-2026.pdf) (p. 3)
- [**Plano Diretor de TIC 2023-2024**](https://www.tre-pb.jus.br/++theme++justica_eleitoral/pdfjs/web/viewer.html?file=https://www.tre-pb.jus.br/transparencia-e-prestacao-de-contas/planejamento-e-gestao/planejamento-estrategico/arquivos/tre-pb-pdtic-2023-2024/@@download/file/TRE_PB_PDTIC_2023_2024_v1.pdf)
  - **PDTIC 2024-2025** no **Processo SEI nº** [0009140-88.2023.6.15.8000](https://sei.tre-pb.jus.br/sei/controlador.php?acao=procedimento_trabalhar&id_procedimento=1731776)
- [Planilha de Controle/Aba Plano de Contratações](https://docs.google.com/spreadsheets/d/1zJuztvGnc1ayNyRi5nSrLAkMDc6fnLNd9di6VOnq96w)

</div>

### 2.5 Clientes

<div style="background-color:yellow">

<b>Exemplos</b>

- COINF
- AGGTIC
- STIC
- SAO

</div>

### 2.6 Saídas / Produtos

<div style="background-color:yellow">

<b>Exemplos</b>

- Documento de abertura e apresentação do processo de gestão das Contratações (licitações e/ou contratações diretas);
- Processos SEI específicos dos DFDs iniciados;
- [Planilha de Controle/Aba Plano de Contratações](https://docs.google.com/spreadsheets/d/1zJuztvGnc1ayNyRi5nSrLAkMDc6fnLNd9di6VOnq96w) atualizada;
- Documentos de Formalização de Demanda (DFDs) das contratações;
- **Apresentação do Monitoramento da gestão das Contratações** (em *.pptx ou markdown/marp);
- **Portarias** de designação para membros de **equipe de planejamento de contratação** elaborada e publicada no BAE

</div>

## 3. Etapa / Entrega / Atividade do Processo

|ID|Entrada(s)|Riscos/Controles Associados|Etapa/Entrega/Atividade|Atores|Prazo/Condição|Saídas<br>Produto/Serviço/Capacidade Relacionado|Anotação/Observação|
|:---:|:---|:---|:---|:---|:---|:---|:---|
|-|---|---|---|---|---|---|---|

- **Legenda:**
  - **Atores:**
    - <span style="background-color:yellow">Colaborador da Unidade;</span>
    - <span style="background-color:yellow">Chefe da Unidade;</span>
    - <span style="background-color:yellow">Coordenador;</span>
    - <span style="background-color:yellow">AGGTIC;</span>
    - <span style="background-color:yellow">STIC;</span>
    - <span style="background-color:yellow">SAO;</span>
  - **Papéis:**
    - <b style="font-size:30px">🏃</b>**(E) Executa**: minuta saída da atividade/entrega/etapa para ser analisada e revisada pelo responsável;;
    - <b style="font-size:30px">🕵️</b>**(O) Observa**: Parte interessada que entende haver valor no acompanhamento e na observação da saída da atividade/entrega/etapa;
    - <b style="font-size:30px">🤝</b>**(A) Apoia**: presta informações especializadas adicionais necessárias e/ou essenciais para quem executa, é responsável e aprova a saída da atividade/entrega/etapa;
    - <b style="font-size:30px">👨‍💼</b>**(R) Responsável**: Assina e responsabiliza-se pela saída da atividade/entrega/etapa;
    - <b style="font-size:30px">🤴</b>**(APR) Aprova**: revisa, aprova e responsabiliza-se pela saída da atividade/entrega/etapa;
  - Os **PRAZOS** e/ou **CONDIÇÕES** podem ser:
    - Em dd/mm/yyyy;
    - Entre dd/mm/yyyy e dd/mm/yyyy;
    - Até dd/mm/yyyy;
    - Após dd/mm/yyyy;
    - Antes de NOME-DO-EVENTO;
    - Durante NOME-DO-EVENTO;
    - Após NOME-DO-EVENTO;
    - Uma mistura de DATAS e NOME-DE-EVENTOS;

## 4. Identificação de Oportunidade de Melhorias

|#|Problemas/dificuldades/gargalo|Ideias de melhorias|
|:---:|:---|:---|
|1|-|-|

##### Orientações

- **Problemas/dificuldades/gargalo**: Problemas e dificuldades eventualmente detectados no processo, no âmbito da
unidade no qual o mesmo está sendo mapeado;
- **Ideias de melhorias**: possíveis soluções de melhoria aos problemas e dificuldades eventualmente
encontrados no processo

## 5. Modelagem do Processo ( Mapa do Processo )

- Incluir imagem do BPMN do processo;
- Incluir link para o arquivo ".bpmn";

## Metodologia

- [Metodologia de Gestão de Processos do TRE-PB](https://www.tre-pb.jus.br/++theme++justica_eleitoral/pdfjs/web/viewer.html?file=https://www.tre-pb.jus.br/transparencia-e-prestacao-de-contas/planejamento-e-gestao/gestao-de-processos/arquivos/trepb-metodologia-de-gestao-de-processos/@@download/file/trepb-metodologia-de-gestao-de-processos.pdf)
- [Guia Prático de Gestão de Processos do TRE_PB](https://www.tre-pb.jus.br/++theme++justica_eleitoral/pdfjs/web/viewer.html?file=https://www.tre-pb.jus.br/transparencia-e-prestacao-de-contas/planejamento-e-gestao/gestao-de-processos/arquivos/trepb-guia-pratico-de-gestao-de-processos/@@download/file/trepb-guia-pratico-de-gestao-de-processos.pdf)
  - Formulário de Mapeamento de Processo: Páginas 22 a 26
