# Resumo: AZ-900 - Conceitos Básicos do Microsoft Azure

Este documento resume o conteúdo das apresentações sobre os conceitos fundamentais da computação em nuvem, com foco no Microsoft Azure (AZ-900), ministrado por Valéria Baptista [source: 63].

## Objetivo do Curso

Fornecer conhecimento básico sobre [source: 5]:
* Conceitos do Azure
* Principais serviços do Azure
* Soluções e ferramentas de gerenciamento
* Segurança geral e de rede
* Governança, privacidade e conformidade
* Gerenciamento de custos do Azure

## Pré-requisitos

* Conhecimentos básicos de informática [source: 66].
* Familiaridade com computação em nuvem é útil, mas não obrigatória [source: 66].
* Disposição para aprender novas tecnologias [source: 67].

## Conceitos Abordados

### 1. O que é Computação em Nuvem?
* É o fornecimento de serviços de computação (como servidores, armazenamento, redes, software) pela Internet [source: 24].
* Habilita inovação mais rápida, recursos flexíveis e economias de escala [source: 24].

### 2. Modelos de Nuvem [source: 21]
* **Nuvem Pública:**
    * Infraestrutura pertencente a provedores de serviços de nuvem (como Microsoft Azure) que a disponibilizam para o público geral ou organizações [source: 6].
    * Acessada geralmente pela Internet via conexão segura [source: 6].
    * Vantagens: Não exige despesas de capital (CapEx) para escalar, provisionamento rápido, pagamento conforme o uso (OpEx) [source: 9, 10].
* **Nuvem Privada:**
    * Infraestrutura de nuvem operada exclusivamente para uma única organização [source: 26].
    * Pode ser gerenciada pela própria organização ou por terceiros, localizada no data center da organização ou fora dele [source: 26].
    * Vantagens: Maior controle sobre recursos e segurança [source: 11].
    * Desvantagens: Organização é responsável pela manutenção e atualizações do hardware [source: 11].
* **Nuvem Híbrida:**
    * Combina nuvens públicas e privadas, permitindo que dados e aplicativos sejam compartilhados entre elas [source: 8].
    * Vantagens: Maior flexibilidade, permite às organizações executar aplicativos no local mais apropriado, mantendo controle sobre segurança, conformidade e requisitos legais [source: 13, 14].

### 3. Comparação de Modelos de Preços (CapEx vs. OpEx)
* **CapEx (Despesas de Capital):** Gasto inicial em infraestrutura física, cujo valor se reduz com o tempo [source: 15, 16].
* **OpEx (Despesas Operacionais):** Gastos com produtos e serviços conforme a necessidade, geralmente no modelo "pague conforme o uso" [source: 17]. A cobrança é imediata.
* **Modelo Baseado em Consumo:** Modelo principal da nuvem, onde os usuários pagam apenas pelos recursos que utilizam [source: 18, 30]. Oferece melhor previsão de custos e cobrança baseada no uso real [source: 19, 20].

### 4. Benefícios da Computação em Nuvem
* **Alta Disponibilidade (High Availability):** Garante a máxima disponibilidade dos serviços, mesmo com interrupções, com garantias definidas nos Contratos de Nível de Serviço (SLAs) [source: 57, 58].
* **Escalabilidade (Scalability):** Capacidade de ajustar recursos (verticalmente: adicionar CPU/RAM; horizontalmente: adicionar VMs) para atender à demanda [source: 28, 33, 35]. Paga-se apenas pelo que se usa, permitindo reduzir custos se a demanda cair [source: 30, 31].
* **Elasticidade (Elasticity):** Capacidade de aumentar ou diminuir recursos (geralmente de forma automática) para lidar com picos ou quedas repentinas na demanda [source: 34, 36].
* **Confiabilidade (Reliability):** A natureza descentralizada da nuvem, com recursos em múltiplas regiões, suporta uma infraestrutura resiliente [source: 37, 38, 39].
* **Previsibilidade (Predictability):** Permite prever custos (devido ao modelo de consumo) e desempenho [source: 40].
* **Segurança (Security):** Oferece ferramentas de segurança, mas a implementação é uma responsabilidade compartilhada. O nível de controle varia conforme o modelo de serviço (IaaS, PaaS, SaaS) [source: 41, 42, 43].
* **Governança (Governance):** Ferramentas para auditoria, garantia de conformidade com padrões corporativos e gerenciamento de atualizações e patches [source: 44, 45, 46].
* **Gerenciabilidade (Manageability):** Facilidade de gerenciar recursos (escalonamento automático, implantação via modelos) e o ambiente de nuvem (através de portal web, CLI, APIs, PowerShell) [source: 49, 50, 51, 52, 53].

## O que foi Aprendido (Recaps)

* **Conceitos:** Definição de computação em nuvem, modelos (público, privado, híbrido), modelo baseado em consumo e comparação de preços [source: 1, 2].
* **Benefícios:** Vantagens de alta disponibilidade, escalabilidade, confiabilidade, previsibilidade, segurança, governança e capacidade de gerenciamento na nuvem [source: 60, 61].

## Para Saber Mais

* **Fórum/Artigos Dio:** https://web.dio.me/articles [source: 4]
* **Microsoft Learn (Módulos Relacionados):**
    * [Descrever conceitos de nuvem](https://learn.microsoft.com/training/modules/describe-cloud-compute/) (links específicos nos slides [source: 3])
    * [Descrever os benefícios de usar serviços de nuvem](https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/) (links específicos nos slides [source: 3])

