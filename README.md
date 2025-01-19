# big-data-and-ia-fundamentals

## Introtuction

* China principal pais a investir em Inteligencia Artificial
* Entenderemos o que é IA, Big Data, IOT etc.
* apenas conhecimento não é pratico.

### O que é Big Data

- 5 Vs: Velocidade, volume, varieddade, veracidade e valor
- Fenômeno da massificação de elementos de produção e armazenamento de dados, bem como processo e tecnologias para extraí-los e analisá-los.

### Oque é Inteligência Artificial

- Reprodução de caracteristicas de inteligência, antes exclusiva de seres vivos, através de computadores
- Tipos: 
    - Forte: inteligência de multipços propósitos.
    - Fraca: inteligências especifica

### Oque é IOT

- Conexão de objetos gerando informações e dados.
- Big Data + IA, processamento e analise das informações geradas.

## Data Architecture

### Estruturas de dados 
- Dados estruturados, armazenados mesma estruturas e rígidas, SGBD, planilha eletrônica
- Semiestruturados, Flexivel, mais fácil sua estrutura muda, XML, JSON, RDF
- Não estruturados, Sem estrutura definida, 80 a 90% dados existentes % videos, imagens, paginas internet, Tweets

### Produção e Guarda
- Modelo Relacional
 - ACID, Consistente isolado durabilidade
 - SGDB, Sistemas gerenciadores de bancos de dados relacionais
 - SQL Linguagem padrão CRUD
 - Formas Normais, modelagem e padrões de implementações
- MySQL
- Oracle
- SQL server
- Postgre SQL

#### Vantagens 
* Grandes volumes, consultas em processo, integridades, reduzir redundancias e acesso concorrentes

#### Desvantagens
* Não é bom para analises, escalabilidade e redundância

### NoSQL 
* Mais flexíveis, desnormalizados, sem restriç~eos de integridade, modelo transacionais mais flexíveis
* Processamento eficients, paralelismos, estalabilidade e custo menor

Tipos: 
 - Key-Value Pair (KVP), Couchebase, Amazon DynamoDB 
 - Colunas Ordenadas, Apache HBASE, Hypertable
 - Banco de dados de documentos, CouchDB, MongoDB
 - Banco de dados de Grafos, Neo4j

### Armazenamento e Análise

- Data Mart(DM): Banco de dados analítico departamental
- Data WareHouse(DW): Conjunto de DM, reúne dados para apoio de uma organização para decições
- consolidades de varias fontes
- durabilidde 3 a 10 anos
- otimizado para consultas
- inclusão e consulta
- não integro, redundante
- modelo multidimensional

* OLAP: Sistema Analíticos, capacidade de manipular e analisar grade colume de dados.
* ETL: Extração transformação Carga, extrair dados de diversos sistemas para determinada necessidade de negocios

- Granularidade, informação não detalhada, os detalhes são formecidos atravesde relatórios, com finalidade de conferência.

- BI feramentas, tecnologia e processos para analise de dados

#### DW tradicional problemas

- arquiteturas vertical, estruturados, dificuldade de processar grandes volumes, processo contrução demorado e caros

#### MapReduce

- Simplificar processamento de dados em larga escala atraves de Clusters, distribuidos e balanceamentos de carga

    - criado pelo Gloogle
    - cluster conjunto de maquinas
    - concorencia
    - tolerancia de falhas
    - balanciamentos de cargas
    - distribuição

#### Datalake

- Repositorio de dados de varias fontes
- Não tratados
- Armazena tudo
- Pode alimentar um DW

### Analizar Dados

- DW tradicional não é substituido por datalake ou Map Reduce
- NoSQL não substitui modelo tradicional
* *Tecnologias diferentes para problemas diferentes