# Projeto-Final-Semantix
Projeto Final Semantix com métricas da Covid 19 de acordo com dados do Ministério da Saúde brasileiro disponíveis no site  https://covid.saude.gov.br/ 
sobre a epidemia de Covid-19. 

Campanha Nacional de Vacinação contra Covid-19
O projeto foi dividido em dois níveis, básico e avançado. Recomendamos fortemente fazer primeiro o básico e se sobrar tempo, pode aventurar no avançado.
Os exercícios podem ser feitos em qualquer linguagem e todas as questões são bem abertas, tendo várias formas de serem realizadas e interpretadas, pois a idéia é não termos projetos iguais.
O projeto deve estar no github.com, a forma de organizar o conteúdo é por sua conta, caso nunca tenha usado, este já é seu primeiro desafio.
Ao final do projeto você precisa preencher o formulário com o seu nome completo, e- mail utilizado no treinamento e o link do github do seu projeto.
Nível Básico:
Dados: https://mobileapps.saude.gov.br/esus- vepi/files/unAFkcaNDeXajurGB7LChj8SgQYS2ptm/04bd3419b22b9cc5c6efac2c652810 0d_HIST_PAINEL_COVIDBR_06jul2021.rar
Referência das Visualizações:
• Site: https://covid.saude.gov.br/
• Guia do Site: Painel Geral
1. Enviar os dados para o hdfs
2. Otimizar todos os dados do hdfs para uma tabela Hive particionada por
município.
3. Criar as 3 vizualizações pelo Spark com os dados enviados para o HDFS:
4. Salvar a primeira visualização como tabela Hive
5. Salvar a segunda visualização com formato parquet e compressão snappy
6. Salvar a terceira visualização em um tópico no Kafka
7. Criar a visualização pelo Spark com os dados enviados para o HDFS
8. 8. Salvar a visualização do exercício 6 em um tópico no Elastic
9. Criar um dashboard no Elastic para visualização dos novos dados enviados
