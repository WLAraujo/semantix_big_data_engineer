# semantix_big_data_engineer

Repositório com os arquivos referentes ao treinamento da semantix de big data engineer. O treinamento visa ensinar sobre diversas tecnologias na área de big data dando maior enfoque na parte de engenharia de dados. O treinamento foi divido em 6 cursos. Até o momento foram trabalhados os dois primeiros: Big Data Foundations e Mongo DB Básico.

O treinamento usa como principal recurso educacional containers e redes de containers para simular clusters e ambientes que possuam ferramentas de big data amplamente utilizadas.

Na pasta `docker-bigdata` temos um arquivo `docker-compose` que possui uma simula uma estrutura de cluster com várias ferramentas distribuídas em nós diferentes. Esse "cluster" foi usado durante o primeiro curso do treinamento Big Data Foundations. Para entender melhor sua arquitetura acesse a imagem `ecosystem.jpeg`. As ferramentas que foram usadas nesse curso foram: Hadoop, HDFS, Hive, Sqoop, HBase e Spark.

O segundo treinamento, Mongo DB Básico, usou o `docker-compose` contido na pasta `ambiente-mongo` e passou por diversos tópicos e operações possíveis no Mongo, também apresentando noções que NoSQL.
