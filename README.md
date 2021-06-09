# Warehouse_Project

### Problema
  Falta de informação (quantidade real dentro do estoque), dificuldade para fazer a precificação dos produtos e perdas excessivas dentro do estoque por quebras ou por passar da validade do produto;

### Introdução 
  A gestão de estoque é fundamental para o planejamento das empresas, previsão e controle do estoque é um diferencial no curto e no longo prazo onde são aplicados. Através dela a empresa consegue controlar as suas entradas e saÌdas de mercadorias e fazer uma previsão de qual será o tamanho do estoque capaz de acompanhar a variação da demanda gerando melhor controle sobre o fluxo de caixa. </br>
  Muitas empresas buscam manter estoques mínimos para tentar obter vantagem competitiva no mercado. Com os baixos valores agregados aos estoques, elas conseguem ter a oportunidade de investir o capital ao invés de deixá-lo ocioso em forma de estoques. Se a empresa não possui o estoque para atendimento imediato ao seu cliente, ela gera uma abertura para que o mesmo busque seus concorrentes, correndo riscos de perdê-los.</br>
  Segundo o João José Viana no livro "Administração de materiais: um enfoque prático" o estoque pode representar aproximadamente até 46% dos ativos totais. Portanto os estoques são recursos ociosos que possuem valor econômico, os quais representam um investimento destinado a incrementar as atividades de produção e servir aos clientes.</br>
  O Instituto de Educação Tecnológica (Ietec) (2016), faz referência a uma pesquisa desenvolvida pelo Supply Chain Benchmarking Study 2007, publicada pelo Centro de Estudo em Logística, cujos resultados apontam que, empresas que conseguem gerir seus estoques de forma otimizada podem reduzir entre 40% a 65% os seus ciclos financeiros. Dessa forma, os recursos financeiros retornam ao caixa de 2 a 3 meses mais cedo, quando comparado a outras empresas. Portanto, ser eficiente na administração de estoque se torna um diferencial competitivo em épocas de grande competitividade e diminuição das margens de lucro.</br>
  Para Ching em Gestão de estoque na cadeia de logística integrada: Supply Chain(2010) a administração de estoques, bem trabalhado como um conceito integrado, e não apenas como uma estratégia para diminuição de custos, é essencial para a sobrevivência do negócio.</br>
  Com o objetivo de ajudar uma determinada empresa, o projeto será construido de maneira que registre as vendas e o registro das movimentações no estoque de maneira detalhada para que seja possivel extrair indicadores e gerar relatórios que auxiliem na tomada de futuras decisões.
  
### Proposta de Solução
  Por meio de registro das vendas, controle do estoque (quantidade minima e máxima necessária | data de vencimento), categorização dos itens é possivel se ter um controle dos bens evitando perdas dentro do estoque e planejar a reposição dos produtos por parte do comprador.
  Serão gerados os seguintes indicadores:
  . Média móvel de produtos vendidos e vendas realizadas em determinado periodo de tempo;
  . Classificação ABC dos produtos cadastrados;
 Também será aplicado um modelo machine learning de apredizagem por reforço para realizar o cálculo de previsão de demanda através dos registros das vendas, utilizando Machine Learning para combinar dados de séries temporais com variáveis adicionais para criar previsões;

### Arquitetura do projeto
A estrutura do projeto consiste em quatro partes: </br>
1.REGISTRADOR - Registrar e enviar as vendas de forma detalhada e padronizada;</br>
2.GERENCIADOR - Disponibilizar informações, correção dados do estoque e das vendas que forem lançados de maneira incorreta;</br>
3.API - Método de acesso ao banco de dados;</br>
4.VISUALIZADOR - Disponibilizar as informações para individuos remotos;</br>
O projeto é para ser o mais modular possivel e aplicavel em outros casos onde já se possuam partes que façam tarefas semelhantes;</br>
![image](https://user-images.githubusercontent.com/55815066/115421864-bbbf1b80-a1d2-11eb-96bf-f4e90d3c9249.png)
