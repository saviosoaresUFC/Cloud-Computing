**Nome:** Sávio de Carvalho Soares  
**Matrícula:** 555524

---

### 2.1 Quais os fatores que você deve considerar na seleção de uma região da AWS? Comente brevemente sobre cada um deles.

- **Latência (proximidade com o usuário):** Para garantir uma boa experiência de uso, a região deve estar geograficamente próxima ao seu público-alvo. Quanto menor a distância física entre o data center e o usuário final, menor será o tempo de resposta da aplicação.
- **Custo:** Algumas regiões são mais baratas que outras devido a impostos locais, custos de energia e infraestrutura. Por exemplo, Ohio é mais barata que São Paulo.
- **Disponibilidade:** Nem todas as regiões da AWS são idênticas. Regiões mais novas ou menores podem não oferecer todos os serviços (como instâncias específicas de EC2 ou recursos avançados de IA). É essencial verificar se os serviços necessários para o projeto estão disponíveis na região escolhida.

---

### 2.2 Acesse Infraestrutura da AWS e liste, de todas as regiões disponíveis da AWS, quais tem um número de zonas de disponibilidade maior ou igual a três. Cite o nome da região e a quantidade de zonas.

- **AWS GovCloud (US-East):** 3 zonas
- **AWS GovCloud (US-West):** 3 zonas
- **Canada (Central):** 3 zonas
- **Canada West (Calgary):** 3 zonas
- **Mexico (Central):** 3 zonas
- **US East (N. Virginia):** 6 zonas
- **US East (Ohio):** 3 zonas
- **US West (N. California):** 3 zonas
- **US West (Oregon):** 4 zonas
- **South America (São Paulo):** 3 zonas
- **Europe (Frankfurt):** 3 zonas
- **Europe (Ireland):** 3 zonas
- **Europe (London):** 3 zonas
- **Europe (Milan):** 3 zonas
- **Europe (Paris):** 3 zonas
- **Europe (Spain):** 3 zonas
- **Europe (Stockholm):** 3 zonas
- **Europe (Zurich):** 3 zonas
- **AWS ESC (Germany):** 3 zonas
- **Africa (Cape Town):** 3 zonas
- **Israel (Tel Aviv):** 3 zonas
- **Middle East (Bahrain):** 3 zonas
- **Middle East (UAE):** 3 zonas
- **Asia Pacific (Hong Kong):** 3 zonas
- **Asia Pacific (Hyderabad):** 3 zonas
- **Asia Pacific (Jakarta):** 3 zonas
- **Asia Pacific (Malaysia):** 3 zonas
- **Asia Pacific (Mumbai):** 3 zonas
- **Asia Pacific (Osaka):** 3 zonas
- **Asia Pacific (Seoul):** 4 zonas
- **Asia Pacific (Singapore):** 3 zonas
- **Asia Pacific (Taipei):** 3 zonas
- **Asia Pacific (Thailand):** 3 zonas
- **Asia Pacific (Tokyo):** 3 zonas
- **Asia Pacific (New Zealand):** 3 zonas
- **Australia (Melbourne):** 3 zonas
- **Australia (Sydney):** 3 zonas

---

### 3. Definição de serviços por categoria:

#### **Armazenamento**

- **Amazon S3:** Armazenamento de objetos para guardar e recuperar qualquer volume de dados.
  - [Documentação](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
- **Amazon EBS:** Serviço de armazenamento em bloco de alto desempenho.
  - [Documentação](https://docs.aws.amazon.com/ebs/latest/userguide/what-is-ebs.html)
- **Amazon EFS:** Sistema de arquivos NFS simples, escalável e sem servidor para uso com serviços AWS.
  - [Documentação](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)

#### **Computação**

- **Amazon EC2:** Fornece capacidade computacional redimensionável.
  - [Documentação](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- **AWS Lambda:** Executa código sem provisionar ou gerenciar servidores, respondendo a eventos.
  - [Documentação](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
- **Amazon ECS:** Serviço de orquestração de contêineres.
  - [Documentação](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html)

#### **Banco de Dados**

- **Amazon RDS:** Relational Database Service (Serviço de Banco de Dados Relacional).
  - [Documentação](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
- **Amazon DynamoDB:** Banco NoSQL de chave-valor com desempenho de milissegundos em qualquer escala.
  - [Documentação](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
- **Amazon ElastiCache:** Serviço de armazenamento em cache na memória.
  - [Documentação](https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/WhatIs.html)

#### **Rede e Entrega de Conteúdo**

- **Amazon VPC:** Provisiona uma seção isolada da nuvem AWS para lançar recursos em rede virtual definida.
  - [Documentação](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
- **Amazon CloudFront:** Rede de entrega de conteúdo (CDN) global.
  - [Documentação](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- **Amazon Route 53:** Serviço web de Sistema de Nomes de Domínio (DNS).
  - [Documentação](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
