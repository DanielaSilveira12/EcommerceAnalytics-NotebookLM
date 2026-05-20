# EcommerceAnalytics-NotebookLM

## Contexto
Guia de estudos sobre Ecommerce Analytics utilizando materiais do canal Ecommerce Pro e Jerry Strazzeri, ambos do Youtube; conteúdo escrito a partir de um resumo sobre Entendimento de Negócios para Ecommerce, desenvolvido com Gemini Plus; e conteúdo adicional adquirido com Deep Research através da pesquisa "Análise Estratégica de Métricas de Performance no E-commerce".

## Objetivo
Aprender a identificar e utilizar métricas de negócios dentro de ambientes de Ecommerce.

## Fontes Textuais
EntendimentoNegóciosEcommerce: Conteúdo escrito a partir de um resumo sobre Entendimento de Negócios para Ecommerce, desenvolvido com Gemini Plus.

## Fontes Visuais
### Conceitos de Ecommerce
https://www.youtube.com/watch?v=j4Z7Pa6tncU
https://www.youtube.com/watch?v=utTip29fV34
https://www.youtube.com/watch?v=xETGO3OpAao
https://www.youtube.com/watch?v=zYnMDAbcJi4

### Pensamento Analítico
https://www.youtube.com/watch?v=jlheUWI-d4o
https://www.youtube.com/watch?v=s2502j_r6Yk
https://www.youtube.com/watch?v=TtiXinVULZA

## Prompts

## 01. Quais são as principais métricas para alavancar um ecommerce?

Para alavancar um e-commerce de forma sustentável, é fundamental ir além das "métricas de vaidade" (como visualizações de página) e focar em indicadores que medem a **saúde financeira**, a **eficiência do funil** e a **fidelização do cliente**.

As principais métricas podem ser divididas em pilares estratégicos:

### 1. O "Padrão de Ouro" da Viabilidade
A métrica definitiva para o crescimento escalável é a relação entre o valor gerado pelo cliente e o custo para atraí-lo:
*   **LTV (Lifetime Value):** Estima a receita total que um cliente trará durante todo o seu relacionamento com a marca.
*   **CAC (Custo de Aquisição de Clientes):** Soma dos investimentos em marketing e vendas dividida pelo número de novos clientes.
*   **Razão LTV:CAC:** Um negócio é considerado saudável e escalável quando essa proporção é de pelo menos **3:1** (o cliente rende três vezes mais do que custou para ser adquirido).

### 2. Eficiência de Receita (O Trio de Ouro)
Essas três métricas determinam a capacidade da loja de transformar tráfego em dinheiro:
*   **Taxa de Conversão (CR):** Porcentagem de visitantes que realizam uma compra. No Brasil, a média gira em torno de 1,66%, mas varia muito por setor.
*   **Ticket Médio (AOV):** Valor médio gasto em cada pedido. É uma das métricas mais baratas de se otimizar através de estratégias como *upselling* e *cross-selling*.
*   **Receita por Visitante (RPV):** Considerada a métrica mais abrangente, pois combina conversão e ticket médio (RPV = CR × AOV). Ela revela a qualidade real do tráfego atraído.

### 3. Saúde do Funil e Comportamento
Identificam onde o dinheiro está "vazando" na jornada do usuário:
*   **Taxa de Adição ao Carrinho:** Mede o desejo de compra imediato e a eficácia das páginas de produto.
*   **Taxa de Abandono de Carrinho:** Shoppers que adicionam itens, mas não finalizam. A média de mercado é alta, cerca de 70%, representando uma grande oportunidade de recuperação de receita.
*   **Tempo de Carregamento:** Sites que demoram mais de **3 segundos** para carregar aumentam drasticamente a taxa de rejeição e o abandono.

### 4. Retenção e Lealdade
Vender para quem já é cliente é de 5 a 25 vezes mais barato do que adquirir um novo:
*   **Taxa de Recompra:** Porcentagem de clientes que fizeram mais de uma transação.
*   **Churn Rate:** Taxa de clientes que param de comprar na loja em um período definido.
*   **NPS (Net Promoter Score):** Mede a satisfação e a probabilidade de recomendação da marca.

### 5. Excelência Operacional e Logística
No e-commerce, a experiência termina na entrega:
*   **OTIF (On-Time In-Full):** Pedidos entregues no prazo e sem faltas. Benchmarks de elite visam 95% a 98%.
*   **Taxa de Pedido Perfeito:** O indicador supremo de qualidade: entregue no prazo, completo, sem danos e com documentação correta.
*   **Taxa de Devolução/Reembolso:** Indica problemas na descrição do produto, qualidade ou danos no transporte.

