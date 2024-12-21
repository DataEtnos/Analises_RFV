# Analises_RFV

Trabalhei com um dataset de transações comerciais que incluía colunas como número de fatura, código de produto, descrição, quantidade, preço unitário, ID do cliente e país. O objetivo principal era segmentar clientes com base em seus comportamentos de compra.

Uma das primeiras etapas foi a criação de uma coluna chamada "Amount", que não existia originalmente no dataset. Essa coluna foi estruturada multiplicando a quantidade de produtos pelo preço unitário, fornecendo um indicador essencial para análise de valor monetário das transações. Além disso, construí um dataframe de RFV (Recência, Frequência e Valor) a partir das informações de vendas dos clientes, permitindo uma segmentação mais detalhada e baseada em comportamento.

O processo de limpeza de dados foi fundamental para garantir a qualidade da análise. Tratei dados nulos, padronizei informações e realizei uma análise rigorosa de outliers, removendo valores atípicos que poderiam distorcer os resultados. Essas etapas foram cruciais para assegurar a consistência e a integridade dos dados antes de avançar para as análises.

Realizei visualizações gráficas para entender distribuições e relações entre variáveis, utilizando bibliotecas como Seaborn e Matplotlib. Testei diferentes algoritmos de clusterização, incluindo K-means, DBSCAN, Mean Shift e K-means++. Utilizei métricas como Silhouette Score e Davies-Bouldin Index para avaliar os resultados. O K-means++ apresentou os melhores resultados, com clusters bem definidos que destacaram grupos de clientes com comportamentos distintos.

Entre os clusters identificados, destaco:

Compradores Frequentes: Clientes que realizam compras recorrentes em grandes quantidades. As estratégias propostas incluem oferecer programas de fidelidade para incentivar ainda mais as compras recorrentes, disponibilizar descontos progressivos com base no volume de compras e enviar recomendações personalizadas de produtos relacionados aos itens comprados frequentemente.

Oportunistas: Clientes que compram em eventos sazonais. As estratégias sugeridas envolvem criar campanhas específicas para datas comemorativas e eventos sazonais, enviar e-mails promocionais antecipados para maximizar a conversão e oferecer cupons de desconto válidos por tempo limitado para estimular novas compras.

Exploradores: Clientes que experimentam produtos variados sem um padrão claro. Para eles, propus implementar promoções de "compre e experimente" com descontos em novos produtos, enviar pesquisas para entender melhor suas preferências e interesses e oferecer recomendações de produtos baseadas em tendências gerais do mercado.

Este projeto reforçou a importância da análise de dados na tomada de decisões estratégicas. A clusterização não apenas organiza dados, mas também revela insights valiosos para ações mais assertivas.

Se você também trabalha com dados ou tem interesse em projetos semelhantes, adoraria trocar ideias! Deixe seu comentário ou entre em contato.


![df original](https://github.com/user-attachments/assets/44c9f5e3-253d-484d-a6e3-9d00e639bc52)

![RFV](https://github.com/user-attachments/assets/8fdff4a2-4b13-4456-b6ea-d4f6b03d5882)
![analises](https://github.com/user-attachments/assets/439a5266-441a-4841-897b-6ad422490a94)
![cotovelok++](https://github.com/user-attachments/assets/d7ec7d60-dbab-4fa5-9925-4f791f1876cf)

![k++](https://github.com/user-attachments/assets/5cdedc9f-6b90-4fb2-a0d5-dec9017668f4)
