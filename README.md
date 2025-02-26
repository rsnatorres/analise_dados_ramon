# analise_dados_ramon

A maior parte dos produtos de trabalho são desenvolvidos em equipe, mas algumas análises são feitas individualmente.

Este repositório contém códigos de análise de dados escritos 100% por mim.

Formato dos Arquivos:

Quando não há necessidade de compartilhar código durante a análise de dados, opto por utilizar o formato Jupyter Notebooks (.ipynb). Esse formato apresenta algumas vantagens:

✅ Permite estruturar uma narrativa do processo de análise, facilitando a compreensão em revisitas futuras.
✅ Justifica as decisões de transformação de dados ao longo do fluxo de análise.
✅ Possibilita o compartilhamento dos resultados sem a necessidade de executar novamente o código.

No entanto, Jupyter Notebooks não são ideais para trabalho colaborativo e versionamento de código, pois:

❌ Não são facilmente comparáveis em pull requests, já que não são arquivos de texto simples.

Quando a colaboração e o controle de versão são essenciais, outras abordagens, como scripts .py organizados em módulos, podem ser mais adequadas.

Análises de dados:

1) 2023_08_analise_dados_netimoveis.ipynb:
- Análise de dados de mercado imobiliário com base de dados própria construída através de webscraping

2) 2024_01_analise_belo_monte:
- Análise de dados com foco na renda das famílias afetadas pela usina de Belo Monte. 

3) 2024_05_analise_dados_car: 
- Essa foi a análise de dados que me permitiu identificar os problemas de sobreposição de geometrias na base de dados do CAR. Ainda nesse notebook, esbocei uma solução prévia para solução das geometrias.

4) 2024_07_analise_mercado_imobiliario_rmbh.ipynb
- Análise de dados que realizei para publicação de um capítulo de livro sobre o comportamento do mercado imobiliário na Região Metropolitana de Belo Horizonte.

5) 2024_12_analise_mercado_imobiliario.ipynb: 
- Análise de dados sobre mercado imobiliário em Belo Horizonte que costumo realizar para uma empresa que faz serviços de avaliação de impacto de empreendimentos da MRV.

6) crawler.ipynb
- Crawlers utilizado para minerar dados de imóveis de um portal de imobiliárias.

