# DATA SUS 
Os dados descritos neste DataCard foram retirados do DataSus (Departamento de Informática do Sistema Único de Saúde), plataforma e sistema de informações de saúde mantido pelo Ministério da Saúde do Brasil. Os dados abrangem os nascimentos ocorridos em todo o território nacional em 2022 e incluem informações sobre as características do parto, dos pais e dos recém-nascidos.

#### Link do conjunto de dados
https://s3.sa-east-1.amazonaws.com/ckan.saude.gov.br/SINASC/DNOPEN22.csv
#### Autores do cartão de dados
- **Luís Carlos M. A. Júnior** 
- **Mariana Aparecida Ferreira**
-  **Marco Antonio J. Ticona**

## Autoria
### Publicadores
#### Organização publicadora
Departamento de Informática do Sistema Único de Saúde (DataSUS)

#### Tipos de indústria
- Instituições Médicas
- Intituições acadêmicas

### Proprietários de conjunto de dados
#### Equipe
Nome da equipe: Departamento de Informática do Sistema Único de Saúde
#### Detalhes do contatos
- **Proprietários do conjunto de dados:** CGIAE/DASNT/SVS
- **Website:** https://opendatasus.saude.gov.br/dataset/sistema-de-informacao-sobre-nascidos-vivos-sinasc

## Motivações e Intenções

### Motivações

#### Propósitos

- Análise de dados
- Coleta de dados
- Monitoramento
- Pesquisa em Saúde

#### Domínios de Aplicação

`Machine Learning`, `Classification`, `Nascidos Vivos`, `SUS`.

#### Fatores Motivadores

- Armazenamento de grandes volumes de dados de saúde em bancos de dados seguros
- Utilização dos dados por profissionais de saúde, pesquisadores e o público em geral para pesquisas

### Aplicações

#### Uso do conjunto de dados

- Suporte à tomada de decisão
- Padronização dos dados
- Armazenamento de dados
- Disponibilização de Dados

#### Casos de uso adequados

**Caso de uso adequado:** Estudo utilizando machine learning da relação dos dados coletados pelo SINASC e o peso do recém nascido. https://repositorio.unesp.br/handle/11449/236236

**Caso de uso adequado:** Mortalidade infantil entre os anos de 2000 e 2017 em uma cidade do Sul do Brasil: técnicas de mineração de dados. https://rsdjournal.org/index.php/rsd/article/view/7489

#### Espaço de pesquisa e Problemas

O objetivo da utilização da base de dados é criar um modelo de *machine learning* que seja capaz de estimar a probabilidade de um recém-nascido nascer com alguma anomalia congênita, a partir de informações gerais da mãe, pai e outras informações demográficas.

