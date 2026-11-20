
# Dashboard de Vendas Porsche

## Sobre o projeto

Este projeto tem como objetivo desenvolver um dashboard interativo para análise de vendas de veículos Porsche, utilizando uma base de dados disponibilizada em Excel.

A proposta foi transformar os dados em informações relevantes para apoiar a análise de desempenho comercial, comportamento dos clientes, desempenho dos modelos e acompanhamento operacional.

O dashboard foi desenvolvido em HTML, CSS e JavaScript, com identidade visual inspirada no site oficial da Porsche Brasil e nos princípios de visualização de dados do livro *Storytelling with Data*.

---

## 1. Perguntas de negócio escolhidas

As perguntas foram definidas buscando explorar diferentes perspectivas do negócio, indo além da análise do faturamento total.

### Performance comercial

- Como o faturamento evoluiu ao longo dos meses?
- Quais vendedores apresentam o maior faturamento?
- Quais clientes compram com maior frequência?
- Quais clientes apresentam maior faturamento e ticket médio?

**Justificativa:** avaliar o desempenho comercial, identificar os principais vendedores e compreender quais clientes possuem maior participação nos resultados.

### Clientes e mercado

- Quais estados concentram o maior volume de vendas?
- Como as vendas estão distribuídas entre as cidades?

**Justificativa:** identificar os mercados com maior participação nas vendas e compreender a distribuição geográfica dos resultados.

### Produtos e valor

- Quais modelos Porsche geram maior faturamento?
- Como o preço dos veículos se relaciona com a quilometragem?

**Justificativa:** identificar os modelos com maior contribuição financeira e explorar possíveis relações entre as características dos veículos e seus preços.

### Operação e pagamento

- Como estão distribuídos os veículos por status de entrega?
- Quais métodos de pagamento apresentam maior ticket médio?
- Qual é a participação de cada método de pagamento no faturamento?

**Justificativa:** acompanhar aspectos operacionais das vendas e compreender o comportamento dos clientes em relação às formas de pagamento.

---

## 2. Prompt e evolução até a versão final

O desenvolvimento começou com um prompt solicitando a criação de um dashboard de vendas em HTML, utilizando a identidade visual da Porsche e os princípios do livro *Storytelling with Data*.

Durante o processo, o prompt passou por ajustes para tornar a análise mais orientada a perguntas de negócio e melhorar a experiência visual.

As principais mudanças foram:

- **Análise de negócio:** organização do dashboard em quatro áreas: performance comercial, clientes e mercado, produtos e valor, operação e pagamento.
- **Indicadores:** inclusão de métricas como ticket médio, frequência de compra e participação no faturamento.
- **Visualizações:** escolha de gráficos que permitissem explorar melhor os dados, como a relação entre quilometragem e preço dos veículos.
- **Identidade visual:** definição de uma estética premium, com imagem de um Porsche no topo, tons escuros e detalhes em vermelho.
- **Experiência de uso:** redução de textos explicativos e elementos desnecessários, priorizando uma interface mais limpa e objetiva.

O objetivo dos ajustes foi equilibrar qualidade visual, clareza das informações e profundidade analítica.

---

## 3. Tratamento da base de dados

A base utilizada contém 100 registros e informações sobre vendas, clientes, modelos, preços, quilometragem, pagamentos, localização, vendedores e status de entrega.

Antes da construção das análises, foram observados alguns pontos que exigiram cuidados:

### Datas

Foram identificados 76 registros com datas interpretáveis e 24 datas inválidas. Os registros com datas inválidas foram desconsiderados das análises que dependem da dimensão temporal.

### Padronização dos vendedores

Foram identificadas variações de capitalização nos nomes dos vendedores. Foi realizada uma padronização para evitar que a mesma pessoa aparecesse em categorias diferentes nos agrupamentos.

### Quilometragem

Foram encontrados registros com quilometragem igual a zero. Esses valores foram mantidos, preservando a informação original da base, sem substituições arbitrárias.

### Integridade dos dados

Os valores originais de vendas foram preservados. Como a base não apresenta custos dos veículos, não foram criados indicadores de lucro ou margem.

---

## 4. Ferramentas e abordagem utilizadas

O desenvolvimento foi realizado com o auxílio do **ChatGPT**, utilizando prompts para definir as análises, estruturar as visualizações e desenvolver o dashboard.

Tecnologias e ferramentas utilizadas:

- **Excel:** fonte dos dados.
- **ChatGPT:** apoio na definição das perguntas de negócio, elaboração dos prompts e desenvolvimento do código.
- **HTML:** estrutura da aplicação.
- **CSS:** identidade visual, layout e responsividade.
- **JavaScript:** filtros, cálculos e interatividade.
- **Chart.js:** construção dos gráficos.

### Utilização de Canvas ou agente com skill

O projeto foi desenvolvido por meio de interação conversacional com o ChatGPT, com geração e execução de código. Não foi utilizado o Canvas como ambiente de desenvolvimento nem um agente com skill específica.

---

## 5. Considerações finais

O projeto demonstra como a inteligência artificial pode apoiar não apenas a construção de dashboards, mas também a definição das perguntas de negócio e a escolha das visualizações mais adequadas.

O processo reforçou a importância de compreender os dados antes de construir os gráficos, definir uma narrativa para a análise e utilizar a IA como ferramenta de apoio, mantendo a validação das informações e das regras de negócio como parte fundamental do desenvolvimento.