### Dica para o Analista: Captado vs. Faturado
É crucial diferenciar **Transações Captadas** (pedidos feitos) de **Transações Faturadas** (pedidos pagos). O marketing deve ser avaliado pelo esforço de venda (captado), mas o negócio só sobrevive com o dinheiro no caixa (faturado). A relação entre os dois gera a **Taxa de Aprovação**, essencial para identificar problemas no checkout ou meios de pagamento.

## 02. Quais variáveis são necessárias para realizar esse tipo de análise?
Para realizar uma análise estratégica e profunda do e-commerce, como a redução do CAC ou a alavancagem de vendas discutida anteriormente, você precisa coletar variáveis de diferentes áreas da operação. O segredo não está em olhar apenas para o faturamento, mas para a **inter-relação** entre dados financeiros, comportamentais e operacionais.

Abaixo, listo as variáveis fundamentais divididas por categoria:

### 1. Variáveis Financeiras e de Transação
Estes são os dados brutos de entrada e saída que alimentam os principais KPIs de rentabilidade:
*   **Receita Total (Gross Sales):** O faturamento bruto antes das deduções.
*   **Número de Pedidos/Transações:** A quantidade total de vendas concluídas em um período.
*   **Custo das Mercadorias Vendidas (COGS):** O valor gasto para produzir ou adquirir os produtos vendidos, essencial para calcular o lucro bruto.
*   **Ticket Médio (AOV):** Embora seja um KPI, ele é derivado da divisão da receita pelo número de pedidos.

### 2. Variáveis de Marketing e Aquisição
Necessárias para medir a eficiência do crescimento e calcular o CAC e o ROAS:
*   **Investimento Total em Marketing e Vendas:** Inclui gastos com anúncios (mídia paga), salários da equipe, ferramentas de software, produção de conteúdo e licenças.
*   **Número de Novos Clientes Adquiridos:** Quantidade de pessoas que realizaram a primeira compra no período definido.
*   **Cliques e Impressões:** Variáveis de topo de funil para medir o CTR (Taxa de Cliques) e a eficácia das campanhas.

### 3. Variáveis de Tráfego e Comportamento (On-site)
Essenciais para entender o funil de conversão e identificar gargalos na jornada do usuário:
*   **Sessões/Visitantes Únicos:** O volume de tráfego que chega à loja.
*   **Taxa de Adição ao Carrinho:** Número de sessões onde pelo menos um item foi adicionado ao carrinho.
*   **Carts Created (Carrinhos Criados):** Variável base para calcular a taxa de abandono.
*   **Inícios de Checkout (Checkout Initiations):** Quantidade de usuários que começaram a preencher os dados de pagamento.
*   **Tempo de Carregamento da Página:** O tempo que o site leva para renderizar completamente (idealmente abaixo de 3 segundos).
*   **Taxa de Rejeição (Bounce Rate):** Visitantes que saem após ver apenas uma página.

### 4. Variáveis de Retenção e Lealdade
Para calcular o LTV e a sustentabilidade a longo prazo:
*   **Frequência de Compra:** Quantas vezes o mesmo cliente compra por ano.
*   **Tempo Médio de Retenção (Lifespan):** O período em anos que um cliente mantém relacionamento com a marca.
*   **Número de Clientes no Início e no Fim do Período:** Necessário para calcular o Churn Rate (Taxa de Abandono).
*   **Pedidos Recorrentes:** Compras feitas por clientes que já estão na base.

### 5. Variáveis Operacionais e Logísticas
Fundamentais para a experiência do cliente e eficiência de custos:
*   **Data do Pedido vs. Data da Entrega Real:** Variáveis para medir o Order Cycle Time e a pontualidade.
*   **Pedidos com Erro ou Danificados:** Quantidade de entregas que chegaram incompletas, danificadas ou com documentação errada.
*   **Custos de Frete:** O valor total gasto com transportadoras e logística de entrega.
*   **Taxa de Devoluções/Reembolsos:** Número de itens devolvidos em relação aos vendidos.

### Variáveis de Contexto (Específicas para o Brasil)
Devido às particularidades do mercado brasileiro, um analista deve considerar:
*   **Método de Pagamento:** Diferenciar entre Pix (40% de share), Cartão de Crédito (34%) e Boleto (8%), pois cada um tem taxas de aprovação e tempos de processamento distintos.
*   **Dispositivo (Device):** O mobile domina 72% das transações no Brasil, mas o desktop costuma ter taxas de conversão superiores (3,9% vs 1,8%).

