<!-- antes de enviar a versão final, solicitamos que todos os comentários, colocados para orientação ao aluno, sejam removidos do arquivo -->
# Predição de Geração de Energia Eólica

#### Aluno: [Tales Simões Mattos](https://github.com/Talesbr/ProjetoBI)
#### Orientadora: [Manoela Rabello Kohler](https://github.com/link_do_github).


---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

<!-- para os links a seguir, caso os arquivos estejam no mesmo repositório que este README, não há necessidade de incluir o link completo: basta incluir o nome do arquivo, com extensão, que o GitHub completa o link corretamente -->
- [Link para o código](https://github.com/link_do_repositorio). <!-- caso não aplicável, remover esta linha -->


- Trabalhos relacionados: <!-- caso não aplicável, remover estas linhas -->
    - [Nome do Trabalho 1](https://link_do_trabalho.com).
    - [Nome do Trabalho 2](https://link_do_trabalho.com).

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

A geração de energia eólica com uso de aerogeradores tem se tornado uma das principais formas de geração de energia elétrica renovável, apresentando crescimento expressivo ao longo dos últimos anos, onde em 2020 existia 17,8 GW de capacidade instalada no Brasil, sendo o equivalente a 10,1% da Matriz Elétrica Brasileira, e com um total de emissões evitadas em 2020 de 21,2 milhões de toneladas de CO2, sendo equivalente à emissão anual de cerca de 21 milhões de automóveis de passeio.

A Energia eólica vem a ser a energia produzida a partir da energia cinética do vento (massas de ar em movimento) e do aquecimento eletromagnético do Sol (energia solar), que, juntos, movimentam as pás de captadores, onde a energia cinética do vento normalmente é convertida em energia mecânica por moinhos e cataventos, ou em energia elétrica por turbinas eólicas (ou aerogeradores).

Este trabalho buscou utllizar uma rede neural LSTM (Long Short Term Model) para avaliar a predição de geração de energia elétrica proveniente de um aerogerador, utilizando os dados coletados referentes a um ano de produção deste aerogerador e utilizando a rede para prever a geração para os meses seguintes. 

Foi utilizada uma base de daos de uma erogerador A aplicação de um modelo de redes neurais em LSTM (Long Short Term Model) apresentou resultados satisfatórios para a base de dados utilizada, obtida do www.kaggle.com, https://www.kaggle.com/theforcecoder/wind-power-forecasting?select=Turbine_Data.csv.

### Abstract <!-- Opcional! Caso não aplicável, remover esta seção -->

<!-- trocar o texto abaixo pelo resumo do trabalho, em inglês -->

The generation of wind energy using wind turbines has become one of the main forms of renewable electricity generation, showing significant growth over the past few years, where in 2020 there was 17.8 GW of installed capacity in Brazil, equivalent to 10.1% of the Brazilian Electricity Matrix, and with a total avoided emissions in 2020 of 21.2 million tons of CO2, equivalent to the annual emission of around 21 million passenger cars.

Wind energy is the energy produced from the kinetic energy of the wind (moving air masses) and the electromagnetic heating of the Sun (solar energy), which together move the pickup blades, where the kinetic energy of the wind it is usually converted into mechanical energy by windmills and weathervanes, or into electrical energy by wind turbines (or wind turbines).

This work sought to use a neural network LSTM (Long Short Term Model) to evaluate the prediction of electricity generation from a wind turbine, using data collected for one year of production of this wind turbine and using the network to predict the generation for the following months.

An erogenerator database was used. The application of a neural network model in LSTM (Long Short Term Model) presented satisfactory results for the database used, obtained from www.kaggle.com, https://www.kaggle .com/theforcecoder/wind-power-forecasting?select=Turbine_Data.csv.

### 1. Introdução


Energia eólica é a energia cinética derivada da força dos ventos, que pode ser utilizada para várias finalidades, incluindo a produção de eletricidade a partir de aerogeradores, onde os ventos movimetnam as hélices das turbinas eólicas, gerando força mecânica, que depois é convertida em energia elétrica por meio de um gerador. 

Atualmente a energia eólica é a segunda fonte renovável mais utilizada no mundo, depois da energia hídrica, onde segundo os dados da Agência Internacional de Energia Renovável (Irena), a capacidade total instalada de geradores eólicos atingiu 732,41 GW em 2020, impulsionado pela sua fonte de energia inesgotável, que é o vento, e pelo fato de não emitir poluentes, gases de efeito estufa e nem gerar resíduos, apresentando ainda as vantagens de não haver custos associados à obtenção de uma matéria-prima, diferente do que ocorre com combustíveis fósseis.

Uma das desvantagens da geração de energia eólica é a sua intermitência, onde por esta razão se torna de fundamental importância tentar prever o comprtamento de sua geração, diretamente relacionada ao regime dos ventos. O objetivo deste trabalho foi avvaliar a geração de energia eólica de um aerogerador, tomando por base os dados registrados de geração de energia de janeiro de 2018 a março de 2020 com intervalos de 10 minutos, buscando realizar a previsao da geração com base nestes registros, através do uso de uma Redes Neurais LSTM (Long Short Term Model)


### 2. Modelagem

Inicialmente foi realizado o pré-tratamento da base de dados, composta por mais de 118.000 registros de 22 atributos, contemplando o registro da geração de energia obtida pelo aerogerador, desde de janeiro de 2018 a março de 2020, onde após o tratamento foi identificado que os dados do ano de 2018 possuíam muitas ausÊncias de informações, onde optou-se por utilizar os dados do ano de 2019 (52.600 registros), sendo os dados referentes ao ano de 2020 (4.700 registroa) utilizados para testar os resultados. Foi testada uma rede neural LSTM e utilizado o indicador de acurácia R2.


### 3. Resultados

Após a aplicação da rede neural os resutlados do modelo testado apresentaram um resultado satisfatório para a previsão de geraçã ode energia com alto valor de R2, de 0,94.

### 4. Conclusões

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin pulvinar nisl vestibulum tortor fringilla, eget imperdiet neque condimentum. Proin vitae augue in nulla vehicula porttitor sit amet quis sapien. Nam rutrum mollis ligula, et semper justo maximus accumsan. Integer scelerisque egestas arcu, ac laoreet odio aliquet at. Sed sed bibendum dolor. Vestibulum commodo sodales erat, ut placerat nulla vulputate eu. In hac habitasse platea dictumst. Cras interdum bibendum sapien a vehicula.

Proin feugiat nulla sem. Phasellus consequat tellus a ex aliquet, quis convallis turpis blandit. Quisque auctor condimentum justo vitae pulvinar. Donec in dictum purus. Vivamus vitae aliquam ligula, at suscipit ipsum. Quisque in dolor auctor tortor facilisis maximus. Donec dapibus leo sed tincidunt aliquam.

---

Matrícula: 192.101.067

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
