
<p align="center">
  <img src="https://github.com/Mat3usCod3/Titanic/blob/main/img.jpg?raw=true"/>
</p>


# Análise exploratória Titanic

Realizamos neste projeto, uma análise simples dos dados do acidente ocorrido em 12 de abril de 1912, com o navio Titanic. Nesta base de dados, existem informações extremamente relevantes em relação às vítimas e sobreviventes do acidente.

## Autores

- [@Mat3usCod3](https://github.com/Mat3usCod3)


## Algumas Questões que foram analisadas:


#### Quantiade de pessoas de ambos os sexos que sobreviveram;

#### Quantiade de pessoas de ambos os sexos que faleceram;

#### Tripulantes do sexo masculino que não sobreviveram;

#### Tripulantes do sexo feminino que não sobreviveram;

#### Tarifa em relação as classes 1, 2, e 3; 



## Apêndice

No decorrer deste projeto, relacionamos as informações presentes nas colunas, para dessa forma, extrair melhores informações, e também, refinar as análises. Por exemplo, na última etapa, buscamos compreender a relação existente entre a coluna `Pclass` referente as classes, e a coluna `Fare` que corresponde a tarifa, fazendo o seguinte questionamento: Existe algum tipo de relação entre a classe e o valor da tarifa? Nesta análise, preocupamos em responder e tratar questões dessa natureza.


## Bibliotecas utilizadas 

```python
import pandas as pd
import numpy as np
import matplotlib as plt
import matplotlib.pyplot as plt
import math as mt
import statistics as st

# Data frame;
data = pd.read_csv('titanic.csv')
data.head(4)

```


## Instalação 

Instalação de algumas bibliotecas importantes:

```bash
  conda install pandas
  conda install -c anaconda numpy
  conda install -c conda-forge matplotlib
```
    
## Recursos utilizados
**Linguagem:** Linguagem Python versão 3.8.8.

**Editor:** Anaconda Navigator, Notebook Jupyter.


## Exemplo gráficos

Exemplo de gráfico piechart utilizado no projeto:

![teste](https://github.com/Mat3usCod3/Titanic/blob/main/g.png?raw=true)
## Feedback

Estamos disponíveis para receber qualquer tipo de sugestão e Feedback, por favor entre em contato por meio do seguinte e-mail: mateusmenezes1997@gmail.com


## Suporte

Para suporte, ou qualquer dúvida entre em contato atravéz do seguinte e-mail: mateusmenezes1997@gmail.com