## 03. Como o GA4 utiliza IA para prever a probabilidade de churn?

O Google Analytics 4 (GA4) utiliza **Inteligência Artificial (IA)** e algoritmos de **Machine Learning** para transformar métricas que antes eram apenas descritivas em **métricas preditivas**. Essa tecnologia analisa grandes volumes de dados históricos e padrões de comportamento dos usuários para antecipar ações futuras com alta precisão.

Abaixo, detalho como o GA4 aplica essa tecnologia para prever o *churn* (probabilidade de abandono):

### 1. Identificação de Padrões de Desengajamento
O sistema de IA do GA4 monitora usuários que anteriormente eram ativos, mas que começam a apresentar sinais comportamentais de perda de interesse ou desengajamento. Através do aprendizado de máquina, a ferramenta identifica correlações entre certas interações no site (ou a falta delas) e a probabilidade de o usuário não retornar nos dias seguintes.

### 2. Métricas Preditivas Específicas
O GA4 oferece indicadores automáticos baseados nessas previsões:
*   **Probabilidade de Churn (7 dias):** Identifica a chance de um usuário que esteve ativo nos últimos 7 dias não retornar nos próximos 7 dias.
*   **Prováveis Compradores que Deixarão a Loja (7 dias):** Uma variação focada especificamente em usuários que já realizaram compras anteriormente, mas que demonstram alta probabilidade de não visitar o site ou aplicativo na próxima semana.

### 3. Criação de Públicos-Alvo Preditivos
A IA permite que o analista utilize o **Audience Builder** (Construtor de Públicos) para gerar listas dinâmicas baseadas nessas condições preditivas. Por exemplo, é possível criar um segmento de usuários com "LTV preditivo alto" ou com "alta probabilidade de churn". 

### 4. Aplicação Estratégica (Prevenção)
Uma vez que a IA identifica esses usuários em risco, o analista pode tomar decisões proativas:
*   **Intervenções Preventivas:** Disparar campanhas de marketing personalizadas ou ofertas especiais para reativar esses clientes antes que eles abandonem a marca definitivamente.
*   **Integração com Anúncios:** Esses públicos preditivos ficam automaticamente disponíveis para uso em contas conectadas, como **Google Ads**, **Display & Video 360** e **Search Ads 360**, permitindo lances mais estratégicos para retenção.

Além do churn, essa mesma infraestrutura de IA no GA4 é utilizada para prever a **Probabilidade de Compra** nos próximos 7 dias e realizar a **Previsão de Receita** para os próximos 28 dias.


## Dificuldades
Durante a elaboração deste NotebookLM, as maiores dificuldades se concentraram na escolha e análise das fontes de pesquisa:
 Além das fontes coletadas manualmente, foram analisadas as pesquisas realizadas através da Deep Research, necessitante de uma triagem detalhada dos links para não ocorrer alteração no viés da pesquisa.

## Indicações de Uso do NotebookLM
Ouvir o "Resumo em Áudio" e ver os slides poderá auxiliar na elaboração de prompts e dúvidas sobre o tema.

## Considerações Finais
Através da elaboração deste NotebookLM focado em Ecommerce Analytics, foram realizados testes de temáticas relevantes e informativas. Foram utilizadas várias fontes de pesquisa, tornando a pesquisa mais e menos avançada. A maioria das perguntas foram sobre métricas e outras sobre cases de outros empresas, tornando as referencias coerentes com cenários reais. 

O resultado final da pesquisa focou em uma abordagem direcinada para a elaboração de Métricas de Performance, a fim de destacar indicadores para serem apresentados em um Dashboard por um Analista de Dados de Ecommerce. 


## Guia de Estudos
### Resumo
Guia de estudos sobre Ecommerce Analytics focado em Métricas de Performance e elaboração de Dashboard.

### Glossário de Conceitos
Este glossário reúne os principais termos e conceitos de e-commerce e análise de dados encontrados nos documentos consultados, organizados por categorias para facilitar a consulta.

#### 1. Métricas Financeiras e de Rentabilidade
*   **AOV (Average Order Value / Ticket Médio):** O valor médio que os clientes gastam em cada compra. É calculado dividindo a receita total pelo número de pedidos.
*   **CLV ou LTV (Customer Lifetime Value / Valor do Tempo de Vida do Cliente):** Estima a receita ou o lucro total que um cliente trará para a empresa durante todo o seu relacionamento com a marca.
*   **Contribuição Margem (Contribution Margin):** A lucratividade de cada pedido após a contabilização dos custos variáveis (COGS, frete, taxas de pagamento).
*   **ROI (Return on Investment / Retorno sobre Investimento):** Relação entre o lucro gerado e o montante investido na operação ou em uma ação específica.
*   **RPV (Revenue Per Visitor / Receita por Visitante):** Combina taxa de conversão e ticket médio em um único número, dividindo a receita total pelo número de visitantes únicos.

