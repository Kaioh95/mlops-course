# Software-Enginnering Design Patterns for Machine Learning Applications

O artigo [1] faz um estudo de 15 padrões de design para machine learning encontrados em pesquisas. Ao todo foram recuperados 32 documentos acadêmicos e 48 gray documents, porém destre estes foram escolhidos 19 documentos acadêmicos e 19 gray documents, seguindo dois critérios definidos pelos autores.

Os autores extraíram do artigos 69 padrões, contudo ao revisar, apenas 33 padrões eram relacionados a arquitetura e design de sistemas ML. Ao final 3 desenvolvedores ML selecionaram 15 padrões.

    P1 Different Workloads in Different Computing Environments
    P2 Distinguish Business Logic from ML Models
    P3 ML Gateway Routing Architecture
    P4 Microservice Architecture for ML
    P5 Lambda Architecture for ML
    P6 Kappa Architecture for ML
    P7 Data Lake for ML
    P8 Separation of Concerns and Modularization of ML Components
    P9 Encapsulate ML Models within Rule-base Safeguards
    P10 Discard PoC Code
    P11 Parameter-Server Abstraction
    P12 Data Flows Up, Model Flows Down
    P13 Secure Aggregation
    P14 Deployable Canary Model
    P15 ML Versioning

No artigo os padrões foram classificados em 3 categorias, onde temos:

- P1-P6 são padrões de topologia dos sistemas ML definindo a arquitetura do sistema.
- P7-P10 são padrões de programação de sistemas ML que definem design de componentes particulares
- P11-P15 padrões de operação de modelos que focam em modelos ML.

Os autores indentificaram ao menos um atributo de qualidade, definidos em ISO/IEC 25010:2011, para cada padrão design ML estudados. Para avaliar como desenvolvedores ML percebem os padrões de design existentes, 118 participantes de um total de mais 600 particiantes de um seminário online, responderam um questionário para determinar como alguns padrões vem sendo utilizado. Ao final do artigo os pesquisadores detalharam apenas o padrão de design P2.


# References
[1] H. Washizaki, et al.,"Software-Engineering Design Patterns for Machine Learning Applications" in Computer, vol. 55, no. 03, pp. 30-39, 2022. doi: 10.1109/MC.2021.3137227