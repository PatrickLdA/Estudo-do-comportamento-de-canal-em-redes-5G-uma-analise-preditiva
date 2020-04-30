# Estudo-do-comportamento-de-canal-em-redes-5G-uma-analise-preditiva
## Introdução
Scripts e dados usados na defesa do TCC "Estudo do comportamento de canal em redes 5G: uma análise preditiva", pela Universidade Federal de Uberlândia. O trabalho completo pode ser encontrado [aqui](https://repositorio.ufu.br/handle/123456789/26151).

Um parâmetro que passa a ser particularmente importante no dimensionamento das redes 5G é o estado do canal de comunicação, principalmente ao considerar as novas frequências usadas, o número crescente de dispositivos conectados e a necessidade de alocar recursos de forma eficiente. Para dimensionar os efeitos do canal, a Base Station (BS) recebe do User Equipment (UE) uma medição da qualidade do canal, chamada Channel Quality Information/Indicator (CQI), a partir da qual faz o escalonamento dos recursos para melhor atender os usuários. O estudo aqui desenvolvido visa avaliar a aplicação de uma rede neural temporal para prever o CQI ao longo de uma transmissão. Por fim, avalia-se a confiabilidade da rede, comparando os valores preditos pelo sistema e os reais.


## Arquivos
O arquivo **TCC.ipynb** contém todo o trabalho desenvolvido. Nas pastas *Seed_7*, *Seed_8*, *Seed_9* e *Seed_10* estão os relatórios usados nas análises. Dentro de cada uma: 2 arquivos csv contém os dados brutos e na pasta *Adaptação* os dados tratados e prontos para serem usados.

Os demais arquivos são oriundos das simulações e não são críticos para o entendimento e a execução, sendo criados em toda a execução do código.



## Bases de dados
As bases usadas nas análises estão no diretório *Seed_numero/Adaptação* e são **CQIReport.csv** e **SINRReport.csv**. Em **CQIReport.csv**, há 2 colunas:
- Índice: índice temporal da simulação;
- CQI: métrica de qualidade de canal passada do UE para a BS.

Em **SINRReport.csv**:
- Índice: índice temporal da simulação;
- SINR: relação sinal-ruído + interferência do canal.


## Contato
Gostou do meu trabalho? Tem sugestões, críticas ou conselhos? Você pode me achar aqui:
- Email: patrickluizdearaujo@gmail.com.
- [LinkedIn](https://www.linkedin.com/in/patrick-luiz-de-ara%C3%BAjo-b91565131/).
