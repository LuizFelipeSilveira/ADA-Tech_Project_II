**PROJETO FINAL - MÓDULO II | TÉCNICAS DE PROGRAMAÇÃO I | ADA TECH**
##

O projeto a seguir foi desenvolvido como entrega final para o Módulo II (Técnicas de Programação I) da formação em Ciência de Dados da ADA Tech.
O objetivo desse projeto é explorar um dataset robusto e, a partir de hipóteses formuladas, tentar encontrar respostas nos dados. 

Formato do arquivo: **Jupyter Notebook**

Linguagem de programação utilizada: **Python**

Bibliotecas utilizadas: **Pandas** | **Matplotlib**

Dataset: **MICRODADOS DO ENEM 2013**
##

As hipóteses formuladas e exploradas pelo grupo foram:

   1. Relação entre posse de automóvel e presença dos candidatos nos dias de prova.
   2. Relação entre posse de automóvel e nota dos participantes.
   3. Estrangeiros tem mais dificuldade em provas de língua portuguesa? (Redação e Linguagens e Códigos)
   4. Qual o perfil dos candidatos que feriram direitos humanos e consequentemente zeraram a redação?
   5. Como cada Sexo performou no ENEM 2013?

##

**Instruções de uso:**

   1. Por se tratar de um dataset robusto (mais de 7M de registros), o usuário do código deve fazer o download do arquivo que contém os microdados do ENEM 2013 pelo link a seguir:
   https://download.inep.gov.br/microdados/microdados_enem_2013.zip
   2. O usuário deve extrair o .zip baixado e na pasta DADOS encontrará o arquivo MICRODADOS_ENEM_2013.csv
   3. O arquivo deve ser movido para a pasta onde está o repositório Git, de modo que o algoritmo possa fazer a leitura correta dos dados e funcionar da forma correta.
   4. É necessário que o usuário tenha as bibliotecas Pandas e Matplotlib instaladas.



**Conclusões de cada hipótese:**

1. Relação entre posse de automóvel e presença dos candidatos nos dias de prova.
   
   - **44.12%** dos participantes tem automóvel. 
   - **27.17%** dos candidatos não estiveram presentes em nenhum dos dois dias de prova
   - **32.83%** dos participantes que alegaram ter ao menos 1 automóvel estiveram presentes nos dois dias de prova
   - **36.97%** dos participantes que alegaram não ter nenhum automóvel estiveram presentes nos dois dias de prova
   - **1.17%** de evasão parcial de candidatos com automóvel
   - **1.79%** de evasão parcial de candidatos sem automóvel
   - Embora o automóvel seja um facilitador para chegar ao local da prova, mais pessoas sem automóvel compareceram aos dois dias de prova (**36.97%**) do que pessoas com automóvel (**32.83%**).
  Uma possibildiade é de que muitos candidatos se preocupam menos com a hora por terem o automóvel como meio de transporte, mas acabam se atrasando e perdendo a prova enquanto pessoas que não tem automóvel se organizam e chegam mais cedo ao local da prova, reduzindo o número de atrasos.

2. Relação entre posse de automóvel e nota dos participantes.

   - Por se tratar de um grupo bem reduzido em relação ao todo e não trabalhar com todas as faixas de renda, a análise possivelmente não é confiável. No entanto a amostra indica que, a princípio, ter ou não um automóvel não tem grandes interferências no resultado final da prova.

3. Estrangeiros tem mais dificuldade em provas de língua portuguesa? (Redação e Linguagens e Códigos)

   - Estrangeiros tiraram notas maiores que os brasileiros, de forma geral em provas relacionadas à língua portuguesa. Isso pode estar atrelado ao fato de que estrangeiros tem uma preocupação maior com o estudo da língua portuguesa do que os próprios brasileiros, que se sentem mais a vontade por se tratar do seu idioma nativo. No entanto, provavelmente os estrangeiros estudam e se atentam mais à norma culta, o que resulta em maiores notas.

4. Qual o perfil dos candidatos que feriram direitos humanos e consequentemente zeraram a redação?

   - Mulheres cometeram 55% das infrações enquanto homens 45%.
   - No quesito cor/raça, pessoas pardas anularam 43%, seguida por pessoas brancas 38% e pretas 15%.
   - Entre escolas públicas e privadas a análise ficou prejudicada, porque das 164 ocorrências 131 não tem dados,
80% de missing values.
   - Analisando faixa etária, os jovens entre 17 a 18 anos e 26 a 30 foram os campeões. Entre os candidatos de 17 a 18 anos representam 24% das anulações, enquanto que candidatos entre 26 a 30 anos foi de 13%.
   - No quesito de UF e região, os estados com maior percentual foram SP (15%), BA(13%) e MA(9%). Por região ficou assim: Nordeste 36,58%, Sudeste 29,87%, Centro 13,41%, Sul 10,97% e Norte 9,14%.
   - Considerando faixa de renda familiar, 78% das ocorrências aconteceram nas faixas de renda entre menos de um salário mínimo até dois salários mínimos.

5. Como cada Sexo performou no ENEM 2013?

   - Utilizando o método describle obtemos diversas métricas do dataframe. Podemos comparar a média de cada Gênero por Matéria assim como o desvio padrão.
   - Observamos que a média das mulheres foi menor do que a dos homens nas provas objetivas, sendo a maior disparidade na prova de matemática e a menor em linguagens e códigos.
   - Já na redação as mulheres performaram melhor em média, e foi a prova com maior desvio padrão para ambos os gêneros.


