# UFES - Projeto Final de Ciência de Dados

## Objetivo

O objetivo do projeto é coletar os dados das ações brasileiras que estão listadas na Ibovespa (bolsa de valores brasileira) e conseguir analisar os dados obtidos para obter insights sobre as melhores ações a serem compradas no momento em que o programa rodar.

## Ferramentas

1. Obtenção dos dados: Utilizarei urllib e BeautifulSoup para obter os dados usando webscrapping;
2. Processamento dos dados: Utilizarei o dataframe do pandas para guardar todas informações obtidas no webscrapping de forma padronizada e limpa;
3. Análises: Analisarei os dados fazendo gráficos com matplotlib e seaborn. Tentarei fazer agrupamentos das ações conforme fatores que são positivos na hora de comprar uma ação e utilizarei conceitos das aulas passadas para tentar fazer os agrupamentos e análises mais complexas.

## Fonte de dados

A fonte de dados é o https://statusinvest.com.br/

Utilizarei um arquivo de texto com a lista de todas ações do ibovespa para acessá-los um a um e coletar as informações necessárias. 

Exemplo de uma url da ação específica https://statusinvest.com.br/acoes/vale3

Lista de dados a serem coletados:
- Valor atual, mín. 52 semanas, máx. 52 semanas, dividend yield, valorização(12m)
- Tipo, tag along, liquidez média diária
- Indicadores de valuation, endividamento, eficiência, rentabilidade e crescimento
- Patrimônio líquido, ativos, ativo circulante, dívida bruta, disponibilidade, dívida líquida,
- valor de mercado, valor de firma, nº total de papeis, segmento de listagem, free float
- Setor de atuação, subsetor de atuação, segmento de atuação
