<h1>Estudo Técnico Prelimiar</h1>

- **DFD(s) que compõe(m) a solução de TIC**: Doc. SEI nº 1744124

## 1. Necessidade da contratação

- Comunicação de dados de alta velocidade:
  - (ITEM 1) Entre a secretaria do TRE-PB (STRE) e o Fórum Eleitoral de João Pessoa (Fórum JPA)
    - Para suportar o tráfego de dados das aplicações da Justiça Eleitoral;
    - Para suportar a replicação e espelhamento de todas as máquinas virtuais da solução de virtualização do TRE-PB (Site 1) para o Fórum Eleitoral de João Pessoa (Site 2).
  - (ITEM 2) Entre a secretaria do TRE-PB (STRE) e a Internet
    - Que suporte a necessidade de largura de banda e desempenho atualmente requeridos pelo TRE-PB;
  - (ITEM 3) Para atender a necessidade de **realização de eventos externos à secretaria do TRE-PB, aos Fóruns Eleitoral e às zonas eleitorais**, relacionados ao cumprimento da missão intitutucional do TRE-PB e da sua [carta de serviços ao cidadão](https://www.tre-pb.jus.br/institucional/carta-de-servicos/carta-de-servicos-1), em que se demande a utilização de infraestrutura de TIC, juntamente com a necessidade de comunicação de dados;

## 2. Equipe de planejamento da contratação

- **Membro da Área Demandante**:
  - Matrícula: 30990122
  - Nome Completo: Daniel de Lima Claudino
  - Ramal: 1413
  - E-mail Funcional: daniel.claudino@tre-pb.jus.br
- **Membro da Área Técnica**:
  - Matrícula: 0554
  - Nome Completo: PEDRO DE FIGUEIRÊDO LIMA NETO
  - Ramal: 1338
  - E-mail Funcional: pedro.lima@tre-pb.jus.br
- **Membro da Área Administrativa**:
  - Matrícula: ----
  - Nome Completo: Mário Cezar Delgado Régis
  - Ramal: 1277
  - E-mail Funcional: mario.delgado@tre-pb.jus.br 

## 3. Normativos que disciplinam os serviços ou a aquisição a serem contratados, de acordo com a sua natureza:

- **[Resolução ANATEL nº 750, de 15 de março de 2022](https://informacoes.anatel.gov.br/legislacao/resolucoes/2022/1640-resolucao-750)**
  - Altera o **Regulamento de Serviços de Telecomunicações**, o Regulamento do Serviço Telefônico Fixo Comutado e o Regulamento do Serviço Móvel Pessoal, e substitui itens da Norma do Serviço Móvel Global por Satélite Não-Geoestacionário.
- **[Norma de Distribuição Unificada nº 09 da Energiza (GTD-NRM/Nº144/2021)](https://www.energisa.com.br/Documents/Normas%20t%C3%A9cnicas/NDU%20009%20-%20Crit%C3%A9rios%20para%20Compartilhamento%20de%20Infraestrutura%20da%20Rede%20El%C3%A9trica%20de%20Distribui%C3%A7%C3%A3o%20%20Vers%C3%A3o%206.0.pdf)**
  - Estabelece Critérios para Compartilhamento de Infraestrutura da Rede Elétrica de Distribuição
- **[Resolução ANATEL nº 73, de 25 de novembro de 1998](https://informacoes.anatel.gov.br/legislacao/resolucoes/13-1998/34-resolucao-73)**
  - Dispõe sobre o **Regulamento dos Serviços de Telecomunicações**.
- **[Lei nº 9.472, de 16 de julho de 1997](https://informacoes.anatel.gov.br/legislacao/leis/2-lei-9472)**
  - Dispõe sobre a **organização dos serviços de telecomunicações**, a criação e funcionamento de um órgão regulador e outros aspectos institucionais, nos termos da Emenda Constitucional nº 8, de 1995

## 4. Referência a outros instrumentos de planejamento do órgão ou entidade (se houver):

- **PLANO ESTRATÉGICO INSTITUCIONAL 2021-2026**
  - OE 8: Aperfeiçoar a governança e gestão
    - **PLANO DIRETOR DE TIC 2023-2024**
      - OTIC 6: Promover serviços de infraestrutura e soluções corporativas de TIC 

## 5. Requisitos da contratação

- Descrição detalhada da necessidade, elencando os requisitos necessários ao atendimento da necessidade.
  - (1) Link de fibra óptica dedicado e ponto a ponto para comunicação de dados com velocidade de 1 Gbps entre secretaria do TRE-PB (STRE) e o Fórum Eleitoral de João Pessoa;
  - (2) links (dedicado e compartilhado) para comunicação de dados com velocidade de 1Gbps entre a secretaria do TRE-PB (STRE) e a Internet;
  - (3) links (dedicado e compartilhado) para comunicação de dados com a Internet, com velocidade de, no mínimo, 50Mbps a ser disponibilizado sob demanda do TRE-PB, para realização de eventos externos institucionais em qualquer local de qualquer cidade sede de zona eleitoral da Paraíba, permitida a subcontratação de serviços;
    - Serão contratados 10 unidades do serviço de disponibilização de links (dedicado e compartilhado) para comunicação de dados com a Internet, nos termos expecificados, com duração de 1 a 90 dias, para cada solicitação de disponibilização;

### 5.1. Descrição detalhada da necessidade, elencando os requisitos necessários ao seu atendimento

#### (1) Link de fibra óptica dedicado e ponto a ponto para comunicação de dados com velocidade de 1 Gbps entre <u>secretaria do TRE-PB (STRE)</u> e o <u>Fórum Eleitoral de João Pessoa</u>

- Banda: mínima determinística de 1Gbps (dez gigabit por segundo) para upload e download simultâneo (full-duplex);
- Tecnologia: realizado através do uso de fibras ópticas;
- Disponibilidade: mínima de 99,5%;
- Latência: máximo de 3ms (três milissegundos);
- Perda de pacotes: máxima de 0,5%;
- As fibras ópticas deverão ser compatíveis com os switches do TRE-PB que possuem **transceivers SFP 1000BaseLX LC Duplex1Gbps monomodo e multimodo**;
- O serviço deverá seguir a **Norma de Distribuição Unificada nº 09 da Energiza** de utilização de posteamento urbano da concessionária paraibana de energia elétrica Energisa Paraíba;
- As entradas dos cabos nas 2 (duas) edificações deverão ser subterrâneas, utilizando os dutos já existentes, compartilhando o espaço com cabos de outras operadoras;
- Devem ser efetuadas todas as **identificações necessárias nos cabos externos**, bem como nos **cabos internos** e **nas tampas das caixas subterrâneas**, quando houver, segundo as normas estabelecidas;
- <span style="background-color:yellow">As terminações dos cabos deverão ocorrer em **distribuidores internos ópticos (DIO)**, de responsabilidade da Contratada, a serem instalados nos racks de 19 polegadas existentes nas salas do TRE-PB</span>;
- Os **distribuidores internos ópticos (DIO)** que receberão as pontas dos cabos externos deverão possuir adaptadores ópticos do tipo LC duplex monomodo 9/125;
- Todos os **distribuidores internos ópticos (DIO)** deverão ter identificação clara a qual cabo pertencem;
- Deverá haver correspondência perfeita na sequência numérica das fibras e dos respectivos adaptadores entre cada DIO do mesmo cabo;
- Deverão ser utilizados cabos de fibra óptica homologados pela ANATEL.

#### (2) links (dedicado e compartilhado) para comunicação de dados com velocidade de 1Gbps entre a secretaria do TRE-PB (STRE) e a Internet

- Deverá possuir banda de 1Gbps;
- Deve apresentar simetria na velocidade de download e upload;
- Deve ter garantia mínima de 99% (noventa e nove por cento) da banda (velocidade) contratada, para download e upload;
- Não deve possuir franquia, ou seja, **não deve ter limites ou condições** relativas ao **volume ou tipo de tráfego**;
- Deve possuir SLA (Service Level Agreement) estabelecido de, no mínimo, 99% (noventa e nove por cento) de disponibilidade, **a ser medida mensalmente através de ferramenta da Contratada e cuja informação será encaminhada para o TRE-PB juntamente com os documentos**;
- Disponibilizar meios de aferir a velocidade do link contratado;
- Fornecer o link, obrigatoriamente, por meio terrestre, implementado por meio de fibra óptica;
- Fornecer equipamentos de roteamento com suporte a tunelamento VPN com IPSec e com suporte ao protocolo SNMP versão 2 e 3, com acesso somente leitura ao TRE/PB, para possibilitar monitoramento de forma remota;
- Fornecer equipamentos de roteamento dimensionados para que tenham capacidade de encaminhamento de pacotes IP, em pacotes por segundo, compatíveis com as velocidades dos links conectados, limitando o uso de memória a 70% do total disponível quando da carga máxima da CPU;
- Latência bidirecional máxima de 10 milisegundos;
- Fornecer pelo menos 13 (treze) endereços IP úteis de internet fixos (excluídos os IP's de rede, de broadcast e de gateway), exclusivos e dedicados;
- O link contratado deve suportar todas as aplicações TCP/IP, sem restrição ou moderação por porta ou protocolo;
- O link contratado deve permitir conexões entrantes;
- O link contratado deve obedecer os padrões de qualidade de serviço estabelecidos pela ANATEL.

#### (3) links (dedicado e compartilhado) para comunicação de dados com a Internet, com velocidade de, no mínimo, 50Mbps a ser disponibilizado sob demanda do TRE-PB, para realização de eventos externos institucionais em qualquer local de qualquer cidade sede de zona eleitoral da Paraíba, permitida a subcontratação de serviços

- Requisitos necessários para atendimento da necessidade com padrões mínimos de qualidade e desempenho:
  - Solicitação de **instalação de acesso a internet** para evento do TRE-PB
    - A CONTRATANTE **demandará da CONTRATADA a instalação de acesso a Internet** em qualquer local dos municípios do ANEXO II deste estudo técnico preliminar;
      - O prazo para **instalação de acesso a internet** no local indicado pela CONTRATANTE e início da utilização dos serviços pela CONTRATADA será de <span style="background-color:tomato"><u>**até 15 dias corridos**</u></span>;
      - A CONTRATANTE indicará o **período de utilização do acesso a internet**
      - A CONTRATANTE pagará a CONTRATADA por evento de contratação, por período não inferior a 30 dias em cada evento que demande a instalação (<span style="background-color:tomato">**COMO ACERTAR O PAGAMENTO ?**</span>)
  
  - <span style="background-color:tomato">Esses limites de velocidade serão suficientes para o uso que pretende-se fazer do serviço de acesso a internet ?</span>
    - <span style="background-color:yellow">O links (dedicado e compartilhado) para comunicação de dados com a Internet deve possuir **Velocidade nominal de, no mínimo, download de 50Mbps**, com possibilidade de upgrade desta velocidade, durante a vigência do contrato;</span>
    - <span style="background-color:yellow">A **velocidade de upload** deve ser de, pelo menos, 10% da capacidade nominal de download;</span>
    - Velocidade mínima de 20% da velocidade nominal; 
  - Acesso deve ser obrigatoriamente fornecido através de **par-metálico** ou **fibra óptica**; 
  - <span style="background-color:yellow">**Acesso bidirecional e Acesso assimétrico**</span>; 
  - A CONTRATANTE **não terá qualquer tipo de limitação** quanto a quantidade de dados e/ou tipo de conteúdo da informação trafegada; 
  - <span style="background-color:tomato">**Fornecimento mínimo de 1 endereços IP (V4) fixo ou variável por acesso**</span>
  - Prazo médio de indisponibilidade dos circuitos de 72 horas;
  - Possibilidade de utilização de provedores de conteúdo por acesso;
  - A subcontratação de empresas locais para provimento de acesso a internet é permitida
    - Qualquer questão e/ou problema referente à prestação de serviços de internet será tratado exclusiva e obrigatoriamente com a CONTRATADA, devendo se responsabilizar pelos serviços prestados por eventuais empresas subcontratadas para prestação de serviço de internet sem nenhum custo adicional para a CONTRATANTE.

- Instalação:
  - A CONTRATANTE disponibilizará os seguintes recursos para instalação do(s) equipamento(s) a infraestrutura: 
  - Tomada elétrica tripolar com tensão estabilizada 110 ou 220V; 
  - Tubulação (dutos) desobstruída com fio guia; 
  - Toda a infraestrutura externa para a instalação, ativação e equipamentos (Cabos, equipamentos, conectores, etc.) do acesso a Internet banda larga não deverá possuir qualquer ônus para a CONTRATANTE. 


- Roteador:
  - O modem ou roteador será fornecido pela CONTRATADA com suporte para instalação e configuração; 
  - A configuração será executada para que a rede de computadores da CONTRATANTE possua acesso a internet; 
  - Deve possuir a quantidade mínima necessária de memória que atenda a velocidade e funcionalidades deste item, em conformidade com as recomendações do fabricante; 
  - Possuir 1 (um) porta de LAN a 10/100/1000 Mbps que seja compatível com o padrão IEEE 802.3 e tais portas deverão ser fornecidas no padrão RJ-45; 
  - Responder por todas as normas definidas pela Agência Nacional de Telecomunicações – ANATEL.


- Suporte
  - A CONTRATADA deverá prestar suporte técnico relativo ao serviço contratado, fornecendo meios para que o CONTRATANTE possa realizar abertura e acompanhamento de chamados técnicos através de Central de Atendimento 0800 ou Sistema Web;
  - O suporte técnico deve operar no regime 24x7x365 (ininterrupto) exclusivo para atendimento de clientes de comunicações de dados;
  - É de exclusiva responsabilidade da CONTRATADA prover e manter a infraestrutura de comunicação de dados necessária para garantir a execução ininterrupta dos serviços ora contratados, sem quaisquer ônus para o CONTRATANTE.
  - Quaisquer custos relativos a manutenção e suporte do serviço, seja referente a equipamentos e insumos ou referente a despesas com pessoal técnico correrão por conta da CONTRATADA.

### 5.2. Justificativa para Tipo de serviço Continuado

- Para as **necessidades 01 e 02** do **item 1** deste documento:
  - Nos termos do [inciso XV, do art. 6º da lei 14.1333/2021](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14133.htm#art6xv), os **itens 01 e 02** deste estudo preliminar caracterizam-se como **serviços continuos** haja vista tratar-se da necessidade de contratação de serviços pela Administração Pública para a **manutenção da atividade administrativa**, decorrentes de **necessidades permanentes ou prolongadas**;
- Para as **necessidade 03** do **item 1** deste documento:
  - Trata-se de necessidade do Tribunal para eventual realização de evento externo relacionado ao cumprimento de sua  missão institucional e sua carta de serviços ao cidadão, <u>**não sendo, dessa forma, enquadrado como de natureza continuada.**</u>

### 5.3 Duração inicial do contrato

- Os links de Comunicação de Dados do TRE-PB são essenciais para todos os demais ativos de TIC que suportam serviços essenciais a realização da missão institucional do TRE-PB;
- Trata-se de um ativo de TIC sensível para o trabalho de todos os servidores e a prestação de serviços a população;
- Conforme evidencia-se no "ANEXO I - Links de Comunicação de Dados Atual do TRE-PB", as necessidades 01 e 02 deste estudo técnico preliminar referem-se atualmente aos links 
  - Entre STRE e o Fórum JPA
    - Relacionado com o Contrato TRE-PB nº 30/2019 com vencimento no mês de julho/2024
  - Entre STRE e a Internet
    - Relacionado com o Contrato TRE-PB nº 38/2019 com vencimento no mês de setembro/2024
- Ambos os contratos, em especial o Contrato TRE-PB nº 30/2019, tem seus vencimentos para meses muito próximos ao início início do ano 

- Para a **necessidade 01** do **item 1** deste documento:
  - A duração inicial do contrato será de 15 meses;
    - Justificativa: 
      -   
      - Por tratar-se de um recurso de TIC sensível
- Para a **necessidade 02** do **item 1** deste documento:
- Para a **necessidade 03** do **item 1** deste documento:
vi) Avaliar a duração inicial do contrato de prestação de serviços de natureza continuada, que poderá, excepcionalmente, ser superior a 12 meses, e justificar a decisão;

vii) Identificar a necessidade de a Contratada promover a transição contratual com transferência de conhecimento, tecnologia e técnicas empregadas;

viii) Observar, como requisito normativo, a necessidade de alinhamento com a Instrução Normativa nº 06/2022 - TRE/PB, a qual dispõe sobre a configuração segura de ativos de TIC deste Regional e

ix) Elencar, como requisito de segurança e privacidade, nos casos em que acontece acesso à informações sigilosas ou restritas do TRE-PB, a necessidade de assinatura, pelo representante da contratada, de Termo de Responsabilidade e Confidencialidade das Informações do Tribunal Regional Eleitoral da Paraíba, e a necessidade de assinatura, pelos empregados da contratada com acesso à informações sigilosas ou restritas do TRE-PB, da Declaração de Ciência do Termo de Responsabilidade e Confidencialidade das Informações deste Tribunal, nos termos da Portaria nº 280/2023 -TRE-PB/PTRE/ASPRE (Publicada na BAE em 12/09/2023).


## Anexo I - Links de Comunicação de Dados Atual do TRE-PB

### Figura: LINKS DE COMUNICAÇÃO DE DADOS DO TRE-PB

<p align="center">

![](./figuras/TRE-PB-STIC-COINF-SEINF-REDES%20DE%20COMUNICAÇÃO%20DE%20DADOS%20DO%20TRE-PB.png)

</p>

## Anexo II - Cidades, Microregiões e Mesoregiões da Paraíba

- <u>**MESORREGIÃO DO SERTÃO PARAIBANO**</u>
  - Microrregião de Catolé do Rocha
    - BELÉM DO BREJO DO CRUZ
    - BOM SUCESSO
    - BREJO DO CRUZ
    - BREJO DOS SANTOS
    - CATOLÉ DO ROCHA
    - JERICÓ
    - LAGOA
    - MATO GROSSO
    - RIACHO DOS CAVALOS
    - SÃO BENTO
    - SÃO JOSÉ DO BREJO DO CRUZ
  - Microrregião de Cajazeiras
    - BERNARDINO BATISTA
    - BOM JESUS
    - BONITO DE SANTA FÉ
    - CACHOEIRA DOS ÍNDIOS
    - CAJAZEIRAS
    - CARRAPATEIRA
    - MONTE HOREBE
    - POÇO DANTAS
    - POÇO JOSÉ DE MOURA
    - SANTA HELENA
    - SANTARÉM
    - SÃO JOÃO DO RIO DO PEIXE
    - SÃO JOSÉ DE PIRANHAS
    - TRIUNFO
    - UIRAÚNA
  - Microrregião de Sousa
    - APARECIDA
    - CAJAZEIRINHAS
    - CONDADO
    - LASTRO
    - MALTA
    - MARIZÓPOLIS
    - NAZARÉZINHO
    - PAULISTA
    - POMBAL SANTA CRUZ
    - SÃO BENTINHO
    - SÃO DOMINGOS DE POMBAL
    - SÃO FRANCISCO
    - SÃO JOSÉ DA L. TAPADA
    - SOUSA
    - VIEIRÓPOLIS
    - VISTA SERRANA
  - Microrregião de Patos
    - AREIA DE BARAÚNAS
    - CACIMBA DE AREIA
    - MÃE D'ÁGUA
    - PASSAGEM
    - PATOS
    - QUIXABA
    - SANTA TEREZINHA
    - SÃO JOSÉ DE PIRANHAS
    - SÃO JOSÉ DO BONFIM
  - Microrregião de Piancó
    - AGUIAR
    - CATINGUEIRA
    - COREMAS
    - EMAS
    - IGARACY
    - NOVA OLINDA
    - OLHO D´ÁGUA
    - PIANCÓ
    - SANTANA DOS GARROTES
  - Microrregião de Itaporanga
    - BOA VENTURA
    - CONCEIÇÃO
    - CURRAL VELHO
    - DIAMANTE
    - IBIARA
    - ITAPORANGA
    - PEDRA BRANCA
    - SANTA INÊS
    - SANTANA DE MANGUEIRA
    - SÃO JOSÉ DE CAIANA
    - SERRA GRANDE
  - Microrregião da Serra de Teixeira
    - ÁGUA BRANCA
    - CACIMBAS
    - DESTERRO
    - IMACULADA
    - JURÚ
    - MANAÍRA
    - MATURÉIA
    - PRINCESA ISABEL
    - SÃO JOSÉ DE PRINCESA
    - TAVARES
    - TEIXEIRA
- <u>**MESORREGIÃO DA BORBOREMA**</u>
  - Microrregião do Seridó Ocidental
    - Paraibano
    - JUNCO DO SERIDÓ
    - SALGADINHO
    - SANTA LUZIA
    - SÃO JOSÉ DO SABUGI
    - SÃO MAMEDE
    - VÁRZEA
  - Microrregião do Seridó Oriental
    - Paraibano
    - BARAÚNA
    - CUBATI
    - FREI MARTINHO
    - JUZEIRINHO
    - NOVA PALMEIRA
    - PEDRA LAVRADA
    - PICUÍ
    - SERIDÓ
    - TENÓRIO
  - Microrregião do Cariri Ocidental
    - AMPARO
    - ASSUNÇÃO
    - CAMALAÚ
    - CONGO
    - COXIXOLA
    - LIVRAMENTO
    - MONTEIRO
    - OURO VELHO
    - PARARI
    - PRATA
    - SÃO JOSÉ DO TIGRE
    - SÃO JOSÉ DOS CORDEIROS
    - SÃO SEBASTIÃO DO UMBUZEIRO
    - SERRA BRANCA
    - SUMÉ TAPEROÁ
    - ZABELÊ
  - Microrregião do Cariri Oriental
    - ALCANTIL
    - BARRA DE SANTANA BARRA DE
    - SÃO MIGUEL BOQUEIRÃO
    - CABACEIRAS CARAÚBAS
    - CATURITÉ GURJÃO
    - RIACHO DE SANTO ANTÔNIO SANTO
    - ANDRÉ
    - SÃO DOMINGOS DO CARIRI
    - SÃO JOÃO DO CARIRI
- <u>**MESORREGIÃO DO AGRESTE PARAIBANO**</u>
  - Microrregião do Curimataú
    - Ocidental
    - ALGODÃO DE JANDAÍRA
    - ARARA
    - BARRA DE SANTA ROSA
    - CUITÉ
    - DAMIÃO
    - NOVA FLORESTA
    - OLIVEDOS POCINHOS
    - REMÍGIO SOLEDADE
    - SOSSEGO
  - Microrregião do Curimataú Oriental
    - ARARUNA
    - CACIMBA DE DENTRO
    - CAMPO DE SANTANA
    - CASSERENGUE
    - DONA INÊS
    - RIACHÃO
    - SOLÂNEA
  - Microrregião de Esperança
    - AREIAL
    - ESPERANÇA
    - MONTADAS
    - SÃO SEBASTIÃO DE LAGOA DE ROÇA
  - Microrregião do Brejo Paraibano
    - ALAGOA GRANDE
    - ALAGOA NOVA AREIA
    - BANANEIRAS
    - BORBOREMA
    - MATINHAS PILÕES
    - SERRARIA
  - Microrregião de Guarabira
    - ALAGOINHA ARAÇAGI
    - BELÉM CAIÇARA
    - CUITEGI
    - DUAS ESTRADAS
    - GUARABIRA
    - LAGOA DE DENTRO
    - LOGRADOURO
    - MULUNGU
    - PILOEZINHOS
    - PIRPIRITUBA SERRA
    - DA RAIZ
    - SERTÃOZINHO
  - Microrregião de Campina Grande
    - BOA VISTA
    - CAMPINA GRANDE
    - FAGUNDES
    - LAGOA SECA
    - MASSARANDUBA
    - PUXINANÃ
    - QUEIMADAS
    - SERRA REDONDA
  - Microrregião de Itabaiana
    - CALDAS BRANDÃO
    - GURINHÉM
    - INGÁ
    - ITABAIANA
    - ITATUBA
    - JUAREZ TÁVORA
    - MOGEIRO
    - RIACHÃO DO BACAMARTE
    - SALGADO DE SÃO FÉLIX
  - Microrregião de Umbuzeiro
    - AROEIRAS
    - GADO BRAVO
    - NATUBA
    - SANTA CECÍLIA DE UMBUZEIRO
    - UMBUZEIRO
- <u>**MESORREGIÃO DA MATA PARAIBANA**</u>
  - Microrregião do Litoral Norte
    - BAÍA DA TRAIÇÃO
    - CAPIM
    - CUITÉ DE MAMANGUAPE
    - CURRAL DE CIMA
    - ITAPOROROCA
    - JACARAÚ
    - MAMANGUAPE
    - MARCAÇÃO
    - MATARACA
    - PEDRO RÉGIS
    - RIO TINTO
  - Microrregião de Sapé
    - CRUZ DO ESPÍRITO SANTO
    - JURIPIRANGA
    - MARI
    - PILAR
    - RIACHÃO DO POÇO
    - SÃO JOSÉ DOS RAMOS
    - SÃO MIGUEL DE TAIPU
    - SAPÉ
    - SOBRADO
  - Microrregião de João Pessoa
    - BAYEUX
    - CABEDELO
    - CONDE
    - JOÃO PESSOA
    - LUCENA SANTA RITA
  - Microrregião do Litoral Sul
    - ALHANDRA CAAPORÃ
    - PEDRAS DE FOGO
    - PITIMBÚ