#### 2. Aquisição e Marketing
*   **CAC (Customer Acquisition Cost / Custo de Aquisição de Clientes):** Soma dos investimentos em marketing e vendas dividida pelo número de novos clientes adquiridos.
*   **CPA (Cost Per Acquisition / Custo por Aquisição):** Focado no custo de gerar um lead ou uma conversão específica (como um download ou cadastro), muitas vezes usado em nível de campanha.
*   **CPC (Cost Per Click / Custo por Clique):** Valor pago por cada clique em um anúncio.
*   **CTR (Click-Through Rate / Taxa de Cliques):** Porcentagem de pessoas que clicaram em um anúncio ou link após vê-lo.
*   **ROAS (Return on Ad Spend / Retorno sobre Gastos com Anúncios):** Mede quanta receita bruta é gerada para cada real investido em campanhas publicitárias.

#### 3. Conversão e Funil (On-site)
*   **Taxa de Abandono de Carrinho (Cart Abandonment Rate):** Porcentagem de usuários que adicionam itens ao carrinho, mas não finalizam a compra.
*   **Taxa de Conversão (Conversion Rate):** Porcentagem de visitantes que realizam uma ação desejada (geralmente uma compra) em relação ao total de visitantes.
*   **Micro-conversões:** Pequenas ações que sinalizam progresso em direção à compra, como inscrições em newsletters ou adições à lista de desejos.
*   **Taxa de Rejeição (Bounce Rate):** Porcentagem de visitantes que saem do site após visualizar apenas uma página, sem interagir.

#### 4. Retenção e Fidelidade
*   **Churn Rate (Taxa de Abandono/Cancelamento):** Taxa na qual os clientes param de comprar ou cancelam suas assinaturas em um período definido.
*   **NPS (Net Promoter Score):** Métrica qualitativa que mede a satisfação e lealdade do cliente através da probabilidade de recomendação da marca.
*   **RFM (Recency, Frequency, Monetary Value):** Técnica de segmentação que analisa a Recência (data da última compra), Frequência (quantas vezes comprou) e Valor Monetário (total gasto) para personalizar o marketing.
*   **Taxa de Recompra (Repeat Purchase Rate):** Porcentagem de clientes que realizaram mais de uma transação na loja.

#### 5. Operação e Logística (Supply Chain)
*   **Giro de Estoque (Inventory Turnover):** Mede quantas vezes o estoque total é vendido e reposto ao longo de um período.
*   **Order Cycle Time:** Tempo total decorrido entre a realização do pedido pelo cliente e a entrega final.
*   **OTIF (On-Time In-Full):** Indicador que mede se os pedidos foram entregues no prazo prometido e com todos os itens corretos.
*   **Taxa de Pedido Perfeito (Perfect Order Rate):** Porcentagem de pedidos entregues no prazo, completos, sem danos e com a documentação correta.

#### 6. Comportamento e UX (Experiência do Usuário)
*   **Dead Clicks:** Cliques realizados em elementos que não são interativos, frustrando o usuário.
*   **Rage Clicks (Cliques de Raiva):** Cliques rápidos e repetidos em um mesmo elemento, sinalizando erro no site ou frustração do usuário.
*   **Scroll Depth (Profundidade de Rolagem):** Mede até que ponto da página o visitante rolou o conteúdo.
*   **Tempo de Carregamento (Page Load Time):** Tempo que uma página leva para ser totalmente renderizada; idealmente deve ser inferior a 3 segundos.

#### 7. Metodologia Analítica
*   **Análise de Coorte (Cohort Analysis):** Estudo do comportamento de grupos de usuários que compartilham uma característica comum, como o mês da primeira compra.
*   **Laranja com Laranja (Apples to Apples):** Conceito de comparar dados sob as mesmas condições e contextos, evitando comparar períodos sazonais distintos (ex: semana comum vs. Black Friday).
*   **Pensamento Analítico:** Capacidade de resolver problemas de forma metodológica, estruturada e sustentada por fatos, eliminando achismos e vieses.
*   **Viés de Confirmação (Confirmation Bias):** Tendência de procurar e valorizar apenas informações que confirmem crenças pré-existentes.