## Visão geral do conjunto de dados
#### Características do conjunto de dados
Categoria | Data
--- | ---
Formato | text/csv 
Tipo de dados | Dados Tabulares 
Espaço | Bruto 
Criado | 10/Agosto/2023 
Licença | [Creative Commons Atribuição](http://www.opendefinition.org/licenses/cc-by) 
Tamanho do conjunto de dados | 848,4 MB 
Número de Instâncias | 2471519 
Número de campos | 150762659 
Classes rotuladas | 1 
Número de rótulos | 61 

**Tabela 1:** Tabela com as características da base de dados

#### Estatística descritiva
| index | ORIGEM     | CODESTAB            | CODMUNNASC          | LOCNASC              | IDADEMAE            | ESTCIVMAE           | ESCMAE              | CODOCUPMAE          | QTDFILVIVO          | QTDFILMORT           | CODMUNRES          | GESTACAO           | GRAVIDEZ             | PARTO                | CONSULTAS           | DTNASC              | HORANASC            | SEXO                | APGAR1             | APGAR5              | RACACOR             | PESO                | IDANOMAL            | DTCADASTRO          | CODANOMAL | NUMEROLOTE          | VERSAOSIST | DTRECEBIM           | DIFDATA             | OPORT\_DN          | DTRECORIGA          | NATURALMAE         | CODMUNNATU         | CODUFNATU  | ESCMAE2010          | SERIESCMAE          | DTNASCMAE           | RACACORMAE          | QTDGESTANT          | QTDPARTNOR          | QTDPARTCES           | IDADEPAI            | DTULTMENST          | SEMAGESTAC          | TPMETESTIM          | CONSPRENAT         | MESPRENAT           | TPAPRESENT          | STTRABPART          | STCESPARTO          | TPNASCASSI          | TPFUNCRESP         | TPDOCRESP           | DTDECLARAC          | ESCMAEAGR1         | STDNEPIDEM           | STDNNOVA            | CODPAISRES | TPROBSON           | PARIDADE            | KOTELCHUCK         |
| ----- | ---------- | ------------------- | ------------------- | -------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | -------------------- | ------------------ | ------------------ | -------------------- | -------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------ | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | --------- | ------------------- | ---------- | ------------------- | ------------------- | ------------------ | ------------------- | ------------------ | ------------------ | ---------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | -------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------ | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------ | ------------------- | ------------------- | ------------------ | -------------------- | ------------------- | ---------- | ------------------ | ------------------- | ------------------ |
| count | 2471519\.0 | 2448501\.0          | 2471519\.0          | 2471519\.0           | 2471503\.0          | 2460132\.0          | 2457513\.0          | 2278165\.0          | 2423212\.0          | 2397009\.0           | 2471519\.0         | 2444962\.0         | 2468998\.0           | 2469409\.0           | 2465822\.0          | 2471519\.0          | 2469829\.0          | 2471519\.0          | 2444624\.0         | 2444735\.0          | 2414652\.0          | 2471235\.0          | 2446907\.0          | 2471519\.0          | 21802     | 2469935\.0          | 2469909    | 2469794\.0          | 2471519\.0          | 2471519\.0         | 2471519\.0          | 2426801\.0         | 2426801\.0         | 2426801\.0 | 2440176\.0          | 1565561\.0          | 2450759\.0          | 2402913\.0          | 2415044\.0          | 2397250\.0          | 2390397\.0           | 857760\.0           | 1194226\.0          | 2444717\.0          | 2444717\.0          | 2431037\.0         | 2417255\.0          | 2446942\.0          | 2437849\.0          | 2436317\.0          | 2451148\.0          | 2400915\.0         | 2453953\.0          | 2439252\.0          | 2440176\.0         | 2471517\.0           | 2471519\.0          | 2471510\.0 | 2471519\.0         | 2471519\.0          | 2471519\.0         |
| mean  | 1\.0       | 2962668\.4586479645 | 320111\.91146821046 | 1\.029269449273908   | 27\.547548192334787 | 2\.0755081434654725 | 4\.114844153418517  | 700930\.7692256706  | 1\.0352400037635998 | 0\.26908785073397723 | 320022\.072609193  | 4\.877479895393058 | 1\.0233641339523158  | 1\.582327998318626   | 3\.6955518281530457 | 15642141\.901971217 | 1262\.7327325090118 | 1\.4882179744521487 | 8\.414735353984907 | 9\.360270131527548  | 2\.837407212302228  | 3152\.9213623957253 | 2\.048963037826938  | 15648088\.814662157 | NaN       | 20220392\.787815064 | NaN        | 15640034\.015753945 | 29\.416477882630076 | 22\.9033420337857  | 15664306\.743303208 | 830\.9863750674242 | 311373\.5473188778 | NaN        | 3\.1967907232920902 | 3\.811117548278221  | 15704964\.557372635 | 2\.835469282491709  | 1\.283247841447195  | 0\.6702538325164251 | 0\.40557949160746104 | 32\.095903282969594 | 15643388\.288550073 | 38\.36182306581907  | 5\.321702675606216  | 8\.922603810637188 | 4\.501833277829604  | 1\.0701700326366543 | 1\.970831663486951  | 2\.303172780881962  | 1\.1454824433285955 | 2\.912739934566613 | 3\.1925485125428237 | 15677723\.280993517 | 6\.456832212102734 | 0\.09654313524851336 | 0\.9999546837390285 | 1\.0       | 4\.193926488123296 | 0\.6347614564160745 | 4\.468125472634441 |
| std   | 0\.0       | 1949102\.912568308  | 100324\.96278914549 | 0\.25467784630698914 | 6\.73475558490455   | 1\.507764699602635  | 0\.7277809648231253 | 304689\.81963343563 | 1\.3322762659922467 | 0\.8502081854840524  | 100231\.2069535304 | 0\.458704252662167 | 0\.16073481285374852 | 0\.49510312985241994 | 0\.7312869358057765 | 8761444\.83290858   | 605\.5844610613963  | 0\.5001558165069437 | 2\.875395264707814 | 2\.3762584804254865 | 1\.4220042383464424 | 560\.858914247192   | 0\.6416686651596737 | 8779476\.226844812  | NaN       | 1868\.0409517624785 | NaN        | 8645726\.966753276  | 36\.81876947575624  | 20\.71738527814682 | 8693617\.156456223  | 9\.76209883337617  | 97949\.11592303887 | NaN        | 1\.1119241817640617 | 2\.1582868818275367 | 8780308\.734587755  | 1\.4220748279234074 | 1\.5144512964593022 | 1\.3204935722187419 | 0\.9246068407190831  | 7\.735224935967807  | 8664233\.909369253  | 2\.2287437483124233 | 3\.2898798576532178 | 6\.77509134207274  | 14\.064090765358962 | 0\.5162331692827294 | 0\.9870494447694967 | 1\.3757980030286423 | 0\.4497183378653401 | 1\.449718899083731 | 1\.1014913766910073 | 8759733\.058571905  | 2\.492138126142752 | 0\.29533471447836424 | 0\.0067315841926361 | 0\.0       | 2\.761537812022454 | 0\.4814970858365123 | 1\.47789832338908  |
| min   | 1\.0       | 57\.0               | 110001\.0           | 1\.0                 | 9\.0                | 1\.0                | 1\.0                | 10115\.0            | 0\.0                | 0\.0                 | 110000\.0          | 1\.0               | 1\.0                 | 1\.0                 | 1\.0                | 1012022\.0          | 0\.0                | 0\.0                | 0\.0               | 0\.0                | 1\.0                | 100\.0              | 1\.0                | 1012002\.0          | NaN       | 20210010\.0         | NaN        | 1022022\.0          | 0\.0                | 0\.0               | 1022022\.0          | 811\.0             | 110000\.0          | NaN        | 0\.0                | 1\.0                | 1011970\.0          | 1\.0                | 0\.0                | 0\.0                | 0\.0                 | 9\.0                | 1012022\.0          | 19\.0               | 1\.0                | 0\.0               | 1\.0                | 1\.0                | 1\.0                | 1\.0                | 1\.0                | 1\.0               | 0\.0                | 1012022\.0          | 0\.0               | 0\.0                 | 0\.0                | 1\.0       | 1\.0               | 0\.0                | 1\.0               |
| 25%   | 1\.0       | 2118513\.0          | 260210\.0           | 1\.0                 | 22\.0               | 1\.0                | 4\.0                | 421125\.0           | 0\.0                | 0\.0                 | 260190\.0          | 5\.0               | 1\.0                 | 1\.0                 | 4\.0                | 8062022\.0          | 842\.0              | 1\.0                | 8\.0               | 9\.0                | 1\.0                | 2875\.0             | 2\.0                | 8062022\.0          | NaN       | 20220012\.0         | NaN        | 8082022\.0          | 11\.0               | 10\.0              | 8082022\.0          | 825\.0             | 250040\.0          | NaN        | 3\.0                | 3\.0                | 8071992\.0          | 1\.0                | 0\.0                | 0\.0                | 0\.0                 | 26\.0               | 8072021\.0          | 38\.0               | 2\.0                | 7\.0               | 2\.0                | 1\.0                | 2\.0                | 1\.0                | 1\.0                | 2\.0               | 3\.0                | 8062022\.0          | 5\.0               | 0\.0                 | 1\.0                | 1\.0       | 2\.0               | 0\.0                | 4\.0               |
| 50%   | 1\.0       | 2458705\.0          | 330060\.0           | 1\.0                 | 27\.0               | 2\.0                | 4\.0                | 622105\.0           | 1\.0                | 0\.0                 | 330045\.0          | 5\.0               | 1\.0                 | 2\.0                 | 4\.0                | 15122022\.0         | 1232\.0             | 1\.0                | 9\.0               | 9\.0                | 4\.0                | 3195\.0             | 2\.0                | 15122022\.0         | NaN       | 20220022\.0         | NaN        | 15072022\.0         | 19\.0               | 17\.0              | 15072022\.0         | 831\.0             | 314330\.0          | NaN        | 3\.0                | 3\.0                | 16021984\.0         | 4\.0                | 1\.0                | 0\.0                | 0\.0                 | 32\.0               | 15112021\.0         | 39\.0               | 8\.0                | 9\.0               | 2\.0                | 1\.0                | 2\.0                | 2\.0                | 1\.0                | 2\.0               | 3\.0                | 16012022\.0         | 6\.0               | 0\.0                 | 1\.0                | 1\.0       | 4\.0               | 1\.0                | 5\.0               |
| 75%   | 1\.0       | 2792168\.0          | 355030\.0           | 1\.0                 | 33\.0               | 2\.0                | 4\.0                | 999992\.0           | 2\.0                | 0\.0                 | 355030\.0          | 5\.0               | 1\.0                 | 2\.0                 | 4\.0                | 23072022\.0         | 1734\.0             | 2\.0                | 9\.0               | 10\.0               | 4\.0                | 3500\.0             | 2\.0                | 23082022\.0         | NaN       | 20220041\.0         | NaN        | 23052022\.0         | 33\.0               | 29\.0              | 23062022\.0         | 835\.0             | 355030\.0          | NaN        | 3\.0                | 5\.0                | 23091986\.0         | 4\.0                | 2\.0                | 1\.0                | 1\.0                 | 37\.0               | 23092021\.0         | 40\.0               | 8\.0                | 10\.0              | 3\.0                | 1\.0                | 2\.0                | 3\.0                | 1\.0                | 5\.0               | 4\.0                | 23082022\.0         | 8\.0               | 0\.0                 | 1\.0                | 1\.0       | 5\.0               | 1\.0                | 5\.0               |
| max   | 1\.0       | 9999999\.0          | 530010\.0           | 9\.0                 | 99\.0               | 9\.0                | 9\.0                | 999995\.0           | 99\.0               | 99\.0                | 530010\.0          | 9\.0               | 9\.0                 | 9\.0                 | 9\.0                | 31122022\.0         | 7058\.0             | 2\.0                | 99\.0              | 99\.0               | 5\.0                | 7000\.0             | 9\.0                | 31122022\.0         | NaN       | 20230009\.0         | NaN        | 31122022\.0         | 380\.0              | 380\.0             | 31122022\.0         | 853\.0             | 530010\.0          | NaN        | 9\.0                | 8\.0                | 31122008\.0         | 5\.0                | 99\.0               | 99\.0               | 99\.0                | 99\.0               | 31122021\.0         | 45\.0               | 9\.0                | 99\.0              | 99\.0               | 9\.0                | 9\.0                | 9\.0                | 9\.0                | 5\.0               | 5\.0                | 31122022\.0         | 12\.0              | 1\.0                 | 1\.0                | 1\.0       | 11\.0              | 1\.0                | 9\.0               |

**Tabela 2:** Tabela com estatísticas descritivas de todas as colunas numéricas da base de dados

### Sensibilidade dos dados
#### Tipos de sensibilidade
- Informações demográficas da mãe e do pai, como idade, município e escolaridade
- Data de nasncimento do recém-nascido
- Recém-nascido com anomalia
- Origem racial ou étnica dos pais e do recém-nascido 

#### Campo(s) com dados confidenciais
**Dados sensíveis coletados intencionalmente**

(S/PII foram coletados como parte do
processo de criação de conjunto de dados.)

Nome do Campo | Descrição 
--- | ---
CODESTAB | Quasi-identificadores 
CODMUNNASC | Quasi-identificadores 
IDADEMAE | Quasi-identificadores 
ESTCIVMAE | Dados sensíveis 
ESCMAE | Dados sensíveis 
CODOCUPMAE | Dados sensíveis 
QTDFILMORT | Dados sensíveis 
CODMUNRES | Dados sensíveis 
SEXO | Quasi-identificadores 
RACACOR | Quasi-identificadores 
IDANOMAL | Dados sensíveis 
DTNASCMAE | Quasi-identificadores 
RACACORMAE | Dados sensíveis 
SERIESCMAE | Dados sensíveis 
IDADEPAI | Quasi-identificadores 

**Tabela 3:** Tabela com as variáveis que são sensíveis/identificadores

## Licença e Acesso

### Tipo de Licença

CC BY 4.0

### Permissões de licença

**Share** — copy and redistribute the material in any medium or format

**Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

**Attribution** — You must give [appropriate credit](https://creativecommons.org/licenses/by/4.0/#), provide a link to the license, and [indicate if changes were made](https://creativecommons.org/licenses/by/4.0/#). You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**No additional restrictions** — You may not apply legal terms or [technological measures](https://creativecommons.org/licenses/by/4.0/#) that legally restrict others from doing anything the license permits.



## Versionamento e Manutenção

### Status do conjunto de dados

| Versão             | 1.0            |
| ------------------ | -------------- |
| Última Atualização | 10/Agosto/2023 |
| Primeira versão    | 10/Agosto/2023 |

### Plano de manutenção

Atualização do dataset são publicados no [opendatasus](https://opendatasus.saude.gov.br/dataset/sistema-de-informacao-sobre-nascidos-vivos-sinasc/resource/41a83273-5760-48a3-9740-1be727db06cf)

### Dicionário das variáveis do DATASUS:

- **ORIGEM**:  Banco de dados origem (1-Oracle, 2-FTP, 3-SEAD)
- **CODESTAB**: Código do estabelecimento onde ocorreu o nascimento
- **CODMUNNASC**:  Código IBGE do município de nascimento
- **LOCNASC**: Local de nascimento (1-Hospital, 2-Outros estabelecimentos de saúde, 3-Domicílio, 4-Outros, 5-Aldeia indígena)
- **IDADEMAE**: Idade da mãe
- **ESTCIVMAE**: Situação conjugal da mãe (1-Solteira, 2-Casada, 3-Viúva, 4-Separada judicialmente/divorciada, 5-União estável, 9-Ignorada)
- **ESCMAE**: Escolaridade em anos de estudos concluídos da mãe (1-Nenhuma, 2-1 a 3 anos, 3-4 a 7 anos, 4-8 a 11 anos, 5-12 e mais, 9-Ignorado)
- **CODOCUPMAE**: Código de ocupação da mãe conforme tabela do CBO (Código Brasileiro de Ocupações)
- **QTDFILVIVO**: Número de filhos vivos
- **QTDFILMORT**: Número de perdas fetais e abortos.
- **CODMUNRES**: Código IBGE do município de residência
- **GESTACAO**: Semanas de Gestação (1- Menos de 22 semanas, 2- 22 a 27 semanas, 3- 28 a 31 semanas, 4- 32 a 36 semanas, 5- 37 a 41 semanas, 6- 42 semanas e mais, 9- Ignorados)
- **GRAVIDEZ**: Tipo de gravidez (1- Única, 2- Dupla, 3- Tripla ou mais, 9- Ignorado)
- **PARTO**: Tipo de Parto (1- Vaginal, 2- Cesário, 9- Ignorado)
- **CONSULTAS**: Número de consultas de pré-natal (1- Nenhuma, 2- de 1 a 3, 3- de 4 a 6, 4- 7 e mais, 9- Ignorado)
- **DTNASC**: Data de nascimento dd mm aaaa
- **HORANASC**: Hórario de nascimento
- **SEXO**: Sexo do recém nascido (1- M - Masculino, 2- F - Feminino, 0 – I - Ignorado)
- **APGAR1**: Apgar no 1º minuto 00 a a10  
- **APGAR5**: Apgar no 5º minuto 00 a 10
- **RACACOR**: Tipo de raça e cor do nascido (1– Branca; 2– Preta; 3– Amarela; 4– Parda; 5–  Indígena).
- **PESO**: Peso ao nascer em gramas.  
- **IDANOMAL**: Anomalia identificada (1– Sim; 2– Não; 9– Ignorado)
- **DTCADASTRO**: Data do cadastro da DN no sistema
- **CODANOMAL**: Código da anomalia (CID-10)  
- **NUMEROLOTE**: Número do lote
- **VERSAOSIST**: Versão do sistema
- **DTRECEBIM**: Data do último recebimento do lote, dada pelo Sisnet.  
- **DIFDATA**: Diferença entre a data de Nascimento e data do recebimento original da DN  ([DTNASC] – [DTRECORIGA])
- **DTRECORIGA**: Cria-se campo DTRECORIGA e copia os valores de DTRECORIG para esse campo.  Se DTRECORIGA = Nulo, copia os valores de DTRECEBIM. Se DTRECEBIM =  Nulo, copia os valores de DTCADASTRO
- **NATURALMAE**: Se a mãe for estrangeira, constará o código do país de nascimento.
- **CODMUNNATU**: Código do município de naturalidade da mãe
- **CODUFNATU**: Código UF de naturalidade  
- **ESCMAE2010**: Escolaridade 2010. (0 – Sem escolaridade; 1 – Fundamental I (1ª a 4ª série);  2 – Fundamental II (5ª a 8ª série); 3 – Médio (antigo 2º Grau); 4 – Superior  incompleto; 5 – Superior completo; 9 – Ignorado).
- **SERIESCMAE**: Série escolar da mãe. Valores de 1 a 8.  
- **DTNASCMAE**: Data de nascimento da mãe: dd mm aaaa  
- **RACACORMAE**: Tipo de raça e cor da mãe: 1– Branca; 2– Preta; 3– Amarela; 4– Parda; 5– Indígena.  
- **QTDGESTANT**: Número de gestações anteriores  
- **QTDPARTNOR**: Número de partos vaginais
- **QTDPARTCES**: Número de partos cesáreos  
- **IDADEPAI**: Idade do pai  
- **DTULTMENST**: Data da última menstruação (DUM): dd mm aaaa  
- **SEMAGESTAC**: Número de semanas de gestação.  
- **TPMETESTIM**: Método utilizado. Valores: 1– Exame físico; 2– Outro método; 9– Ignorado.
- **CONSPRENAT**: Número de consultas pré‐natal  
- **MESPRENAT**: Mês de gestação em que iniciou o pré‐natal
- **TPAPRESENT**: Tipo de apresentação do RN. Valores: 1– Cefálico; 2– Pélvica ou podálica; 3–  Transversa; 9– Ignorado.
- **STTRABPART**: Trabalho de parto induzido? Valores: 1– Sim; 2– Não; 3– Não se aplica; 9– Ignorado.  
- **STCESPARTO**: Cesárea ocorreu antes do trabalho de parto iniciar? Valores: 1– Sim; 2– Não; 3– Não  se aplica; 9– Ignorado.
- **TPNASCASSI**: Nascimento foi assistido por? Valores: 1– Médico; 2– Enfermagem ou Obstetriz; 3–  Parteira; 4– Outros; 9– Ignorado
- **TPFUNCRESP**: Tipo de função do responsável pelo preenchimento. Valores: 1– Médico; 2–  Enfermeiro; 3– Parteira; 4– Funcionário do cartório; 5– Outros.
- **TPDOCRESP**: Tipo do documento do responsável. Valores: 1‐CNES; 2‐CRM; 3‐ COREN; 4‐RG; 5‐ CPF.
- **DTDECLARAC**: Data da declaração: dd mm aaaa
- **ESCMAEAGR1**: Escolaridade 2010 agregada. Valores: 00 – Sem Escolaridade; 01 – Fundamental I  Incompleto; 02 – Fundamental I Completo; 03 – Fundamental II Incompleto; 04 –  Fundamental II Completo; 05 – Ensino Médio Incompleto; 06 – Ensino Médio  Completo; 07 – Superior Incompleto; 08 – Superior Completo; 09 – Ignorado; 10 –  Fundamental I Incompleto ou Inespecífico; 11 – Fundamental II Incompleto ou  Inespecífico; 12 – Ensino Médio Incompleto ou Inespecífico.
- **STDNEPIDEM**: Status de DO Epidemiológica. Valores: 1 – SIM; 0 – NÃO. 	
- **STDNNOVA**: Status de DO Nova. Valores: 1 – SIM; 0 – NÃO.
- **CODPAISRES**: Código do país de residência  
- **TPROBSON**: Código do Grupo de Robson, gerado pelo sistema  
- **PARIDADE**: Define se é a primeira gravidez ou se teve mais de uma. 1 – Multípara; 0- Nulípara.  
- **KOTELCHUCK**: índice de Kotelchuck - Avaliação da assistência pré-natal